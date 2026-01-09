Docker Fedora Rawhide (Development)
=====================

This Dockerfile can build containers capable to use systemd.

[![Build fedora-rawhide](https://github.com/buluma/fedora/actions/workflows/fedora-rawhide.yml/badge.svg?branch=main)](https://github.com/buluma/fedora/actions/workflows/fedora-rawhide.yml)
![GitHub top language](https://img.shields.io/github/languages/top/buluma/fedora)

![Docker Pulls](https://img.shields.io/docker/pulls/buluma/fedora?label=pulls&logo=docker&logoColor=white)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora/rawhide?logo=docker&logoColor=white&label=rawhide)

Repository Structure
--------------------

This repository uses separate directories (folders) rather than git branches to maintain different Fedora versions. Each version has its own directory with its own Dockerfile and configuration.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:rw \
  buluma/fedora:rawhide
```