# Python-Security-Header-Scanner
A Python CLI tool for checking HTTP security headers on websites.

A simple and fast Command Line Interface (CLI) tool written in Python to check for essential HTTP security headers (like HSTS and CSP) on any target website.

---

## ✨ Key Features

* **Security Header Check:** Verifies the presence of crucial HTTP security headers that mitigate common attacks like Clickjacking and XSS.
* **Vulnerability Reporting:** Issues clear warnings for headers that are either missing or weakly configured.
* **CLI Interface:** Easy to run directly from your terminal or command prompt.

---

## 🛠️ How to Run

This project primarily requires the `requests` Python library.

### 1. Requirements

Ensure you have Python 3 and the `requests` library installed:

```bash
pip install requests
