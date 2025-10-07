# 📄 Project Documentation – T-Pot Honeypot on Microsoft Azure Cloud

**Author:** Bhargav Pavan Sai Surisetti 
**Date:** 07 October 2025  
**Project Repository:** [tpot-honeypot-on-azure-cloud]

---

## 📘 Overview
This folder contains the **complete documentation** for the project *T-Pot Honeypot on Microsoft Azure Cloud*.  
It includes step-by-step guides, installation instructions, configuration details, screenshots, and post-deployment observations.

The documentation outlines how a honeypot system can be securely deployed and monitored on **Microsoft Azure** using the **T-Pot framework**, which integrates multiple honeypots, logging, and visualization tools.

---

## 📚 Included Documents

| File / Folder | Description |
|----------------|-------------|
| **HONEYPOT.pdf** | Complete report including all steps (from Azure setup to dashboard verification). |
---

## 🏗️ Document Summary
The documentation covers:

1. **Azure Account Creation** – Setting up a new Microsoft Azure account and resource group.  
2. **Virtual Machine Deployment** – Creating a VM, configuring inbound ports (1–65535), and assigning public IP.  
3. **Installation Process** – Connecting via PuTTY, cloning the T-Pot GitHub repository, and executing installation commands.  
4. **System Reboot and Login** – Accessing the VM via SSH on custom port `64295` post-installation.  
5. **T-Pot Web Interface Access** – Navigating to dashboards like Attack Map, Cyberchef, Kibana, and Spiderfoot.  
6. **Operational Verification** – Ensuring logging, visualization, and monitoring components work as intended.  
7. **Importance & Remedies** – Explaining the research value, operational significance, and best security practices.  
8. **Conclusion** – Summarizing results and research outcomes.  

---

## 🧠 Key Objectives
- Demonstrate the process of deploying a honeypot on Azure Cloud.  
- Collect and visualize cyberattack data using T-Pot dashboards.  
- Enhance understanding of network security, monitoring, and isolation.  
- Provide an educational and research-oriented framework for cybersecurity learners.

---

## 🔒 Security & Ethical Considerations
When operating honeypots:
- Always **isolate** them from production networks.  
- **Restrict SSH** and admin ports to trusted IPs only.  
- Follow all **ethical and legal guidelines** regarding data capture and usage.  
- Use collected data **strictly for research, defense, and educational purposes**.  

---

## 🧩 Tools & Technologies
| Category | Tools / Services |
|-----------|------------------|
| Cloud Platform | Microsoft Azure |
| Framework | T-Pot (Telekom Security) |
| OS | Ubuntu Server 22.04 LTS |
| Access | PuTTY / SSH |
| Dashboards | Kibana, Cyberchef, Spiderfoot, Elasticvue |
| Monitoring | Azure Monitor, NSG Logs |
| Version Control | Git, GitHub |

---

## 🏁 Conclusion
The documentation in this folder provides all the necessary information to **deploy, operate, and analyze a honeypot system in the cloud** using T-Pot on Microsoft Azure.  
It serves as a **comprehensive guide** for cybersecurity researchers, students, and professionals looking to explore real-world attack analysis and honeypot deployment strategies.

---

## 📬 Author
**Name:** Bhargav
**Date:** 07 October 2025  

---
