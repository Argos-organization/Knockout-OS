# Security Policy

## Supported Versions

Knockout OS is currently under active development.

At this stage, only the latest development version is considered supported for security fixes.

| Version                    | Supported |
| -------------------------- | --------- |
| Latest development version | Yes       |
| Older development versions | No        |
| Unreleased versions        | No        |

## Reporting a Vulnerability

If you discover a security vulnerability in Knockout OS, please **do not create a public GitHub issue** containing technical details of the vulnerability.

Instead, report the issue privately to the project maintainers.

The report should contain, when possible:

* A short description of the vulnerability.
* The affected component or version.
* Steps required to reproduce the issue.
* The potential security impact.
* Any possible mitigation or fix you have identified.

Please avoid including passwords, private keys, personal information, or other sensitive information in the report.

## Security Response

The maintainers will review security reports and attempt to:

1. Confirm and reproduce the vulnerability.
2. Determine its severity and affected components.
3. Develop or coordinate an appropriate fix.
4. Test the fix.
5. Release the fix when appropriate.
6. Publish relevant information about the vulnerability after a fix is available.

Security reports will be handled confidentially as reasonably possible.

## Security Development Principles

Security is considered part of the design of Knockout OS.

The project aims to:

* Follow the principle of least privilege.
* Minimize unnecessary privileges.
* Protect user data and credentials.
* Avoid storing secrets in the source repository.
* Review dependencies for known vulnerabilities.
* Keep dependencies reasonably up to date.
* Test security-sensitive components.
* Separate user privileges where possible.
* Avoid exposing unnecessary system services.
* Document important security decisions.

## Secrets

Never commit the following to the repository:

* Passwords.
* API keys.
* Private keys.
* Authentication tokens.
* Personal credentials.
* Production secrets.
* `.env` files containing real secrets.

Use local configuration or a dedicated secret-management mechanism instead.

## Third-Party Components

Knockout OS uses third-party software and libraries.

Security issues affecting third-party components should be evaluated according to their respective security policies and licenses.

Relevant third-party components and their licensing information are documented in `THIRD_PARTY_LICENSES/`.

## Scope

This policy applies to security issues affecting Knockout OS source code, build tools, official scripts, system services, desktop components, and other software maintained by the project.

Issues exclusively affecting third-party software should generally be reported to the relevant upstream project as well.

