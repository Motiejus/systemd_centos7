systemd-enabled CentOS 7 Docker image
=====================================

1. starts systemd
2. starts bash as root shell for development

To be started like::

    $ docker run --privileged -ti -v /sys/fs/cgroup:/sys/fs/cgroup:ro -p systemd_centos7
