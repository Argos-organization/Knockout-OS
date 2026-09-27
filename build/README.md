# Knockout OS Build System

This directory contains the configuration and documentation required to build Knockout OS images.

## Build system

Knockout OS will initially use Debian's `live-build` to generate a customized Debian-based ISO.

## Planned structure

```text
build/
├── README.md
├── config/       # live-build configuration
├── scripts/      # build helper scripts
├── output/       # generated images (ignored by Git)
└── cache/        # temporary build data (ignored by Git)
```

## Requirements

The ISO build will require a Linux build environment with:

* Debian or another compatible Linux distribution
* `live-build`
* `debootstrap`
* `xorriso`
* `qemu` for testing

The exact requirements may change during development.

## Build status

The ISO build system is not implemented yet.
