<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&width=800&lines=Hi%2C+I'm+Jimil+Prabtani+%F0%9F%91%8B;Cloud+Security+Engineer;AZ-500+%26+AZ-700+Certified;I+Build%2C+Break%2C+and+Secure+Things+to+Understand+Them" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-jimilprabtani.me-00D4FF?style=for-the-badge&logo=googlechrome&logoColor=black)](https://jimilprabtani.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jimil-prabtani-35a4902aa/)
[![Email](https://img.shields.io/badge/Email-jimilprabtani0816%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jimilprabtani0816@gmail.com)

</div>

---

## 🔐 About Me

> **Cloud Security Engineer** blending Azure and AWS security engineering with hands-on network defense and DevSecOps automation — **AZ-500** and **AZ-700** certified, currently working toward **SC-100 (Security Architecture)**,  **AZ-400 (DevOps Engineer Expert)** and **AWS Security Specialty**

- 🎓 Came up through a Software Systems Engineering background before specializing in security
- 🧠 I learn by building and reverse engineering — every project below started as "how does this actually work under the hood?"
- 🛠️ Currently building: hands-on Security projects both locally and in cloud environments, and **Also actively working on Software Engineering**
- 🎸 Away from the terminal: reading, writing, learning guitar, and staying active

---

## 🏆 Certifications

<div align="center">

![AZ-500](https://img.shields.io/badge/AZ--500-Azure_Security_Engineer_Associate-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AZ-700](https://img.shields.io/badge/AZ--700-Azure_Network_Engineer_Associate-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Security+](https://img.shields.io/badge/CompTIA-Security%2B-E4002B?style=for-the-badge)
![Network+](https://img.shields.io/badge/CompTIA-Network%2B-E4002B?style=for-the-badge)
![Palo Alto Networks](https://img.shields.io/badge/Palo_Alto_Networks-Security_Fundamentals-00A99D?style=for-the-badge)

**🎯 Currently pursuing:** SC-100 (Cybersecurity Architect Expert) · AZ-400 (DevOps Engineer Expert) ·  AWS Security Specialty

</div>

---

## ⚡ Expertise

<table>
<tr>
<td width="33%" valign="top">

**Cloud Security**
- Hands on experience of Azure and AWS environments 
- AWS IAM, Entra ID
- Microsoft Defender for Cloud, Sentinel
- AWS Security Hub, CSPM, GuardDuty, WAF
- Secrets Manager, IAM Access Analyzer
- Zero Trust, CAF/WAF frameworks

</td>
<td width="33%" valign="top">

**Network Security**
- Firewall design & hardening (pfSense)
- VLAN segmentation, Cisco switch config
- Attack simulation & mitigation (SYN/ICMP/flood)
- DNS, routing, OSI-layer troubleshooting
- Azure/AWS VPC & landing zone design

</td>
<td width="33%" valign="top">

**DevSecOps & AI Security**
- CI/CD security (GitHub Actions OIDC, Jenkins)
- Terraform IaC, GitOps with ArgoCD
- Container & Kubernetes hardening
- SAST/dependency scanning (Trivy, SonarQube, gitleaks)
- LLM/AI security (OWASP LLM Top 10, MITRE ATLAS)

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [DevOps + AIOps Playbook](https://github.com/JimilPrabtani/DevOps-project-02)

A 7-service e-commerce app running end-to-end on **AWS EKS** — Terraform-provisioned VPC/EKS, GitHub Actions CI with **OIDC** (no long-lived keys) plus gitleaks/Trivy scanning, GitOps via **ArgoCD**, and full observability with **Prometheus/Grafana**. Ships with **Kira**, a Bedrock AI agent that answers questions about live logs, metrics, and service health through a Streamlit chat UI. Passed a 28-issue security audit — secrets removed, least-privilege IRSA, default-deny NetworkPolicies.

`Terraform` `AWS EKS` `ArgoCD` `GitHub Actions` `AWS Bedrock`

</td>
<td width="50%" valign="top">

### 🔐 [WebPenTest AI Toolkit](https://github.com/JimilPrabtani/WebVAPT-toolkit)

An automated web-app pentesting toolkit covering the **OWASP Top 10** across 30+ checks. Crawls a target, runs concurrent vulnerability scans, and sends HIGH/CRITICAL findings to an AI provider for CVSS scoring and fix suggestions — usable as a Streamlit dashboard, a FastAPI service for CI/CD, or a CLI.

`Python` `FastAPI` `Streamlit` `OWASP`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎬 [DevSecOps Pipeline — Netflix Clone](https://github.com/JimilPrabtani/DevSecOps-Project)

A full deployment security pipeline: **Jenkins** builds, **SonarQube** for code quality, **Trivy** + OWASP Dependency-Check for vulnerability scanning, containerized and shipped to EKS with ArgoCD, monitored via Prometheus/Grafana — plus hardened EC2 provisioning with locked-down security groups and key-only SSH.

`Jenkins` `SonarQube` `Docker` `Prometheus` `Grafana`

</td>
<td width="50%" valign="top">

### 📡 [Network Traffic Analyzer v2.0](https://github.com/JimilPrabtani/Python-Network-Analyzer)

A professional-grade network security monitoring tool — live packet analysis with Scapy, intelligent alert deduplication that filters out ephemeral-port and broadcast noise, and PDF security reports with concrete mitigation commands attached to every finding.

`Python` `Scapy` `Network Security`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎣 [Phishing Awareness Simulation Tool](https://github.com/JimilPrabtani/-Phishing-Awareness-Simulation-Tool-)

A Flask platform for running controlled, ethical phishing-awareness campaigns for security teams — unique tracking tokens per recipient, a click-rate analytics dashboard, IP/user-agent capture, and SMTP-based delivery, built to train employees rather than attack them.

`Python` `Flask` `SQLite`

</td>
<td width="50%" valign="top">

### 🕵️ [Git Vulnerabilities Scraper](https://github.com/JimilPrabtani/Git-Vulnerabilities-scraper)

An offline-first Git security scanner. Bare-clones a repo and checks every branch, full commit history (including secrets that were committed and later deleted), GitHub Actions workflows for risky patterns like unpinned actions, and dependency-pinning hygiene — zero external calls beyond the initial clone.

`Python` `Git` `Supply Chain Security`

</td>
</tr>
</table>

---

## 🧰 More Builds

| Project | What it does |
|---|---|
| [AI Security Scanner for Python](https://github.com/JimilPrabtani/Vulnerability-scanner) | Gemini-powered static vulnerability scanner for Python code |
| [GitHub Finder](https://github.com/JimilPrabtani/Github-finder) · [live demo](https://master.d3pi7onc804mcv.amplifyapp.com/) | Vue app to search & compare GitHub profiles, generate shareable badge cards, and browse 35+ curated dev/AI learning resources |
| [Blog Writer Crew](https://github.com/JimilPrabtani/Blog_writer_crew_project) | CrewAI multi-agent pipeline (research → draft → edit → social copy), powered by Gemini |
| [AWS Security Monitoring System](https://github.com/JimilPrabtani/AWS-Security-Monitoring) | CloudTrail + CloudWatch + SNS pipeline that alerts on secrets-access events |
| [AWS Three-Tier Architecture](https://github.com/JimilPrabtani/AWS-Three-Tier-App) | Classic three-tier web delivery pattern built on AWS |
| [Networking Projects](https://github.com/JimilPrabtani/Networking-projects) | Ongoing collection of hands-on network security builds — VLAN segmentation, DHCP snooping, attack simulation & mitigation on a pfSense/Kali homelab |

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=JimilPrabtani&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=JimilPrabtani&theme=tokyonight&hide_border=true" />

<br/>

<img width="70%" src="https://github-readme-activity-graph.vercel.app/graph?username=JimilPrabtani&theme=tokyo-night&hide_border=true&area=true" />

</div>

---

## 🛠️ Tech Arsenal & Security Stack

<div align="center">

### 🛡️ Blue Team & Defensive Security
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Microsoft Defender for Cloud](https://img.shields.io/badge/Defender_for_Cloud-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure WAF](https://img.shields.io/badge/Azure_WAF-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Front Door](https://img.shields.io/badge/Azure_Front_Door-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS Security Hub](https://img.shields.io/badge/AWS_Security_Hub-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS GuardDuty](https://img.shields.io/badge/AWS_GuardDuty-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS WAF](https://img.shields.io/badge/AWS_WAF-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS Secrets Manager](https://img.shields.io/badge/AWS_Secrets_Manager-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212529?style=for-the-badge&logo=pfsense&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy_Analyzer-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Aikido Security](https://img.shields.io/badge/Aikido_Security-6B46C1?style=for-the-badge)

<br/>

### ⚔️ Red Team & Offensive Security
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C93?style=for-the-badge&logo=kalilinux&logoColor=white)
![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Web VAPT](https://img.shields.io/badge/Web_VAPT_Toolkit-DC3545?style=for-the-badge&logo=bugcrowd&logoColor=white)
![Phishing Simulation](https://img.shields.io/badge/Phishing_Simulation-FFC107?style=for-the-badge&logo=googlegmail&logoColor=black)
![Git Scanner](https://img.shields.io/badge/Git_Vulnerability_Scanner-F05032?style=for-the-badge&logo=git&logoColor=white)
![Attack Simulation](https://img.shields.io/badge/Attack_Simulation-8B0000?style=for-the-badge&logo=target&logoColor=white)

<br/>

### 🔒 DevSecOps, IaC & Supply Chain Security
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Gitleaks](https://img.shields.io/badge/Gitleaks-000000?style=for-the-badge&logo=git&logoColor=white)
![OWASP Dep-Check](https://img.shields.io/badge/OWASP_Dep--Check-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

<br/>

### ☁️ Cloud Platform & Identity Management
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![AWS IAM](https://img.shields.io/badge/AWS_IAM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)
![OIDC & Identities](https://img.shields.io/badge/OIDC_%26_Managed_Identities-0078D4?style=for-the-badge&logo=openid&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

<br/>

### 🤖 AI Security & Intelligent Automation
![OWASP LLM Top 10](https://img.shields.io/badge/OWASP_LLM_Top_10-000000?style=for-the-badge&logo=owasp&logoColor=white)
![MITRE ATLAS](https://img.shields.io/badge/MITRE_ATLAS-FF6600?style=for-the-badge&logo=mitre&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

<br/>

### 💻 Languages, Web Frameworks & Databases
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

<br/>

### 📊 Monitoring, Observability & Analytics
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![AWS CloudWatch](https://img.shields.io/badge/AWS_CloudWatch-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS CloudTrail](https://img.shields.io/badge/AWS_CloudTrail-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Log Analytics](https://img.shields.io/badge/Azure_Log_Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

</div>

---

<div align="center">

**Open to Cloud Security Engineering, Security Architecture, SOC Analysis, and DevSecOps roles.**

</div>
