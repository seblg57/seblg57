### Hey, I'm Sebastien — aka Sebux. 👾

```bash
/sebux $ cat about.json
{
  "title":      "Senior Systems & Security Architect · Solo Founder",
  "experience": "20+ years infrastructure",
  "languages":  ["FR", "EN", "DE"],
  "location":   "EU",
  "day_job":    "architecting / integrating TIP/SOAR platforms",
  "night_job":  "building my own behavioral research platform from scratch",
  "sovereignty": true
}
```

---

### 💼 Professional background



---

### ⬡ HexG — Behavioral Intelligence Platform

> *Not what hit you. Why.*

My main research project. A distributed attacker intelligence system built entirely on **primary session data** — no feed aggregation, no OSINT resale.

A network of geographically spread deception sensors (FR · PL · SG) captures adversarial behavior in real time.
A deterministic classification engine reconstructs actor profiles: TTPs, timing patterns, kill chain stages, cross-sensor behavioral correlation.

```bash
/sebux $ cat hexg_pipeline.sh

Tarentula sensors (FR/PL/SG)
  → deathweb-ingest (Python, stateless)
    → NATS JetStream (at-least-once delivery)
      → deathweb-cognition (deterministic engine + AI gate)
        → ClickHouse EPYC (3-layer immutable: raw → fact → cognition)
          → deathweb-intel (Go REST API, read-only)
            → PurpleCore UI (React/TypeScript)
```

**What comes out:** not "this IP is bad". But — *why* it showed up, *how* it behaved, *when* and across *which sensors simultaneously*, *which MITRE TTPs* it mapped to, and what *actor archetype* it reconstructs to.

**Model:** proprietary data accumulation → on-demand API (DomainTools model, but behavioral depth)

---

### ◈ WatchScope — Security SaaS

Security monitoring platform for  agencies. Funds HexG infrastructure while I accumulate proprietary data. The two products feed each other.

---

### 🛠 Stack

**Systems & Infra**

[![](https://skillicons.dev/icons?i=linux,bash,python,ansible,docker,nginx,aws)](https://skillicons.dev)

**Dev**

[![](https://skillicons.dev/icons?i=go,ts,react,postgres,git)](https://skillicons.dev)

**Also in prod**

![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![NATS](https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Haiku-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

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
- **20 years of prod scars** — I've operated 1500 server Linux estates and petabyte-scale storage. I don't build toys

---

### 🏠 Lab

Multiple AMD workstations · High-end GPUs · Solar panels incoming · Local inference: soon™

---

### 📬 Contact

I talk to serious people.  

[![Email](https://img.shields.io/badge/shellguru@protonmail.com-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:security@hexg.io)

---

![Profile views](https://komarev.com/ghpvc/?username=sebux&color=6e40c9&style=flat-square)

*20 years of infrastructure. Two products in prod. Solo. Self-funded. EU-sovereign.*
