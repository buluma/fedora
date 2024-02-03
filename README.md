# Fedora Base Docker Images

[![Build fedora-35](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml) [![Build fedora-36](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml) [![Build fedora-37](https://github.com/buluma/fedora/actions/workflows/fedora-37.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-37.yml) [![Build fedora-38](https://github.com/buluma/fedora/actions/workflows/fedora-38.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-38.yml) [![Build fedora-39](https://github.com/buluma/fedora/actions/workflows/fedora-39.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-39.yml) [![Build fedora-40](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-40.yml)


## Quick reference

    Maintained by: Michael Buluma

    Where to get help: the Docker Community Forums, the Docker Community Slack, or Stack Overflow

## Supported tags and respective Dockerfile links
    35
    36
    37
    38
    39, latest
    rawhide, 40

## Quick reference (cont.)

    Where to file issues: Fedora's bugzilla page or GitHub

    Supported architectures: (more info) amd64, arm32v7, arm64v8, ppc64le, s390x

    Published image artifact details: repo-info repo's repos/fedora/ directory (history) (image metadata, transfer size, etc)

    Image updates: official-images repo's library/fedora label
    official-images repo's library/fedora file (history)

    Source of this description: docs repo's fedora/ directory (history)

# Fedora

This image serves as the official Fedora image for the Fedora Distribution.

The fedora:latest tag will always point to the latest stable release.

This image is a relatively small footprint in comparison to a standard Fedora installation. This image is generated in the Fedora Build System and is built from this kickstart file.

Fedora Rawhide is available via fedora:rawhide and any specific version of Fedora as fedora:$version (example: fedora:39).
