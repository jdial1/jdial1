# Justin Dial (@jdial1)

**Full-Stack Software Engineer & Database Architect**  
 🔗 [github.com/jdial1](https://github.com/jdial1)

---

## 💡 About Me

Software Engineer with a focus on **Laboratory Information Systems (LIS)**, **healthcare data integration**, and **high-performance relational database architectures**. My professional work centers on building reliable clinical data pipelines, optimizing SQL queries for sub-millisecond execution, and automating laboratory hardware workflows.

Outside of healthcare systems, I build real-time multiplayer applications and simulation games using modern **TypeScript**, **Node.js**, and **WebSockets**.

---

## 🛠️ Skills & Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Current Focus** | LIS Automation, HL7 Mirth Connect Channels, Database Change Control (Liquibase) |
| **Core Languages** | JavaScript (ES6+), TypeScript, Python, SQL, Bash |
| **Infrastructure & DB** | Node.js, Socket.IO, DB2 / SQL Relational Databases, Linux (Arch / OpenWrt) |

---

## ⚡ Key Technical Domains & Impact

### 🏥 1. Healthcare IT & Laboratory Automation (MAWDDev)
Core contributor to clinical laboratory diagnostic pipelines and automated reporting suites for MAWD Pathology Group:

* **Database & Schema Management:** Long-term maintainer of clinical database migrations via `MAWDDev/mawd_lis_db_liquibase` and order management APIs (`mawd-api`). Implemented accession order lock logging (`accession_order_lock_log`) and specimen-container relational mappings.
* **Mirth Connect HL7 Routing:** Maintained and upgraded clinical messaging engines in `MAWDDev/mirth-change-control` and `dspencer-kc/MirthChannels`, including COM port discovery and node-local routing logic.
* **Lab Hardware Integration:** Engineered real-time WebSocket communication between server backends and laboratory barcode/slide-tracking hardware in `dspencer-kc/MAWDSlideTracker`.
* **Python Automation Suite:** Built and maintained daemon utilities for lab operations, including `pyAutoReport`, `pyPDFsplit`, `pyPDFscan`, `pyFolderWatcher`, and `pyFax`.

### 🚀 2. Performance Engineering & Optimization
* **LIS Query Latency:** Refactored slide distribution and specimen select queries in production LIS tables, reducing average fetch time from **3.0s down to 15ms** — a **99.5% latency reduction**.
* **API Optimization:** Rebuilt production diagnostic queries in `mawd-api` to reduce function complexity and cut execution time from **700ms down to 140ms**.
* **Client-Side Bottlenecks:** Eliminated UI freezing during rapid laboratory slide scanning by decoupling excessive data table re-fetches (`loadTableData()`) from hardware input events.

---

## 📂 Featured Repositories & Engineering Projects

| Repository | Tech Stack | Description & Architecture |
| :--- | :--- | :--- |
| **[jdial1/LAP](https://github.com/jdial1/LAP)** | JavaScript, Node.js, Socket.IO | Real-time multiplayer web adaptation of a tabletop deduction puzzle. Implements an event-driven client-server architecture (`SEND_GUESS` $\rightarrow$ `SERVER_GUESS_RESPONSE`) over persistent WebSockets. |
| **[jdial1/reactor-knockoff-2](https://github.com/jdial1/reactor-knockoff-2)** | JavaScript, PWA, HTML5/CSS | Complex management simulation game. Features a custom UI vulnerability hardening pass addressing stored/reflected XSS vectors in user-controlled dynamic interpolation. |
| **[jdial1/infiniteRTS](https://github.com/jdial1/infiniteRTS)** | TypeScript | Real-time strategy simulation experiment focusing on algorithmic resource generation, map entity scaling, and game-loop optimization. |
| **[jdial1/openwrt-linksys-ea7500v2-bin](https://github.com/jdial1/openwrt-linksys-ea7500v2-bin)** | C, Shell, Embedded Linux | Custom OpenWrt firmware builds and configuration for Linksys EA7500v2 networking hardware. |

---

## 🤝 Open-Source Contributions & Community

* **[commaai/connect](https://github.com/commaai/connect):** Logged telemetry UI regressions for Openpilot autonomous vehicle overlay mapping.
* **[LukeSmithxyz/LARBS](https://github.com/LukeSmithxyz/LARBS):** Debugged Arch Linux AUR helper installer execution failures on clean boot environments.
* **[dbeaver/dbeaver](https://github.com/dbeaver/dbeaver):** Active tester and bug reporter for SQL editor parsing behavior on DB2/SQL query syntaxes.
