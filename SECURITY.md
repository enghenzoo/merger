# Security Policy

## 🛡️ Protecting the Project

We take the security of **Merger** seriously. Although this is a showcase repository, the underlying platform is designed with security best practices in mind.

### Supported Versions

We currently support and provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

### 🔒 Security Measures

- **Authentication:** Powered by `NextAuth.js` with secure OAuth providers (GitHub, Google).
- **Data Protection:** All database interactions are handled via `Drizzle ORM` to prevent SQL injection.

## 🐛 Reporting a Vulnerability

**Please do NOT report security vulnerabilities through public GitHub Issues.**

If you discover a security vulnerability in Merger, please report it responsibly by:

1.  **Using GitHub's Private Vulnerability Reporting:** Go to the [Security tab](../../security/advisories/new) of this repository and select "Report a vulnerability".
2.  **Contacting the Maintainer:** Send a private message to the project maintainer on [GitHub](https://github.com/enghenzoo) or use the contact information on their profile.

### Please include:
- A detailed description of the vulnerability and its potential impact.
- Clear steps to reproduce the issue (PoC).
- Any supporting evidence (screenshots, logs, etc.).

All reports will be reviewed promptly, and we will work with you to resolve the issue. Thank you for helping keep Merger secure!
