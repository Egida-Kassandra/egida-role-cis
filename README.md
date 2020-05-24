# egida-role-cis

<!-- PROJECT SHIELDS -->
[![EGIDA VERSION](https://img.shields.io/badge/egida-v0.0.1-blue?style=for-the-badge&logo=ansible&color=ff69b4)](https://github.com/antonioalfa22/egida)
[![GitHub license](https://img.shields.io/badge/license-Apache-blue?style=for-the-badge)](https://github.com/antonioalfa22/egida-role-cis/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/badge/release-v.0.0.1-yellowgreen?style=for-the-badge)](https://github.com/antonioalfa22/egida-role-cis/releases)

<!-- PROJECT LOGO -->

<br />
<p align="center">
  <a href="https://github.com/antonioalfa22/egida-role-cis">
    <img src="img/logo.svg" alt="Logo" width="180" height="180">
  </a>

  <h3 align="center">egida-role-cis</h3>

  <p align="center">
    <a href="https://github.com/antonioalfa22/egida"><strong>EGIDA</strong></a> CIS Benchmarks Role
    <br />
    <a href="https://github.com/antonioalfa22/egida-role-cis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/antonioalfa22/egida-role-cis">View Source</a>
    ·
    <a href="https://github.com/antonioalfa22/egida-role-cis/issues">Report Bug</a>
    ·
    <a href="https://github.com/antonioalfa22/egida-role-cis/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Example Playbook](#example-playbook)
* [Lynis Scores](#lynis-scores)
* [CIS Benchmarks Exclusions](#cis-benchmarks-exclusions)
* [License](#license)
* [Contact](#contact)

<!-- ABOUT THE PROJECT -->
## About the Project

This role was developed and tested against Ubuntu Linux 16.04 LTS and 18.04 LTS.

The CIS Benchmarks used for this repository can be found at [CIS Center for Intenet Security](https://www.cisecurity.org/cis-benchmarks/).

<!-- GETTING STARTED -->
## Getting Started

Getting Started

### Prerequisites

1. Ansible

### Installation

1. Download the source from [here](https://github.com/antonioalfa22/egida-role-cis/releases).

<!-- EXAMPLE PLAYBOOK -->
## Example Playbook

```yaml
---

- name: Harden Server
  hosts: localhost
  connection: local
  become: yes
  
  roles:
    - egida-role-cis
```

<!-- Lynis scores -->
## Lynis scores

* Initial Lynis score: 62%
* Lynis score with All + Extras: 83%

<!-- CIS Benchmarks Exclusions -->
## CIS Benchmarks Exclusions

### 1 Initial setup

#### 1.1 Filesystem Configuration

* 1.1.2
* 1.1.5
* 1.1.6
* 1.1.7
* 1.1.8
* 1.1.9
* 1.1.10
* 1.1.11
* 1.1.12
* 1.1.13
* 1.1.14
* 1.1.15
* 1.1.16
* 1.1.17
* 1.1.18
* 1.1.19
* 1.1.20
* 1.1.21
* 1.1.22
* 1.1.23

#### 1.2 Configure software updates

* 1.2.2

#### 1.3 Configure sudo

* 1.3.1
* 1.3.2
* 1.3.3

#### 1.5 Secure Boot Settings

* 1.5.4

#### 1.7 Mandatory Access Control

* 1.7.1.1
* 1.7.1.2
* 1.7.1.3
* 1.7.1.4

### 3 Network Configuration

#### 3.7 Disable IPv6

* 3.7

### 4 Logging and auditing

#### 4.1 Configure System accouting

* 4.1.1.4
* 4.1.2.1
* 4.1.2.2
* 4.1.2.3
* 4.1.11

#### 4.2 Configure Logging

* 4.2.1.2
* 4.2.1.3
* 4.2.1.4
* 4.2.1.5
* 4.2.1.6
* 4.2.2.1
* 4.2.2.2
* 4.2.2.3
* 4.2.3
* 4.3

### 5 Access Autentication and Authorization

#### 5.2 SSH Server configuration

* 5.2.2
* 5.2.3
* 5.2.13
* 5.2.15
* 5.2.20
* 5.2.21
* 5.2.22
* 5.2.23

#### 5.4 User Accounts and environment

* 5.4.1.5
* 5.4.2
* 5.5
* 5.6

### 6 System file permissions

#### 6.1 System file permissions

* 6.1.1
* 6.1.10
* 6.1.11
* 6.1.12
* 6.1.13
* 6.1.14

#### 6.2 User Accounts and environment

* All

<!-- LICENSE -->
## License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Authors:

* [Antonio Payá González](https://antoniopg.tk)
* [Alba Cotarelo Tuñón](https://antoniopg.tk)
* [Jose Manuel Redondo Lopez](http://orcid.org/0000-0002-0939-0186)

Project Link: [https://github.com/antonioalfa22/egida-role-cis](https://github.com/antonioalfa22/egida-role-cis)
