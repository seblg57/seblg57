
![Linkedin_banner](https://github.com/user-attachments/assets/2124903b-a60c-4d77-acb0-e5dc26679cb1)
### Hey, I'm Sebux. 👾
```bash
/sebux $ cat about.json
{
  "title":      "Systems thinker, Researcher and Solo Founder",
  "experience": "20+ years in mission-critical infrastructure",
  "languages":  ["FR", "EN", "DE"],
  "location":   "EU",
  "day_job":    "architecting / deploying TIP/SOAR platforms",
  "night_job":  "building my own apt behavioral research platform from scratch",
  "weekend_job": "night_job",
  "sovereignty": true
}
```

---

### 💼 Pro background

20 years of system engineering. 


### 🌒 Free Background

IRC operator roots. BSD and Gentoo first. Sun Microsystems later.

---

### 🏠 Lab

Multiple AMD 5950 - AMD 3990 - RTX workstations - EPYC AMD - XEON · High-end GPUs · Solar panels  · Local inference: soon™

---

### 📡 How I build

- **Primary data > aggregated feeds** — the moat is what you capture yourself
- **Deterministic pipeline** — same input, same output, always. Raw data never mutates
- **EU sovereign** — bare-metal , self-hosted auth, WireGuard overlay, zero cloud dependency on control plane
- **AI gate** — ~88% of sessions resolved deterministically before any model sees them
- **20 years of prod scars** — I've operated 1xxxxx-servers Linux estates and petabyte-scale storage. I don't build toys

---

### 📬 Contact

I talk to serious people.  

[![Email](https://img.shields.io/badge/security@hexg.io-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:security@hexg.io)

---

![Profile views](https://komarev.com/ghpvc/?username=sebux&color=6e40c9&style=flat-square)

*20 years of infrastructure. Two research products in prod. Solo. Self-funded. EU-sovereign.*

---

###  ⬡ HexG — Behavioral Intelligence Platform

> *Yes, Shodan says it's bad. HeXG tells you why — and shows you why.**

Distributed attacker intelligence built entirely on **primary session data**. A network of geographically spread deception sensors  observes adversarial behavior in real time and reconstructs actor profiles — TTPs, timing patterns, kill chain stages, cross-sensor behavioral correlation.

```bash
Tarentula sensors
  → deathweb-ingest (Python, stateless)
    → NATS JetStream (at-least-once)
      → deathweb-cognition (deterministic engine + AI gate)
        → ClickHouse EPYC (3-layer immutable: raw → fact → cognition)
          → deathweb-intel (Go REST API, read-only)
            → PurpleCore UI (React/TypeScript)
```

**Model:** proprietary data accumulation → on-demand API (DomainTools model, but behavioral depth)

---

### ⬢ HeXG Auth — Sovereign Access Layer

> *No outsourced trust. No external gatekeeper. Built to stand free.*

HeXG includes a self-hosted authentication layer built with the same philosophy as the platform itself: control, resilience, and sovereignty.

Designed as a hardened access pipeline rather than a standard login form, it combines **custom Proof-of-Work**, **anti-bot controls**, **approval-based onboarding**, **MFA enforcement**, **token lifecycle management**, and **full auditability** into a single defensive layer.

The objective is simple: keep the entry point observable, abuse-resistant, and fully controlled — without outsourcing identity or trust decisions to third-party platforms.

---

### ◈ WatchScope — Security Visibility SaaS

> *See what is exposed. Understand what matters.*

WatchScope is a security visibility platform designed to help organizations monitor external exposure, surface meaningful signals, and turn scattered technical findings into actionable operational insight.

It focuses on clarity over noise: infrastructure visibility, exposure monitoring, change detection, and security-relevant observations presented in a way that supports fast understanding and decision-making.

The goal is not to flood teams with raw data, but to provide a cleaner operational view of what deserves attention.


### 🔬 What I'm building right now

```python
/sebux $ cat current_focus.py
{
  "priority_1": "Actor Profile UI — behavioral timeline per attacker IP",
  "priority_2": "Credential Explorer — cross-sensor credential family analysis",
  "priority_3": "Notable Campaigns — coordinated cluster auto-detection",
  "horizon":    "HexG-ML via CatBoost — proprietary classification model",
  "moat":       "primary data accumulated over time, not the code"
}
```


---
### 🛠 Stack — Systems & Infra

![Linux](https://img.shields.io/badge/Linux-8A6D1F?style=for-the-badge&logo=linux&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red_Hat-7A1F1F?style=for-the-badge&logo=redhat&logoColor=white)
![AlmaLinux](https://img.shields.io/badge/AlmaLinux-4E5F3A?style=for-the-badge&logo=almalinux&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-6E1E1E?style=for-the-badge&logo=oracle&logoColor=white)
![Sun_Microsystems](https://img.shields.io/badge/Sun_Microsystems-3A3A3A?style=for-the-badge&logo=sun-microsystems&logoColor=white)
![FreeBSD](https://img.shields.io/badge/FreeBSD-6A2B2B?style=for-the-badge&logo=freebsd&logoColor=white)
![Gentoo](https://img.shields.io/badge/Gentoo-4A3D63?style=for-the-badge&logo=gentoo&logoColor=white)
![Arch_Linux](https://img.shields.io/badge/Arch_Linux-1F4E6B?style=for-the-badge&logo=archlinux&logoColor=white)
![BlackArch](https://img.shields.io/badge/BlackArch-111111?style=for-the-badge&logo=archlinux&logoColor=white)
![Kali_Linux](https://img.shields.io/badge/Kali_Linux-4A5D6E?style=for-the-badge&logo=kalilinux&logoColor=white)
![Parrot_OS](https://img.shields.io/badge/Parrot_OS-2E6A73?style=for-the-badge&logo=parrotsecurity&logoColor=white)
![Raspberry_Pi](https://img.shields.io/badge/Raspberry_Pi-6B2942?style=for-the-badge&logo=raspberrypi&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-4C5863?style=for-the-badge&logo=vmware&logoColor=white)

### ⚙️ Automation & Platform

![Ansible](https://img.shields.io/badge/Ansible-1A1A1A?style=for-the-badge&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-245C85?style=for-the-badge&logo=docker&logoColor=white)

### 🌐 Web / Edge / Access

![Nginx](https://img.shields.io/badge/Nginx-1E5A3A?style=for-the-badge&logo=nginx&logoColor=white)
![ModSecurity](https://img.shields.io/badge/ModSecurity-4B3566?style=for-the-badge&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-2E5F73?style=for-the-badge&logo=caddy&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-6A2323?style=for-the-badge&logo=wireguard&logoColor=white)

### ☁️ Cloud

![AWS](https://img.shields.io/badge/AWS-2B3440?style=for-the-badge&logo=amazon-web-services&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-1F4F75?style=for-the-badge&logo=microsoftazure&logoColor=white)

### 🔬 Observability & Security

![Grafana](https://img.shields.io/badge/Grafana-8A4B1F?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-8A503A?style=for-the-badge&logo=prometheus&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-7A1F1F?style=for-the-badge&logo=zabbix&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-111111?style=for-the-badge&logo=splunk&logoColor=white)

### 💻 Dev

![Python](https://img.shields.io/badge/Python-325A7A?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-1F6A7A?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-2F5E8A?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-2A5A66?style=for-the-badge&logo=react&logoColor=white)
![Java](https://img.shields.io/badge/Java-8A5A1F?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-3E6A2A?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-3A4F8A?style=for-the-badge&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-8A741F?style=for-the-badge&logo=clickhouse&logoColor=white)
![NATS](https://img.shields.io/badge/NATS-2A6A8A?style=for-the-badge&logo=natsdotio&logoColor=white)

### 🤖 AI used for cognition and analytics

![OpenAI](https://img.shields.io/badge/OpenAI-3B2E63?style=for-the-badge&logo=openai&logoColor=white)
![Claude_Haiku](https://img.shields.io/badge/Claude_Haiku-8A5A46?style=for-the-badge&logo=claude&logoColor=white)
![Mistral_AI](https://img.shields.io/badge/Mistral_AI-8A4A1F?style=for-the-badge&logo=mistral-ai&logoColor=white)
![Mistral_Nemo](https://img.shields.io/badge/Mistral_Nemo-7A431E?style=for-the-badge&logo=mistral-ai&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-3B4F8A?style=for-the-badge&logoColor=white)
![Qwen_3](https://img.shields.io/badge/Qwen_3-55408A?style=for-the-badge&logoColor=white)
![Grok](https://img.shields.io/badge/Grok-111111?style=for-the-badge&logo=xai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-3A3A3A?style=for-the-badge&logo=ollama&logoColor=white)

### 🧠 ML used for training

![Machine_Learning](https://img.shields.io/badge/Machine_Learning-2A4F73?style=for-the-badge&logoColor=white)
![Deep_Learning](https://img.shields.io/badge/Deep_Learning-5A2F7A?style=for-the-badge&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-1A1A1A?style=for-the-badge&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-2F5F8A?style=for-the-badge&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-8A741F?style=for-the-badge&logoColor=white)
![Random_Forest](https://img.shields.io/badge/Random_Forest-2F6A4A?style=for-the-badge&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-8A541F?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-8A3F2A?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-7A461F?style=for-the-badge&logoColor=white)

---
