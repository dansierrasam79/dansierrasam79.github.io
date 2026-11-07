# Daniel Chakraborty

[![Google Developer Profile](https://img.shields.io/badge/Google_Developer-danielchakraborty-4285F4?logo=google&logoColor=white)](https://g.dev/danielchakraborty)

### Developer Hub & Portfolio

Welcome to my personal developer portal and open-source landing hub. This repository hosts documentation, user policies, and support resources for my software utilities, Chrome extensions, themes, and Google Workspace add-ons.

🌐 **Domain:** danielchakraborty.com | **GitHub Pages:** dansierrasam79.github.io
---

### 🏛️ Architecture & Design Philosophy
Every utility in this portfolio is engineered around strict, privacy-first principles:
- **100% Deterministic & In-Memory:** Client-side processing with zero third-party telemetry, remote databases, or background servers.
- **Least-Privilege Scopes:** Minimal OAuth boundaries (e.g., `spreadsheets.currentonly`, `script.container.ui`, Chrome Manifest V3) ensuring user data never leaves the local session.
- **Zero-Maintenance Footprint:** Self-contained runtimes with no recurring external API overhead (outside optional user BYOK).
- **Core Ethos & Dedication:** Built on principles of integrity, transparency, and humble service—founded in memory of my late father, an ordained pastor, whose lifelong counsel remains: *"If you have tried everything else and failed, try Jesus."*

---

### 🚀 Active & Published Fleet

#### 🧩 Google Workspace Add-ons
- **FormulaFix AI:** An AI-powered Google Sheets add-on that assists users with creating, debugging, and optimizing complex spreadsheet formulas directly inside Google Sheets via BYOK Gemini API integration.
- **Sheet Data Cleaner Studio:** A zero-AI, deterministic spreadsheet sanitization workbench for Google Sheets.
- **Sheet Table Reshaper Studio:** In-memory unpivot/melt engine with multi-tier stacked header collapsing, delimited text-to-rows vertical explosion, and hierarchy unmerge/auto-fill.
- **Sheet Consolidator Studio:** Multi-tab union and stacking engine with regex sheet-name filtering (`^2026_Q[1-4]`) and schema auto-alignment.

#### 🌐 Chrome Extensions & Browser Tools
- **FactLens:** Lightweight in-browser fact and entity context reader for research workflows.
- **Tabulara:** Client-side web table and tabular data extractor to instant CSV.
- **CleanMark:** A zero-telemetry, client-side webpage-to-Markdown extractor for Chromium and Edge.

#### 🎨 Chrome Themes
A curated fleet of distraction-free browser themes published on the Chrome Web Store:
- **Tab Beacon Suite:** Royal Violet, Amber Gold, Acid Lime, Electric Coral, Electric Cyan.
- **Developer & Minimalist Palette:** OLED PurePitch, NordHorizon, PaperLens, Tokyo Night, Solarized Sepia, Catppuccin Mocha.
- **Biblical Themes:** Byzantine Gold, Codex Vellum, Mount Sinai Dawn & Gethsemane Olive.

---

### 🛠️ Active Development & Pipeline

#### 📊 In-Progress Workspace Utilities
- **Luach Workweek & Jewish Calendar Harmonizer:** Replaces standard Mon–Fri defaults with Sunday–Thursday workweeks in Sheets and Gantt charts; features an in-memory lunisolar Hebrew calendar engine computing dynamic Chagim, Erev Chag, and Chol HaMoed with custom formulas (`=ISRAEL_WORKDAYS()`, `=IS_CHAG()`).
- **SheetDiff & Reconciliation Studio:** Replaces brittle lookup formulas with a deterministic, in-memory two-sheet diffing and reconciliation engine in Google Sheets; features composite key entity matching, cell-level delta and numeric variance tracking, non-destructive visual audit overlays, and automated report tab generation with zero external APIs or third-party telemetry.
- **ChoiceEliminator Studio:** Enforces real-time choice quotas on Multiple Choice, Dropdown, and Checkbox items in Google Forms; features an in-memory concurrency engine using LockService serialization and DocumentProperties snapshots to dynamically eliminate or annotate exhausted slots ([FULL]) with deterministic zero-server execution.
---

### 💻 Tech Stack & System Architecture

#### 🛡️ Deterministic Core (Production Utilities)
Zero-server, in-memory execution engine prioritizing data privacy, low permissions, and predictable performance.
- **Runtimes & Scripting:** JavaScript (ES6+), TypeScript, Google Apps Script (V8 runtime), HTML5 / Modern CSS
- **Platform APIs:** Chrome Extensions API (Manifest V3), Google Workspace Add-ons SDK, Google Sheets API
- **Algorithms & Processing:** In-memory tabular parsing, regex streaming engines, lunisolar calendar mathematics, and Unicode BiDi directional text algorithms
- **Local Dev & Delivery:** Visual Studio Code, PowerShell, Git, GitHub Actions, GitHub Pages

#### 🧠 AI & Experimental Systems
Agentic frameworks, API integrations, and prototype pipelines.
- **AI Runtimes & APIs:** Google Gemini API (BYOK integration in FormulaFix AI)
- **Agent Orchestration:** LangGraph, LLM agent scaffolding, and graph-based workflow patterns
- **Data & Exploration:** Python (prototyping, data modeling, Pandas/BigQuery schema generation)
- **Edge & Mobile Concepts:** Android ML Kit, Room database (SnapToTask prototype)
---

### 📬 Support & Contact
If you have questions, feedback, or require technical support for any of the hosted tools or add-ons:
- **Email:** swapan.eseva.kendra@gmail.com
- **GitHub:** @dansierrasam79
- **Website:** danielchakraborty.com
---
© 2026 Daniel Chakraborty. All rights reserved.

*Dedicated in loving memory to my late father, Rev. Swapan Chakraborty, who believed: "If you have tried everything else and failed, try Jesus."*
