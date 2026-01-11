\# CampusConnect Vulnerability Lab – Testing



This document contains all test cases used to validate vulnerabilities

implemented in the application.



---



\## Test Case 1: SQL Injection – Login Bypass

\*\*Payload:\*\*

' OR '1'='1' --



\*\*Expected Result:\*\*

Login should fail



\*\*Actual Result:\*\*

Login bypass successful



\*\*Status:\*\* Vulnerable



---



\## Test Case 2: Broken Authentication

\*\*URL:\*\*

/dashboard?user=admin



\*\*Expected Result:\*\*

Access denied



\*\*Actual Result:\*\*

Admin dashboard accessed



\*\*Status:\*\* Vulnerable



---



\## Test Case 3: SQL Injection – Marks Data Exposure

\*\*Payload:\*\*

' OR '1'='1' --



\*\*Expected Result:\*\*

Only user marks displayed



\*\*Actual Result:\*\*

All student marks exposed



\*\*Status:\*\* Vulnerable



---



\## Test Case 4: Stored XSS

\*\*Payload:\*\*

<script>alert('XSS')</script>



\*\*Expected Result:\*\*

Input sanitized



\*\*Actual Result:\*\*

Script executed for all users



\*\*Status:\*\* Vulnerable



---



\## Test Case 5: Reflected XSS

\*\*Payload:\*\*

<script>alert('XSS')</script>



\*\*Expected Result:\*\*

Input escaped



\*\*Actual Result:\*\*

Immediate script execution



\*\*Status:\*\* Vulnerable



---



\## Test Case 6: IDOR

\*\*URL:\*\*

/profile?id=2



\*\*Expected Result:\*\*

Access restricted



\*\*Actual Result:\*\*

Unauthorized user data accessed



\*\*Status:\*\* Vulnerable



---



\## Test Case 7: Admin Panel Exposure

\*\*URL:\*\*

/admin



\*\*Expected Result:\*\*

Authentication required



\*\*Actual Result:\*\*

Admin panel accessible without login



\*\*Status:\*\* Vulnerable



