<div align="center">

# Hi, I am Kelvin Amartey Winston 👋

### Security-Focused Python & Backend Engineer | DevSecOps & AppSec

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kelvin-amartey-winston-2935b8386/)
[![Email](https://img.shields.io/badge/Email-D14836.svg?logo=gmail&logoColor=white)](mailto:kelvinamarteywinston@gmail.com)
[![Location](https://img.shields.io/badge/Location-Accra%2C%20Ghana-blue.svg)](https://github.com/Drizzy-ul)
[![Timezone](https://img.shields.io/badge/Timezone-UTC%2B0%20%2F%20GMT-orange.svg)](https://github.com/Drizzy-ul)
[![Status](https://img.shields.io/badge/Availability-Open%20to%20Remote%20Roles-brightgreen.svg)](mailto:kelvinamarteywinston@gmail.com)
[![Security+](https://img.shields.io/badge/CompTIA-Security%2B%20Track-red.svg?logo=comptia&logoColor=white)](https://github.com/Drizzy-ul)

<p align="center">
  Backend software engineer with a cybersecurity foundation. I specialize in building <b>resilient, transaction-heavy distributed systems</b>, <b>automated defense tooling</b>, and <b>cryptographically sound backend architectures</b>.
</p>

</div>

---

### 💼 Technical Expertise

- **Backend Engineering**: Async Python (`FastAPI`, `Starlette`), RESTful API architecture, pessimistic concurrency locking (`SELECT FOR UPDATE`), double-entry financial ledger invariants, task queues (`Celery`), distributed caching (`Redis`).
- **Application & Network Security**: OWASP Top 10 mitigation, RFC 6238 TOTP MFA, RBAC route guards, sliding-window rate limiting, intrusion detection systems (IDS), OS-level firewall automation (`iptables`, `ufw`, `netsh`).
- **DevSecOps & Cloud**: Docker containerization, Docker Compose orchestration, automated CI/CD pipelines (`GitHub Actions`), Linux system administration, structured audit logging.

---

### 🛠️ Tech Stack & Tooling

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | `Python 3.10+`, `SQL`, `Bash / Shell` |
| **Frameworks & Libs** | `FastAPI`, `Pydantic v2`, `SQLAlchemy 2.0 (Async)`, `Celery`, `ReportLab`, `Paramiko` |
| **Databases & Caches** | `PostgreSQL`, `Redis`, `SQLite (aiosqlite)`, `Alembic` |
| **Security & Auth** | `PyJWT (Token Rotation)`, `PyOTP (MFA/TOTP)`, `Bcrypt`, `SlowAPI`, `MITRE ATT&CK` |
| **DevOps & Testing** | `Docker`, `Docker Compose`, `GitHub Actions (CI/CD)`, `pytest`, `pytest-asyncio`, `Git` |

</div>

---

### 🚀 Featured Engineering Projects

#### 1. [LogSentinel](https://github.com/Drizzy-ul/log-sentinel) — Autonomous Real-Time Log IDS & Active Firewall Daemon
[![CI Status](https://github.com/Drizzy-ul/log-sentinel/actions/workflows/ci.yml/badge.svg)](https://github.com/Drizzy-ul/log-sentinel/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Drizzy-ul/log-sentinel/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B%20(Zero%20Deps)-blue.svg?logo=python&logoColor=white)](https://github.com/Drizzy-ul/log-sentinel)

> **Autonomous host-based intrusion prevention daemon with zero third-party dependencies.**
- **Real-Time Log Stream Analysis**: Tails Nginx and Apache HTTP access logs using high-performance regex signatures to detect SQLi, XSS, Path Traversal, and RCE attacks on the fly.
- **Sliding-Window Rate Limiting**: Tracks per-IP infraction velocity using stateful memory buffers and isolates brute-force/recon sweeps.
- **Active Firewall Enforcement**: Triggers automated OS-level IP bans via `iptables`, `ufw`, and Windows `netsh` with automated whitelisting and dry-run safety modes.
- **Cross-Platform CI**: Automated cross-platform test matrix across Ubuntu, Windows, and macOS with 100% test pass rates.
- `Python (stdlib)` · `iptables` · `ufw` · `netsh` · `GitHub Actions CI` · `MIT License`

#### 2. [FinTech Multi-Currency Ledger](https://github.com/Drizzy-ul/fintech-multicurrency-ledger) — Production-Grade Double-Entry System
[![CI Status](https://github.com/Drizzy-ul/fintech-multicurrency-ledger/actions/workflows/ci.yml/badge.svg)](https://github.com/Drizzy-ul/fintech-multicurrency-ledger/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Drizzy-ul/fintech-multicurrency-ledger/blob/main/LICENSE)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688.svg?logo=fastapi&logoColor=white)](https://github.com/Drizzy-ul/fintech-multicurrency-ledger)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1.svg?logo=postgresql&logoColor=white)](https://github.com/Drizzy-ul/fintech-multicurrency-ledger)

> **High-throughput financial ledger handling multi-currency wallets with strict mathematical invariants.**
- **Double-Entry Accounting Engine**: Implements balanced immutable journal entries with FX clearing accounts ($\sum \text{Debits} = \sum \text{Credits}$).
- **Concurrency & Double-Spend Defense**: Row-level pessimistic locking (`with_for_update`) prevents race conditions, negative balances, and duplicate withdrawals.
- **Real-Time FX Caching**: Live currency conversion engine (GHS / USD / GBP) backed by Redis caching and 60-second rate lock guarantees.
- **Asynchronous Statement Worker**: Celery task queue compiling branded, bank-grade PDF transaction statements via ReportLab.
- `FastAPI` · `PostgreSQL` · `Redis` · `Celery` · `ReportLab` · `Docker Compose` · `pytest`

#### 3. [HoneyGuard](https://github.com/Drizzy-ul/honeyguard) — Multi-Service Honeypot & SOC Telemetry Sentinel
[![CI Status](https://github.com/Drizzy-ul/honeyguard/actions/workflows/ci.yml/badge.svg)](https://github.com/Drizzy-ul/honeyguard/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Drizzy-ul/honeyguard/blob/main/LICENSE)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-red.svg)](https://github.com/Drizzy-ul/honeyguard)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688.svg?logo=fastapi&logoColor=white)](https://github.com/Drizzy-ul/honeyguard)

> **Deliberate low-interaction SSH and HTTP decoy sensors feeding real-time threat intelligence.**
- **Multi-Vector Decoy Services**: Simulates vulnerable OpenSSH services and decoy HTTP endpoints (`.env`, `wp-login.php`, `admin`).
- **Threat Intelligence & MITRE ATT&CK**: Extracts IoCs (default credential probing, malware drop commands, Log4j/Spring4Shell payloads) and maps them directly to MITRE tactics.
- **Real-Time SOC Dashboard**: FastAPI WebSocket dashboard streaming live attack feeds with GeoIP location mapping and Discord/Slack webhook alerts.
- `Python` · `FastAPI` · `Paramiko` · `GeoIP` · `WebSockets` · `pytest`

#### 4. [SecureAuth Backend API](https://github.com/Drizzy-ul/secure-auth-api) — Enterprise Auth & Authorization Engine
[![CI Status](https://github.com/Drizzy-ul/secure-auth-api/actions/workflows/ci.yml/badge.svg)](https://github.com/Drizzy-ul/secure-auth-api/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Drizzy-ul/secure-auth-api/blob/main/LICENSE)
[![OWASP](https://img.shields.io/badge/OWASP-Top%2010-orange.svg)](https://github.com/Drizzy-ul/secure-auth-api)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688.svg?logo=fastapi&logoColor=white)](https://github.com/Drizzy-ul/secure-auth-api)

> **Hardened authentication and authorization microservice following NIST and OWASP standards.**
- **Multi-Factor Authentication (MFA)**: RFC 6238 TOTP authenticator integration with SVG/PNG QR code generation and single-use emergency recovery codes.
- **Granular RBAC**: Declarative route guards (`RequirePermission`, `RequireRole`) enforcing the Principle of Least Privilege and hierarchical escalation protection.
- **Token Security**: Short-lived JWT access tokens with single-use refresh token rotation and automatic family revocation upon replay attack detection.
- **Rate-Limiting**: Sliding-window rate limiters defending against credential stuffing and brute-force attacks; 14 automated unit tests running in CI.
- `FastAPI` · `SQLAlchemy Async` · `PyJWT` · `PyOTP` · `Bcrypt` · `SlowAPI` · `pytest`

---

### 📊 GitHub Activity & Metrics

<div align="center">

<img src="https://github-readme-stats-eight-theta.vercel.app/api?username=Drizzy-ul&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Kelvin's GitHub Stats" height="165" />
<img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Drizzy-ul&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
<br/><br/>
<img src="https://streak-stats.demolab.com?user=Drizzy-ul&theme=tokyonight&hide_border=true" alt="Kelvin's GitHub Streak" height="165" />

</div>

---

### 📬 Connect With Me

- **Email**: [kelvinamarteywinston@gmail.com](mailto:kelvinamarteywinston@gmail.com)
- **LinkedIn**: [Kelvin Amartey Winston](https://www.linkedin.com/in/kelvin-amartey-winston-2935b8386/)
- **Location**: Accra, Ghana (UTC+0 / GMT • Available for remote roles worldwide)