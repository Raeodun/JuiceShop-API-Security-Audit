# Juice Shop API Security Audit

## 📌 Overview
This project is a **professional-style API security assessment** of the OWASP Juice Shop application.  
The focus was on identifying vulnerabilities in REST API endpoints and providing remediation guidance.

## 🎯 Objectives
- Perform security testing against API endpoints used by the Juice Shop web and mobile apps.
- Identify vulnerabilities using the OWASP API Security Top 10 methodology.
- Produce a client-ready report and proof-of-concept exploit demonstrations.

## 🛠 Tools & Technologies
- **Postman** – API testing
- **OWASP ZAP** – Automated scanning
- **Burp Suite (Community Edition)** – Intercepting proxy
- **jq** – JSON response parsing

## 🧪 Methodology
1. API Reconnaissance
2. Automated Vulnerability Scanning
3. Manual Exploitation
4. Documentation of Proof-of-Concept Exploits
5. Remediation Recommendations

## 🔍 Key Findings (Examples)
- **Broken Authentication (Critical)** – Session fixation via stolen cookies.
- **Excessive Data Exposure (High)** – Leakage of sensitive fields in API responses.
- **BOLA / IDOR (High)** – Unauthorized access to other users' resources.
- **Missing Rate Limiting (Medium)** – Brute force protection absent.

## 📄 Deliverables
- **[JuiceShop_API_Security_Audit.pdf](./JuiceShop_API_Security_Audit.pdf)** – Full consulting-style report.
- **/screenshots/** – API exploitation proof.
- **/tools_used.md** – List of tools & commands.

## 📚 References
- [OWASP API Security Top 10](https://owasp.org/API-Security/)
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)

---

⚠ **Disclaimer:** This project was conducted in a local lab environment on an intentionally vulnerable application.  
Do **not** attempt these techniques on systems without explicit authorization.
