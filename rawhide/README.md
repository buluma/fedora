Docker Fedora Rawhide (Development)
=====================

This Dockerfile can build containers capable to use systemd.

[![Build fedora-rawhide](https://github.com/buluma/fedora/actions/workflows/fedora-rawhide.yml/badge.svg?branch=main)](https://github.com/buluma/fedora/actions/workflows/fedora-rawhide.yml)
![GitHub top language](https://img.shields.io/github/languages/top/buluma/fedora)

![Docker Pulls](https://img.shields.io/docker/pulls/buluma/fedora?label=pulls&logo=docker&logoColor=white)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora/rawhide?logo=docker&logoColor=white&label=rawhide)

Branches
--------

This repository has multiple branches that relate to Fedora versions.

|Branch |Fedora Version|Docker image tag|
|-------|--------------|----------------|
|rawhide |rawhide (44)   |rawhide         |

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