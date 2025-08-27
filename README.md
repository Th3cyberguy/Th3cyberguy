# 🛡️ Isaiah's Cybersecurity Homelab Portfolio

Welcome to my cybersecurity portfolio!  
This repository highlights the **homelab environment** I’ve built and the projects I run to simulate, detect, and respond to real-world attacks.  

My focus areas: **Digital Forensics & Incident Response (DFIR), Threat Hunting, Detection Engineering, and SOC Automation**.

---

## 🔥 Featured Homelab Projects

### 1. Graylog Syslog Server Setup
- Deployed Graylog on a dedicated VM to centralize log ingestion.  
- Forwarding logs from **Pangolin Secure Tunnel, Authentik, VPS firewall, and internal services**.  
- Built custom pipelines for:
  - Authentication monitoring  
  - Access attempts + GeoIP enrichment  
  - Alert routing to Slack/Discord  

📂 [See Project →](./graylog-homelab)

---

### 2. Wazuh for Endpoint & Network Detection
- Running a Wazuh cluster on Proxmox for **endpoint telemetry + host intrusion detection**.  
- Integrated agents across:
  - VPS
  - Homelab VMs
  - Internal workstations  
- Wrote detection rules for:
  - Password spraying
  - Reverse shells
  - File integrity monitoring (FIM)

📂 [See Project →](./wazuh-homelab)

---

### 3. Splunk Threat Hunting Dashboards
- Built **custom Splunk dashboards** using:
  - MITRE ATT&CK mapping  
  - Risk scoring + emojis for quick triage  
  - Network/user activity baselining (service accounts, logon hours, subnets)  
- Created CSV/KV lookups for:
  - Known good users/services  
  - Malicious IOC tracking  
  - Network baselines  

📂 [See Project →](./splunk-dashboards)

---

### 4. Proxmox Homelab Infrastructure
- Virtualized lab environment running on:
  - Intel i9 desktop (64GB DDR5 + RTX 4080)  
  - NASYNC server (64GB DDR5 + 36TB storage)  
- Segmented networks with UniFi UDR7 firewall + VLANs.  
- Hosting:
  - SIEM stack (Graylog, Wazuh, Splunk test instance)  
  - Blue team tooling (TheHive, Cortex, n8n)  
  - Adversary simulation VMs  

📂 [See Project →](./proxmox-homelab)

---

### 5. Network Security & Monitoring
- Deployed **Zeek sensor** on a dedicated NIC for traffic analysis.  
- Configured SPAN/mirror port on UniFi to feed logs to SIEMs.  
- Running **Pi-hole DNS** internally for malicious domain detection + ad blocking.  
- Built custom detections for:
  - Beaconing traffic  
  - Known bad DNS queries  
  - Suspicious ports/protocols  

📂 [See Project →](./network-monitoring)

---

## 🧰 Skills Demonstrated
- **SIEM Engineering**: Splunk ES, Graylog, Wazuh  
- **Detection Engineering**: Sysmon, Zeek, Suricata rules  
- **DFIR**: Endpoint forensics, log analysis, IOC tracking  
- **Infrastructure**: Docker, Proxmox, Cloudflare Tunnel, UFW hardening  
- **Networking**: VLAN segmentation, SPAN ports, VPN tunneling  
- **Automation**: Python, PowerShell, Bash, n8n workflows  

---

## 📸 Screenshots & Diagrams
*(coming soon — screenshots of dashboards, network diagrams, and log pipelines)*

---

## 📬 Contact
- [LinkedIn](https://linkedin.com/in/yourprofile)  
- [Email](mailto:youremail@example.com)
