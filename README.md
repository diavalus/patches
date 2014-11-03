patches
=======

Collection of patches I made for various software, for various reasons.

Included
--------

####mpc
- Patch to show bitrate in `mpc status` by default. Apply to mpc/src/status.c
```bash
patch -p1 status.c mpc-bitrate.patch
```

- Patch to prettify the volume output - when volume was different than 100%, volume was `volume:90%` or the equivalent, therefore harder to get values with `awk` or such.
```bash
patch -p1 status.c mpc-volume.patch
```
