![SendGrid Logo](https://uiux.s3.amazonaws.com/2016-logos/email-logo%402x.png)

# SendGrid Documentation

[![Build Status](https://travis-ci.org/sendgrid/docs.svg?branch=develop)](https://travis-ci.org/sendgrid/docs)
[![Twitter Follow](https://img.shields.io/twitter/follow/sendgrid.svg?style=social&label=Follow)](https://twitter.com/sendgrid)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./license)

## Introduction

This is a Gatsby site.

The develop branch is merged to production weekly (unless we need to do a release sooner than that).

The master branch is continuously deployed to production.

- **_Please_, feel free to make any contributions you feel will make SendGrid Documentation better.**
- **Submit all pull requests to the develop branch**

- **All third party contributors acknowledge that any contributions they provide will be made under the same open source license that the open source project is provided under.**
  - **When making contributions, be sure to place an "x" in the brackets of the PR description where it says "[ ] I acknowledge that all my contributions will be made under the project's license."**

## Table of Contents

- [Local Dependency Setup](#local-dependency-setup)
  - [Mac](#mac)
  - [Windows](#windows)
  - [Linux](#linux)
- [Local Repository Setup](#local-repository-setup)
- [About](#about)
- [License](#license)

## Local Dependency Setup

### Dependencies

- Required:
  - [Git](https://git-scm.com)
  - [npm](https://www.npmjs.com)
  - [yarn](https://yarnpkg.com/en/)
  - [Gatsby](https://www.gatsbyjs.org)

**Note:** Dependencies differ for work on the `old-develop` branch. If you need to work on `old-develop`, please see the README file after checking out that branch. This is uncommon.

## Setup Steps

#### Mac

- Install Git
  - [Git for Mac](https://git-scm.com/download/mac)

We recommend using [Homebrew](https://brew.sh/) to install and manage packages on a MacOS.

- Install Homebrew:

  ```shell
  $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```

- Install npm:

  ```shell
  $ brew install npm
  ```

- Set your Node.js version to 12

  ```shell
  $ npm install -g n

  $ n 12.16.1
  ```

- Install yarn

  ```shell
  $ brew install yarn
  ```

#### Windows

- Install Git

  - [Git for Windows](https://git-scm.com/download/win)

- Install npm

  - To install Node.js and npm on Windows, you can download the installer here:
    - https://nodejs.org/en/#home-downloadhead
  - Use Node.js version 12, the current Long Term Support (LTS) version.

- Install Yarn:
  - To install Yarn on windows, you can download the installer here:
    - https://classic.yarnpkg.com/en/docs/install/#windows-stable

#### Linux

- Install Git:

  - [Git for Linux](https://git-scm.com/download/linux)

- Install npm:

  - To install Node.js and npm on Linux, select the package and instillation appropriate for your Linux distribution. You can find help here:
    - https://nodejs.org/en/download/package-manager/
  - Use Node.js version 12, the current Long Term Support (LTS) version.

- Install Yarn:
  - To install Yarn on Linux, follow the directions for your Linux distribution on the yarn site. You will find Debian/Ubuntu directions here:
    - https://classic.yarnpkg.com/en/docs/install/#debian-stable

## Local Repository Setup

**Note:** When working on Windows, you may need to run Command Prompt or PowerShell as an Administrator.

**Note:** When working on Mac or Linux, you may need to run some commands using "sudo."

- Clone the SendGrid Docs Repo

  - SSH:

    ```shell
    $ git clone git@github.com:sendgrid/docs.git
    ```

  - HTTPS:

    ```shell
    $ git clone https://github.com/sendgrid/docs.git
    ```

- Go to your docs directory

  ```shell
  $ cd docs
  ```

- Switch to develop branch to make changes

  ```shell
  $ git checkout develop
  ```

- Install the Gatsby CLI

  ```shell
  $ npm install -g gatsby-cli
  ```

- Install npm package dependencies

  ```shell
  $ yarn install
  ```

- Build the local site
  - With the Gatsby CLI installed globally, you can run:
    ```shell
    $ gatsby develop
    ```
  - Alternatively, you can run:
    ```shell
    $ yarn develop
    ```
  - Either of the above commands should start a hot-reloading development environment accessible at [localhost:8000](localhost:8000)

## About

SendGrid is guided and supported by the SendGrid [Developer Experience Team](mailto:dx@sendgrid.com).
It is maintained and funded by SendGrid, Inc. The names and logos are trademarks of SendGrid, Inc.

## License

SendGrid Documentation is licensed under the **[MIT License (MIT)](https://github.com/sendgrid/docs/blob/develop/license)**
