### Ethical Hacking Technical Report
**Client:** SecureTech
**Date:** May 7, 2024
**Prepared by:** Vinz Christian Margate and Shiela A. Clorado

**Executive Summary**
This report outlines vulnerabilities discovered during an ethical hacking assessment of SecureTech. The vulnerabilities listed below pose significant risks to the security and integrity of the website and its data. Recommendations for remediation are provided to address these vulnerabilities and improve overall security.

**Vulnerabilities**
1.	SQL Injection (High Risk)
    - Description: The website is vulnerable to SQL injection attacks, allowing attackers to execute malicious SQL queries.
    - 	Recommendation: Implement input validation and use parameterized queries to prevent SQL injection attacks.

2.	Cross-Site Scripting (XSS) (Medium Risk)
    -	Description: The website does not adequately sanitize user input, leading to potential XSS attacks.
    -	Recommendation: Implement output encoding and sanitize user input to prevent XSS attacks.

3.	Insecure Direct Object References (IDOR) (High Risk)
    -	Description: The website exposes sensitive data through insecure direct object references, allowing unauthorized access to resources.
    -	Recommendation: Implement access controls and validate user permissions to prevent IDOR vulnerabilities.

4.	Weak Password Policy (Medium Risk)
    -   Description: The website allows weak passwords, increasing the risk of unauthorized access and brute force attacks.
    -	Recommendation: Enforce strong password policies with minimum length, complexity requirements, and account lockout mechanisms.



5.	Missing Security Headers (Low Risk)
    -	Description: The website lacks essential security headers such as Content Security Policy (CSP) and Strict-Transport-Security (HSTS).
    -	Recommendation: Implement security headers to enhance protection against various web-based attacks.

6.	Sensitive Data Exposure (High Risk)
    - Description: The website exposes sensitive information such as user credentials or session tokens in cleartext or weakly encrypted formats.
    -	Recommendation: Encrypt sensitive data both at rest and in transit using strong encryption algorithms.

7.	Outdated Software (Medium Risk)
    -	Description: The website is running outdated software versions with known vulnerabilities.
    -	Recommendation: Regularly update software and apply security patches to mitigate known vulnerabilities.

8.	File Upload Vulnerability (Medium Risk)
    -	Description: The website allows file uploads without proper validation, potentially leading to malicious file execution.
    -	Recommendation: Implement file type verification, size limits, and malware scanning for uploaded files.

9.	Session Management Issues (High Risk)
    -	Description: The website has weaknesses in session management, such as predictable session tokens or session fixation vulnerabilities.
    -	Recommendation: Use secure session management practices, including random session tokens, session expiration, and HTTPS.

 **Recommendations for Remediation**
1.	Conduct a comprehensive security audit of the entire website to identify and address vulnerabilities.
2.	Implement a web application firewall (WAF) to protect against common web-based attacks.
3.	Train developers and administrators on secure coding practices and security best practices.
4.	Perform regular penetration testing and vulnerability assessments to proactively identify and mitigate security risks.
5.	Monitor and log security events to detect and respond to potential security incidents in a timely manner.
6.	Develop and maintain an incident response plan to effectively respond to security breaches or incidents.

**Conclusion:** Addressing the vulnerabilities outlined in this report is crucial to improving the overall security posture of SecureTech. By implementing the recommended remediation measures and adopting a proactive approach to security, SecureTech can significantly reduce the risk of security breaches and protect sensitive data.

Signature: 
![](/images/signature1.png)![](/images/signature2.png)
