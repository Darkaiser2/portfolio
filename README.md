# Portfolio — Jonathan Campos

> **Live site:** https://darkaiser2.github.io/portfolio/

## What this is

A personal portfolio site. Two purposes:

1. **Learn who I am as a person.** Cyberpunk lounge vibe, Lima radio stations, multiplayer arcade game, live chat with whoever else is online. Lights on, doors open.
2. **Learn who I am as a worker.** Credentials, skills, projects, and how I think about infrastructure + AI engineering.

## About me

Infrastructure Operations Engineer with 10+ years in network/data-center ops at a global financial-data firm. Recently promoted from Network Operations Engineer (May 2026). Bilingual English/Spanish, based remotely.

Building toward an **AI Infrastructure Operations Engineer** role — production observability, GPU fleet ops, MLOps tooling.

## Credentials

- ITIL® 4 Foundation (PeopleCert, 2025)
- AWS Certified Cloud Practitioner (Credly, 2021)
- *In progress:* AWS Solutions Architect Associate, HashiCorp Terraform Associate, NVIDIA NCA-AIIO

## Selected projects

- **app1 — Control Change Assistant.** ITIL/ServiceNow change-request generator powered by LLMs. AIOps for ITSM.
- **app2 — AlgoTrader.** Multi-strategy trading bot with regime detection, AI analyst (Claude Opus 4.7), Telegram control surface, Railway-hosted CI/CD. MLOps in production.
- **Portfolio (this site).** Cyberpunk lounge — Lima radio (8 stations), real-time chat, *Void Serpent* multiplayer horror snake game (server-authoritative Socket.io).
- **Internal:** KMZ carrier path-diff tool for fiber/POP deployment validation.

## Tech

- **Frontend:** vanilla HTML/CSS/JS, no framework, single-page
- **Backend (chat + game):** Node + Express + Socket.io on Railway
- **Hosting:** GitHub Pages (static frontend)
- **Fonts:** Orbitron, JetBrains Mono, Inter

## Local dev

Static site — no build step.

```powershell
# Option 1 — open file directly
start index.html

# Option 2 — serve locally (cleaner URLs, Socket.io works)
python -m http.server 8000
```

Then http://localhost:8000

The chat + game widgets need the Railway backend to be reachable. Static parts (lounge, credentials) render fine offline.

## Contact

- **Email:** jpros1207@gmail.com
- **GitHub:** [@Darkaiser2](https://github.com/Darkaiser2)
- **LinkedIn:** [jonathan-campos-14229456](https://www.linkedin.com/in/jonathan-campos-14229456/)
