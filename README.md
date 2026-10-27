# Daniel Chakraborty
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
- **FormulaFix AI**  
  An AI-powered Google Sheets add-on that assists users with creating, debugging, and optimizing complex spreadsheet formulas directly inside Google Sheets via BYOK Gemini API integration.
  - *Landing & Docs:* FormulaFix AI Overview
  - *Policies:* Privacy Policy | Terms of Service
- **Sheet Data Cleaner Studio**  
  A zero-AI, deterministic spreadsheet sanitization workbench for Google Sheets.
  - *Features:* Trims erratic whitespace, normalizes text casing, batch-removes empty structures, composite deduplication, and exports clean BigQuery/Pandas schemas.

#### 🌐 Chrome Extensions & Browser Tools
- **FactLens:** Lightweight in-browser fact and entity context reader for research workflows.
- **Tabulara:** Client-side web table and tabular data extractor to instant CSV.

#### 🎨 Chrome Themes
A curated fleet of distraction-free browser themes published on the Chrome Web Store:
- **Tab Beacon Suite:** Royal Violet, Amber Gold, Acid Lime, Electric Coral, Electric Cyan.
- **Developer & Minimalist Palette:** OLED PurePitch, NordHorizon, PaperLens, Tokyo Night, Solarized Sepia, Catppuccin Mocha.

---

### 🛠️ Active Development & Pipeline

#### 📊 In-Progress Workspace Utilities
- **Sheet Table Reshaper Studio (Current Sprint):** In-memory unpivot/melt engine with multi-tier stacked header collapsing, delimited text-to-rows vertical explosion, and hierarchy unmerge/auto-fill.
- **Sheet Consolidator Studio:** Multi-tab union and stacking engine with regex sheet-name filtering (`^2026_Q[1-4]`) and schema auto-alignment.

#### 🇮🇱 Regional Tech & Productivity Suite
- **Luach Workweek & Jewish Calendar Harmonizer:** Replaces standard Mon–Fri defaults with Sunday–Thursday workweeks in Sheets and Gantt charts; features an in-memory lunisolar Hebrew calendar engine computing dynamic Chagim, Erev Chag, and Chol HaMoed with custom formulas (`=ISRAEL_WORKDAYS()`, `=IS_CHAG()`).
- **BiDi & Hebrew Punctuation Fixer:** Resolves inverted punctuation and mixed LTR/RTL numeric bugs using native Unicode directional marks.
- **Israeli Business & Statutory Validator:** Validation engine for Teudat Zehut (9-digit checksum) and Het-Peh corporate IDs, +972 phone standardization, and VAT calculations.
- **Israeli ERP & Ledger Sanitizer:** Ingestion cleaner resolving Windows-1255 encoding artifacts, trailing currency symbols (₪), and flipped RTL exports from Priority, Morning, iCount, and Hashavshevet.

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
