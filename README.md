<div align="center">

`$ whoami`

# Fernando Morales

**Backend & Full-Stack Developer** · **Based in Peru**

Remote roles and selected freelance work

![Open to remote roles](https://img.shields.io/badge/Open-Remote%20roles-0E7490?style=flat-square&labelColor=0C1410)

[![English, current language](https://img.shields.io/badge/EN-English%20%C2%B7%20current-15803D?style=flat-square&labelColor=0C1410)](README.md) [![Switch to Spanish](https://img.shields.io/badge/ES-Espa%C3%B1ol-334155?style=flat-square&labelColor=0C1410)](README.es.md)

[![About](https://img.shields.io/badge/-About-6D28D9?style=flat-square&labelColor=0C1410)](#about) [![Stack](https://img.shields.io/badge/-Stack-0E7490?style=flat-square&labelColor=0C1410)](#stack) [![Work](https://img.shields.io/badge/-Work-15803D?style=flat-square&labelColor=0C1410)](#selected-work) [![Contact](https://img.shields.io/badge/-Contact-6D28D9?style=flat-square&labelColor=0C1410)](#contact)

</div>

```text
role     Backend & Full-Stack Developer
base     Peru
open     remote roles · selected freelance
study    Systems Engineering (student)
focus    backend · business apps · automation · Windows tools
```

---

## About

I'm a **Systems Engineering student** and software developer building applications that have to operate under real technical and business constraints. My work includes web applications with **Angular and Spring Boot**, backend services in **Java and Python**, and native Windows utilities written in **C++ and C#**.

I'm particularly interested in business workflows, automation, software licensing, offline environments, legacy Windows applications and integrations with existing software.

I use AI as a **development tool**, not as a substitute for software engineering: architecture, business rules, validation, security decisions and final verification remain explicit parts of my process. When a project integrates an LLM, the model may interpret requests or propose operations, but deterministic application code validates permissions, arguments and business rules before any sensitive action is executed.

> **The model proposes. The code decides.**

I'm open to **remote roles** and **selected freelance projects** in backend engineering, full-stack web development, automation and applied AI.

---

## Stack

Grouped by where I use each technology.

- **Backend** — `Java` `Spring Boot` `Python` `FastAPI` `C#` `.NET`
- **Frontend** — `Angular` `React`
- **Data** — `MySQL` `MariaDB` `SQLAlchemy` `Flyway`
- **Native Windows** — `C++` `Win32 API` `Windows CNG` `Windows Forms`
- **AI & automation** — `LLM tool calling` `LangGraph` `agent workflows` `human approval flows`
- **Infrastructure** — `Docker` `GitHub Actions` `REST APIs` `SSE`

---

## Selected work

Start with these three projects.

### [Overseer](https://github.com/FerS00/Overseer)

![Testing / preview](https://img.shields.io/badge/Status-Testing%20%2F%20preview-6D28D9?style=flat-square&labelColor=0C1410) `Public source · MIT`

Local, read-only, real-time activity monitor for Claude Code and Codex, with an animated pixel mascot for each agent.

Agent hooks and Codex session rollouts feed a single event stream that is redacted before storage, deduplicated and replayed to the dashboard over Server-Sent Events after reconnects. File readers persist byte offsets so they resume after restarts, and the server binds to loopback with a token-protected ingest endpoint by default.

Overseer only observes agent activity; it never sends commands to either agent.

`Java 21` `Spring Boot 3.5` `Angular 22` `Node.js 24` `H2` `Flyway` `SSE` `Docker` `Playwright`

---

### [OPERATIX](https://github.com/FerS00/OPERATIX)

![MVP](https://img.shields.io/badge/Status-MVP-0E7490?style=flat-square&labelColor=0C1410) `Public source`

Sales assistant that converts natural-language requests into validated business operations.

The LLM interprets the request and proposes tool calls, but it does not write directly to business data. The application validates arguments, permissions and business rules, handles idempotency and controls what can be written to Excel, Google Sheets or MySQL.

It also includes per-currency reporting, a React dashboard and Telegram confirmations for operations that require explicit user approval. Production deployment is out of scope for this MVP.

`Python` `FastAPI` `LangGraph` `SQLAlchemy` `MySQL` `React` `Docker`

---

### [VENTAS_DPP case study](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)

![Private source](https://img.shields.io/badge/Status-Private%20source-334155?style=flat-square&labelColor=0C1410) `Not in production`

Web storefront and back office built to replace a hosted store for a software reseller.

The system covers catalog management, bundles, offers with price snapshots, customer accounts with one-time codes, permission-based administration, notifications, spreadsheet synchronization and XLSX/PDF exports.

It also includes a guided assistant with an optional LLM-backed mode, while the application's business logic remains independent from the model.

`Angular 20` `Spring Boot 3.4` `Java 17` `Spring Security` `Flyway` `MariaDB / MySQL` `Docker`

[![Read case study](https://img.shields.io/badge/Read-case%20study-C2410C?style=flat-square&labelColor=0C1410)](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)

---

## Additional work

### [RelayForge](https://github.com/FerS00/RelayForge)

![Paused / early development](https://img.shields.io/badge/Status-Paused%20%2F%20early%20development-334155?style=flat-square&labelColor=0C1410) `Public source · Apache-2.0`

Self-hosted work console for coordinating coding agents (Claude Code, Codex, and Antigravity) on Windows.

Claude Code handles planning, Codex implements changes within isolated Git worktrees, declared checks verify test/lint suites, and Antigravity executes read-only audits. The operator retains full control with human-approved delivery actions (commit/push). Includes resilient process supervision via Windows Job Objects, real-time SSE streaming, and secure remote access through Tailscale Serve with pairing codes.

`Python 3.13+` `FastAPI` `React` `TypeScript` `SQLite` `Tailscale` `Windows Job Objects`

---

### [WLQuickGen](https://github.com/FerS00/WLQuickGen)

![Source-available](https://img.shields.io/badge/Status-Source--available-0E7490?style=flat-square&labelColor=0C1410) `PolyForm Noncommercial`

Portable Win32 utility for generating licenses for software protected with WinLicense.

It detects the available generator SDK and architecture automatically, writes license files atomically and exposes stable control IDs so its interface can also be automated using tools such as pywinauto.

The application is available in English, Spanish and Portuguese.

`C++17` `Win32 API` `CMake` `GitHub Actions`

---

### [LICENSE-SERVICE](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)

![Private source](https://img.shields.io/badge/Status-Private%20source-334155?style=flat-square&labelColor=0C1410)

Offline licensing system for .NET desktop applications.

A packager prepares an existing executable, the customer generates a hardware-bound request code, and a separate issuer workstation produces the activation response.

Licenses use ECDSA P-256 signatures and authenticated encryption, while signing material remains isolated on the issuer machine.

`C#` `.NET 10` `Windows Forms` `ECDSA P-256` `AES-GCM` `Docker`

[![Read case study](https://img.shields.io/badge/Read-case%20study-C2410C?style=flat-square&labelColor=0C1410)](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)

---

### [Hwid-Keygen-Core](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)

![Private source](https://img.shields.io/badge/Status-Private%20source-334155?style=flat-square&labelColor=0C1410)

Offline activation layer built around an unusual constraint: the original application source code is unavailable and only the WinLicense-protected executable can be extended.

A native plugin executes before the application, derives the hardware identity and verifies an ECDSA P-256 signed activation response generated on a separate issuer machine.

`C++17` `Win32` `Windows CNG` `CMake`

[![Read case study](https://img.shields.io/badge/Read-case%20study-C2410C?style=flat-square&labelColor=0C1410)](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)

---

### Private projects

> [!NOTE]
> Some of my work cannot be published because it contains proprietary code, customer-specific integrations or implementation details that should remain private. For these projects I publish technical case studies explaining the problem, architecture, design decisions, security model and technologies without exposing the original source code.
>
> **[Browse the case studies →](https://github.com/FerS00/portfolio)**

---

## Contact

I'm open to remote software development roles, selected freelance projects and technical collaborations.

- **Website** — [fextracode.com](https://fextracode.com) · Spanish & English
- **Portfolio** — [github.com/FerS00/portfolio](https://github.com/FerS00/portfolio)
- **LinkedIn** — [Fernando Morales](https://linkedin.com/in/fernando-trinidad-morales-pe%C3%B1a-3632b2391)
- **Email** — [moralespenafernando@gmail.com](mailto:moralespenafernando@gmail.com)
- **Telegram** — [@FerS_00](https://t.me/FerS_00)
- **GitHub** — [@FerS00](https://github.com/FerS00)

If you're interested in one of my private projects, I can discuss its architecture, my responsibilities and the technical decisions involved without exposing confidential source code.

---

<div align="center">

[![English, current language](https://img.shields.io/badge/EN-English%20%C2%B7%20current-15803D?style=flat-square&labelColor=0C1410)](README.md) [![Switch to Spanish](https://img.shields.io/badge/ES-Espa%C3%B1ol-334155?style=flat-square&labelColor=0C1410)](README.es.md)

[Top ↑](#fernando-morales)

</div>
