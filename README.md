# Shlifim Project - beyond 05 team 3

![shlifim_logo_2](https://user-images.githubusercontent.com/40122521/110316976-2990f880-8014-11eb-8ee8-96c21dd4b29f.png)

**Description**: Shlifim is the project our group will work on during the course.
The project will be forum based web application for helping students find answers
to their homework and assignments and also share summaries.

**Technology stack**: 
* [Vagrant](https://www.vagrantup.com/) -  an open-source software product for building and maintaining portable virtual software development environments
* [PipEnv](https://github.com/pypa/pipenv) - tool that manages a virtualenv for your projects
* [Django](https://www.djangoproject.com/) - Python Web framework

**Status**: 
Demo stage

## Dependencies
The dependencies that must be installed for this software to work are:
* [Vagrant](https://www.vagrantup.com/downloads)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## Installation

To install make sure you have Git installed already and all the dependencies mentioned above.

Enter in the Command Line: 
```
git clone https://github.com/beyond-io/shlifim.git 
```
## How to start the app
In your local git repository you made, enter the command:
```
vagrant up
```
Afterwards vagrant will boot up, configure, download and install all the needed additional dependencies.
A script will launch the app and you can access it in: http://127.0.0.1:8000/

**Team members**:
* Aviv Zafrani
* Danit Levi
* Ido Kahlon
* Rebecca Tubman
* Lior Noy

Contributing
------------

For contributing please follow the next steps:

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull request** so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!

[![Python Status](https://github.com/beyond-io/shlifim/actions/workflows/flake8.yml/badge.svg)](https://github.com/beyond-io/shlifim/actions/workflows/flake8.yml)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/beyond-io/shlifim/graphs/commit-activity)
