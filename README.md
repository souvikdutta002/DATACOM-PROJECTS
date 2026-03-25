

<img src ="https://cdn.theforage.com/vinternships/companyassets/gCW7Xki5Y3vNpBmnn/3gcAGm4XfHPEeiGo3/1677531088428/datacom%20logo.png" alt ="DATACOM">

# Datacom Cybersecurity Job Simulation – Task 1
## Ransomware Incident Investigation – Orion Health Services

## 📌 Project Overview
This project was completed as part of the **Datacom Cybersecurity Job Simulation on Forage**.

The objective of this task was to investigate a **ransomware attack** on Orion Health Services, identify the **attack vector, impacted systems, and indicators of compromise (IOCs)**, and prepare a structured report for the executive team.

---

## 🏢 Organization Background
**Orion Health Services** is a mid-sized healthcare technology provider with:

- 250 employees  
- Cloud-based software services  
- Operations across Australia and New Zealand  
- Sensitive data handling (patient and employee data)

---

## 🚨 Incident Summary

| Category | Details |
|---------|--------|
| Incident Type | Ransomware Attack |
| Detection Time | Monday Morning |
| Impact | System lockouts and encrypted files |
| Ransom Note | Found on shared drive |

The attack caused significant disruption, including **loss of access to critical systems** and potential exposure of sensitive data.

---

## 🎯 Objective of Investigation

- Identify how the attack occurred  
- Analyze affected systems and data  
- Examine Indicators of Compromise (IOCs)  
- Assess the impact of the breach  
- Provide insights for remediation and prevention  

---

## 🔍 Attack Timeline (High-Level)

1. **Initial Compromise**
   - A phishing email was sent to a finance team member  
   - The email contained a **malicious Excel attachment**

2. **Execution**
   - The attachment was opened, triggering malicious code  
   - Malware was deployed into the internal network  

3. **Privilege Escalation**
   - Attackers used tools like **Mimikatz** to harvest credentials  

4. **Lateral Movement**
   - Unauthorized access across internal systems  
   - Suspicious login from an overseas IP detected  

5. **Payload Deployment**
   - Ransomware executed across systems  
   - Files encrypted with `.orionlock` extension  

6. **Impact**
   - Employees locked out of systems  
   - Critical business operations disrupted  

---

## 💥 Systems Affected

- File Server  
- HR Systems  
- Finance Systems  
- Backup Server (Partially Encrypted)  

---

## 📂 Compromised Data

- Employee payroll records  
- Patient appointment schedules  
- Internal system credentials  

This indicates a **high-severity data breach**, especially due to **sensitive healthcare information exposure**.

---

## ⚠️ Indicators of Compromise (IOCs)

The following IOCs were identified during the investigation:

- Suspicious login from an **overseas IP address**
- Use of **Mimikatz** for credential harvesting
- Encrypted files with `.orionlock` extension
- Unusual outbound network traffic from internal server

---

## 🧠 Analysis & Findings

- The **initial entry point** was a phishing attack targeting a finance employee  
- Lack of email filtering or user awareness contributed to compromise  
- Attackers successfully escalated privileges using credential dumping tools  
- Backup systems were also targeted, reducing recovery options  
- The attack demonstrates characteristics of a **modern ransomware campaign with lateral movement**

---

## 🛡 Recommended Mitigation Strategies

### Immediate Actions
- Isolate infected systems from the network  
- Disable compromised accounts  
- Initiate incident response protocol  
- Restore systems from clean backups (if available)  

---

### Long-Term Security Improvements

- Implement **multi-factor authentication (MFA)**  
- Conduct **phishing awareness training for employees**  
- Deploy **endpoint detection and response (EDR) tools**  
- Regularly update and patch systems  
- Secure and isolate backup systems  
- Monitor network traffic for anomalies  

---

## 🧰 Skills Demonstrated

- Incident analysis and reporting  
- Understanding ransomware attack lifecycle  
- Threat detection and IOC analysis  
- Risk assessment in cybersecurity  
- Security recommendations and mitigation planning  

---

## 📚 Key Learnings

Through this task, I learned:

- How ransomware attacks are executed in real-world scenarios  
- The importance of identifying **initial attack vectors**  
- How attackers use tools like **Mimikatz** for credential access  
- The role of **IOCs in threat detection and response**  
- How to structure a professional cybersecurity incident report  

