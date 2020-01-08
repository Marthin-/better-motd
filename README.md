
00-header
=========

Simple `uname -a`

15-services
===========

Checks whether listed services are active and enabled.
Use file `/etc/motd-services.conf` to add services. If empty, defaults to sshd and postfix

20-ports
========

Checks what services are listening and list the ports used by each process


30-load-w
=========

Checks if you are alone on the server, prints connected users otherwise.

Also checks if load has been above 2 in the last 10 minutes, prints uptime if that's the case

90-disk-space
=============

Checks if disk space or inode is short or critical, prints it in red if that's the case
