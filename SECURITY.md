# Security Policy

## Supported Scope

Security fixes are handled for the default branch of this repository.

## Reporting a Vulnerability

Do not open public issues for suspected secrets, credentials, or exploitable vulnerabilities.
Report privately to the repository owner or organization maintainer.

Include:
- affected file, service, or workflow
- observed impact
- reproduction steps if safe
- whether any credential may need rotation

## Secret Handling

Real secrets must not be committed.
Use `.env.example` only for placeholders and keep local `.env` files untracked.

If a real secret was committed:
1. rotate it first
2. remove or redact the committed value
3. decide separately whether git history cleanup is required
