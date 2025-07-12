# 🔎 Lite-VulnScanner

A lightweight Python-based vulnerability scanner designed for educational and portfolio purposes. This tool performs basic TCP port scanning on target IP addresses and generates a scan report with open ports and scan duration.

---

## 💼 Project Purpose

This scanner was built to showcase my understanding of:

- Network enumeration
- Python scripting
- Port scanning using sockets
- Timeouts, error handling, and basic report generation
- Practical cybersecurity tool development

It simulates core concepts behind tools like Nmap — in a simplified, easy-to-understand format.

---

## ⚙️ Features

- Scan common TCP ports on a given host
- Detects and logs open ports
- Generates a plain text report (`scan_report.txt`)
- Includes scan time and date
- Designed to be easily extendable (e.g., add banner grabbing or CVE lookup)

---

## 🚀 How to Use

1. **Install Python 3.x** if not already installed.
2. Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/lite-vulnscanner.git
cd lite-vulnscanner
