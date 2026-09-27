# Knockout OS — Project Specification

## Current Release

* **Version:** `0.1.0-dev`
* **Codename:** `Laura`
* **Status:** Early development

## Base System

* **Base distribution:** Debian Stable
* **Build system:** Debian `live-build`

## Supported Architectures

* `amd64`
* `arm64`

## First ISO

The first Knockout OS ISO should be:

* Live bootable
* Installable
* Directly usable after installation
* Equipped with networking, audio, USB and storage support
* Equipped with a graphical desktop environment
* Equipped with essential everyday and development software

## Desktop

**Status:** To be decided.

The first release may use an existing desktop environment while the future Knockout OS desktop is developed separately.

## Development Direction

Knockout OS will progressively add its own components on top of the Debian base.

Planned technologies include:

* Rust
* Python

The architecture will evolve during development.

## Design Principle

The first versions should prioritize a functional and maintainable system over replacing every Debian component immediately.

The project will progressively move from a customized Debian system toward a more distinct Knockout OS environment.
