<p align="center">
  <img src="https://www.gitskins.com/api/section/wordmark?username=Th3cyberguy&theme=cyber&label=Th3cyberguy" width="100%" alt="Th3cyberguy" />
</p>

<table width="100%">
<tr>
<td width="62%" valign="middle">
<h3>Hey, I'm Isaiah, but everybody calls me Layton 👋</h3>
<p><b>Detection Engineer · DFIR Specialist · AI-Driven Security</b></p>
<p>I write detections, run down incidents, and build AI agents that handle the investigative grunt work while analysts stay in control. My mission is to give back to the community by sharing knowledge, creating educational content, and building tools that help defenders stay ahead of adversaries.</p>
<p>
<a href="https://www.linkedin.com/in/isaiah-a-a3a70b181/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:Th3cyberguy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
</td>
<td width="38%" valign="middle" align="center">
<img src="https://www.gitskins.com/api/section/portrait?username=Th3cyberguy&theme=cyber" width="240" alt="Animated ASCII portrait of Layton" />
</td>
</tr>
</table>

<p align="center">
  <img src="https://www.gitskins.com/api/section/highlights?username=Th3cyberguy&theme=cyber&items=Threat%20Detection::Behavioral%20Rules%20%26%20Tuning|DFIR::Windows%20%26%20AD%20Forensics|Automation::PowerShell%2C%20Python%20%26%20SOAR" width="100%" alt="Focus areas: threat detection, DFIR, and security automation" />
</p>

<p align="center">
  <img src="https://www.gitskins.com/api/readme-reference/divider?username=Th3cyberguy&theme=cyber&v=readme-reference-2" width="100%" alt="" />
</p>

## 🎯 About Me

- 💼 **Solutions Senior Consultant at Deloitte**, supporting federal government clients
- 🎖️ **9-year military veteran**: 12B Combat Engineer with two combat tours in Afghanistan
- 🧭 Led DFIR solutions and security consulting across federal projects
- 🤖 Building AI agents for DFIR and security operations
- ☁️ AWS GovCloud and enterprise security operations
- 👥 Mentor to the next generation of SOC analysts

**What drives me**

- **Education & mentorship:** reference material, SOC playbooks, and cheat sheets that help junior analysts level up
- **Tool development:** practical DFIR tools like WinDEAS and MIMIR that streamline investigations
- **AI for defenders:** agents and LLM workflows that speed up investigations without compromising evidence integrity
- **Community contribution:** documentation organized around frameworks like MITRE ATT&CK
- **Continuous learning:** threat hunting, detection engineering, and adversary tradecraft

<p align="center">
  <img src="https://www.gitskins.com/api/readme-reference/divider?username=Th3cyberguy&theme=cyber&v=readme-reference-2" width="100%" alt="" />
</p>

## 🤖 My AI Journey

I love AI, and I've gone all in on it. What started as homelab experiments turned into building agents that work DFIR investigations alongside me. The part that hooks me: pairing an agent that never gets tired of triage with an analyst who never gives up the final call.

<p align="center">
  <img src="https://www.gitskins.com/api/section/highlights?username=Th3cyberguy&theme=cyber&items=Agentic%20DFIR::Multi-Agent%20Investigations|Local%20LLMs::RAG%2C%20Qdrant%20%26%20Fine-Tuning|Guardrails::Human-Approved%2C%20Audit-Chained" width="100%" alt="AI focus areas: agentic DFIR, local LLMs, and guardrails" />
</p>

**01 · The homelab spark (2025)**<br />
Self-hosted LLMs with LocalAI, a Qdrant vector DB, and RAG pipelines over my own Splunk logs and threat intel. n8n workflows scraped and enriched intel feeds and pushed them into the vector DB for AI-driven queries, and I started training smaller models on an RTX 4080 for Splunk query assistance and DFIR helpers.

**02 · From experiments to platforms**<br />
Built Morpheus, my own self-hosted AI chat platform, and started wiring LLMs into security workflows: vulnerability analysis, risk scoring, and natural-language questions over security data.

**03 · Agentic DFIR (2026)**<br />
Built MIMIR for the SANS Find Evil! hackathon: nine specialist agents working one case in parallel, with guardrails enforced by the architecture instead of the prompt.

