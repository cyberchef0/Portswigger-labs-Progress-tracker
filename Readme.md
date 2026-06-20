# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-39-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--06--16-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-14%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 19 of 61
- **Practitioner**: 20 of 174
- **Expert**: 1 of 39

## Categories Covered

- **Authentication vulnerabilities**: 4/14 lab
- **SQL injection**: 4/18 lab
- **Access control**: 5/13 lab
- **Cross-site request forgery (CSRF)** 1/12 lab
- **Cross-site scripting** 15/30 
- **Prototype pollution** 10/10
- **GraphQL API vulnerabilities** 3/5
- **API testing** 3/5
- **DOM-based vulnerabilities** 1/7

## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic          | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-15 | Prototype pollution     | Detecting server-side prototype pollution without polluted property reflection | PRACTITIONER | N/A |
| 2  | 2026-06-15 |  Prototype pollution    | Bypassing flawed input filters for server-side prototype pollution | PRACTITIONER | N/A |
| 3  | 2026-06-15 |  Prototype pollution    | Remote code execution via server-side prototype pollution | PRACTITIONER | N/A |
| 4  | 2026-06-15 |  Prototype pollution    | Exfiltrating sensitive data via server-side prototype pollution | Expert | N/A |
| 5  | 2026-06-16 |   Cross-site scripting  |  DOM XSS in document.write sink using source location.search inside a select element | PRACTITIONER | N/A |
| 6  | 2026-06-16 |  DOM-based vulnerabilities   | DOM-based cookie manipulation | PRACTITIONER | N/A |
| 7  | 2026-06-18 |  SQL injection  | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | APPRENTICE | N/A |
| 8  | 2026-06-18 |  SQL injection   | SQL injection vulnerability allowing login bypass | APPRENTICE | N/A |
| 9  | 2026-06-18 |  SQL injection   | SQL injection UNION attack, determining the number of columns returned by the query | PRACTITIONER | N/A |
| 10  | 2026-06-18 |  SQL injection   | Blind SQL injection with conditional errors | PRACTITIONER | N/A |
| 11  | 2026-06-18 |  XSS   |DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded| PRACTITIONER | N/A |
| 12  | 2026-06-18 |   XSS  | PRACTITIONER Reflected DOM XSS| PRACTITIONER | N/A |
| 13  | 2026-06-18 |  XSS   | Stored DOM XSS | PRACTITIONER | N/A |
| 14  | 2026-06-18 |  XSS   | Reflected XSS into HTML context with most tags and attributes blocked| PRACTITIONER | N/A |
| 15  | 2026-06-18 |     |  | PRACTITIONER | N/A |
| 16  | 2026-06-18 |     |  | PRACTITIONER | N/A |
| 17  | 2026-06-18 |     |  | PRACTITIONER | N/A |
| 18  | 2026-06-18 |     |  | PRACTITIONER | N/A |
| 19  | 2026-06-18 |     |  | PRACTITIONER | N/A |

