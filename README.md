
[![Build Status](https://travis-ci.org/DieterReuter/make-roofs-debian-arm64.svg)](https://travis-ci.org/DieterReuter/make-roofs-debian-arm64)

# rootfs-bookworm-armhf

Create and package a Debian rootfs for ARMhf 

This rootfs builder is meant to run on TravisCI only (issues with debootstrap on CircleCI).


## Using the builder with a local Vagrant (tested on OS X)
```
vagrant up --provider=virtualbox
```
or for a subsequent rebuild
```
vagrant provision
```


---
The MIT License (MIT)

Copyright (c) 2015 Dieter Reuter
