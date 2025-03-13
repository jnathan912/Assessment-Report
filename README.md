**Security Vulnerability Assessment Report**

**Nine-Twelve Consulting LLC**

**March 12, 2025**
________________________________________
**1. Executive Summary**
   
The primary objective of this vulnerability assessment was to identify security weaknesses in a virtual machine and ensure compliance with industry standards. The assessment focused on a private IP address of a virtual machine deployed on Microsoft Azure.

**Business Impact:**
The vulnerabilities identified pose a significant risk to security and compliance. If exploited, an attacker could gain unauthorized access to sensitive data, potentially leading to a data breach. Such an event could trigger legal repercussions and reputational damage for the organization.
________________________________________
**2. Methodology**
   
The assessment was conducted using Tenable Nessus Professional, utilizing an Advanced Scan configuration. The following approach was taken:

•	**Scanning Tool:** Tenable Nessus Professional

•	**Scan Type:** Advanced Scan

•	**Scan Duration:** One-day scan 

•	**Compliance Standards Referenced:** Windows DISA STIG

•	**Scan Authentication:** Authenticated scan using Windows credentials (username and password)

![image](https://github.com/user-attachments/assets/710bc2ce-9862-489f-8cb0-c66f74442730)
![image](https://github.com/user-attachments/assets/0677c6f9-b2b2-4793-a4c2-f13339a20f39)
![image](https://github.com/user-attachments/assets/2a75fd83-804e-49fa-af57-aec869d34faa)


________________________________________
 
 

**3. Findings**

**3.1 Tenable Nessus Scans**

The scan results revealed 56 vulnerabilities on the assessed virtual machine, categorized as follows:

•	**Critical:** 6

•	**High:** 7

•	**Medium:** 10

•	**Low:** 1

**Key Findings:**

•	**Outdated Software:** Mozilla Firefox version 110.0 (deprecated) was detected.

•	**Missing Security Patches:** The system lacked several critical security updates.

•	**False Positive:** Paint 3D was flagged as outdated, but the application was not installed.

 ![image](https://github.com/user-attachments/assets/dce8b1c3-820b-49db-b6b4-3f65ac3bc69a)
![image](https://github.com/user-attachments/assets/4a95e44e-b556-4312-9b66-a71f08fe85b1)


________________________________________
 
**3.2 DISA STIG Compliance Results**

•	**Total Compliance Checks:** 261

•	**Non-Compliant Items:** 146

•	**Compliance Pass Rate:** 44.1%

The high number of non-compliant configurations indicates a significant need for remediation to align the virtual machine with Department of Defense (DoD) security benchmarks. Key areas of non-compliance may include outdated security configurations, weak password policies, and insufficient system hardening.

 ![image](https://github.com/user-attachments/assets/3156248e-626f-4486-833b-72996bbb2492)


**4. Recommendations**

**Priority Remediations:**

**1. Address Critical Vulnerabilities Immediately:**

o	Uninstall the outdated version of Mozilla Firefox and install the latest version.

o	Apply all missing security patches and updates.

**2.	Continuous Monitoring & Automation:**

o	Schedule weekly automated scans to proactively detect and mitigate vulnerabilities.

**3.	Best Practices for Improved Security:**

o	Enable email notifications for new vulnerabilities and scheduled assessments.

o	Regularly audit compliance against industry security benchmarks.
 
 ![image](https://github.com/user-attachments/assets/22192c50-d05b-4f41-bc4c-238afbb52725)
![image](https://github.com/user-attachments/assets/78d113f1-e5c9-4946-b143-ed5b8c483f68)

________________________________________

