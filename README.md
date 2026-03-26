
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
  "night_job":  "building my own attacker behavioral research platform from scratch",
  "sovereignty": true
}
```

---

### 💼 Professional background

20 years of system engineering across banking, defense, government, and intelligence sectors. 

---

### ⬡ HexG — Behavioral Intelligence Platform

> *Not what hit you. Why.*

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

### ◈ WatchScope — Security SaaS

Security monitoring platform for web agencies. Funds HexG infrastructure. The two products feed each other.

---

### 🛠 Stack — Systems & Infra

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![AlmaLinux](https://img.shields.io/badge/AlmaLinux-ACE96C?style=for-the-badge&logo=almalinux&logoColor=black)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Sun Microsystems](https://img.shields.io/badge/Sun_Microsystems-333333?style=for-the-badge&logo=sun-microsystems&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-1A1918?style=for-the-badge&logo=ansible&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-web-services&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)

### 🔬 Observability & Security

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logo=zabbix&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)

### 💻 Dev

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![NATS](https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white)

### 🤖 AI used in prod

![Anthropic](https://img.shields.io/badge/Claude_Haiku-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral_AI-FA520F?style=for-the-badge&logo=mistral-ai&logoColor=white)
![Grok](https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=xai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-FFFFFF?style=for-the-badge&logo=ollama&logoColor=black)

---

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

### 📡 How I build

- **Primary data > aggregated feeds** — the moat is what you capture yourself
- **Deterministic pipeline** — same input, same output, always. Raw data never mutates
- **EU sovereign** — bare-metal , self-hosted auth, WireGuard overlay, zero cloud dependency on control plane
- **AI gate** — ~88% of sessions resolved deterministically before any model sees them
- **20 years of prod scars** — I've operated 1xxxxx-servers Linux estates and petabyte-scale storage. I don't build toys

---

### 🏠 Lab

Multiple AMD 5950 - 3990 - rtx workstations · High-end GPUs · Solar panels  · Local inference: soon™

---

### 📬 Contact

I talk to serious people.  

[![Email](https://img.shields.io/badge/security@hexg.io-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:security@hexg.io)

---

![Profile views](https://komarev.com/ghpvc/?username=sebux&color=6e40c9&style=flat-square)

*20 years of infrastructure. Two products in prod. Solo. Self-funded. EU-sovereign.*
