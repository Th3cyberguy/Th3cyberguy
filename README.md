# 🛡️ Isaiah's Cybersecurity & AI Homelab Portfolio

Welcome to my cybersecurity & AI portfolio!  
This repository showcases my **homelab environment** and the projects I’ve built to simulate, detect, and respond to real-world attacks — while also exploring **AI/ML integrations for SOC operations**.  

My focus areas: **DFIR, Threat Hunting, Detection Engineering, SOC Automation, and AI-driven Security**.

---

## ⚡ Homelab Build — Order of Operations

### 1) Proxmox Homelab Infrastructure
- Virtualized environment running on:
  - Intel i9 desktop (64GB DDR5 + RTX 4080)  
  - NASYNC server (64GB DDR5 + 36TB storage)  
- Network segmentation with UniFi UDR7 + VLANs.  
- Hosting:
  - SIEM stack (Logstash, Wazuh, Splunk test instance)  
  - Blue Team tooling (TheHive, Cortex, n8n)  
  - Adversary simulation VMs  

---

### 2) VPS with Pangolin & Authentik
- Hardened VPS setup with **UFW firewalling** and **Cloudflare WAF**.  
- Deployed **Pangolin Secure Tunnel** for private access.  
- Integrated **Authentik IAM** for Single Sign-On (SSO) across lab services.  
- All containers run **non-root**, following Docker hardening best practices.  

---

### 3) Log Centralization with Logstash
- Deployed **Logstash** for centralized log ingestion and parsing.  
- Ingesting:
  - VPS firewall logs  
  - Authentik authentication events  
  - Pangolin secure tunnel access attempts  
- Built pipelines for:
  - GeoIP enrichment  
  - Authentication monitoring  
  - Alert forwarding to Slack/Discord  

---

### 4) Wazuh for Endpoint & Host Monitoring
- Wazuh cluster on Proxmox for **endpoint telemetry + HIDS**.  
- Agents deployed on:
  - VPS  
  - Homelab VMs  
  - Workstations  
- Detection rules for:
  - Password spraying  
  - Reverse shells  
  - File integrity monitoring (FIM)  

---

### 5) Network Security & Monitoring
- **Zeek sensor** deployed on dedicated NIC for deep packet analysis.  
- SPAN/mirror port on UniFi for full visibility.  
- **Pi-hole DNS** for blocking malicious domains & ad tracking.  
- Custom detections for:
  - Beaconing traffic  
  - Known bad DNS queries  
  - Suspicious ports/protocols  

---

### 6) AI / ML Security Integrations
- Built **RAG (Retrieval-Augmented Generation) pipelines** with:
  - **LocalAI** (self-hosted LLMs)  
  - **Qdrant Vector DB** for log + intel embeddings  
- Integrated **n8n automation** for:
  - Scraping threat intel feeds  
  - Enriching with OSINT  
  - Pushing to vector DB for AI-driven queries  
- Training custom AI models on RTX 4080 for:
  - Splunk query assistance  
  - DFIR investigation helpers  
  - Cybersecurity-specific knowledge bases  

---

## 🧰 Skills Demonstrated
- **SIEM Engineering**: Splunk ES, Logstash, Wazuh  
- **Detection Engineering**: Sysmon, Zeek, Suricata rules  
- **DFIR**: Forensics, log analysis, IOC tracking  
- **Infrastructure**: Docker, Proxmox, Cloudflare Tunnel, UFW hardening  
- **Networking**: VLAN segmentation, SPAN ports, VPN tunneling  
- **Automation**: Python, PowerShell, Bash, n8n workflows  
- **AI/ML**: LocalAI, RAG pipelines, vector DBs, model fine-tuning  

---

## 📜 Certifications
<p align="left">
  <img src="https://img.shields.io/badge/-CNSP-blue?logo=comptia&style=for-the-badge" alt="CNSP" />
  <img src="https://img.shields.io/badge/-Pentest%2B-red?logo=comptia&style=for-the-badge" alt="Pentest+" />
  <img src="https://img.shields.io/badge/-CNVP-yellow?logo=comptia&style=for-the-badge" alt="CNVP" />
  <img src="https://img.shields.io/badge/-CSAP-green?logo=comptia&style=for-the-badge" alt="CSAP" />
</p>

---

## 📸 Screenshots & Diagrams
*(coming soon — dashboards, network topology diagrams, AI pipeline architecture)*

---

## 📬 Contact
<p align="left">
  <a href="https://www.linkedin.com/in/isaiah-a-a3a70b181">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile"/>
  </a>
</p>