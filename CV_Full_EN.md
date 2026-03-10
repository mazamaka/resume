# Maksym Babenko

**Python Developer | AI Automation Engineer | DevOps**

Budapest, Hungary (from Kyiv, Ukraine) | $5,500+/mo

- Email: mazamaka603@gmail.com
- Phone: +380 99 045 1609
- GitHub: [github.com/mazamaka](https://github.com/mazamaka)
- LinkedIn: [linkedin.com/in/max-bob-python](https://linkedin.com/in/max-bob-python)
- Telegram: [@Mazamaka](https://t.me/Mazamaka)

---

## Profile

Full-Stack Python Developer with 8+ years of experience building production systems end-to-end — from backend microservices and admin panels to AI-powered browser automation and DevOps infrastructure. Developed and shipped 40+ projects including large-scale ad management platforms, AI agent ecosystems, Telegram bots, and blockchain tools.

Deep expertise in antifraud and fingerprinting: built custom antidetect browser with CDP-level spoofing (Canvas, WebGL, Audio, Navigator, TLS), bot-detection bypass, antifraud endpoint analysis (Apple, Google), fingerprint monitoring tools. Completed professional antifraud course (15 modules: DNS identifiers, WebGPU, VM detection, deanonymization, and more).

Currently focused on AI-first development: building multi-agent systems with Claude Code, browser automation with AI (browser-use), and full-cycle development where AI agents handle architecture, coding, testing, review, and deployment.

Strong DevOps skills: Docker, CI/CD (GitLab), Linux server administration, Portainer, Nginx, monitoring (Prometheus/Grafana).

---

## Core Skills

### Languages & Frameworks
- **Python** (primary): FastAPI, Flask, Aiohttp
- **JavaScript/TypeScript**: React, Chrome Extensions (Manifest V3), jQuery, HTMX
- **HTML/CSS**: Jinja2, TailwindCSS
- **SQL**: PostgreSQL, MySQL, SQLite
- **NoSQL**: MongoDB, Redis

### AI & LLM
- Claude API / Claude Code (primary development environment)
- OpenAI API (GPT-4, GPT-3.5) — content generation, chat bots
- browser-use — AI-powered browser automation with LLM agents
- Multi-agent systems (14 specialized agents: architect, developer, reviewer, deployer, etc.)
- Stable Diffusion / Midjourney API — image generation pipelines
- NLP: transformers, zero-shot classification

### Backend & Architecture
- Microservices architecture (FastAPI)
- REST API design, Swagger/OpenAPI
- ORM: SQLAlchemy (async), SQLModel, Alembic migrations
- Task queues: Celery, RabbitMQ, Temporal
- Async programming: asyncio, aiohttp, asyncpg
- Admin panels: Starlette Admin, Flask-Admin, FastAPI Admin
- Pydantic, pydantic-settings for configuration

### Antifraud & Fingerprinting
- **Custom antidetect browser development** (nodriver + CDP injection) — CreepJS: headless 0%, stealth 0%
- CDP-level fingerprint spoofing: Canvas noise, WebGL vendor/renderer, Audio, Navigator, Screen, Plugins, Battery, Permissions
- Antifraud system analysis: IPQS, FingerprintPro, AntCaptcha, CreepJS, BrowserLeaks, Sannysoft
- Fingerprint monitoring tool (Chrome Extension — intercepts Canvas, WebGL, Navigator, MediaDevices API calls)
- Bot-detection bypass: CDP marker removal (`cdc_*`, `__webdriver_*`), `navigator.webdriver` spoofing, `window.chrome` emulation
- Cloudflare bypass via TLS fingerprinting (tls-client)
- Docker GPU (NVIDIA) for real WebGL rendering in headless mode
- Knowledge: DNS fingerprinting, WebGPU, WASM fingerprint, TCP/UDP/QUIC network fingerprints (M1D/M1D1), VPN/Proxy detection (10 geolocation methods), VM detection & bypass, ultrasonic deanonymization

### Browser Automation & RPA
- Playwright, Selenium, nodriver
- Octo Browser API (antidetect browser integration)
- CDP (Chrome DevTools Protocol) — low-level browser control
- Zennoposter, BAS (Browser Automation Studio)

### DevOps & Infrastructure
- Docker, Docker Compose — containerization of all projects
- CI/CD: GitLab pipelines, automated deployments
- Linux server administration (Ubuntu, Debian)
- Nginx + Certbot (SSL, reverse proxy)
- Portainer — container management
- Prometheus + Grafana — monitoring and alerting
- MinIO (S3-compatible storage)
- DNS management (Cloudflare)
- SSH tunnel management, systemd services

### Blockchain & Web3
- Solana: copy-trading bot, transaction analysis
- Web3 integration (wallets, smart contracts)
- NFT marketplaces (Binance NFT)
- Pump.fun trading automation

### Telegram & Bots
- aiogram 3 (primary framework)
- Pyrogram, Telethon
- Bot funnels, interactive surveys, admin integrations
- Google Sheets API integration

### Tools & Workflow
- Git (GitHub, GitLab)
- Claude Code — full-cycle AI-assisted development
- MCP (Model Context Protocol) servers
- ClickUp, task management automation
- Whisper — audio/video transcription

---

## Work Experience

### Traffic Devils, Kyiv (Remote) — Python Developer
**November 2022 — Present** (~3.5 years)

Led development of a comprehensive Google Ads farm management ecosystem — a multi-service platform handling hundreds of advertising accounts with AI-powered automation.

**Key projects & achievements:**

**Google Ads Ecosystem (5 services, 800+ Python files):**
- **google-admin** (555 .py files) — Full management platform with Starlette Admin dashboard, 40+ database tables, audit system, payment card providers (Brocard, FlexCard), Octo Browser sync, bulk operations with SSE, task automation engine
- **google-client** (126 .py files) — AI-powered task runner: polls admin for tasks, launches Octo Browser profiles, executes actions via browser-use + Claude/GPT. Metrics collection for LLM costs tracking
- **google-logflow** — Centralized log collection service (FastAPI + PostgreSQL + MinIO)
- **chrome-pf-api** — Chrome behavioral factor emulation and metrics analysis
- **checker-chrome-pf-api** — Automated health checker with auto-restart for failed emulations

**AI & Content Generation:**
- AI-powered website auto-generation service (GPT, Claude, Gemini) — generates landing pages with text + images
- White Page Generator v1 & v2 — automated landing page creation with AI content
- Browser Automation System — self-learning browser automation using browser-use + Claude Sonnet

**Apple Developer Automation (apple_farm, 167 .py files):**
- Full pipeline: profile creation → warm-up → registration → verification → payment
- Multi-provider SMS integration (HeroSMS, SMS-Activate, SMSPVA)
- **Statistical fingerprint analysis** — measuring each parameter's impact (IPQS fraud score, FP Pro bot probability, AntCpt canvas hash) on registration success rate
- Apple antifraud bypass (endpoint analysis: `idmsa.apple.com`, `gsa.apple.com`, headers: `X-Apple-I-FD-Client-Info`)
- Octo Browser + Playwright automation, Google Sheets sync

**Telegram Bots (7+ bots):**
- Recruiting bot with funnel surveys, resume storage in MinIO, Google Sheets export
- Account issuance bot (Google Sheets + MySQL sync)
- Payment/vacancy approval bot with admin panel
- UGC Talent Hub bot for creator onboarding
- Daily report bot with multi-handler architecture
- Domain management bot (Cloudflare API, DNS)

**Infrastructure & DevOps:**
- Docker/Compose containerization for all projects (dev + prod environments)
- GitLab CI/CD pipelines with automated deployments via Portainer API
- Linux server administration, SSL, domain management
- Prometheus + Grafana monitoring stack

**Blockchain:**
- Solana copy-trading bot (automated trade analysis and execution)
- Pump.fun trading automation

**Other services:**
- Mobile Cloaking backend for iOS apps (geo-targeting, offer selection)
- SIM Bank — web service for SIM card automation (Flask + Telegram bot)
- Modem Farm management system
- TD Accounts Shop — admin panel for account store management
- URL Validator with Prometheus/Grafana monitoring
- PDF Link Checker with HTML/CSV reports
- IPQS Fingerprint Checker (FastAPI + browser extensions for Firefox/Chrome) — fingerprint quality analysis via IPQS, FingerprintPro, AntCaptcha, CreepJS

---

### Freelance — RPA Python Developer
**June 2022 — November 2022** (6 months)

- Built Facebook Farm automation system with admin panel + REST API (Selenium, FastAPI)
- Built Reddit Farm system with OAuth API, proxy support, upvoting automation (asyncprawcore, PostgreSQL)

---

### AcidBro, Kyiv — RPA Python Developer (Team Lead)
**January 2021 — June 2022** (1.5 years)

Led the automation team, managing multi-project pipelines.

- **Google Farm** automation (Zennoposter, Python Selenium) — ad account creation and management
- **Banking automation** (Zennoposter, BAS, Android emulation, Python)
- **Antidetect browser development** — contributed to browser fingerprint evasion
- **Binance NFT** — automated NFT/box purchasing bot
- **Telegram Farm** (Pyrogram, Telethon) — mass account management with asyncio, multiprocessing
- Server infrastructure administration

---

### Financial Broker, Kyiv — RPA Developer (Team Lead)
**June 2020 — January 2021** (8 months)

- Led the automation division
- Mass account registration and SERM campaigns via Zennoposter
- Mobile proxy network setup and administration

---

### Quora Project, Kyiv — RPA Developer
**September 2019 — May 2020** (9 months)

- Built Telegram service for automated comment boosting and trend monitoring
- Scaled Quora account networks, optimized engagement pipelines
- Configured mobile proxy systems for large-scale operations

---

### OnlineReputation, Kyiv — Zennoposter Developer & System Administrator
**October 2017 — August 2019** (2 years)

- Designed automation templates for social media (parsing, posting, engagement)
- POST/GET request workflow development and debugging
- Office IT infrastructure administration (networking, video surveillance)

---

## Open Source & Side Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [octo-mcp](https://github.com/mazamaka/octo-mcp) | MCP Server for Octo Browser — 40+ AI tools for browser management | Python, Pydantic, Playwright, CDP |
| [nodriver-antidetect](https://github.com/mazamaka/nodriver-antidetect) | Antidetect browser with CDP-level fingerprint spoofing (CreepJS: headless 0%, stealth 0%) | Python, nodriver, Docker |
| [detect-expert-client](https://github.com/mazamaka/detect-expert-client) | Python client for detect.expert with Cloudflare bypass via TLS fingerprinting | Python, tls-client, Click CLI |
| [Flipper](https://github.com/mazamaka/Flipper) | FastAPI backend for Flipper Zero SubGHz control | FastAPI, Python |
| [antifraud-spy](https://github.com/mazamaka/antifraud-spy) | Chrome Extension for monitoring antifraud/fingerprinting techniques | JavaScript, Manifest V3 |
| [browser-automation-system](https://github.com/mazamaka/browser-automation-system) | Self-learning browser automation with AI | FastAPI, React, browser-use, Claude |
| [weekly-report-agent](https://github.com/mazamaka/weekly-report-agent) | CLI agent: git logs → Claude analysis → ClickUp tasks | Python, Claude API |
| [virustotal-scraper](https://github.com/mazamaka/virustotal-scraper) | VirusTotal file scanner via browser automation | Python, httpx, Docker |

---

## AI-First Development Workflow

Currently building all projects using **Claude Code** as primary development environment with a custom multi-agent system:

| Agent | Role |
|-------|------|
| **architect** | System design, project structure |
| **developer** | Code implementation |
| **debugger** | Root cause analysis, profiling |
| **reviewer** | Code review, security audit |
| **tester** | Unit/integration/e2e tests |
| **devops** | Docker, CI/CD, infrastructure |
| **deployer** | Automated deployment via Portainer API |
| **techlead** | Project analysis, sprint planning |
| **orchestrator** | Multi-agent coordination |
| **scraper** | Web scraping, browser automation |
| **transcriber** | Meeting transcription (Whisper) |
| **documenter** | Documentation, README |

**Custom hooks:** auto-linting (ruff), security validation, pre-commit checks.
**MCP integrations:** Docker, PostgreSQL, Chrome DevTools, Sentry, Vercel, SSH, context7.

---

## Education

**Kyiv National University of Technologies and Design (KNUTD)**
Mechatronics and Computer Technologies — Electrical Engineering
2013 — 2019 | Graduated with Honors

---

## Languages

- Ukrainian — Fluent
- Russian — Fluent
- English — Intermediate (reading documentation, technical communication)

---

## Hobbies

Cycling, longboarding, wakeboarding, tennis (court & table), volleyball, running, Muay Thai, night car rides, tech webinars, self-development
