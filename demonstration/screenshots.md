\# CampusConnect Vulnerability Lab – Demonstration



This document maps each screenshot to the corresponding

functionality or security vulnerability demonstrated in the application.



---



\## 1. Login Page

!\[Login Page](../screenshots/01\_login\_page.png)



Description:  

Initial login interface of the CampusConnect application.



---



\## 2. JavaScript Validation

!\[JS Validation](../screenshots/02\_js\_validation.png)



Description:  

Client-side JavaScript validation implemented in the login form.



---



\## 3. Normal Login

!\[Normal Login](../screenshots/03\_normal\_login.png)



Description:  

Successful login using valid student credentials.



---



\## 4. SQL Injection – Login Bypass

!\[SQL Injection Login](../screenshots/04\_sql\_injection\_login.png)



Description:  

Authentication bypass using SQL Injection payload in the login form.



---



\## 5. Broken Authentication

!\[Broken Authentication](../screenshots/05\_broken\_auth.png)



Description:  

User impersonation by directly modifying URL parameters.



---



\## 6. Normal Marks View

!\[Normal Marks](../screenshots/06\_normal\_marks.png)



Description:  

Authorized student marks displayed correctly.



---



\## 7. SQL Injection – Marks Exposure

!\[SQL Injection Marks](../screenshots/07\_sql\_injection\_marks.png)



Description:  

Exposure of all students’ marks using SQL Injection.



---



\## 8. JavaScript Warning (Discussion Module)

!\[JS Warning](../screenshots/08\_JS\_Discussion\_Warning.png)



Description:  

Client-side JavaScript warning shown during discussion input.



---



\## 9. Stored XSS Attack

!\[Stored XSS](../screenshots/09\_stored\_xss.png)



Description:  

Stored Cross-Site Scripting payload executed for all users.



---



\## 10. Admin Panel – Security Misconfiguration

!\[Admin Panel](../screenshots/10\_Admin\_Panel.png)



Description:  

Admin panel accessible without authentication due to misconfiguration.



---



\## 11. Reflected XSS

!\[Reflected XSS](../screenshots/11\_reflected\_xss.png)



Description:  

Immediate execution of malicious script via URL input.



---



\## 12. IDOR Vulnerability

!\[IDOR](../screenshots/12\_IDOR.png)



Description:  

Insecure Direct Object Reference allowing unauthorized data access.



---



\## 13. Hardcoded Credentials

!\[Hardcoded Credentials](../screenshots/13\_Hardcoded\_Credentials.png)



Description:  

Sensitive credentials exposed directly in source code.



---



\## 14. Verbose Error Disclosure

!\[Verbose Error](../screenshots/14\_Verbose\_Error.png)



Description:  

Detailed system error messages revealing internal information.



---



\## 15. Database Proof

!\[Database Proof](../screenshots/15\_Database\_proof.png)



Description:  

Proof of database access and backend data exposure.



