<div align="center">

`$ whoami`

# Fernando Morales

**Desarrollador backend y full-stack** · **Perú**

Roles remotos y trabajo freelance seleccionado

![Abierto a roles remotos](https://img.shields.io/badge/Disponible-Roles%20remotos-0E7490?style=flat-square&labelColor=0C1410)

[![Idioma actual: español](https://img.shields.io/badge/ES-Espa%C3%B1ol%20%C2%B7%20actual-15803D?style=flat-square&labelColor=0C1410)](README.es.md) [![Cambiar a inglés](https://img.shields.io/badge/EN-English-334155?style=flat-square&labelColor=0C1410)](README.md)

[![Sobre mí](https://img.shields.io/badge/-Sobre%20m%C3%AD-6D28D9?style=flat-square&labelColor=0C1410)](#sobre-mí) [![Stack](https://img.shields.io/badge/-Stack-0E7490?style=flat-square&labelColor=0C1410)](#stack) [![Proyectos](https://img.shields.io/badge/-Proyectos-15803D?style=flat-square&labelColor=0C1410)](#proyectos-destacados) [![Contacto](https://img.shields.io/badge/-Contacto-6D28D9?style=flat-square&labelColor=0C1410)](#contacto)

</div>

```text
rol       Desarrollador backend y full-stack
base      Perú
modalidad roles remotos · freelance seleccionado
estudios  Ingeniería de Sistemas (estudiante)
enfoque   backend · apps de negocio · automatización · herramientas Windows
```

---

## Sobre mí

Soy **estudiante de Ingeniería de Sistemas** y desarrollador de software. Construyo aplicaciones que deben funcionar bajo restricciones técnicas y de negocio reales. Mi trabajo incluye aplicaciones web con **Angular y Spring Boot**, servicios backend en **Java y Python** y utilidades nativas para Windows escritas en **C++ y C#**.

Me interesan especialmente los flujos de negocio, la automatización, el licenciamiento de software, los entornos sin conexión, las aplicaciones Windows heredadas y las integraciones con software existente.

Uso la IA como **herramienta de desarrollo**, no como sustituto de la ingeniería de software: la arquitectura, las reglas de negocio, la validación, las decisiones de seguridad y la verificación final siguen siendo partes explícitas de mi proceso. Cuando un proyecto integra un LLM, el modelo puede interpretar solicitudes o proponer operaciones, pero el código determinista de la aplicación valida permisos, argumentos y reglas de negocio antes de ejecutar cualquier acción sensible.

> **El modelo propone. El código decide.**

Estoy abierto a **roles remotos** y **proyectos freelance seleccionados** en ingeniería backend, desarrollo web full-stack, automatización e IA aplicada.

---

## Stack

Agrupado según dónde utilizo cada tecnología.

- **Backend** — `Java` `Spring Boot` `Python` `FastAPI` `C#` `.NET`
- **Frontend** — `Angular` `React`
- **Datos** — `MySQL` `MariaDB` `SQLAlchemy` `Flyway`
- **Windows nativo** — `C++` `Win32 API` `Windows CNG` `Windows Forms`
- **IA y automatización** — `LLM tool calling` `LangGraph` `flujos de agentes` `flujos de aprobación humana`
- **Infraestructura** — `Docker` `GitHub Actions` `REST APIs` `SSE`

---

## Proyectos destacados

Empieza por estos tres proyectos.

### [Overseer](https://github.com/FerS00/Overseer)

![Pruebas / vista previa](https://img.shields.io/badge/Estado-Pruebas%20%2F%20vista%20previa-6D28D9?style=flat-square&labelColor=0C1410) `Código público · MIT`

Monitor de actividad local, de solo lectura y en tiempo real para Claude Code y Codex, con una mascota pixel animada para cada agente.

Los hooks de los agentes y los rollouts de sesión de Codex alimentan un único flujo de eventos. Los eventos se filtran para eliminar datos sensibles antes de almacenarse, después se deduplican y se reenvían al panel mediante Server-Sent Events tras las reconexiones. Los lectores de archivos guardan offsets de bytes para reanudar tras los reinicios, y el servidor se enlaza a loopback con un endpoint de ingesta protegido por token de forma predeterminada.

Overseer solo observa la actividad de los agentes; nunca envía comandos a ninguno de los dos.

`Java 21` `Spring Boot 3.5` `Angular 22` `Node.js 24` `H2` `Flyway` `SSE` `Docker` `Playwright`

---

### [OPERATIX](https://github.com/FerS00/OPERATIX)

![MVP](https://img.shields.io/badge/Estado-MVP-0E7490?style=flat-square&labelColor=0C1410) `Código público`

Asistente de ventas que convierte solicitudes en lenguaje natural en operaciones de negocio validadas.

El LLM interpreta la solicitud y propone llamadas a herramientas, pero no escribe directamente en los datos de negocio. La aplicación valida argumentos, permisos y reglas de negocio, gestiona la idempotencia y controla lo que puede escribirse en Excel, Google Sheets o MySQL.

Incluye además reportes por moneda, un panel en React y confirmaciones por Telegram para las operaciones que requieren aprobación explícita del usuario. El despliegue en producción queda fuera del alcance de este MVP.

`Python` `FastAPI` `LangGraph` `SQLAlchemy` `MySQL` `React` `Docker`

---

### [Caso de estudio de VENTAS_DPP](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)

![Código privado](https://img.shields.io/badge/Estado-C%C3%B3digo%20privado-334155?style=flat-square&labelColor=0C1410) `Aún no está en producción`

Tienda web y back office construidos para reemplazar una tienda alojada de un revendedor de software.

El sistema cubre la gestión del catálogo, los bundles, las ofertas con capturas de precio, las cuentas de cliente con códigos de un solo uso, la administración basada en permisos, las notificaciones, la sincronización de hojas de cálculo y las exportaciones a XLSX/PDF.

Incluye también un asistente guiado con un modo opcional respaldado por LLM, mientras la lógica de negocio de la aplicación sigue siendo independiente del modelo.

`Angular 20` `Spring Boot 3.4` `Java 17` `Spring Security` `Flyway` `MariaDB / MySQL` `Docker`

[![Leer caso de estudio](https://img.shields.io/badge/Leer-caso%20de%20estudio-C2410C?style=flat-square&labelColor=0C1410)](https://github.com/FerS00/portfolio/blob/main/projects/ventas-dpp/README.md)

---

## Trabajo adicional

### [RelayForge](https://github.com/FerS00/RelayForge)

![En pausa / desarrollo temprano](https://img.shields.io/badge/Estado-En%20pausa%20%2F%20desarrollo%20temprano-334155?style=flat-square&labelColor=0C1410) `Código público · Apache-2.0`

Consola de trabajo autoalojada para coordinar agentes de programación (Claude Code, Codex y Antigravity) en Windows.

Claude Code se encarga de la planificación, Codex implementa cambios dentro de worktrees de Git aislados, las comprobaciones declaradas verifican las suites de test y lint, y Antigravity ejecuta auditorías de solo lectura. El operador mantiene el control total, con acciones de entrega (commit/push) aprobadas por una persona. Incluye supervisión resiliente de procesos mediante Windows Job Objects, streaming SSE en tiempo real y acceso remoto seguro a través de Tailscale Serve con códigos de emparejamiento.

`Python 3.13+` `FastAPI` `React` `TypeScript` `SQLite` `Tailscale` `Windows Job Objects`

---

### [WLQuickGen](https://github.com/FerS00/WLQuickGen)

![Código disponible](https://img.shields.io/badge/Estado-C%C3%B3digo%20disponible-0E7490?style=flat-square&labelColor=0C1410) `PolyForm Noncommercial`

Utilidad Win32 portable para generar licencias de software protegido con WinLicense.

Detecta automáticamente el SDK del generador y la arquitectura disponibles, escribe los archivos de licencia de forma atómica y expone IDs de control estables para que su interfaz también pueda automatizarse con herramientas como pywinauto.

La aplicación está disponible en inglés, español y portugués.

`C++17` `Win32 API` `CMake` `GitHub Actions`

---

### [LICENSE-SERVICE](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)

![Código privado](https://img.shields.io/badge/Estado-C%C3%B3digo%20privado-334155?style=flat-square&labelColor=0C1410)

Sistema de licenciamiento sin conexión para aplicaciones de escritorio .NET.

Un empaquetador prepara un ejecutable existente, el cliente genera un código de solicitud vinculado al hardware y una estación emisora separada produce la respuesta de activación.

Las licencias usan firmas ECDSA P-256 y cifrado autenticado, mientras que el material de firma permanece aislado en la máquina emisora.

`C#` `.NET 10` `Windows Forms` `ECDSA P-256` `AES-GCM` `Docker`

[![Leer caso de estudio](https://img.shields.io/badge/Leer-caso%20de%20estudio-C2410C?style=flat-square&labelColor=0C1410)](https://github.com/FerS00/portfolio/blob/main/projects/license-service/README.md)

---

### [Hwid-Keygen-Core](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)

![Código privado](https://img.shields.io/badge/Estado-C%C3%B3digo%20privado-334155?style=flat-square&labelColor=0C1410)

Capa de activación sin conexión construida alrededor de una restricción poco habitual: el código fuente original de la aplicación no está disponible y solo puede extenderse el ejecutable protegido con WinLicense.

Un plugin nativo se ejecuta antes que la aplicación, deriva la identidad del hardware y verifica una respuesta de activación firmada con ECDSA P-256 y generada en una máquina emisora separada.

`C++17` `Win32` `Windows CNG` `CMake`

[![Leer caso de estudio](https://img.shields.io/badge/Leer-caso%20de%20estudio-C2410C?style=flat-square&labelColor=0C1410)](https://github.com/FerS00/portfolio/blob/main/projects/hwid-keygen-core/README.md)

---

### Proyectos privados

> [!NOTE]
> Parte de mi trabajo no puede publicarse porque contiene código propietario, integraciones específicas de clientes o detalles de implementación que deben mantenerse privados. Para estos proyectos publico casos de estudio técnicos que explican el problema, la arquitectura, las decisiones de diseño, el modelo de seguridad y las tecnologías, sin exponer el código fuente original.
>
> **[Ver los casos de estudio →](https://github.com/FerS00/portfolio)**

---

## Contacto

Estoy abierto a roles remotos de desarrollo de software, proyectos freelance seleccionados y colaboraciones técnicas.

- **Web** — [fextracode.com](https://fextracode.com) · Español e inglés
- **Portafolio** — [github.com/FerS00/portfolio](https://github.com/FerS00/portfolio)
- **LinkedIn** — [Fernando Morales](https://linkedin.com/in/fernando-trinidad-morales-pe%C3%B1a-3632b2391)
- **Correo** — [moralespenafernando@gmail.com](mailto:moralespenafernando@gmail.com)
- **Telegram** — [@FerS_00](https://t.me/FerS_00)
- **GitHub** — [@FerS00](https://github.com/FerS00)

Si te interesa alguno de mis proyectos privados, puedo hablar de su arquitectura, de mis responsabilidades y de las decisiones técnicas involucradas, sin exponer código fuente confidencial.

---

<div align="center">

[![Idioma actual: español](https://img.shields.io/badge/ES-Espa%C3%B1ol%20%C2%B7%20actual-15803D?style=flat-square&labelColor=0C1410)](README.es.md) [![Cambiar a inglés](https://img.shields.io/badge/EN-English-334155?style=flat-square&labelColor=0C1410)](README.md)

[Arriba ↑](#fernando-morales)

</div>
