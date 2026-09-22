# Security Policy

## Supported Versions

We prioritize security across our open-source tools, Web API widgets, and repository scripts. The following versions are currently supported with security updates:

| Version / Component | Supported          |
| ------------------- | ------------------ |
| Main Branch (`main`)| :white_check_mark: |
| Web Widgets / Tools | :white_check_mark: |
| Historical Releases | :x:                |

---

## Reporting a Vulnerability

We take the security and integrity of our codebase, scripts, and infrastructure seriously. 

If you discover a potential security vulnerability (such as a script exploit, malicious dependency, cross-site scripting in web widgets, or unauthorized access risk), please follow these steps:

### How to Report
1. **Do NOT open a public GitHub issue** for security vulnerabilities.
2. Report the vulnerability privately by emailing **mdakibislam@gmail.com** or using [GitHub Security Advisories](https://github.com/mdakibislam/academy-of-open-science/security/advisories/new) if enabled.
3. Include as much detail as possible:
   * Description of the vulnerability or flaw.
   * Steps to reproduce or proof-of-concept (PoC).
   * Potential impact on users or the repository.

### What Happens Next
* **Acknowledgment:** We will acknowledge receipt of your report within 48 hours.
* **Assessment:** We will investigate and confirm the report.
* **Fix & Release:** If validated, a patch will be prepared and committed to the `main` branch promptly.
* **Attribution:** Once resolved, we will gladly credit you in the release notes or security advisories for your contribution (unless you prefer to remain anonymous).

---

## Educational & Data Integrity

Since AOS is an open educational repository:
* **Mathematical & Scientific Accuracy:** Errors in formulas or derivations are **not** security vulnerabilities. Please report formula errors or typos via a standard GitHub Issue or Pull Request.
* **Dependency Safety:** All Python tools and JavaScript utilities contributed to the `/tools` directory must be audited for malicious code, telemetry, or hidden tracking before submission.