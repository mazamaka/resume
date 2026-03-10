# Максим Бабенко

**Python Developer | AI Automation Engineer | DevOps**

Будапешт, Венгрия (из Киева, Украина) | $6,000+/мес

- Email: mazamaka603@gmail.com
- Телефон: +380 99 045 1609
- GitHub: [github.com/mazamaka](https://github.com/mazamaka)
- LinkedIn: [linkedin.com/in/max-bob-python](https://linkedin.com/in/max-bob-python)
- Telegram: [@Mazamaka](https://t.me/Mazamaka)

---

## Профиль

Full-Stack Python разработчик с 8+ годами опыта. Строю production-системы "под ключ" — от backend-микросервисов и админ-панелей до AI-powered браузерной автоматизации и DevOps-инфраструктуры. Разработал и запустил 40+ проектов: масштабные платформы управления рекламой, экосистемы AI-агентов, Telegram-боты, blockchain-инструменты.

Глубокая экспертиза в antifraud и fingerprinting: разработка антидетект-браузера с CDP-уровневым спуфингом (Canvas, WebGL, Audio, Navigator, TLS), обход bot-detection систем, анализ antifraud-эндпоинтов (Apple, Google), инструменты мониторинга fingerprint-техник. Прошёл профессиональный курс по антифроду (15 модулей: от DNS-идентификаторов и WebGPU до VM-детекта и деанонимизации).

Сейчас фокус на AI-first разработке: мультиагентные системы на Claude Code, браузерная автоматизация с AI (browser-use), полный цикл разработки где AI-агенты занимаются архитектурой, кодом, тестами, ревью и деплоем.

Сильные DevOps навыки: Docker, CI/CD (GitLab), администрирование Linux-серверов, Portainer, Nginx, мониторинг (Prometheus/Grafana).

---

## Ключевые навыки

### Языки и фреймворки
- **Python** (основной): FastAPI, Flask, Aiohttp
- **JavaScript/TypeScript**: React, Chrome Extensions (Manifest V3), jQuery, HTMX
- **HTML/CSS**: Jinja2, TailwindCSS
- **SQL**: PostgreSQL, MySQL, SQLite
- **NoSQL**: MongoDB, Redis

### AI и LLM
- Claude API / Claude Code (основная среда разработки)
- OpenAI API (GPT-4, GPT-3.5) — генерация контента, чат-боты
- browser-use — AI-powered браузерная автоматизация с LLM-агентами
- Мультиагентные системы (14 специализированных агентов: architect, developer, reviewer, deployer и др.)
- Stable Diffusion / Midjourney API — пайплайны генерации изображений
- NLP: transformers, zero-shot классификация

### Backend и архитектура
- Микросервисная архитектура (FastAPI)
- Проектирование REST API, Swagger/OpenAPI
- ORM: SQLAlchemy (async), SQLModel, Alembic миграции
- Очереди задач: Celery, RabbitMQ, Temporal
- Асинхронное программирование: asyncio, aiohttp, asyncpg
- Админ-панели: Starlette Admin, Flask-Admin, FastAPI Admin
- Pydantic, pydantic-settings для конфигурации

### Antifraud и Fingerprinting
- **Разработка антидетект-браузера** (nodriver + CDP injection) — CreepJS: headless 0%, stealth 0%
- Спуфинг fingerprint на CDP-уровне: Canvas noise, WebGL vendor/renderer, Audio, Navigator, Screen, Plugins, Battery, Permissions
- Анализ antifraud-систем: IPQS, FingerprintPro, AntCaptcha, CreepJS, BrowserLeaks, Sannysoft
- Мониторинг fingerprint-техник (Chrome Extension — перехват Canvas, WebGL, Navigator, MediaDevices API)
- Обход bot-detection: удаление CDP-маркеров (`cdc_*`, `__webdriver_*`), подмена `navigator.webdriver`, эмуляция `window.chrome`
- Обход Cloudflare через TLS fingerprinting (tls-client)
- Docker GPU (NVIDIA) для реального WebGL рендеринга в headless-режиме
- Знание: DNS fingerprinting, WebGPU, WASM fingerprint, TCP/UDP/QUIC сетевые отпечатки (M1D/M1D1), VPN/Proxy детект (10 методов геолокации), VM-детект и обход, ультразвуковая деанонимизация

### Браузерная автоматизация и RPA
- Playwright, Selenium, nodriver
- Octo Browser API (интеграция с антидетект-браузером)
- CDP (Chrome DevTools Protocol) — низкоуровневое управление браузером
- Zennoposter, BAS (Browser Automation Studio)

### DevOps и инфраструктура
- Docker, Docker Compose — контейнеризация всех проектов
- CI/CD: GitLab пайплайны, автоматический деплой
- Администрирование Linux-серверов (Ubuntu, Debian)
- Nginx + Certbot (SSL, reverse proxy)
- Portainer — управление контейнерами
- Prometheus + Grafana — мониторинг и алертинг
- MinIO (S3-совместимое хранилище)
- DNS (Cloudflare)
- SSH-туннели, systemd сервисы

### Blockchain и Web3
- Solana: копитрейдинг-бот, анализ транзакций
- Web3 интеграция (кошельки, смарт-контракты)
- NFT маркетплейсы (Binance NFT)
- Pump.fun автоматизация трейдинга

### Telegram и боты
- aiogram 3 (основной фреймворк)
- Pyrogram, Telethon
- Воронки ботов, интерактивные опросы, интеграция с админкой
- Google Sheets API интеграция

### Инструменты и workflow
- Git (GitHub, GitLab)
- Claude Code — полный цикл AI-assisted разработки
- MCP (Model Context Protocol) серверы
- ClickUp, автоматизация управления задачами
- Whisper — транскрибация аудио/видео

---

## Опыт работы

### Traffic Devils, Киев (удалённо) — Python Developer
**Ноябрь 2022 — настоящее время** (~3.5 года)

Ведущий разработчик комплексной экосистемы управления Google Ads фермой — мульти-сервисная платформа для работы с сотнями рекламных аккаунтов с AI-автоматизацией.

**Ключевые проекты и достижения:**

**Экосистема Google Ads (5 сервисов, 800+ Python файлов):**
- **google-admin** (555 .py файлов) — Полная платформа управления: Starlette Admin dashboard, 40+ таблиц БД, система аудита, провайдеры платёжных карт (Brocard, FlexCard), синхронизация с Octo Browser, массовые операции с SSE, движок автоматизации задач
- **google-client** (126 .py файлов) — AI-powered task runner: поллинг задач из админки, запуск Octo Browser профилей, выполнение действий через browser-use + Claude/GPT. Сбор метрик стоимости LLM
- **google-logflow** — Централизованный сбор логов (FastAPI + PostgreSQL + MinIO)
- **chrome-pf-api** — Эмуляция поведенческих факторов Chrome и анализ метрик
- **checker-chrome-pf-api** — Автоматическая проверка и перезапуск упавших эмуляций

**AI и генерация контента:**
- Сервис автогенерации сайтов на AI (GPT, Claude, Gemini) — лендинги с текстом + изображениями
- White Page Generator v1 и v2 — автоматическое создание лендингов с AI-контентом
- Browser Automation System — самообучающаяся система автоматизации браузера (browser-use + Claude Sonnet)

**Автоматизация Apple Developer (apple_farm, 167 .py файлов):**
- Полный пайплайн: создание профиля → прогрев → регистрация → верификация → оплата
- Мульти-провайдерная SMS интеграция (HeroSMS, SMS-Activate, SMSPVA)
- **Статистический анализ fingerprint** — определение влияния каждого параметра (IPQS fraud score, FP Pro bot probability, AntCpt canvas hash) на успешность регистрации
- Обход antifraud-систем Apple (анализ эндпоинтов `idmsa.apple.com`, `gsa.apple.com`, заголовков `X-Apple-I-FD-Client-Info`)
- Octo Browser + Playwright автоматизация, синхронизация с Google Sheets

**Telegram боты (7+ ботов):**
- Рекрутинг-бот с воронкой опросов, хранение резюме в MinIO, экспорт в Google Sheets
- Бот выдачи аккаунтов (Google Sheets + MySQL синхронизация)
- Бот утверждения платежей/вакансий с админ-панелью
- UGC Talent Hub бот для онбординга креаторов
- Бот ежедневных отчётов с мульти-хэндлерной архитектурой
- Бот управления доменами (Cloudflare API, DNS)

**Инфраструктура и DevOps:**
- Docker/Compose контейнеризация всех проектов (dev + prod окружения)
- GitLab CI/CD пайплайны с автодеплоем через Portainer API
- Администрирование Linux-серверов, SSL, управление доменами
- Стек мониторинга Prometheus + Grafana

**Blockchain:**
- Solana копитрейдинг-бот (автоматический анализ и исполнение сделок)
- Pump.fun автоматизация трейдинга

**Другие сервисы:**
- Mobile Cloaking backend для iOS-приложений (гео-таргетинг, выбор офферов)
- SIM Bank — веб-сервис автоматизации SIM-карт (Flask + Telegram бот)
- Система управления фермой модемов
- TD Accounts Shop — админ-панель управления магазином аккаунтов
- URL Validator с мониторингом Prometheus/Grafana
- PDF Link Checker с отчётами HTML/CSV
- IPQS Fingerprint Checker (FastAPI + браузерные расширения для Firefox/Chrome) — проверка fingerprint-качества профилей через IPQS, FingerprintPro, AntCaptcha, CreepJS

---

### Фриланс — RPA Python Developer
**Июнь 2022 — Ноябрь 2022** (6 месяцев)

- Facebook Farm система автоматизации с админ-панелью + REST API (Selenium, FastAPI)
- Reddit Farm система с OAuth API, поддержка прокси, автоматизация upvoting (asyncprawcore, PostgreSQL)

---

### AcidBro, Киев — RPA Python Developer (Team Lead)
**Январь 2021 — Июнь 2022** (1.5 года)

Руководство командой автоматизации, управление мульти-проектными пайплайнами.

- **Google Farm** автоматизация (Zennoposter, Python Selenium) — создание и управление рекламными аккаунтами
- **Банковская автоматизация** (Zennoposter, BAS, эмуляция Android, Python)
- **Разработка антидетект-браузера** — обход fingerprint-проверок
- **Binance NFT** — автоматизированный бот покупки NFT/box
- **Telegram Farm** (Pyrogram, Telethon) — массовое управление аккаунтами с asyncio, multiprocessing
- Администрирование серверной инфраструктуры

---

### Финансовый Брокер, Киев — RPA Developer (Team Lead)
**Июнь 2020 — Январь 2021** (8 месяцев)

- Руководство отделом автоматизации
- Массовая регистрация и SERM-кампании через Zennoposter
- Настройка и администрирование сетей мобильных прокси

---

### Quora Project, Киев — RPA Developer
**Сентябрь 2019 — Май 2020** (9 месяцев)

- Telegram-сервис для автоматического комментинга и вывода в топ
- Масштабирование сетей Quora-аккаунтов, оптимизация пайплайнов engagement
- Настройка мобильных прокси-систем для масштабных операций

---

### OnlineReputation, Киев — Zennoposter Developer и системный администратор
**Октябрь 2017 — Август 2019** (2 года)

- Шаблоны автоматизации для соцсетей (парсинг, постинг, engagement)
- Разработка и отладка POST/GET workflow
- Администрирование IT-инфраструктуры офиса (сети, видеонаблюдение)

---

## Open Source и pet-проекты

| Проект | Описание | Стек |
|--------|----------|------|
| [octo-mcp](https://github.com/mazamaka/octo-mcp) | MCP Server для Octo Browser — 40+ AI-инструментов для управления браузером | Python, Pydantic, Playwright, CDP |
| [nodriver-antidetect](https://github.com/mazamaka/nodriver-antidetect) | Антидетект-браузер с CDP-уровневым спуфингом fingerprint (CreepJS: headless 0%, stealth 0%) | Python, nodriver, Docker |
| [detect-expert-client](https://github.com/mazamaka/detect-expert-client) | Python клиент для detect.expert с обходом Cloudflare через TLS fingerprinting | Python, tls-client, Click CLI |
| [Flipper](https://github.com/mazamaka/Flipper) | FastAPI backend для управления Flipper Zero SubGHz | FastAPI, Python |
| [antifraud-spy](https://github.com/mazamaka/antifraud-spy) | Chrome Extension для мониторинга antifraud/fingerprinting техник | JavaScript, Manifest V3 |
| [browser-automation-system](https://github.com/mazamaka/browser-automation-system) | Самообучающаяся система автоматизации браузера с AI | FastAPI, React, browser-use, Claude |
| [weekly-report-agent](https://github.com/mazamaka/weekly-report-agent) | CLI агент: git логи → анализ Claude → задачи в ClickUp | Python, Claude API |
| [virustotal-scraper](https://github.com/mazamaka/virustotal-scraper) | VirusTotal сканер файлов через браузерную автоматизацию | Python, httpx, Docker |

---

## AI-First рабочий процесс

Все проекты разрабатываю через **Claude Code** с кастомной мультиагентной системой:

| Агент | Роль |
|-------|------|
| **architect** | Проектирование системы, структура проекта |
| **developer** | Написание кода |
| **debugger** | Root cause анализ, профилирование |
| **reviewer** | Code review, аудит безопасности |
| **tester** | Unit/integration/e2e тесты |
| **devops** | Docker, CI/CD, инфраструктура |
| **deployer** | Автодеплой через Portainer API |
| **techlead** | Анализ проекта, планирование спринтов |
| **orchestrator** | Координация мультиагентных задач |
| **scraper** | Web scraping, автоматизация браузера |
| **transcriber** | Транскрибация созвонов (Whisper) |
| **documenter** | Документация, README |

**Кастомные hooks:** автолинтинг (ruff), валидация безопасности, pre-commit проверки.
**MCP интеграции:** Docker, PostgreSQL, Chrome DevTools, Sentry, Vercel, SSH, context7.

---

## Образование

**Киевский национальный университет технологий и дизайна (КНУТД)**
Мехатроника и компьютерные технологии — Электроэнергетика, электротехника и электромеханика
2013 — 2019 | Диплом с отличием

---

## Языки

- Украинский — свободно
- Русский — свободно
- Английский — Intermediate (чтение документации, техническая коммуникация)

---

## Хобби

Велосипед, лонгборд, вейкбординг, теннис (корт и настольный), волейбол, бег, муай тай, ночные поездки на авто, tech-вебинары, саморазвитие
