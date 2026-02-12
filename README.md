# Cybersecurity Internship - Week 1: Security Assessment

## 📌 Overview
This repository contains the findings for **Week 1: Security Assessment** of the Cybersecurity Internship. The objective was to analyze a vulnerable web application (**OWASP Juice Shop**) to identify common security flaws using automated tools and manual testing techniques.

## 🛠️ Tools Used
- **Target App:** OWASP Juice Shop (running locally on port 3000)
- **Scanning Tool:** OWASP ZAP (Zed Attack Proxy)
- **Manual Testing:** Browser Developer Tools, SQLite3 CLI
- **OS:** Kali Linux

## 🔍 Key Findings Summary
| Vulnerability | Severity | Status |
| :--- | :--- | :--- |
| **SQL Injection** | Critical | 🔴 Identified |
| **Weak Password Hashing (MD5)** | Critical | 🔴 Identified |
| **Reflected XSS** | High | 🟠 Identified |
| **Missing Security Headers** | Medium | 🟡 Identified |
| **Improper Error Handling** | Low | 🔵 Identified |

## 📂 Repository Contents
- **[Week 1 Report](Week1_Internship.pdf):** Detailed breakdown of all vulnerabilities found, including proofs of concept and impact analysis.
- **Evidence Folder:** Contains screenshots validating the exploitation of these vulnerabilities.

## 🚀 Next Steps (Week 2)
The next phase involves patching these vulnerabilities by implementing:
- Input validation (`validator` library).
- Secure password hashing (`bcrypt`).
- HTTP security headers (`helmet.js`).
