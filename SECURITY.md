# Security Policy

## Supported Versions

Korers is currently in pre-release. There is no stable version yet.
Security reports are accepted for the current development state.

| Version | Supported |
|---|---|
| Pre-release (Q3 2026) | Yes |

---

## Reporting a Vulnerability

If you discover a security vulnerability in Korers, please do not open a public GitHub issue.

Public disclosure before a fix is available puts users at risk.

**Report privately via GitHub:**

Go to the Security tab of this repository and click "Report a vulnerability".
This opens a private channel between you and the maintainer.

**What to include:**

- Description of the vulnerability
- Steps to reproduce
- Potential impact in your assessment
- Any suggested fix if you have one

---

## What to Expect

- Acknowledgement within 72 hours
- Status update within 7 days
- Fix timeline communicated as soon as the scope is clear
- Credit in the changelog if you want it

---

## Scope

In scope:

- Core encryption and key derivation
- Vault storage and access control
- Browser extension security
- SSO and SCIM implementation
- Audit log integrity
- Mobile app and bridge communication

Out of scope:

- Vulnerabilities in third-party dependencies that have already been reported upstream
- Issues that require physical access to an already unlocked device
- Social engineering attacks against users

---

## Philosophy

Korers is built on the assumption that security should be verifiable, not trusted blindly.
The source code will be public. Audits are welcome.
If something is wrong, we want to know before anyone else does.
