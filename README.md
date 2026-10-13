<h1 align="center">Roman Cores</h1>

<p align="center">
  <strong>AI/ML engineer &amp; CTO · 10+ years · building agentic systems that touch the real world</strong>
</p>

<p align="center">
  Medellín, Colombia (UTC−5) · Remote-first, open to relocation
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/romancores/"><img src="https://img.shields.io/badge/LinkedIn-romancores-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:coresroman@gmail.com"><img src="https://img.shields.io/badge/Email-coresroman%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://ansi.world"><img src="https://img.shields.io/badge/Building-ansi.world-111111" alt="ANSI"></a>
</p>

I ship production AI systems — LLM pipelines, multi-agent services, MCP tooling — and lead the distributed teams that run them. Two-time cofounder, currently **CTO / Lead AI Engineer at [CIMA](https://cima.tech)** (Azart Technologies), an AI-driven B2B platform for airlines. Next stop: **robotics software** — bringing real-time pipeline and protocol experience to ROS 2 and physical systems.

> Most of my recent work lives in private company repos. Happy to walk through architecture and code on a call.

---

## 🔭 Now

- **CTO / Lead AI Engineer @ CIMA** — LLM-powered document reconciliation for airline financial registries (**−60 % manual processing**), real-time flight-radar data pipeline (**200 ms → 50 ms** render latency), MLOps for model CI/CD and observability. Customers include Royal Air Maroc and Centrum Air.
- **Building [ANSI](https://ansi.world)** — a hands-free AI voice tour guide. Flutter client → NestJS gateway → Python **AgentScope** swarm (6 specialised agents: concierge, planner, researcher, verifier, tour guide, composer) → **MCP** tool servers (Google Places, Wikipedia, DuckDuckGo, city context) over RabbitMQ; Postgres + Qdrant + MinIO; Kubernetes/Ansible specs for prod.
- **Learning ROS 2** — working through a 12-week roadmap (ROS 2 Humble → `ros2_control` → `nav2`). Portfolio repos will land here as they're done.

---

## 🛠 Selected work

| Project | What it is | Stack | Status |
|---|---|---|---|
| [**volve_ddrs**](https://github.com/romancores/volve_ddrs) | *DDR Intelligence* — local-first, provenance-preserving extraction, anomaly flagging and cited Q&A over 1,000 Daily Drilling Reports (Volve corpus). Deterministic parser owns facts; LLMs confined to judgement and wording. Runs on one Apple-Silicon machine, zero data egress. | Python, pdfplumber, local LLMs, ADRs | Public |
| **ANSI** · [ansi.world](https://ansi.world) | Multi-agent travel guide platform (see *Now*). Plus a content-swarm service: Google Sheets MCP + AgentScope swarm that brainstorms, enriches and cross-verifies a content plan under a budget cap. | Python, AgentScope, MCP, NestJS, Flutter, RabbitMQ, Qdrant | Private beta |
| **CIMA** · [cima.tech](https://cima.tech) | Airline operations platform: LLM document reconciliation, real-time flight data, booking-provider and partner integrations, web + mobile + partner APIs. | Python, NestJS, Flutter, LLM pipelines, K8s | In production |
| **AI assistant platform** (solo founder + AI coding agents) | Metered, memory-bearing AI assistant with tools. Python modular monolith with explicit ports; **double-entry token ledger**; tests-as-spec; **diff-scoped mutation testing** in CI; 60+ ADRs; agents implement, I review and merge every PR. | Python 3.12, FastAPI, Pydantic AI, Postgres + pgvector, vLLM | Private, in build |
| **Agent team ops** | A set of scheduled Claude agent "routines" — PM dispatcher, architect/CTO advisor, code reviewer, QA — that run the day-to-day engineering process for an aviation product: Jira conventions, release cards, digests, scorecards. | Claude agents, skills, Jira, Telegram | Private, running daily |
| **Family Compass** | Flutter family-tree app: graph model (`Person` nodes, `parentChild`/`partner` edges), four-way swipe navigation, inline add-relative, on-device Drift/SQLite persistence. 134 tests, `flutter analyze` clean. | Flutter, Dart, Drift | Local, mock-UI phase |
| **MCP servers** | Wikipedia and DuckDuckGo search servers deployed on Railway; Playwright browser, Git-notices and personal-finance MCPs for daily use. | Python, `mcp` SDK, FastAPI | Mixed |
| **fastrtc_speaker_backend** | Real-time voice conversation backend: WebRTC in → STT → LLM → Sesame CSM speech out, with TURN and conversation memory. | Python, FastAPI, FastRTC, Hugging Face | Prototype |

---

## 🤖 Robotics track

**Why:** I want to build systems that act in the physical world, not just on screens.

**What transfers:** 100+ Hz data pipelines with sub-50 ms latency, protocol design (REST / GraphQL / WebSocket / MQTT / custom), distributed multi-service architectures, C/C++ and Python, and leading cross-timezone engineering teams.

**What I'm doing about it (honest status: actively learning, not yet expert):**

- ROS 2 Humble — nodes, topics, services, actions, QoS, tf2, lifecycle nodes
- `ros2_control` — custom `hardware_interface::SystemInterface` with a simulated serial/CAN protocol
- `nav2` + SLAM Toolbox — autonomous mobile robot simulation in Gazebo
- Planned portfolio: **sensor-fusion node** (C++, `message_filters`, latency metrics) → **custom hardware interface** → **end-to-end AMR simulation**

**Ideas I'm exploring:** an **MCP ↔ ROS 2 edge agent** so LLMs can call robot and IoT tools through a standard, metered (HTTP 402) interface; multi-agent job/market scouting for the robotics industry; early team-structure work for an exoskeleton project.

**Target roles:** Robotics Software Engineer · ROS 2 / protocol developer · fleet-management and robot-to-cloud software · autonomous systems.

---

## 🤝 Open source

- [**invoice_su**](https://github.com/HorumDev/invoice_su) — Dart client for the invoice.su acquiring API, any platform
- [**tinkoff_acquiring**](https://github.com/HorumDev/tinkoff_acquiring) — Flutter plugin wrapping native iOS/Android Tinkoff SDKs (Apple Pay / Google Pay)
- [**platinum_list**](https://github.com/romancores/platinum_list) — Flutter SDK for Platinumlist events and ticketing
- [**yandex_mapkit**](https://github.com/HorumDev/yandex_mapkit) — Flutter implementation of Yandex MapKit
- [**weather_kit_native**](https://github.com/romancores/weather_kit_native) · [**tabnavigator_plus**](https://github.com/romancores/tabnavigator_plus) — smaller Flutter utilities

---

## 🧰 Stack

**AI / agents:** LLM integration, RAG, agentic systems (AgentScope, Pydantic AI), MCP server & client development, model evaluation, AI document processing, Hugging Face tooling
**Languages:** Python · Dart · TypeScript · C/C++ · Java · Kotlin
**Backend / infra:** FastAPI, NestJS, GraphQL, RabbitMQ, Postgres/pgvector, Qdrant, Redis, Docker, Kubernetes, AWS, CI/CD, OpenTelemetry
**Mobile:** Flutter at scale (6+ years; apps with 100K+ users and 300K+ monthly transactions)
**Robotics (learning):** ROS 2, DDS, `ros2_control`, `nav2`, Gazebo

---

<details>
<summary><strong>📜 Track record</strong> (click to expand)</summary>

<br>

| Period | Role | Highlights |
|---|---|---|
| 2025 – now | **CTO / Lead AI Engineer**, CIMA · Azart Technologies | AI data services for web, mobile and partner APIs; LLM reconciliation −60 % manual time; flight-radar pipeline 200 → 50 ms; MLOps and data-governance frameworks; technical bridge to international airlines |
| 2023 – 2024 | **Tech Lead, AI Systems**, Shuffle.city · Azart | Led 2 teams / 8 engineers across time zones; 300K+ monthly transactions; CI/CD giving 2× faster releases at 99.5 % reliability; A/B and analytics-driven AI feature validation |
| 2017 – 2024 | **Co-founder & CTO**, [Horum.co](https://horum.co) | AI-enhanced dev agency: 31+ projects with AI/ML components, 15+ web apps, 10+ automation solutions; feature-flag and A/B frameworks; distributed teams across regions |
| 2020 – 2022 | **Co-founder & CPO**, Patrick | AI-enhanced productivity app in 3 languages, 100K+ users; 5+ growth hypotheses tested per week; AWS/Kubernetes |
| 2015 – 2018 | Software engineer & product manager, early ventures | Led teams of 3–20 building multi-platform products from idea to market test |

**Shipped consumer apps:** [Shuffle](https://apps.apple.com/us/app/shuffle-your-evening/id6449493932) · [Flips](https://apps.apple.com/us/app/flips-cards-that-help/id1626446928) · [Mandarin Markets](https://play.google.com/store/apps/details?id=ru.mandarineda.micromarkets) · Sensera (CBT self-help, retired)

**Education:** B.Sc. Secure Information Technologies — ITMO University, St. Petersburg (2020)
**Certifications:** AI Agents + MCP (Hugging Face) · Leadership & Management (Udemy) · Project Management, Business-Process Analysis & Modelling (HSE)
**Languages:** Russian (native) · English (advanced) · Spanish (intermediate)

</details>

---

## 🧭 How I work

- **Hypothesis-driven.** Lean-startup practitioner since 2015: 5 failed projects, several that shipped, and the scars to tell them apart early.
- **AI agents do the typing; I own the architecture and merge every PR.** Tests are the spec, mutation testing keeps them honest, ADRs record the why.
- **Distributed by default.** I've built and run teams across continents, time zones and stacks — async-first, short calls, written decisions.
- **Writing:** [Task decomposition](https://www.linkedin.com/posts/romancores_deadlines-expectations-projectmanagement-activity-7242854692475539456-4jia?utm_source=github) · [Team lead's basics](https://www.linkedin.com/posts/romancores_success-communication-development-activity-7087553061321129984-uKX2?utm_source=github) · [Leverage collaborative tools](https://www.linkedin.com/posts/romancores_efficiency-motivation-communication-activity-7082440502800736257-iiCB?utm_source=github) · [Calls: concise and time-bound](https://www.linkedin.com/posts/romancores_synchronic-communications-technology-activity-7081708190731513856-31Hc?utm_source=github)

---

## 💬 Let's talk

**Ask me about:** running an engineering team with AI agents · multi-agent systems with AgentScope · building MCP servers · Flutter at scale · real-time data pipelines · lean validation of hardware-adjacent ideas.

**I'm looking for:** robotics software roles (ROS 2, protocols, fleet management) and **cofounders in robotics / physical AI** who want a technical partner with production AI and team-building experience.

📫 [LinkedIn](https://www.linkedin.com/in/romancores/) · coresroman@gmail.com

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=romancores&show_icons=true&hide_rank=true&theme=default" alt="GitHub stats">
</p>

⚡ **Fun fact:** 59 countries visited so far — the tour-guide app is partly self-interest. 🌍
