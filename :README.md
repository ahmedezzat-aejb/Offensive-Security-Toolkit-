# 🛡️ Offensive Security & Penetration Testing Portfolio

Welcome to my cybersecurity portfolio repository. This collection showcases custom Python automation tools developed for authorized penetration testing, vulnerability assessment, Android static analysis, and privilege escalation auditing, alongside sample technical reporting.

---

## 📂 Repository Structure

### 1. 📄 Sample Penetration Testing Reports (`/Reports`)
* **`Web_App_Pentest_Report.md`**: A comprehensive Grey-Box Web Application & API penetration testing report aligned with **OWASP Top 10** and **PTES** standards, featuring CVSS v3.1 risk scoring, Proof-of-Concept (PoC) exploits, and actionable remediation roadmaps.

### 2. 🌐 Web Application Security (`/Web-Security`)
* **`header_auditor.py`**: Audits target web servers for critical HTTP security headers (CSP, HSTS, X-Frame-Options, etc.).
* **`sqli_scanner.py`**: Automated error-based SQL Injection vulnerability probe for URL parameters.

### 3. 🔍 Network Reconnaissance (`/Network-Recon`)
* **`port_scanner.py`**: Fast, multi-threaded TCP port scanner with service banner grabbing capabilities.

### 4. 📱 Android Application Security (`/Android-Security`)
* **`apk_manifest_audit.py`**: Static analysis tool that parses `AndroidManifest.xml` to flag high-risk permissions and exported components.

### 5. 🐧 Privilege Escalation (`/Privilege-Escalation`)
* **`linux_suid_auditor.py`**: Scans Linux file systems for SUID binaries and cross-references them against known privilege escalation vectors (GTFOBins).

---

## ⚙️ Installation & Usage

```bash
git clone https://github.com
cd Cybersecurity-Portfolio
pip install requests
```

Example usage:
```bash
python3 Web-Security/header_auditor.py https://example.com
```

---

## ⚠️ Legal Disclaimer
All scripts, tools, and sample reports in this repository are created strictly for **educational purposes, authorized security auditing, and controlled lab environments**. Unauthorized testing against systems without explicit permission is illegal.
