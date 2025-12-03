# Security Policy for SpeechFlow-AI-Natural-Speech-Browser-Extension

As an Apex-mandated project, `SpeechFlow-AI-Natural-Speech-Browser-Extension` adheres to Zero-Defect principles, prioritizing security throughout the development lifecycle. This policy outlines the process for responsibly disclosing security vulnerabilities.

## 🛡️ Commitment to Security

We treat security as a paramount concern. All development follows the **Apex Technical Authority Directives** (referenced in `AGENTS.md`), emphasizing secure-by-default configurations, robust input validation, and adherence to the latest WebExtension security best practices (e.g., Content Security Policy (CSP) hardening, principle of least privilege for background scripts).

## 🚨 Supported Versions

We actively support and backport security fixes to the primary maintained version, which corresponds to the latest stable release on the `main` branch.

| Version | Status | Branch |
| :--- | :--- | :--- |
| Latest Stable | Supported | `main` |
| Previous Major | Maintenance Mode | `release/*` |

## 🔍 Reporting a Vulnerability

If you discover a security vulnerability in this repository, please follow these steps to ensure responsible disclosure:

1.  **Do Not** create a public issue or pull request detailing the vulnerability.
2.  **Contact Us Privately:** Send an email to the designated security contact immediately.

**Security Contact Email:** `security@chirag127.dev` (Placeholder for high-priority security communications).

### Required Information in Disclosure

When reporting, please include the following details to expedite our investigation:

*   **Product:** `SpeechFlow-AI-Natural-Speech-Browser-Extension`
*   **Repository URL:** `https://github.com/chirag127/SpeechFlow-AI-Natural-Speech-Browser-Extension`
*   **Vulnerability Type:** (e.g., XSS, CSP bypass, data leakage, logic flaw).
*   **Steps to Reproduce:** Clear, step-by-step instructions to replicate the issue, including browser version and extension state.
*   **Impact:** A description of the potential harm if exploited.

## 🛠️ Remediation and Disclosure Timeline

Upon receiving a valid vulnerability report, we commit to the following timeline:

1.  **Acknowledgment (T+24 Hours):** We will confirm receipt of your report.
2.  **Triage & Fix Development (Variable):** Our team will immediately begin triage and work to develop a patch based on severity.
3.  **Coordinated Disclosure:** We will not publicly disclose the vulnerability until a patch has been released or **90 days** have passed since initial notification (whichever comes first), unless otherwise agreed upon with the reporter.

## ⚙️ Development & Testing Security Measures

This project employs automated security checks as defined in our CI/CD pipeline (`.github/workflows/ci.yml`):

*   **Static Analysis:** Linting with **Biome** ensures adherence to modern, secure TypeScript coding patterns.
*   **Dependency Scanning:** Regular checks are performed during the CI process to flag known vulnerabilities in third-party libraries.
*   **Architecture Review:** Adherence to the **Feature-Sliced Design (FSD)** pattern helps compartmentalize potential risks between UI, Domain, and Data layers, limiting the blast radius of any single exploit.