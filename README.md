docker-lede-buildroot
========================
[![Build Status](https://travis-ci.org/ssskip/lede-buildroot.svg?branch=master)](https://travis-ci.org/ssskip/lede-buildroot)
[![Docker Build Automated](https://img.shields.io/docker/automated/ssskip/lede-buildroot.svg)](https://hub.docker.com/r/ssskip/lede-buildroot/)
[![Docker Pulls](https://img.shields.io/docker/pulls/ssskip/lede-buildroot.svg)](https://hub.docker.com/r/ssskip/lede-buildroot/)
[![License: MIT](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/ssskip/lede-buildroot/blob/master/LICENSE)

This is a docker container for the [LEDE Project](https://lede-project.org/)
[buildroot](https://openwrt.org/docs/guide-developer/using_the_sdk).

To run a shell in the buildroot, execute the following command:

```sh
docker run -it ssskip/lede-buildroot:latest sudo -iu lede bash
```
