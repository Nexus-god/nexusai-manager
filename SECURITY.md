# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 4.1.x   | :white_check_mark: |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly:

1. **Do NOT** open a public issue
2. Email us at: security@nexus-api-tools.dev
3. Include detailed steps to reproduce
4. Allow up to 48 hours for initial response

We take security seriously and will address confirmed vulnerabilities promptly.

## Security Measures

- AES-256 encrypted local storage for all credentials
- No telemetry data leaves your machine without consent
- All API communications use TLS 1.3
- Session tokens are never stored in plaintext
- Regular dependency audits via `npm audit`
