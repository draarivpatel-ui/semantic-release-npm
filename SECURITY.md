# Security policy

## Reporting a vulnerability

Use the private GitHub Security Advisory form at [Report a vulnerability](https://github.com/draarivpatel-ui/semantic-release-npm/security/advisories/new). Do not open a public issue, pull request or discussion with exploit details.

Never include a live secret, token, cookie, private key or personal data in a report. Use synthetic values and redacted transcripts.

## Supported versions

| Version               | Status    |
| --------------------- | --------- |
| latest default branch | Supported |

Security fixes are applied to the latest state of the default branch.

## Scope

This policy covers the npm publishing plugin implementation, its trusted-publishing and registry authentication logic, unit and integration tests, and repository automation. In scope are registry credential exposure, token redaction failures, package-private bypasses, publish boundary confusion and malicious registry interaction flaws. Vulnerabilities in the npm registry itself, GitHub or a caller-provided semantic-release configuration are out of scope.

## Coordinated disclosure

- Acknowledgment within 3 business days.
- Initial triage within 14 calendar days.
- Fix or mitigation target within 90 calendar days for confirmed reports.
- Public disclosure timing is coordinated with the reporter, normally within 90 days.
