This project presents a vulnerability assessment of a public web application using ethical, read-only techniques. The objective was to identify common security weaknesses, classify risks, and provide practical remediation recommendations.

🛠️ Tools Used
Nmap – for port and service analysis
OWASP ZAP (Passive Scan) – for identifying web security misconfigurations
Browser Developer Tools – for inspecting HTTP headers and client-side behavior
🔍 Key Findings
Open port 8080 increasing the attack surface
Technology disclosure (Apache Tomcat / JSP)
Missing security headers (CSP, X-Frame-Options, HSTS)
No HTTPS enforcement (HTTP access allowed)

⚠️ Approach
All testing was conducted using passive and non-intrusive methods in accordance with ethical security practices.
