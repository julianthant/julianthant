## Hi, I'm Julian (Hein Thant Zaw)

I'm a computer science student at UC San Diego (expected June 2028). I build backend systems that replace manual work with reliable automation, and lately I've been building AI agents and quant research tools. I'm looking for Summer 2027 internships in software engineering, AI agents, and quant.

## What I'm building

- **[HR-Relay](https://github.com/julianthant/hr-relay)**: Built an automation tool in TypeScript and Hono, using Playwright to sign into UCPath, CRM and I-9 through Duo to run employee onboardings, separations and lookups, tracked on a live React dashboard. Guarded against duplicate HR records by pausing for a person when a submission's outcome is unclear, alongside a SQLite queue that survives restarts, dry-run previews, change receipts and about 700 Vitest tests. *TypeScript, Hono, SQLite, React, Playwright, Vitest*
- **Tether** (in progress): a Python harness, planned with LangGraph and LangChain, that will let an AI coding agent work for hours without free rein over the machine, and will save progress to SQLite so a killed run can resume. Planner, coder, tester and reviewer agents will send failing tests and review notes back to the coder, while MCP tools keep file access inside one folder, run only approved commands and log each request. *Python, LangGraph, LangChain, FastMCP, SQLite*
- **Driftwood** (in progress): planned as a Python research pipeline for US stocks that will keep daily market data in DuckDB and train linear and LightGBM models on momentum and volatility signals, tested on later periods it never saw. A C++ simulator called from Python via pybind11 aims to estimate fees and slippage for TWAP, VWAP and immediate orders, and an AI agent will draft research ideas a human approves before Alpaca paper trading. *Python, C++17, pybind11, DuckDB, LightGBM*

## Experience

**University of California, San Diego** · Student Assistant, Human Resources · Oct 2025 – Present
- Found onboarding, separations, and employee lookups done by hand and, outside the student assistant role, independently proposed and built an internal automation platform for UCPath, I-9, CRM, and EDMS.
- Led onboarding for 200+ employees per quarter and automated account provisioning, validation checks, system access setup, and document routing, cutting hours of coordination per hiring cycle.
- Migrated 1000+ department's paper records into EDMS with standardized naming conventions and automation-assisted document handling, reducing record lookup from a manual search to a keyword query.

**Santa Monica College (Emeritus)** · Student Assistant, Insurance Claims · Dec 2024 – Aug 2025
- Built Scribe, a shared, timestamped log any teammate could pick up, after handwritten voicemail notes left no trace of who worked a claim or where they stopped, saving 10+ hours a week.
- Wrote Scribe in Python and FastAPI to pull claim voicemails from an Outlook mailbox through Microsoft Graph with OAuth client credentials, transcribe them with Azure Speech-to-Text, and log each call to a shared tracker.
- Administered the Supplemental Job Displacement Benefits program for 300+ active claims and $100K+ in benefits, handling invoices and adjuster communication, and resolved 100+ weekly inquiries at 90% first-contact resolution.

**KBZ Bank** · Software & Technology Intern · Yangon, Myanmar · May 2023 – Aug 2023
- Wrote SQL queries joining transaction and account tables, using aggregations and date-range filtering to produce summary reports of customer activity for internal reporting.
- Wrote JUnit unit tests for a Java/Spring Boot service class and REST endpoint, covering business logic and request handling in a system processing live financial data.
- Implemented Burmese/English localization in the web frontend by externalizing UI text into translation resource files and adding a language switcher, so the interface could be used in either language.

## Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [HR-Relay](https://github.com/julianthant/hr-relay) | Automation tool that signs into UCPath, CRM and I-9 through Duo to run employee onboardings, separations and lookups, tracked on a live React dashboard | TypeScript, Hono, SQLite, React, Playwright, Vitest |
| Tether (in progress) | Harness that lets an AI coding agent work for hours with file access kept inside one folder, approved commands only, and resumable progress | Python, LangGraph, LangChain, FastMCP, SQLite |
| Driftwood (in progress) | US-stock research pipeline with LightGBM models tested on unseen periods and a C++ fee and slippage simulator for TWAP, VWAP and immediate orders | Python, C++17, pybind11, DuckDB, LightGBM |
| Scribe | Pulls claim voicemails from Outlook through Microsoft Graph, transcribes them with Azure Speech-to-Text, and logs each call to a shared tracker | Python, FastAPI, Microsoft Graph, Azure |
| [fast-duo](https://github.com/julianthant/fast-duo) | Manifest V3 Chrome extension for local Duo authentication with guided WebAuthn enrollment | JavaScript, Chrome MV3, WebAuthn |

## Education

- **University of California, San Diego**: B.S. Computer Science, expected June 2028
- **Santa Monica College**: A.S. Computer Science, August 2025, GPA 3.6

## Skills

- **Languages:** C++, Python, JavaScript/TypeScript, SQL, Java, Go, Swift
- **Developer tools:** Docker, Git, SQLite, Azure, Microsoft Graph, AWS, CI/CD, Claude Code, Jira, Ollama, Codex, Cursor
- **Libraries/frameworks:** React, Next.js, Redis, FastAPI, Hono, Vitest, LangChain, crawl4ai, BeautifulSoup, Playwright

## Contact

[Portfolio](https://www.julianzaw.me) · [LinkedIn](https://www.linkedin.com/in/heinthantzaw/) · [Resume](https://drive.google.com/file/d/14CpukL1E7_-0GyN6aVu-hXnOHizB1uXO/view?usp=sharing) · julianthant@gmail.com
