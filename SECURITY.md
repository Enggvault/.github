# Security Policy

At EnggVault, we take the security of our software and the trust of our users very seriously. We appreciate the efforts of the security community to responsibly disclose vulnerabilities to us.

## Supported Versions

We actively maintain and provide security updates for the following major versions of our software. Please note that support policies may vary slightly by individual project; check specific repositories if in doubt.

| Version | Supported          |
| ------- | ------------------ |
| v2.x.x  | :white_check_mark: |
| v1.x.x  | :x:                |
| < v1.0  | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

If you believe you have found a security vulnerability in any EnggVault project, please report it to us as described below.

1. **Email us**: Send a detailed email to [security@enggvault.com].
2. **Provide details**: Please include:
   - A description of the vulnerability.
   - Steps to reproduce the issue.
   - Any potential impact.
   - Proof of concept (PoC) code if available.

### Response Timeline

We will endeavor to respond to your report within **48 hours**. 

We will keep you informed of our progress as we investigate and work on a fix.

## Responsible Disclosure Policy

We ask that you follow these guidelines for responsible disclosure:

- **Do not disclose the vulnerability publicly** until we have had a chance to investigate, fix the issue, and release an update. We typically ask for a 90-day embargo period.
- **Do not exploit the vulnerability** or use it to access data that does not belong to you.
- **Provide a reasonable amount of time** for us to resolve the issue before making it public.

## Security Best Practices

We employ several practices to ensure the security of our projects:

- Automated dependency scanning (Dependabot/Snyk).
- Static code analysis (SAST) in CI/CD pipelines.
- Mandatory code reviews for all pull requests.
- Least-privilege access controls for organization resources.

Thank you for helping keep EnggVault and our community safe!
