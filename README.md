# wekan
Wekan auto-installation script

Tested on Ubuntu Server 14.04.3 LTS but it schould work on all Debian based distributions

This scripts automates the installation process for Wekan v0.90

It automatically downloads and installs the following packages:

* make, gcc, g++, build-essential, libssl-dev (needed for wekan compilation)
* mongodb-server (NoSQL database)*
* nvm (installs NodeJS v0.10.40)
* forever (runs NodeJS applications at the background forever)
* wekan v0.90

Run as root:

```sh
$ chmod +x autoinstall_wekan.sh
$ ./autoinstall_wekan.sh
```
