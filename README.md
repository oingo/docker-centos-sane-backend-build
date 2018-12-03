## SANE Backend build environment (CentOS - x64) Dockerfile


### Base Docker Image

* [centos:7](https://hub.docker.com/_/centos/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download : `docker pull oingo/docker-centos-sane-backend-build`


### Usage

    docker run -it -v <sane-backend-volume>:/root/project oingo/docker-centos-sane-backend-build /bin/bash
