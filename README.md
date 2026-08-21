# FUTURE_CS_01 — Vulnerability Assessment Report

## Internship
Future Interns | Cyber Security Track
CIN: FIT/AUG26/CS10015

## Task 1: Vulnerability Assessment Report for a Live Website

## Target
- Website: http://demo.testfire.net (Altoro Mutual)
- IP Address: 44.228.249.3
- Server: Apache-Coyote/1.1
- Hosting: Amazon Web Services (us-west-2)

## Scope
Read-only / Passive analysis only. No exploitation attempted.

## Tools Used
- Nmap 7.98 — Network port scanning and service detection
- Chrome DevTools — HTTP response header inspection
- Manual browser review

## Findings Summary
| # | Vulnerability | Risk |
|---|--------------|------|
| 1 | Missing Content-Security-Policy Header | HIGH |
| 2 | Missing X-Frame-Options Header | HIGH |
| 3 | Missing Strict-Transport-Security Header | MEDIUM |
| 4 | Missing X-Content-Type-Options Header | MEDIUM |
| 5 | Missing X-XSS-Protection Header | MEDIUM |
| 6 | Server Version Disclosure (Apache-Coyote/1.1) | LOW |

## Files
- `Ayush K.pdf` — Full Vulnerability Assessment Report
- `EVIDENCE/` — Screenshots of findings

## Prepared by
Ayush K | Cyber Security Intern | August 2026
