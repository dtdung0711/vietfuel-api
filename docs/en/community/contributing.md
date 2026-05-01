# Contributing to VietFuelAPI

Thank you for your interest in contributing to VietFuelAPI.

## General Principles

- This is a non-profit community project for learning and technical research.
- The project does not represent any organization, enterprise, or government agency.
- Please respect public data sources and technical limits of source websites.

## Contribution Workflow

1. Fork the repository and create a new branch from `main`.
2. Use clear branch names: `feat/...`, `fix/...`, `docs/...`, `refactor/...`.
3. Run tests before opening a Pull Request: `npm --prefix backend test`.
4. Open a Pull Request with clear details: problem, root cause, fix, impact.

## Commit Convention

- Use concise English commit messages that describe the actual change.
- Recommended format: `type(scope): short summary`.
- Example: `fix(pvoil): harden fallback parser against cloudflare-protected source`.

## Code Comment Convention

- All new comments should be written in Vietnamese with diacritics.
- Use this format consistently: `// [SECTION] Short and clear explanation.`
- Prioritize comments for complex logic, fallback paths, business mapping, anti-bot handling, and error flows.
- Avoid comments that merely repeat obvious code behavior.

See also: `docs/vi/guides/comment-style.md`.

## Code Rules

- Do not include sensitive information (tokens, cookies, credentials) in code.
- Do not commit runtime files: logs, HTML dumps, dynamic cache files.
- For scraper changes: minimize source load, add safe fallback logic, and keep metadata explicit.

## Pull Request Checklist

- [ ] Backend tests are passing.
- [ ] Related docs are updated (if needed).
- [ ] No unnecessary debug/runtime files are included.
- [ ] Vietnamese comment convention is respected.
- [ ] Legal impact is described if disclaimer/legal docs were changed.

## Bug Reports

When creating an issue, please include:

- Affected endpoint.
- Related data source.
- Error logs (if available).
- Reproduction steps.

Thank you for helping make this community project more stable.
