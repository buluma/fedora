FROM fedora:43

LABEL maintainer="Michael Buluma"
LABEL build_date="2026-01-09"

LABEL org.opencontainers.image.source=https://github.com/buluma/fedora
LABEL org.opencontainers.image.description="Ansible Fedora 43 image"
LABEL org.opencontainers.image.licenses=Apache-2.0

ENV container=docker

# Enable systemd.
RUN dnf -y install systemd && dnf clean all && \
  (cd /lib/systemd/system/sysinit.target.wants/ ; for i in * ; do [ $i == systemd-tmpfiles-setup.service ] || rm -f $i ; done) ; \
  rm -f /lib/systemd/system/multi-user.target.wants/* ;\
  rm -f /etc/systemd/system/*.wants/* ;\
  rm -f /lib/systemd/system/local-fs.target.wants/* ; \
  rm -f /lib/systemd/system/sockets.target.wants/*udev* ; \
  rm -f /lib/systemd/system/sockets.target.wants/*initctl* ; \
  rm -f /lib/systemd/system/basic.target.wants/* ;\
  rm -f /lib/systemd/system/anaconda.target.wants/*

VOLUME ["/sys/fs/cgroup"]
CMD ["/sbin/init"]
