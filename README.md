# GRC102 Week 4 – Linux Security Audit

## Project Overview

This project documents a Linux security audit and control-assurance exercise completed as part of GRC102.

The assessment covered:

- Linux audit logging with auditd
- Critical file monitoring
- Privileged command monitoring
- Linux system log analysis using journalctl
- Security baseline assessment using Lynis
- Identification of security findings
- Continuous control monitoring
- SIEM and security automation concepts
- Governance and escalation recommendations

## Tools Used

- auditd
- auditctl
- ausearch
- aureport
- journalctl
- Lynis
- Linux command-line tools

## Key Findings

- Lynis hardening index: 65/100
- Critical file monitoring was configured for `/etc/passwd` and `/etc/shadow`
- Program execution monitoring was configured
- Privileged activity was observable through system logs
- USB storage controls require further hardening
- FireWire driver controls require further hardening
- An Elastic APT repository signature-verification issue was identified during the audit
- The Lynis version was more than four months old

## Evidence

The accompanying PDF contains the detailed audit report and evidence collected from the authorized laboratory environment.

## Disclaimer

This project was conducted in an authorized cybersecurity training/laboratory environment for educational purposes.
