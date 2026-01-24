# Xenial Builder
This container is based on Ubuntu 16.04, intended to provide a sufficiently
old build environment to compile C programs that will run on machines with
at least GLIBC version 2.23 and related requirements of that era.
The end goal is binary portability.

## Changes from Base
- Fixed the mirror list for APT since Xenial is EOL.
- Provided `build-essenital` and `ca-certificates` packages.
