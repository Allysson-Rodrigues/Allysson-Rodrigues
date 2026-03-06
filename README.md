# Allysson Rodrigues
**Backend-focused student (learning full-stack)**

<p>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Inter&size=16&duration=3000&pause=600&color=6B7280&vCenter=true&width=700&lines=Shipping+reliable+APIs+with+clear+contracts;Auth%2C+payments%2C+observability%2C+DB+policies;Building+an+agentic+workflow+with+MCP+tools" alt="Typing SVG" />
  </a>
</p>

I’m building my backend foundations and learning end‑to‑end delivery (auth, payments, observability, database security) with an honest “learn fast, ship safely” approach.

---

## Engineering Philosophy
- Efficiency is a product of restriction: clear constraints produce better architectures.
- Prefer explicit contracts: predictable errors, stable interfaces, measurable behavior.
- Prefer repeatable workflows: boring checks should be easy, explicit, and reproducible.

---

## AI Workflow (Gemini CLI + Codex CLI + Antigravity)
I run **Gemini CLI** and **Codex CLI** in parallel for faster iteration, and use **Antigravity agents** when a task benefits from specialized roles (planning, debugging, QA, security).

I optimize for fast, safe iteration: clear API contracts, explicit validation, and observability-driven debugging.

### Tool roles (how I split work)

| Tool | Best for | Guardrails |
| --- | --- | --- |
| **Gemini CLI** | Research, quick exploration, alternative approaches, writing drafts | Treat as input; verify claims; avoid copying large chunks of external text |
| **Codex CLI** | Editing code, refactors, running checks/tests, producing focused diffs | Manual-first execution: nothing changes without an explicit command |
| **Antigravity** | Structured sessions, agent selection, repeatable workflows | Keep a single source of truth for rules; use only what the task needs |
| **MCP** | Connecting tools safely via scoped servers | No secrets; least-privilege; explicit boundaries |

### Parallel loop (typical)
1) Use Gemini CLI to explore options and constraints.
2) Use Codex CLI to implement small, reviewable changes.
3) Use an Antigravity agent for a targeted pass (QA/security/perf) when it makes sense.
4) Run explicit validation (tests/lint/build) and capture risks/tradeoffs in the final summary.

### Tooling links
- **Codex CLI** ([npm](https://www.npmjs.com/package/%40openai/codex), [overview](https://openai.com/codex/)): CLI-first workflows, code editing, local validation.
- **OpenAI Codex (Windows app)** ([release](https://openai.com/index/introducing-the-codex-app/)): desktop app for structured coding sessions and project workflows.
- **Gemini CLI** ([docs](https://developers.google.com/gemini-code-assist/docs/gemini-cli), [repo](https://github.com/google-gemini/gemini-cli)): terminal-first AI assistance for research, code iteration, and productivity tasks.
- **Google Antigravity** ([announcement](https://developers.googleblog.com/build-with-google-antigravity-our-new-agentic-development-platform/), [download](https://antigravity.google/download)): focused agent sessions, modular rules/workflows, research loops.
- **Model Context Protocol (MCP)** ([spec](https://modelcontextprotocol.io/specification/)): connect tools and systems safely via scoped servers.

---

## MCP Stack (Current)
<p>
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-MCP-3FCF8E?style=flat&logo=supabase&logoColor=white" />
  <img alt="TestSprite" src="https://img.shields.io/badge/TestSprite-MCP-6B7280?style=flat" />
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-MCP-635BFF?style=flat&logo=stripe&logoColor=white" />
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-MCP-362D59?style=flat&logo=sentry&logoColor=white" />
  <img alt="Clerk" src="https://img.shields.io/badge/Clerk-MCP-000000?style=flat&logo=clerk&logoColor=white" />
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini-MCP-4285F4?style=flat&logo=google&logoColor=white" />
</p>

What I use these for (examples):
- **Supabase**: schema + RLS patterns, local-to-prod iteration, storage.
- **TestSprite**: automated test flows, CI-friendly runs, coverage signals.
- **Stripe**: test-mode checkout flows, webhooks, payments lifecycle.
- **Sentry**: production debugging workflows (issues → events → fix plan).
- **Clerk**: quickstarts/snippets for modern auth providers and app frameworks.

---

## Technical Stack

| Category | Technologies |
| :------- | :----------- |
| **Languages & Runtime** | JavaScript (ES6+), TypeScript, Node.js |
| **Backend** | Express.js, REST APIs, Clean Architecture |
| **Databases** | MySQL, SQLite, PostgreSQL (learning) |
| **Infra** | Docker, Linux CLI, Git |

<p>
  <img alt="Docker" src="https://img.shields.io/static/v1?label=Docker&message=%20&color=2496ED&style=flat&logo=docker&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/static/v1?label=Linux&message=%20&color=FCC624&style=flat&logo=linux&logoColor=111827" />
  <img alt="Git" src="https://img.shields.io/static/v1?label=Git&message=%20&color=F05032&style=flat&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/static/v1?label=GitHub&message=%20&color=181717&style=flat&logo=github&logoColor=white" />
</p>

---

## Featured Work
- [Clean Express API (TS)](https://github.com/Allysson-Rodrigues/clean-express-api) — architecture-first API patterns (request validation, consistent error contracts).
- [Backend TS Foundations](https://github.com/Allysson-Rodrigues/backend-ts-foundations) — TypeScript + Node.js fundamentals through disciplined practice.
- [Petshop Platform (WIP)](https://github.com/Allysson-Rodrigues/petshop-small-breeds) — full-stack practice (auth, payments, observability, DB policies) as the product evolves.
- [TradingView Indicator](https://github.com/Allysson-Rodrigues/tradingview-indicator) — Pine Script automation lab.

---

## Roadmap (2026)
- Ship a full-stack MVP with auth, payments, observability, and secure DB defaults (RLS).
- Publish an API quality baseline: OpenAPI, contract tests, error model, performance budget.
- Harden delivery workflows: CI checks, reproducible local setup, release routines.

---

## Links
<p>
  <a href="https://g.dev/AllyssonRodrigues">
    <img alt="Google Dev" src="https://img.shields.io/badge/g.dev-AllyssonRodrigues-4285F4?style=flat&logo=google&logoColor=white" />
  </a>
  <a href="mailto:alissonrodriig@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-alissonrodriig%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" />
  </a>
  <a href="https://x.com/AllyssonRodriig">
    <img alt="X" src="https://img.shields.io/badge/X-@AllyssonRodriig-111827?style=flat&logo=x&logoColor=white" />
  </a>
</p>
