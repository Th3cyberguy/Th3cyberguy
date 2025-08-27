# 🛡️ Isaiah's Cybersecurity & AI Homelab Portfolio

Welcome to my cybersecurity & AI portfolio!  
This repository highlights the **homelab environment** I’ve built and the projects I run to simulate, detect, and respond to real-world attacks — while also exploring **AI/ML integrations for security operations**.  

My focus areas: **Digital Forensics & Incident Response (DFIR), Threat Hunting, Detection Engineering, SOC Automation, and AI-driven Security**.

---

## 🔥 Featured Homelab Projects

### 1. Graylog SIEM Setup
- Centralized log ingestion on dedicated VM.  
- Forwarding logs from **Pangolin Secure Tunnel, Authentik, VPS firewall, and internal services**.  
- Custom pipelines:
  - Authentication monitoring  
  - Access attempts + GeoIP enrichment  
  - Alert routing to Slack/Discord  

📂 [See Project →](./graylog-homelab)

---

### 2. Wazuh for Endpoint & Network Detection
- Wazuh cluster on Proxmox for endpoint telemetry + HIDS.  
- Integrated agents across **VPS, VMs, and workstations**.  
- Detection rules for:
  - Password spraying  
  - Reverse shells  
  - File integrity monitoring (FIM)  

📂 [See Project →](./wazuh-homelab)

---

### 3. Splunk Threat Hunting Dashboards
- Built custom **Splunk dashboards** with:
  - MITRE ATT&CK mapping  
  - Risk scoring + emoji triage  
  - Network & user baselining (service accounts, logon hours, subnets)  
- CSV/KV lookups for:
  - Known good users/services  
  - Malicious IOCs  
  - Network baselines  

📂 [See Project →](./splunk-dashboards)

---

### 4. Proxmox Homelab Infrastructure
- Virtualized environment running on:
  - Intel i9 desktop (64GB DDR5 + RTX 4080)  
  - NASYNC server (64GB DDR5 + 36TB storage)  
- UniFi UDR7 firewall + VLAN segmentation.  
- Hosting:
  - SIEM stack (Graylog, Wazuh, Splunk test instance)  
  - Blue team tooling (TheHive, Cortex, n8n)  
  - Adversary simulation VMs  

📂 [See Project →](./proxmox-homelab)

---

### 5. Network Security & Monitoring
- Deployed **Zeek sensor** for network traffic analysis.  
- SPAN/mirror port on UniFi to feed traffic to SIEMs.  
- Pi-hole DNS for malicious domain detection + ad blocking.  
- Custom detections:
  - Beaconing traffic  
  - Known bad DNS queries  
  - Suspicious ports/protocols  

📂 [See Project →](./network-monitoring)

---

## 🤖 AI & Machine Learning Projects

### LocalAI / Vector DB / RAG Pipelines
- Running **LocalAI + Qdrant Vector DB** in my lab.  
- Built **RAG (Retrieval-Augmented Generation)** pipeline to enhance LLM responses with homelab/security data.  
- Current experiments:
  - Feeding Splunk logs into vector DB for contextual queries.  
  - Using **n8n automation** to scrape + enrich threat intel → store in Qdrant → query via AI.  
  - Training smaller models on RTX 4080 for **cybersecurity + DFIR-focused tasks**.  

📂 [See Project →](./ai-rag-pipeline)

---

## 🧰 Skills Demonstrated
- **SIEM Engineering**: Splunk ES, Graylog, Wazuh  
- **Detection Engineering**: Sysmon, Zeek, Suricata rules  
- **DFIR**: Forensics, log analysis, IOC tracking  
- **Infrastructure**: Docker, Proxmox, Cloudflare Tunnel, UFW hardening  
- **Networking**: VLAN segmentation, SPAN ports, VPN tunneling  
- **Automation**: Python, PowerShell, Bash, n8n workflows  
- **AI/ML**: LocalAI, RAG pipelines, vector DBs, model fine-tuning  

---

## 📜 Certifications
Here are my earned certifications:

<p align="left">
  <img src="https://img.shields.io/badge/-CompTIA%20Security%2B-red?logo=comptia&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-CompTIA%20CySA%2B-blue?logo=comptia&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/CompTIA_CNVP-yellow?logo=comptia&style=for-the-badge" alt="CompTIA CNVP" />
  <img src="https://img.shields.io/badge/CompTIA_CSAP-blue?logo=comptia&style=for-the-badge" alt="CompTIA CSAP" />
</p>

---

## 📸 Screenshots & Diagrams
*(coming soon — dashboards, lab network diagrams, AI workflow charts)*

---

## 📬 Contact
- [LinkedIn](https://linkedin.com/in/yourprofile)  
- [Email](mailto:youremail@example.com)
