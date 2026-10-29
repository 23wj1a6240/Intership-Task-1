# Vulnerability Disclosure Case Tracker

Prototype for the college assignment **"Designing a Responsible Vulnerability
Disclosure Process"** (Computer Science and Cyber Security).

**Author:** K. Naveen | **Roll No:** 23WJ1A6240

## What it does
Enter a vulnerability report, a severity, and the received date. The tracker:

- builds the seven-stage workflow (receive, acknowledge, triage, prioritize,
  remediate, communicate and disclose, review and close) with an owner per stage
- calculates proposed due dates and shows Done / Due soon / Overdue / Upcoming
- drafts the message to the researcher for each stage
- checks whether a researcher's further testing action is allowed

## Proposed targets (not legal requirements)
| Item | Target |
|---|---|
| Acknowledge | 2 business days |
| Triage | 7 days |
| Fix: Critical / High / Medium / Low | 14 / 30 / 60 / 90 days |
| Researcher updates | every 14 days (7 for Critical) |
| Public disclosure | about 90 days, or when the fix is released |

## Run it
No build step or dependencies. Open `index.html` in any modern browser.

## Publish with GitHub Pages
Repository **Settings > Pages > Deploy from branch > main / (root)**.

## References
ISO/IEC 29147, ISO/IEC 30111, NIST SP 800-216, CISA BOD 20-01,
CERT Guide to Coordinated Vulnerability Disclosure, FIRST CVSS, RFC 9116.
