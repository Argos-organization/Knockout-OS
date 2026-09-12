# Security Policy

## Supported Versions

Knockout OS is currently under active development.

| Version                    | Supported |
| -------------------------- | --------- |
| Latest development version | Yes       |
| Older versions             | No        |

## Reporting a Vulnerability

If you discover a security vulnerability in Knockout OS, please report it privately.

**Do not create a public GitHub issue containing details of an undisclosed vulnerability.**

Security vulnerabilities should be reported through GitHub's private vulnerability reporting system, when available for this repository.

If private vulnerability reporting is unavailable, contact the project maintainers privately through the repository's available contact methods.

## What to Include

Please provide, when possible:

* A clear description of the vulnerability.
* The affected component and version.
* Steps to reproduce the issue.
* The potential security impact.
* Any suggested mitigation or fix.

Do not include passwords, private keys, personal information, or other unnecessary sensitive data.

## Security Response

The maintainers will:

1. Review the report.
2. Attempt to reproduce the issue.
3. Assess its severity and impact.
4. Develop and test an appropriate fix.
5. Release the fix when appropriate.
6. Communicate relevant information about the vulnerability after remediation.

The project will make reasonable efforts to keep vulnerability reports confidential until an appropriate resolution is available.

## Security Principles

Knockout OS aims to:

* Follow the principle of least privilege.
* Minimize unnecessary privileges.
* Protect user data and credentials.
* Avoid storing secrets in the source repository.
* Review dependencies for known vulnerabilities.
* Keep dependencies reasonably up to date.
* Test security-sensitive components.
* Separate user privileges where possible.
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

## Third-Party Components

Knockout OS uses third-party software and libraries.

Security issues affecting third-party components should be evaluated according to their respective security policies.

Relevant third-party components and their licensing information are documented in `THIRD_PARTY_LICENSES/`.

## Scope

This policy applies to security issues affecting Knockout OS source code, build tools, official scripts, system services, desktop components, and other software maintained by the project.
