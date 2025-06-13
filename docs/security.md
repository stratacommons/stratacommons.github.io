---
description: "StrataCommons - Security"
layout: default
nav_order: 2
title: StrataCommons - Security
---

# StrataCommons - Security
{: .no_toc }

At StrataCommons we follow industry best practices around security and privacy:

**Data Encryption**: All data is encrypted both in transit (via HTTPS/TLS) and at rest using industry-standard encryption methods.

**Granular Access Control**: All access to the software is governed by role based access control, and protected with explicit authorization policies.

**Strong Password Security**: All user passwords are individually salted and hashed using secure cryptographic algorithms.

**Hardened Server Infrastructure**: Our application runs on hardened Linux servers configured with the principle of least privilege and ongoing patch management.

**Logging and Monitoring**: We use logging and monitoring tools to detect anomalies, failed logins, and potential abuse patterns.

**Least Privilege Access**: Developer and admin access to production systems is tightly controlled and audited, following the least-privilege principle.

**Comprehensive Audit Trails**: We track key security-relevant actions (e.g., logins, changes to salient data, permission changes) for audit and compliance.

**Data Backups**: All data is backed up daily for business continuity.

**Software Security Updates**: We apply security updates frequently to all layers of the software stack.

**Secure and Trusted Hosting**: All StrataCommons servers are located in Canada. Our hosting provider OVH is subject to strong European privacy protections and committed to [security best practices](https://corporate.ovhcloud.com/en/trusted-cloud/security-certifications/).

**Network Security**: All traffic to and from our servers uses secure network protocols and is protected by firewalls and virtual private networks.

**Static Code Analysis**: We continuously scan our software with Brakeman, a leading static analysis tool, to proactively detect security vulnerabilities.

**Secure Software Supply Chain**: All software dependencies are monitored and audited via bundler-audit, GitHub's Dependabot, and security advisories to ensure no known vulnerabilities are introduced.

**Input data validation and sanitization**: All input data is rigorously validated and sanitized to prevent injection attacks (e.g., SQL injection) and cross-site scripting (XSS), adhering to OWASP guidelines.

**Environment Segregation**: We use separate environments for development, staging, and production to ensure that no development data or credentials are exposed in production or vice versa.

**Incident Response Ready**: We maintain and periodically test an incident response plan to quickly mitigate and respond to security issues.

**Experienced Staff**: All StrataCommons software developers and system administrators have deep industry experience and follow security best practices when working on StrataCommons.
