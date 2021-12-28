# Fedora Base Docker Images

[![Build fedora-30](https://github.com/buluma/fedora/actions/workflows/fedora-30.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-30.yml) [![Build fedora-31](https://github.com/buluma/fedora/actions/workflows/fedora-31.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-31.yml) [![Build fedora-32](https://github.com/buluma/fedora/actions/workflows/fedora-32.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-32.yml) [![Build fedora-33](https://github.com/buluma/fedora/actions/workflows/fedora-33.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-33.yml) [![Build fedora-34](https://github.com/buluma/fedora/actions/workflows/fedora-34.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-34.yml) [![Build fedora-35](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-35.yml) [![Build fedora-36](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml/badge.svg)](https://github.com/buluma/fedora/actions/workflows/fedora-36.yml)


## Quick reference

    Maintained by: Michael Buluma

    Where to get help: the Docker Community Forums, the Docker Community Slack, or Stack Overflow

## Supported tags and respective Dockerfile links

    30
    31
    32
    33
    34
    35, latest
    rawhide, 36

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

Fedora Rawhide is available via fedora:rawhide and any specific version of Fedora as fedora:$version (example: fedora:23).
