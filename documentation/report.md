# CampusConnect Vulnerability Lab – Project Documentation

## 1. Introduction
**CampusConnect Vulnerability Lab** is a deliberately vulnerable full-stack web application built for learning and demonstrating real-world web security vulnerabilities.  
Inspired by DVWA-style labs, this project helps students understand how insecure coding practices lead to exploitable attack surfaces.

---

## 2. Objective
The primary goals of this project are:

- Understand OWASP Top 10 vulnerabilities
- Design a vulnerable web application for learning
- Demonstrate live exploitation techniques on localhost
- Highlight the importance of secure coding practices

---

## 3. Technology Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python (Flask Framework)

### Database
- SQLite

---

## 4. Application Modules
The application includes the following functional modules:

- **Login Module**
- **Dashboard**
- **Marks Viewer**
- **Discussion Board**
- **Admin Panel**

---

## 5. Vulnerabilities Implemented
This lab intentionally includes multiple vulnerabilities to demonstrate exploitation techniques:

1. **SQL Injection (SQLi)**
2. **Broken Authentication**
3. **Stored Cross-Site Scripting (XSS)**
4. **Reflected Cross-Site Scripting (XSS)**
5. **Insecure Direct Object Reference (IDOR)**
6. **Sensitive Data Exposure**
7. **Security Misconfiguration**
8. **CSRF (No Protection Implemented)**

---

## 6. Impact Analysis
These vulnerabilities illustrate how insecure software design can result in:

- Unauthorized access
- Data leakage
- User impersonation
- Malicious script execution
- Privilege escalation

---

## 7. Conclusion
The *CampusConnect Vulnerability Lab* provides practical, hands-on experience in understanding and exploiting web vulnerabilities.  
It reinforces the need for secure coding standards and promotes awareness of real-world cyber attack patterns.

---

## 8. Disclaimer
This application is **intentionally vulnerable** and created **strictly for academic and research purposes**.  
Do **not** deploy or use it in production environments.

