# Security Policy

## Supported Versions

We are currently supporting **Python 3.10+** for the `PyAccelerator-Python-Code-Toolkit-For-Developers` project.

| Version | Supported          |
| ------- | ------------------ |
| 3.10.x  | :white_check_mark: |
| 3.11.x  | :white_check_mark: |
| 3.12.x  | :white_check_mark: |
| 3.13.x+ | :white_check_mark: |

## Reporting a Vulnerability

We take security seriously. If you discover any security vulnerabilities in `PyAccelerator-Python-Code-Toolkit-For-Developers`, please report them to us immediately using the following process.

We will promptly address all valid security reports. We encourage responsible disclosure and will not pursue legal action against individuals who report vulnerabilities in good faith.

### Disclosure Process

1.  **Discover:** Identify a potential security vulnerability.
2.  **Report:** Please use the following methods to report the vulnerability:
    *   **GitHub Security Advisory:** Open a **private** security advisory on our GitHub repository. This is the preferred method as it keeps the vulnerability details confidential until a fix is available.
        *   **Link:** [Open Private Security Advisory](https://github.com/chirag127/PyAccelerator-Python-Code-Toolkit-For-Developers/security/advisories/new)
    *   **Email:** If you are unable to use the GitHub Security Advisory, you can email us at `security@example.com` (replace with actual security contact if available). Please encrypt sensitive information using our PGP key if possible (key available upon request).
3.  **Details:** In your report, please include:
    *   A clear description of the vulnerability.
    *   Affected version(s) (if known).
    *   Steps to reproduce the vulnerability.
    *   Any proof-of-concept (PoC) code or exploit details.
    *   Your suggested mitigation or fix (if any).
4.  **Triage:** We will acknowledge receipt of your report within **48 hours** and will investigate the issue promptly.
5.  **Fix:** We will work to develop and test a fix for the vulnerability.
6.  **Release:** Once a fix is ready, we will coordinate with you for a public disclosure and release the patched version.

## Security Practices

We are committed to maintaining a secure codebase. Our security practices include:

*   **Dependency Scanning:** We regularly scan our project dependencies for known vulnerabilities using automated tools integrated into our CI/CD pipeline (`uv` and `Ruff` are configured for security checks).
*   **Code Reviews:** All code changes undergo rigorous code reviews, with a focus on security best practices.
*   **Principle of Least Privilege:** We strive to implement the principle of least privilege in all components.
*   **Secure Defaults:** Where applicable, we aim to provide secure default configurations.
*   **Regular Audits:** We conduct periodic security audits of the project.
*   **Testing:** We maintain comprehensive test suites (using `Pytest`) to catch regressions, including those that could be security-related.

## Responsible Disclosure

We believe in responsible disclosure. We will publicly acknowledge your contribution if you follow this policy and help us improve the security of `PyAccelerator-Python-Code-Toolkit-For-Developers`.