Docker Fedora 40 (Rawhide)
=====================

This Dockerfile can build containers capable to use systemd.

[![Build fedora-latest](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml/badge.svg?branch=main)](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml)
![GitHub top language](https://img.shields.io/github/languages/top/buluma/fedora)

![Docker Pulls](https://img.shields.io/docker/pulls/buluma/fedora?label=pulls&logo=docker&logoColor=white)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora/latest?logo=docker&logoColor=white&label=latest)

Branches
--------

This repository has multiple branches that relate to Fedora versions.

|Branch |Fedora Version|Docker image tag|
|-------|--------------|----------------|
|master |latest (40)   |rawhide         |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:rw \
  buluma/fedora:rawhide
```
