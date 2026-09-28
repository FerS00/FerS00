<div align="center">

# Fernando Morales (FerS00)

**Systems Engineering · Software Development**

Web applications · AI-assisted workflows · Windows tooling · Software licensing

</div>

I build software for problems where the application has to deal with real constraints: existing business processes, legacy Windows software, offline environments, external APIs and data that cannot simply be handed over to an LLM.

My recent work ranges from Angular/Spring Boot business systems to Python services with tool-calling agents and native C++/C# utilities for Windows.

### Main stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,react,angular,spring,java,cs,cpp,dotnet,mysql,docker,git" />
</p>

## Selected work

### [OPERATIX](https://github.com/FerS00/OPERATIX)

Sales assistant that converts natural-language requests into actual transactions.

The model does not write directly to business data. It proposes tool calls, while the application validates the operation, handles idempotency and decides what is written to Excel, Google Sheets or MySQL. It also includes per-currency reporting, a React dashboard and Telegram confirmations for operations that require user approval.

`Python` `FastAPI` `LangGraph` `SQLAlchemy` `MySQL` `React` `Docker`

**Public source**

---

### [WLQuickGen](https://github.com/FerS00/WLQuickGen)

Portable Win32 utility for generating licenses for software protected with WinLicense.

It detects the available generator SDK and architecture automatically, writes license files atomically and exposes stable control IDs so the interface can also be automated with tools such as pywinauto. The application is available in English, Spanish and Portuguese.

`C++17` `Win32 API` `CMake` `GitHub Actions`

**Public source**

---

### [LICENSE-SERVICE](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)

Offline licensing system for .NET desktop applications.

A packager prepares an existing executable, the customer generates a hardware-bound request code, and a separate issuer workstation returns the activation response. Licenses use ECDSA P-256 signatures and authenticated encryption; signing material remains on the issuer machine.

`C#` `.NET 10` `Windows Forms` `ECDSA P-256` `AES-GCM` `Docker`

**Private source · [Case study](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)**

---

### [VENTAS_DPP](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)

Web storefront and back office built to replace a hosted store for a software reseller.

The system covers catalog management, bundles, offers with price snapshots, customer accounts with one-time codes, permission-based administration, notifications, spreadsheet synchronization and XLSX/PDF exports. It also includes a guided assistant with an optional LLM-backed mode.

`Angular 20` `Spring Boot 3.4` `Java 17` `Spring Security` `Flyway` `MariaDB / MySQL` `Docker`

**Private source · [Case study](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)**

---

### [Hwid-Keygen-Core](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)

Offline activation layer for an unusual constraint: the original application source code is unavailable and only the WinLicense-protected executable can be modified around.

A native plugin runs before the application, derives the hardware identity and verifies an ECDSA P-256 signed activation response generated on a separate issuer machine.

`C++17` `Win32` `Windows CNG` `CMake`

**Private source · [Case study](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)**

## Private projects

Some repositories cannot be published because they contain proprietary code, customer-specific integrations or implementation details that should remain private.

For those projects I publish technical case studies covering the problem, architecture, design decisions, security model and technologies without exposing the original source.

**[Browse the case studies →](https://github.com/FerS00/portfolio)**
