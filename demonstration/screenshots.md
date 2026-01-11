# CampusConnect Vulnerability Lab – Demonstration

This document maps each screenshot to the corresponding functionality or security vulnerability demonstrated in the application.

---

## 1. Login Page
![Login Page](../screenshots/01_login_page.png)

Description:  
Initial login interface of the CampusConnect application.

---

## 2. JavaScript Validation
![JS Validation](../screenshots/02_js_validation.png)

Description:  
Client-side JavaScript validation implemented in the login form.

---

## 3. Normal Login
![Normal Login](../screenshots/03_normal_login.png)

Description:  
Successful login using valid student credentials.

---

## 4. SQL Injection – Login Bypass
![SQL Injection Login](../screenshots/04_sql_injection_login.png)

Description:  
Authentication bypass using SQL Injection payload in the login form.

---

## 5. Broken Authentication
![Broken Authentication](../screenshots/05_broken_auth.png)

Description:  
User impersonation by directly modifying URL parameters.

---

## 6. Normal Marks View
![Normal Marks](../screenshots/06_normal_marks.png)

Description:  
Authorized student marks displayed correctly.

---

## 7. SQL Injection – Marks Exposure
![SQL Injection Marks](../screenshots/07_sql_injection_marks.png)

Description:  
Exposure of all students’ marks using SQL Injection.

---

## 8. JavaScript Warning (Discussion Module)
![JS Warning](../screenshots/08_JS_Discussion_Warning.png)

Description:  
Client-side JavaScript warning shown during discussion input.

---

## 9. Stored XSS Attack
![Stored XSS](../screenshots/09_stored_xss.png)

Description:  
Stored Cross-Site Scripting payload executed for all users.

---

## 10. Admin Panel – Security Misconfiguration
![Admin Panel](../screenshots/10_Admin_Panel.png)

Description:  
Admin panel accessible without authentication due to misconfiguration.

---

## 11. Reflected XSS
![Reflected XSS](../screenshots/11_reflected_xss.png)

Description:  
Immediate execution of malicious script via URL input.

---

## 12. IDOR Vulnerability
![IDOR](../screenshots/12_IDOR.png)

Description:  
Insecure Direct Object Reference allowing unauthorized data access.

---

## 13. Hardcoded Credentials
![Hardcoded Credentials](../screenshots/13_Hardcoded_Credentials.png)

Description:  
Sensitive credentials exposed directly in source code.

---

## 14. Verbose Error Disclosure
![Verbose Error](../screenshots/14_Verbose_Error.png)

Description:  
Detailed system error messages revealing internal information.

---

## 15. Database Proof
![Database Proof](../screenshots/15_Database_proof.png)

Description:  
Proof of database access and backend data exposure.
