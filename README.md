# vulscan

`vulscan` is a lightweight, fast, and efficient command-line tool designed to scan websites for common security vulnerabilities. It helps developers and security researchers identify potential risks before malicious actors do.

## Features

* **SQL Injection (SQLi) Detection:** Scans input parameters for basic SQL injection flaws.
* **Cross-Site Scripting (XSS):** Tests forms and URL parameters for reflected XSS vulnerabilities.
* **Header Analysis:** Checks for missing security headers (e.g., `X-Frame-Options`, `Content-Security-Policy`).
* **Subdomain Enumeration:** Discovers hidden subdomains to map out the target's attack surface.
* **Concurrent Scanning:** Built for speed, allowing multiple checks to run in parallel.
* **Clean Reports:** Generates easy-to-read Markdown and JSON reports.

---

## Installation

### Prerequisites
Make sure you have [Python 3.8+](https://www.python.org/) installed.


