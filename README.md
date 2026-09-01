# Hi, I'm Constantin Renato Irina 👋

**SAP HCM / ABAP developer** at a multinational group: payroll interfaces, custom infotypes and employee-portal integrations. I got into code through **Boolean**'s intensive full-stack bootcamp, and I never dropped the web side — I still build side projects with it.

I'm not a one-language developer: **ABAP** at work, **TypeScript** on my own projects, and **Python**, **Java** and **C / C++** as the foundation everything else sits on.

📍 Rome, Italy

---

## What I do

**At work — SAP HCM / ABAP**
- Outbound payroll interfaces for multiple countries (IT, ES, PT, FR, ZA), with error handling and automated notifications
- Custom infotypes, HR dashboards with approval/rejection logic, portal ↔ SAP-HCM flows
- Debugging and root-cause analysis on production systems
- Object-oriented ABAP: runtime type creation (RTTS), ALV with `CL_SALV_TABLE`, XLSX/CSV parsing, BCS email, background jobs

**On my own projects — web**
- Next.js + TypeScript apps on Postgres with auth and row-level security
- Offline-first and realtime sync across devices
- Automated tests as part of the work, not an afterthought

**Beyond the web — general-purpose languages**
- **Python** for scripting, automation and data wrangling
- **Java** for object-oriented work: classes, inheritance, collections, exception handling
- **C / C++** for the fundamentals that keep paying off: pointers and memory management, data structures, algorithmic complexity

---

## Stack

**Languages** — ABAP · JavaScript · TypeScript · Python · Java · C · C++ · PHP · SQL

**SAP / ERP** — ABAP OO · SAP HCM (PA / OM / Payroll) · SAP Query · Debugger · transports & ChaRM

**Web** — HTML · CSS · Vue 3 + Vite · React · Next.js · Node.js · Laravel · Bootstrap

**Databases** — MySQL · MariaDB · PostgreSQL / Supabase

**Tooling** — Git & GitHub (PR workflow) · Jira · Vercel · Notion for technical documentation

---

## Selected projects

### 🚢 Cruise Companion — offline-first trip planner
*Next.js 14 · TypeScript · Supabase · Leaflet*

A two-person planner built around a real constraint: planning a day ashore **with almost no signal**.
- Local state is the source of truth, the database follows: edits show instantly, are queued and flushed after 600 ms
- Write queue with **operation merging**: create+delete never reaches the DB, edit+edit collapses into one
- Realtime sync between devices, with pending local writes protected from overwrites
- **13 tables with row-level security**, tested for real on Postgres 16: outsiders read 0 rows
- **114 tests**, including mounting all 11 screens in both layouts
- A rule enforced by tests: *an estimate must never look like a certainty* — unknowns stay `TBC`, never invented

### 📊 Generic file comparator (ABAP)
Compares two XLSX/CSV/TXT files with **no predefined layout**: structures and internal tables built at runtime, XLSX parsed natively with `CL_ABAP_ZIP` + iXML (no OLE, no frontend Excel, no external library), differences shown in ALV.

### 🎓 Boolean bootcamp projects
Full-stack exercises in Vue, Laravel and MySQL — kept public because they show where I started.

---

## How I work

- **Reproduce first, diagnose second.** An unverified hypothesis isn't a root cause — and I say so when it stays one.
- **Document the why**, not just the what.
- **Small, reviewable changes** with explicit changelogs.
- **If a value can change, it becomes a parameter** in one place only.

---

## Find me

- 💼 [LinkedIn](https://www.linkedin.com/in/constantin-renato-irina/)

---

## 📊 GitHub Stats

<img src="./profile/stats.svg" alt="GitHub stats" height="165" />
<img src="./profile/top-langs.svg" alt="Top languages" height="165" />
