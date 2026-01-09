\# CampusConnect Vulnerability Lab – CA3 Project



⚠️ \*\*Disclaimer\*\*  

This project is intentionally vulnerable and developed \*\*strictly for academic and educational purposes\*\*.  

It must \*\*NOT\*\* be deployed in a production environment.



---



\## 📌 Project Overview



\*\*CampusConnect Vulnerability Lab\*\* is a deliberately vulnerable full-stack web application designed to demonstrate \*\*real-world web application security issues\*\*.  

The project follows a \*\*DVWA-style (Damn Vulnerable Web Application)\*\* approach where multiple OWASP Top 10 vulnerabilities are intentionally implemented and demonstrated.



This project was developed as part of the \*\*CA3 academic requirement\*\* to gain practical exposure to \*\*web security testing and exploitation\*\*.



---



\## 🎯 Objectives



\- To understand real-world web application vulnerabilities  

\- To implement OWASP Top 10 security risks  

\- To demonstrate security attacks on localhost  

\- To differentiate frontend vs backend security flaws  

\- To understand the importance of secure coding practices  



---



\## 🏗️ Technology Stack



\### Frontend

\- HTML

\- CSS

\- JavaScript



\### Backend

\- Python (Flask Framework)



\### Database

\- SQLite



\### Environment

\- Localhost (127.0.0.1)



---



📂 Repository Structure



\- Backend source code: `app.py`

\- Frontend HTML templates: `templates/`

\- Frontend CSS and JavaScript: `static/`

\- Database file: `campus.db`



These files together implement the complete vulnerable web application.

\## 📸 Screenshots and Demonstration



All screenshots showing the working of the application and exploitation

of vulnerabilities are stored in the following directory:



\- `screenshots/`



Each screenshot is clearly named and mapped to a specific vulnerability.



Detailed explanation of each screenshot is provided in:



\- `demonstration/screenshots.md`



\## 🚨 Vulnerabilities Implemented (OWASP Top 10)



| No | Vulnerability | Description |

|----|---------------|------------|

| 1 | SQL Injection | Login bypass and marks data extraction |

| 2 | Broken Authentication | User impersonation via URL |

| 3 | Stored XSS | Persistent script execution |

| 4 | Reflected XSS | Script execution via URL input |

| 5 | IDOR | Unauthorized object access |

| 6 | Sensitive Data Exposure | Plain-text credentials |

| 7 | Security Misconfiguration | Open admin panel |

| 8 | Verbose Error Messages | Internal system info leakage |



🧪 Testing



All vulnerability test cases, payloads, and results are documented in:



🧪 Testing and Documentation



\- Vulnerability test cases and attack payloads:

  - `testing/test\\\_cases.md`



Each test case includes:

\- Attack payload

\- Target module

\- Expected behavior

\- Actual result

\- Vulnerability status



---



\## 📸 Demonstration



All working screenshots proving the vulnerabilities are stored in:



\- Detailed project documentation:

  - `documentation/report.md`



