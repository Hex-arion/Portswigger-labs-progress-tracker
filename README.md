# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-0-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--00--00-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-0%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 7 of 61
- **Practitioner**: 15 of 174
- **Expert**: 2 of 39

## Categories Covered

- **Authentication vulnerabilities**: 12/14 lab
- **SQL injection**: 3/18 lab
- **Path Traversal**: 6/6 lab
- **Command Injection**: 3/5 lab
- **Access control**: 0/13 lab

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
| 1  | 2026-06-24 | Authenticaion  | Username enumeration via different response | APPRENTICE  | N/A |
| 2  | 2026-06-24 | Authenticaion  | Username enumeration via subtly different responses | PRACTITIONER | N/A |
| 3  | 2026-06-27 | Authenticaion  | Username enumeration via response timing    | PRACTITIONER | N/A |
| 4  | 2026-06-27 | Authenticaion  | Broken brute-force protection, IP block     | PRACTITIONER | N/A |
| 5  | 2026-06-27 | Authenticaion  | Username enumeration via account lock | PRACTITIONER | N/A |
| 6  | 2026-06-27 |  Authenticaion  | Broken brute-force protection, multiple credentials per request | EXPERT | N/A |
| 7  | 2026-06-27 | Authenticaion    | 2FA simple bypass | APPRENTICE | N/A |
| 8  | 2026-06-28 | Authenticaion    | 2FA broken logic | PRACTITIONER | N/A |
| 9  | 2026-06-28 | Authenticaion    | 2FA bypass using a brute-force attack | EXPERT | N/A |
| 10 | 2026-06-28 | Authenticaion    | Brute-forcing a stay-logged-in cookie | PRACTITIONER | N/A |
| 11 | 2026-06-28 | Authenticaion    | Password reset broken logic | APPRENTICE | N/A |
| 12 | 2026-06-28 | Authenticaion    | Password brute-force via password change | PRACTITIONER | N/A |
| 13 | 2026-07-03 |  Path Traversal   | File path traversal, simple case | APPRENTICE | N/A |
| 14 | 2026-07-03 |  Path Traversal   | File path traversal, traversal sequences blocked with absolute path bypass | PRACTITIONER | N/A |
| 15 | 2026-07-03 |  Path Traversal   | File path traversal, traversal sequences stripped non-recursively | PRACTITIONER | N/A |
| 16 | 2026-07-03 |  Path Traversal   | File path traversal, traversal sequences stripped with superfluous URL-decode | PRACTITIONER | N/A |
| 17 | 2026-07-05 |  Path Traversal | File path traversal, validation of start of path  | PRACTITIONER | N/A |
| 18 | 2026-07-05 |  Path Traversal  | File path traversal, validation of file extension with null byte bypass | PRACTITIONER | N/A |
| 19 | 2026-07-05 |  SQL injection  | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | APPRENTICE | N/A |
| 20 | 2026-07-05 |  SQL injection  | SQL injection vulnerability allowing login bypass | APPRENTICE | N/A |
| 21 | 2026-07-05 |  SQL injection  | SQL injection attack, querying the database type and version on Oracle | PRACTITIONER | N/A |
| 22 | 2026-07-05 |  Command Injection  | OS command injection, simple case | APPRENTICE | N/A |
| 23 | 2026-07-05 |  Command Injection  | Blind OS command injection with time delays | PRACTITIONER | N/A |
| 24 | 2026-07-05 | Command Injection | Blind OS command injection with output redirection | PRACTITIONER | N/A |
| 25 | 2026-00-00 |  |  |  | N/A |
| 26 | 2026-00-00 |  |  |  | N/A |
| 27 | 2026-00-00 |  |  |  | N/A |
-++






















