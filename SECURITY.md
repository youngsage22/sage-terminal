# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| latest (main) | ✅ |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Open a [private security advisory](https://github.com/youngsage22/sage-terminal/security/advisories/new) on GitHub and we will respond within 48 hours.

## Upstream Security

SAGE Terminal is based on [Microsoft Terminal](https://github.com/microsoft/terminal). Security issues in the core terminal engine should also be reported to Microsoft via their [Security Response Center](https://msrc.microsoft.com/).

## Scope

Security reports relevant to SAGE Terminal include:
- Escape sequence injection or terminal hijacking via crafted output
- Vulnerabilities in SAGE-specific branding or config code
- Privilege escalation through terminal session handling

Out of scope: vulnerabilities that exist identically in upstream Microsoft Terminal without modification.
