# stig4debian 

## About

This repository is stig4debian package from STIG-4-debian project(https://github.com/hardenedlinux/STIG-4-Debian).

## Usage

```
# stig4debian -h
usage: /usr/bin/stig4debian [options]

  -s    Start checking and output repot in html format.
  -v    Display version
  -h    Display help

  Report is output in /var/log/stig4debian/STIG-for-Debian-*.html

STIG for Debian Compliance Checking Tools (v2.0)

Ported from DISA RHEL 7 STIG
```

## Install  

```
# dpkg -i stig4debian_0.1.0-1_all.deb  
``` 

## Uninstall 

```
# dpkg -r stig4debian
```

