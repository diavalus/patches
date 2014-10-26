patches
=======

Collection of patches I made for various software, for various reasons.

Included
--------

####mpc
A patch for `mpc` to show bitrate in `mpc status` by default.

Apply to mpc/src/status.c
```
patch -p1 status.c mpc-bitrate.patch
```