**04 · Now**<br />
Teaching agents to remember, so every solved case makes the next one faster, and running local models (Llama-3, Whisper, YOLOv8) for evidence-bound analytics.

**How I build AI for security**

- **Trustworthy beats capable.** The hard part of AI-assisted forensics isn't making the agent capable. It's making it trustworthy.
- **Guardrails belong in the architecture, not the prompt.** Read-only evidence, allowlisted tools, and approval gates hold even when a prompt doesn't.
- **Evidence-bound output.** Every finding cites its evidence. No fabricated entities, no unexplained conclusions.
- **Humans make the call.** Agents triage, correlate, and draft. Analysts approve anything that matters.

| 🧠 Models | 🤖 Agents | 📚 Retrieval & Memory | 🔧 Tooling |
| :-- | :-- | :-- | :-- |
| Claude · GPT-4o | Multi-agent orchestration | RAG pipelines | MCP (FastMCP) |
| Llama-3 via llama.cpp | Reflexion loops | Qdrant vector DB | n8n workflows |
| Whisper · YOLOv8 | Human approval gates | sentence-transformers | LocalAI |
| Small-model fine-tuning (RTX 4080) | Hash-chained audit trails | Case-bank memory | FastAPI · React |

## 🛠️ Projects

<table width="100%">
<tr>
<td width="50%" valign="top">
<h3>🧠 MIMIR</h3>
<p><b>Memory-Informed Multi-agent Investigation Responder</b></p>
<p>An autonomous DFIR agent built for the SANS Find Evil! 2026 hackathon. Nine specialist agents work memory, disk, log, network, and malware evidence in parallel through 33 forensic tools over MCP. Evidence stays read-only at the kernel level, every tool call is hash-chained into the audit log, and nothing ships without human approval. A case-bank memory makes each investigation smarter than the last.</p>
<p><sub>Python · Claude · MCP · 541 tests · Private repo</sub></p>
</td>
<td width="50%" valign="top">
<h3>🛡️ WinDEAS</h3>
<p><b>Windows Detection Engineering &amp; Automation Suite</b></p>
<p>A PowerShell DFIR framework for Windows environments: Domain Controller forensics, threat detection automation, memory analysis and artifact collection, and evidence preservation and reporting.</p>
<p><sub>PowerShell · Private repo, walkthroughs available on request</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>💊 Morpheus</h3>
<p><b>Private, self-hosted AI chat platform</b></p>
<p>A Matrix-styled AI workspace: multi-turn chats organized into projects, extended and deep-research thinking modes, a skills framework that generates Word and PowerPoint files, and TOTP MFA.</p>
<p><sub>FastAPI · React · TypeScript · OpenAI-compatible APIs · Private repo</sub></p>
</td>
<td width="50%" valign="top">
<h3>🔬 Detection Engineering Research</h3>
<p>Custom detection rules and automation frameworks focused on behavioral threat detection, evasion technique identification, security event correlation, and false-positive reduction.</p>
<p><sub>More projects coming soon</sub></p>
</td>
</tr>
</table>

## 🔍 Areas of Expertise

| 🛡️ Detection & Response | 🔬 Forensics & Analysis | ⚙️ Automation & Tooling | ☁️ Cloud Security |
| :-- | :-- | :-- | :-- |
| SIEM: Splunk, ELK, Sentinel | Windows: Registry, Event Logs, Memory | PowerShell | AWS GovCloud |
| EDR / XDR | Active Directory investigations | Python for security automation | Azure security |
| Threat hunting | Malware analysis & reverse engineering | Custom tool development | Cloud-native detection |
| Incident response | Timeline analysis | Security orchestration (SOAR) | |

## 📜 Certifications

