# Workshops 2018

## Introduction to PHP Extensions

**Instructor:** Derick Rethans

### Pre-Requisite

Before beginning this tutorial, you'll need a development environment with the following packages:

- Linux
- Compiler: gcc and clang are both excellent choices.
- Build tools: autoconf, automake, libtool
- (Optional) parser generators: re2c and bison
- PHP 7.x with development headers:
	- Either distro packages such as: php7 and php7-devel / php7-dev
	- PHP compiled from source and installed with sudo make install. If compiling from source, then the --enable-debug switch is recommended, as well as the optional re2c and bison packages.

You test whether the prerequisites are met by running `pecl install -f geospatial-beta`  works on the command line, without errors.

Debugging tools that could also be handy: gdb and valgrind, which they can install with their linux package managers too.

## Refactoring Legacy PHP: The Complete Guide

**Instructor:** Junade Ali	


## Drupal: Zero to Hero in 3 hours

**Instructor:** SJ

In this workshop, participants will set up Drupal site from scratch, configure and develop an application, and deploy it to a production-ready server. A topic from https://archkatas.herokuapp.com/kata.html will be used to help define the requirement of the site.

### Pre-workshop survey
Please complete the survey: http://bit.ly/phpconfasia2018-drupalworkshop

### Pre-requisite knowledge
-   understand and speak English
-   comfortable using web based interface and command line
-   computational thinking

### Pre-requisite machine setup
Option #1
-   set up Docker Desktop (https://www.docker.com/products/docker-desktop)
-   set up ddev (https://github.com/drud/ddev), read their installation steps: https://ddev.readthedocs.io/en/latest/#installation
    -   run `ddev config` to configure ddev for php project—just answer all questions with default answers
    -   run `ddev start` to download the necessary docker images prior to the workshop
-   awesome text editor like vi, or powerful IDE... well, any text editor will do
-   (optional) native git client, and GUI if necessary (e.g. https://www.sourcetreeapp.com/)

Option #2 for hardcore coder
-   native web server with PHP 7.x and MySQL / MariaDB
-   native composer, drush, drupal console
-   vi
-   native git client

### Pre-requisite cloud setup
-   we will use Platform.sh development tier, which is free for 30-days when you are using this code: "php-conf-asia-2018"
-   Platform.sh development tier provides git server, web server, db, 3 environment, CLI tools
-   install platform CLI (https://docs.platform.sh/gettingstarted/cli.html)
-   you may also use your self-provisioned server and manually configure drush aliases


## Build your own Secure Messenger in 3 hours

**Instructor:** Ben Dechrai	

## Goodbye jQuery! Enhance your PHP project with VueJS

**Instructor:** Yuri Pratama	

### Pre-Requisites

* Node & NPM
* Composer
* PHP 7.x
* MySQL / MariaDB (Optional)
* Your best text editor / IDE

## Create a framework-less PHP Web Application from scratch

Instructor: Patrick Allaert

## Hands on PHPSpec

**Instructor:** Miro Svrtan	

This is a modeling workshop so no need to bring your laptop, I will be your coding hands so you can focus on thinking about the problem we are solving.


## Workshop by Microsoft

To be announced

## Getting Started with Symfony 4

**Instructor:** Prasetyo Wicaksono

### Pre-Requisites

* PHP 7.2
* Composer
* Internet Connection (used for symfony 4 installation)
