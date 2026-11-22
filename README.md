# OWASP Juice Shop Security Testing

## Overview

This repository documents a structured web application security assessment conducted against OWASP Juice Shop within a controlled educational lab environment.

The project focused on identifying, validating, and documenting common web application vulnerabilities using manual testing methodologies and Burp Suite-based analysis.

The assessment included:
- Web exploitation
- Authentication testing
- Injection attacks
- Authorization analysis
- Client-side vulnerability testing
- Security misconfiguration analysis
- Mitigation documentation

---

# Objectives

- Perform structured web application penetration testing
- Identify vulnerabilities from the OWASP Top 10 category
- Practice manual vulnerability verification techniques
- Analyze insecure authentication mechanisms
- Document exploitation workflows and mitigations
- Improve professional security reporting skills

---

# Vulnerabilities Identified

## Cross-Site Scripting (XSS)
- Stored XSS
- DOM-Based XSS
- Reflected XSS

## Injection Vulnerabilities
- UNION-Based SQL Injection
- Authentication Bypass via SQL Injection

## Authentication Weaknesses
- Brute Force Authentication Attack
- Weak Password Recovery Mechanisms

## Security Misconfigurations
- Broken CORS Configuration
- Missing Authorization Controls

## Other Vulnerabilities
- Cross-Site Request Forgery (CSRF)
- Server-Side Request Forgery (SSRF)

---

# Tools Used

- Burp Suite
- Burp Intruder
- Browser Developer Tools
- Google Chrome
- OWASP Juice Shop
- Kali Linux

---

# Testing Methodology

The assessment included:

- Request interception and modification
- Header manipulation
- Payload injection
- Authorization testing
- Authentication testing
- Client-side vulnerability validation
- Input validation analysis
- Manual exploitation verification

Each vulnerability was documented with:
- Exploitation steps
- Security impact
- Supporting evidence
- Mitigation recommendations

---

# Skills Demonstrated

- Web Application Security Testing
- Burp Suite Usage
- SQL Injection Testing
- XSS Testing
- SSRF Testing
- CSRF Analysis
- Authentication Testing
- Authorization Testing
- Security Reporting
- Vulnerability Documentation

---

# Repository Structure

```text
owasp-juice-shop-security-testing/
│
├── README.md
│
└── reports/
    ├── web-vulnerabilities-assessment-report.pdf
    └── advanced-authentication-and-injection-testing-report.pdf
```

The assessment evidence (steps, impact and mitigations for each finding) is contained in the two PDF reports above. Screenshots referenced in earlier drafts of this README are not included in the repository.