---


<img src ="https://cdn.theforage.com/vinternships/companyassets/gCW7Xki5Y3vNpBmnn/3gcAGm4XfHPEeiGo3/1677531088428/datacom%20logo.png" alt ="DATACOM">


# Datacom Cybersecurity Job Simulation – Task 2
## Cybersecurity Risk Assessment Report – RetailNova Pty Ltd

## 📌 Project Overview
This project was completed as part of the **Datacom Cybersecurity Job Simulation on Forage**.

The objective of this task was to perform a **comprehensive cybersecurity risk assessment** of RetailNova Pty Ltd by analyzing its infrastructure, past incidents, and security controls. The goal was to identify potential vulnerabilities, assess risks, and recommend mitigation strategies.

---

## 🏢 Client Overview

**RetailNova Pty Ltd** is a large-scale retail organization with:

- 1,200 employees  
- Annual revenue of $450 million  
- 85 physical stores across Australia  
- E-commerce website and mobile application  

### 💻 Technology Stack

- **Cloud Hosting:** AWS  
- **Payment Systems:** PayPal, Afterpay  
- **CRM:** Salesforce  
- **ERP:** SAP  
- **Communication Tools:** Microsoft Teams, Slack  
- **POS Systems:** Cloud-connected retail systems  

---

## 🎯 Objective

- Identify cybersecurity risks within the organization  
- Evaluate existing security controls  
- Analyze past incidents for vulnerabilities  
- Recommend actionable mitigation strategies  

---

## 🔍 Risk Assessment Methodology

The risk assessment was conducted based on:

- Asset identification  
- Threat analysis  
- Vulnerability identification  
- Likelihood vs impact evaluation  
- Risk prioritization  

---

## ⚠️ Key Assets Identified

- Customer personal data (PII)  
- Payment information (tokenized)  
- E-commerce platform  
- POS systems  
- Internal corporate systems  
- Cloud infrastructure (AWS)  

---

## 🚨 Identified Risks

### 1️⃣ Phishing Attacks
- Previously compromised customer service accounts (2023)
- Employees vulnerable due to limited awareness training

**Risk Level:** High  

---

### 2️⃣ Third-Party Vendor Risk
- 2025 data leak exposed 5,000 customer emails  
- Reliance on external marketing and logistics services  

**Risk Level:** High  

---

### 3️⃣ Ransomware Attacks
- Attempted attack in 2024 (caused downtime)  
- Potential for future disruption and data encryption  

**Risk Level:** High  

---

### 4️⃣ BYOD (Bring Your Own Device) Policy
- Employees use personal devices  
- Increased risk of malware and unauthorized access  

**Risk Level:** Medium  

---

### 5️⃣ Remote Access via VPN
- Potential risk of credential theft and unauthorized access  
- VPN security depends on authentication strength  

**Risk Level:** Medium  

---

### 6️⃣ Data Storage & Privacy Risks
- Large volumes of customer data stored  
- Risk of data breaches and regulatory non-compliance  

**Risk Level:** High  

---

## 📊 Risk Summary Table

| Risk | Likelihood | Impact | Risk Level |
|------|-----------|--------|------------|
| Phishing Attacks | High | High | High |
| Third-Party Risk | High | High | High |
| Ransomware | Medium | High | High |
| BYOD Policy | Medium | Medium | Medium |
| VPN Access | Medium | Medium | Medium |
| Data Privacy | High | High | High |

---

## 🛡 Existing Security Controls

- Firewalls  
- Antivirus software  
- Basic security awareness training  
- Endpoint protection (ransomware prevention)  
- Role-Based Access Control (RBAC)  

---

## ❗ Gaps Identified

- Lack of advanced phishing protection  
- Insufficient third-party risk management  
- Limited employee security awareness training  
- No mention of multi-factor authentication (MFA)  
- Weak monitoring of BYOD devices  

---

## 🛠 Recommendations

### 🔐 Access & Authentication
- Implement **Multi-Factor Authentication (MFA)**  
- Strengthen password policies  

---

### 🎓 Employee Awareness
- Conduct advanced **phishing simulation training**  
- Regular cybersecurity awareness programs  

