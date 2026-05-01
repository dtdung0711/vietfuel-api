# Security Policy

## Supported Versions

Currently, only the `main` branch is supported.

## Reporting a Vulnerability

If you discover a security issue:

1. Do not disclose it publicly right away.
2. Open an issue with label `security` and include minimal exploitation details.
3. Add reproduction steps and impact level.

Maintainers will respond as quickly as possible and provide a mitigation plan.

## Security Notes

- The project does not collect user-identifying data.
- Public endpoints do not require auth tokens.
- Basic hardening is in place: `helmet`, `rate limiting`, and `cache-control`.

## Reporting Scope

Please prioritize reports related to:

- RCE / command injection.
- SSRF.
- Severe header misconfiguration.
- Sensitive data exposure.
