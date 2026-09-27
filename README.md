# Knockout OS

Knockout OS is a custom Linux distribution based on Debian Stable.

The project aims to provide a customizable, modern and extensible operating system while keeping Debian as its foundation.

## Status

🚧 **Early development**

The first objective is to build a customized Debian-based ISO and progressively replace or extend system components with Knockout OS components.

## Goals

* Debian Stable as the base system
* Custom Knockout OS configuration and tooling
* Custom desktop environment
* Rust components for system-level functionality
* Python components for tooling and orchestration
* Reproducible ISO builds
* Support for x86_64 and, where practical, ARM64
* Experimental and advanced features

## Architecture

The project will be developed progressively:

```text
Debian Stable
     │
     ├── Linux
     ├── systemd
     └── APT
          │
          ▼
   Knockout OS layer
          │
     ┌────┴────┐
     │         │
   Rust     Python
     │         │
     └────┬────┘
          ▼
    KO Desktop
```

This architecture is expected to evolve during development.

## Building

The ISO build system will use Debian's `live-build`.

The build environment will be set up on a Linux system before the first ISO is generated.

See [`build/README.md`](build/README.md) for build-related information.

## Repository structure

```text
.
├── build/                  # ISO build configuration
├── config/                 # Knockout OS configuration
├── scripts/                # Development and build scripts
├── packages/               # Knockout OS packages
├── docs/                   # Project documentation
├── THIRD_PARTY_LICENSES/   # Third-party license information
├── LICENSE
├── NOTICE
├── SECURITY.md
└── README.md
```

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Security

For security-related reports, see [`SECURITY.md`](SECURITY.md).

## License

Knockout OS is distributed under the Apache License 2.0 unless otherwise stated.

See [`LICENSE`](LICENSE) for the complete license text.
## SPEC 

See [`PROJECT_SPEC`](docs/PROJECT_SPEC.md) for the current project specification.
