# FUTURE_CS_01
## Cyber Security Task 1 – Vulnerability Assessment Report

Objective:
Perform a read-only vulnerability assessment of a public website and document the findings in a professional report.

Target Website:
https://demo.owasp-juice.shop

Scope:
* Public-facing resources only
* Passive security testing
* Security header analysis
* Network service enumeration

Tools Used:
* Nmap
* OWASP ZAP
* Browser Developer Tools
* SecurityHeaders.com

Findings Summary:
| ID   | Finding                         | Risk   |
| ---- | ------------------------------- | ------ |
| F-01 | Missing Content Security Policy | Medium |
| F-02 | Missing Referrer Policy         | Low    |
| F-03 | Missing Permissions Policy      | Low    |
| F-04 | Website Accessible Over HTTP    | Medium |
| F-05 | Publicly Accessible Services    | Low    |

Conclusion:
The assessment identified multiple security configuration weaknesses related to missing security headers and exposed services. Recommendations were provided to improve the overall security posture of the application.

Repository Contents:
* Vulnerability_Assessment_Report.pdf
* Evidence Screenshots
* README Documentation

Disclaimer:
This assessment was conducted using passive, read-only techniques in accordance with the task guidelines. No exploitation, denial-of-service testing, authentication bypass, or unauthorized actions were performed.
