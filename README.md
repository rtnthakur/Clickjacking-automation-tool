# ⚡ CJ-Hunter: Clickjacking Vulnerability Scanner

![License](https://img.shields.io/badge/License-MIT-green)
![Version](https://img.shields.io/badge/Version-3.0-blue)
![Language](https://img.shields.io/badge/Language-HTML%2FJS-orange)
![Purpose](https://img.shields.io/badge/Purpose-Educational-red)

**CJ-Hunter** is a lightweight, browser-based penetration testing tool designed to detect **Clickjacking (UI Redress)** vulnerabilities. It allows security researchers and bug bounty hunters to rapidly test single URLs or bulk lists of targets using a visual Proof of Concept (PoC) dashboard.

---

## ⚠️ Disclaimer

> **PLEASE READ BEFORE USE**
>
> This tool is developed for **EDUCATIONAL PURPOSES** and **ETHICAL SECURITY TESTING** only.
>
> * Do not use this tool on websites you do not own or do not have explicit permission to test.
> * The developer (**rtnthakur**) is not responsible for any misuse or damage caused by this program.
> * By downloading or using this software, you agree to obey all applicable local and international laws regarding cybersecurity.

---

## 🚀 Key Features

* **⚡ Quick Single Test:** Instantly test a specific URL.
* **📂 Bulk Scanning:** Upload a `.txt` file containing a list of URLs to queue multiple targets.
* **🤖 Auto-Scan Mode:** Automatically cycles through the target list with adjustable speeds (Fast/Normal).
* **👁️ Visual PoC:** Embeds the target in a frame to visually confirm if the site permits framing (the core indicator of Clickjacking).
* **📝 CSV Reporting:** Export your findings (Vulnerable/Safe/Untested) into a clean CSV report for documentation.
* **📚 Built-in Knowledge Base:** Includes an info panel with vulnerability descriptions, business impact, and remediation code snippets (X-Frame-Options/CSP).
* **🔒 Client-Side Only:** Runs entirely in your browser using HTML5 & JavaScript. No data is sent to external servers.

---

## 🛠️ How to Use
### Running a Scan
1.  **Single Target:** Enter a URL (e.g., `google.com`) in the "Quick Add" box and click `+ TEST NOW`.
2.  **Bulk Scan:** Click "Choose File" and upload a `.txt` file containing a list of URLs (one per line).
3.  **Start Scan:** Select your scan speed and click `▶ START SCAN`.
4.  **Verification:**
    * If the website **loads** inside the frame: **VULNERABLE** (Click "YES (Vuln)").
    * If the website **refuses to connect** or shows an error: **SAFE** (Click "NO (Safe)").
5.  **Export:** Click `⬇ CSV REPORT` to save your results.

---
