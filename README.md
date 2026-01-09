# Docker Fedora Systemd

This Dockerfile can build containers capable to use systemd.

![GitHub top language](https://img.shields.io/github/languages/top/buluma/docker-fedora-systemd) ![Docker Pulls](https://img.shields.io/docker/pulls/buluma/fedora-systemd?label=pulls&logo=docker&logoColor=white)

[![Build fedora-35](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml) [![Build fedora-36](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml) [![Build fedora-37](https://github.com/buluma/fedora/actions/workflows/fedora-37.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-37.yml) [![Build fedora-38](https://github.com/buluma/fedora/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-38.yml) [![Build fedora-39](https://github.com/buluma/fedora/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-39.yml) [![Build fedora-40](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml) [![Build fedora-41](https://github.com/buluma/fedora/actions/workflows/fedora-41.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-41.yml) [![Build fedora-42](https://github.com/buluma/fedora/actions/workflows/fedora-42.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-42.yml) [![Build fedora-43](https://github.com/buluma/fedora/actions/workflows/fedora-43.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-43.yml) [![Build fedora-rawhide](https://github.com/buluma/fedora/actions/workflows/fedora-rawhide.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-rawhide.yml)

![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/latest?logo=docker&logoColor=white&label=latest)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/rawhide?logo=docker&logoColor=white&label=rawhide)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/32?logo=docker&logoColor=white&label=32)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/33?logo=docker&logoColor=white&label=33)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/34?logo=docker&logoColor=white&label=34)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/35?logo=docker&logoColor=white&label=35)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/36?logo=docker&logoColor=white&label=36)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/38?logo=docker&logoColor=white&label=38)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/39?logo=docker&logoColor=white&label=39)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/40?logo=docker&logoColor=white&label=40)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/41?logo=docker&logoColor=white&label=41)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/42?logo=docker&logoColor=white&label=42)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/43?logo=docker&logoColor=white&label=43)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/testing?logo=docker&logoColor=white&label=testing)

Branches
--------

This repository has multiple branches that relate to Fedora versions.

|Branch |Fedora Version|Status|Docker image tag|Docker image size|
|-------|--------------|------|----------------|-----------------|
|43(master)     |43            |Supported|latest              |![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/latest?logo=docker&logoColor=white&label=latest)|
|42     |42            |Supported|42              |![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/42?logo=docker&logoColor=white&label=42)|
|41     |41            |Supported|41              |![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/41?logo=docker&logoColor=white&label=41)|
|rawhide|rawhide (44)  |Supported|rawhide         |![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/rawhide?logo=docker&logoColor=white&label=rawhide)|
|testing|testing (44)  |Supported|testing         |![Docker Image Size (tag)](https://img.shields.io/docker/image-size/buluma/fedora-systemd/testing?logo=docker&logoColor=white&label=testing)|

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Support Policy
--------------

- **Supported versions**: Latest 3 Fedora releases (41, 42, 43) and rawhide/testing (for development)
- **Deprecated versions**: Older versions (30-40) are still available but no longer actively maintained
- **End of Life**: Fedora versions follow the standard Fedora Project lifecycle

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:rw \
  buluma/fedora
```