<p align="center">
  <a href="https://www.credly.com/badges/dd3df412-591d-4fef-b0b1-66067426833d"><img src="https://images.credly.com/size/220x220/images/80d8a06a-c384-42bf-ad36-db81bce5adce/blob" width="110" alt="CompTIA Security+" /></a>
  <a href="https://www.credly.com/badges/59ff5115-4ed1-4c39-91fc-bc98fcae196e"><img src="https://images.credly.com/size/220x220/images/dcd99b5b-da24-40a6-9364-62126d590c37/blob" width="110" alt="CompTIA CySA+" /></a>
  <a href="https://www.credly.com/badges/f80cd694-1adf-434c-b64f-4b45d57d13fd"><img src="https://images.credly.com/size/220x220/images/c7ac176b-15a3-4726-827a-e8cee8fe44dc/blob" width="110" alt="CompTIA PenTest+" /></a>
  <a href="https://www.credly.com/badges/b02cd345-a66c-441f-8f56-53536f3989c8"><img src="https://images.credly.com/size/220x220/images/ba1b8072-8ebe-432c-88e5-05bc809c624a/CompTIA_CSAP.png" width="110" alt="CompTIA Security Analytics Professional (CSAP)" /></a>
  <a href="https://www.credly.com/badges/2b166a5c-3405-430b-b2fc-5317dfc51e8b"><img src="https://images.credly.com/size/220x220/images/3eaf80a9-a69a-480a-a98b-e9a91796d6cb/CompTIA_CNVP.png" width="110" alt="CompTIA Network Vulnerability Assessment Professional (CNVP)" /></a>
  <a href="https://www.credly.com/badges/2f586d58-7702-45fc-a992-7e7dc017b82b"><img src="https://images.credly.com/size/220x220/images/6f68e302-2193-4cbc-b2d9-50541a130ffa/CompTIA_CNSP.png" width="110" alt="CompTIA Network Security Professional (CNSP)" /></a>
</p>

<p align="center"><sub>Continuously updated as I pursue new certifications.</sub></p>

## 🎓 Education

**Bachelor's Degree in Cybersecurity** <sub>(details available on request)</sub>

Coursework: Digital Forensics & Incident Response · Network Security & Penetration Testing · Malware Analysis · Security Operations & Threat Intelligence

<p align="center">
  <img src="https://www.gitskins.com/api/readme-reference/divider?username=Th3cyberguy&theme=cyber&v=readme-reference-2" width="100%" alt="" />
</p>

## 📈 Activity

<p align="center">
  <img src="https://www.gitskins.com/api/section/heatmap?username=Th3cyberguy&theme=cyber" width="100%" alt="Contribution activity for Th3cyberguy" />
</p>

<details>
<summary><b>🎮 Insert coin: contribution arcade</b></summary>
<br />
<p align="center">
  <img src="https://www.gitskins.com/api/section/heatmap?username=Th3cyberguy&theme=cyber&style=jet" width="100%" alt="Contribution graph turned into a jet arcade game" />
</p>
</details>

## 💡 Philosophy

> **"The best defense is a well-informed team backed by solid tools."**

I believe in practical, actionable cybersecurity. Every tool I build and every piece of content I create is designed to help defenders do their jobs better. Whether you're a junior analyst learning the ropes or a seasoned professional looking for reference material, I hope my work helps you in some way.

## 🤝 Let's Connect

I'm always open to collaborating on security projects, sharing knowledge, or talking shop about DFIR, threat detection, and AI for defenders. Reach me on [LinkedIn](https://www.linkedin.com/in/isaiah-a-a3a70b181/) or by [email](mailto:Th3cyberguy@gmail.com).

<p align="center"><i>"Giving back to the community that gave me so much."</i></p>

<!--
  GitSkins panels held back on purpose: they render from PUBLIC repository data,
  and this account has no public repositories yet, so today they would show zeros.
  After making MIMIR, WinDEAS, or Morpheus public, move them above Activity.

<p align="center"><img src="https://www.gitskins.com/api/section/stats?username=Th3cyberguy&theme=cyber" width="100%" alt="GitHub stats for Th3cyberguy" /></p>
<p align="center"><img src="https://www.gitskins.com/api/section/stack?username=Th3cyberguy&theme=cyber" width="100%" alt="Language stack for Th3cyberguy" /></p>
<p align="center"><img src="https://www.gitskins.com/api/section/projects?username=Th3cyberguy&theme=cyber&repos=Th3cyberguy%2FMIMIR%2CTh3cyberguy%2FWinDEAS%2CTh3cyberguy%2FMorpheous" width="100%" alt="Selected projects" /></p>
<p align="center"><img src="https://www.gitskins.com/api/section/system-scan?username=Th3cyberguy&theme=cyber" width="100%" alt="ASCII profile scan for Th3cyberguy" /></p>
-->
