# Docker Fedora Systemd
=====================

This Dockerfile can build containers capable to use systemd.

![GitHub top language](https://img.shields.io/github/languages/top/buluma/docker-fedora-systemd)

[![Build fedora-35](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml) [![Build fedora-36](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml) [![Build fedora-37](https://github.com/buluma/fedora/actions/workflows/fedora-37.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-37.yml) [![Build fedora-38](https://github.com/buluma/fedora/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-38.yml) [![Build fedora-39](https://github.com/buluma/fedora/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-39.yml) [![Build fedora-40](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml)

![Docker Pulls](https://img.shields.io/docker/pulls/buluma/fedora-systemd?label=pulls&logo=docker&logoColor=white)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/latest?logo=docker&logoColor=white&label=latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/rawhide?logo=docker&logoColor=white&label=rawhide)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/32?logo=docker&logoColor=white&label=32)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/33?logo=docker&logoColor=white&label=33)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/34?logo=docker&logoColor=white&label=34)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/35?logo=docker&logoColor=white&label=35)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/36?logo=docker&logoColor=white&label=36)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/38?logo=docker&logoColor=white&label=38)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/testing?logo=docker&logoColor=white&label=testing)

Branches
--------

This repository has multiple branches that relate to Fedora versions.

|Branch |Fedora Version|Docker image tag|Docker image size|
|-------|--------------|----------------|-----------------|
|38     |38            |38              |![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/testing?logo=docker&logoColor=white&label=testing)|
|master |latest (39)   |latest          |-----------------|
|rawhide|rawhide (40)  |rawhide         |-----------------|

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  buluma/fedora-systemd
```
