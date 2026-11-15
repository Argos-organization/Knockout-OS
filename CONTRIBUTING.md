

# Contributing to Knockout OS

Thank you for your interest in contributing to Knockout OS!

Knockout OS is a Debian-based Linux distribution designed to provide a reliable, accessible and customizable operating system.

All contributions are welcome, whether they involve code, documentation, testing, bug reports or suggestions.

## Before contributing

Please read the following documents:

- [README.md](README.md) — Project overview.
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) — Community expectations.
- [LICENSE](LICENSE) — Project licensing.
- [docs/PROJECT_SPEC.md](docs/PROJECT_SPEC.md) — Project specifications.

If you are unsure about a proposed change, open an issue before starting work.

## Reporting bugs

When reporting a bug, please include:

- A clear and descriptive title.
- Steps to reproduce the problem.
- Expected behavior.
- Actual behavior.
- Relevant logs or error messages.
- Your Knockout OS version and system architecture, if applicable.

Please avoid including passwords, private keys or other sensitive information.

## Suggesting features

Feature requests should explain:

- The problem or need being addressed.
- The proposed solution.
- Why the feature would benefit Knockout OS.
- Any potential drawbacks or compatibility concerns.

Large changes should be discussed before implementation.

## Pull requests

1. Fork the repository.
2. Create a dedicated branch for your changes.
3. Keep changes focused and avoid unrelated modifications.
4. Update documentation when necessary.
5. Test your changes as far as reasonably possible.
6. Open a Pull Request against the appropriate branch.
7. Explain what changed and why.

Pull Requests should be clear, constructive and easy to review.

## Development guidelines

- Respect the existing project architecture and specifications.
- Prefer simple, maintainable and well-documented solutions.
- Avoid unnecessary dependencies.
- Consider both `amd64` and `arm64` compatibility.
- Do not commit generated build artifacts, disk images, private keys or local configuration files.
- Respect the licenses of third-party software and components.

Knockout OS currently uses Debian Stable as its base and `live-build` for its initial image-building process. Development decisions may evolve as the project progresses.

## Commit messages

Use clear and descriptive commit messages.

Prefixes such as `feat:`, `fix:`, `docs:`, `build:` and `refactor:` are encouraged.

Examples:

- `docs: update installation instructions`
- `fix: correct package configuration`
- `build: update live-build configuration`

## Code of Conduct

By participating in this project, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

Contributors are expected to communicate respectfully and constructively.

## Questions

If you have questions about contributing, open a GitHub issue or start a discussion in the repository.

Thank you for helping improve Knockout OS!
