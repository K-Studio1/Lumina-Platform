# Security Policy

## Supported Versions
| Version | Supported |
|---------|-----------|
| 3.4.x   | ✅ |
| < 3.4   | ❌ |

## Reporting a Vulnerability
If you find a security vulnerability, please **do NOT** open a public issue.

Report privately to:
- Email: dzulfadhil33333@gmail.com
- TikTok: @kstduioofficial

We will respond within 48 hours and patch critical issues within 7 days.

## Security Measures
- PBKDF2 password hashing (100k iterations)
- Rate limiting on all endpoints
- Input sanitization & XSS protection
- CORS whitelist
- Session expiry & inactivity timeout
