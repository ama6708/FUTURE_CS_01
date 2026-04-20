# 🔐 Web Security Assessment – Task 1

This project presents a vulnerability assessment of a publicly accessible web application using ethical, read-only techniques.

---

## 🎯 Objective

The goal of this assessment was to:
- Identify common security weaknesses  
- Analyze exposed services and configurations  
- Classify risks in a business-friendly manner  
- Provide practical remediation recommendations  

---

## 🌐 Target Application

- https://demo.testfire.net  

This application simulates a real-world online banking platform, making it suitable for identifying common web security issues.

---

## 🛠️ Tools Used

- **Nmap** – Network scanning and port analysis  
- **OWASP ZAP (Passive Scan)** – Identifying web security misconfigurations  
- **Browser Developer Tools** – Inspecting HTTP headers, cookies, and client-side behavior  

---

## 🔍 Methodology

The assessment was conducted using a structured and non-intrusive approach:

1. Information Gathering  
2. Network Scanning  
3. Passive Vulnerability Analysis  
4. Verification of Findings  
5. Documentation and Reporting  

All activities were performed using read-only techniques without exploiting any vulnerabilities.

---

## ⚠️ Key Findings

- Open port 8080 increasing the attack surface  
- Technology disclosure (Apache Tomcat server information)  
- Missing security headers (CSP, X-Frame-Options, HSTS)  
- Lack of HTTPS enforcement  
- Improper resource handling (404 responses)  

---

## 📊 Risk Classification

All identified vulnerabilities were classified as:
- **Medium Risk** – Most findings  
- **Low Risk** – Minor configuration issues  

No critical vulnerabilities were identified.

---

## 🛡️ Recommendations

- Restrict or close unnecessary open ports  
- Hide server technology information  
- Implement standard security headers  
- Enforce HTTPS and enable HSTS  
- Ensure proper resource and configuration management  

---

## 📄 Deliverables

- Vulnerability Assessment Report (PDF)  
- Supporting screenshots and evidence  

---

## ⚠️ Ethical Considerations

This assessment was conducted using:
- Passive scanning techniques  
- Publicly accessible targets only  
- No exploitation or harmful activity  

The purpose of this project is educational and focused on improving security awareness.

---

## 💼 Author

**Ali Alkhatib**  
Cybersecurity Intern  
Future Interns
