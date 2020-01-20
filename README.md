# Centos 8 Base Image

![](https://img.shields.io/docker/cloud/build/pandemonium1986/centos8)
![](https://img.shields.io/github/release/Pandemonium1986/docker-centos8)
![](https://img.shields.io/github/release-date/Pandemonium1986/docker-centos8)
![](https://img.shields.io/github/license/Pandemonium1986/docker-centos8)

Centos 8 docker image. Built to be like my vagrant box to be able to test Ansible playbooks and roles.

## Tags

-   `latest`: Latest version of the centos 8 base image.

## How to Build

This image is built on Docker Hub automatically any time the upstream OS container is rebuilt, and any time a commit is made or merged to the `master` branch. But if you need to build the image on your own locally, do the following:

1.  [Install Docker](https://docs.docker.com/engine/installation/).
2.  `cd` into this directory.
3.  Run `docker build -t localhost/centos8:test .`

## How to Use

1.  [Install Docker](https://docs.docker.com/engine/installation/).
2.  Pull this image from Docker Hub: `docker pull pandemonium1986/centos8:latest` (or use the image you built earlier, e.g. `localhost/centos8:test`).
3.  Run a container from the image: `docker run --detach --privileged --name centos8-pdm-hub pandemonium1986/centos8:latest`.

## Author Information

-   **Michael Maffait** - _Initial work_ - [Pandemonium1986](https://github.com/Pandemonium1986)