---

### 🖥 Endpoint & Network Security
- Deploy **Endpoint Detection and Response (EDR)**  
- Monitor unusual network activity  
- Strengthen VPN security  

---

### 🔗 Third-Party Risk Management
- Perform vendor security assessments  
- Enforce strict data protection agreements  
- Continuous monitoring of third-party access  

---

### ☁️ Cloud Security (AWS)
- Enable logging and monitoring (CloudTrail)  
- Apply least privilege access controls  
- Regular security audits  

---

### 📦 Data Protection
- Encrypt sensitive data  
- Implement data loss prevention (DLP) tools  
- Ensure compliance with data protection regulations  

---

## 🧠 Skills Demonstrated

- Cybersecurity risk assessment  
- Threat and vulnerability analysis  
- Security control evaluation  
- Risk prioritization  
- Professional report writing  

---

## 📚 Key Learnings

- Importance of identifying both **technical and human risks**  
- Impact of third-party vulnerabilities in modern systems  
- Role of layered security (defense in depth)  
- Practical application of risk assessment frameworks  

---


## 📎 About the Program

This project was completed as part of the **Datacom Cybersecurity Job Simulation on Forage**, which provides real-world experience in cybersecurity operations, incident response, and risk management.

---


# 💫 About Me:
As a dedicated Cybersecurity student at The Neotia University, I am committed to building a strong foundation in network security, ethical hacking, and threat analysis. My journey so far has included hands-on internships and industry-backed simulations, where I’ve developed a keen understanding of how to protect digital environments against evolving threats.

- Completed virtual job simulations with Deloitte Australia, Tata, KPMG, AIG Sheild's Up and Datacom through Forage, gaining real-world exposure to threat detection, risk analysis, and incident response.
- Currently interning as a Penetration Testing, applying classroom knowledge to practical scenarios and strengthening my analytical and problem-solving abilities.
- Actively learning key tools and techniques, including Identity and Access Management (IAM), log analysis, and risk identification, Top 10 OWASP.

I am passionate about bridging academic knowledge with practical experience and am eager to connect with professionals, mentors, and peers who share my enthusiasm for cybersecurity. My goal is to contribute to a safer digital world by continuously learning, collaborating, and challenging myself.

Let’s connect if you are looking for a motivated cybersecurity enthusiast ready to take on new challenges and make an impact!


## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/souvikdutta002) 

# 💻 Tech Stack:
![Static Badge](https://img.shields.io/badge/Html-gray?style=for-the-badge&logo=html5) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)


# TOOLS
![Static Badge](https://img.shields.io/badge/BURPSUITE-white?style=for-the-badge&logo=burpsuite) ![Static Badge](https://img.shields.io/badge/Nmap-lightblue%20?style=for-the-badge) ![Static Badge](https://img.shields.io/badge/Wireshark-blue?style=for-the-badge&logo=wireshark)![Static Badge](https://img.shields.io/badge/OWSAP_ZAP-indigo?style=for-the-badge&logo=zap) ![Static Badge](https://img.shields.io/badge/Metasploit_Framework-white?style=for-the-badge&logo=metasploit)





![](https://github-readme-stats.vercel.app/api?username=souvikdutta002&theme=github_dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=souvikdutta002&theme=github_dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=souvikdutta002&theme=github_dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=souvikdutta002&icon=0&color=3)](https://visitcount.itsvg.in)


<h2 align="center">✨ Thank You for Visiting My Profile ✨</h2>

<p align="center">
I truly appreciate you taking the time to explore my GitHub profile.<br>
I'm constantly learning and building projects in <b>Cybersecurity, Ethical Hacking, and Software Development</b>.
</p>

<p align="center">
⭐ Consider giving a <b>Star</b> to the repositories you like <br>
🍴 Feel free to <b>Fork</b> and explore the code <br>
🤝 Let's connect and collaborate
</p>

<p align="center">
<img src="https://img.shields.io/badge/Focus-Cybersecurity-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Learning-Ethical%20Hacking-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Goal-Penetration_Testing-red?style=for-the-badge">
</p>

<p align="center">
<i>“Security is not a product, but a continuous process.”</i>
</p>

<p align="center">
🚀 Thanks again for visiting , Have a great day!
</p>
