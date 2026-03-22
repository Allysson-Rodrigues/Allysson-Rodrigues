# Allysson Rodrigues
**Backend-first builder exploring full-stack delivery**

<p>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Inter&size=16&duration=3000&pause=600&color=6B7280&vCenter=true&width=760&lines=Reliable+APIs+with+explicit+contracts;Auth%2C+observability%2C+deployment%2C+DB+policies;AI-assisted+workflows+with+Codex%2C+Gemini%2C+and+MCP" alt="Typing SVG" />
  </a>
</p>

I build my backend foundations in public and treat delivery as a system: clear contracts, safe defaults, reproducible workflows, and pragmatic automation. My current focus is Node.js, TypeScript, API architecture, and AI-assisted developer tooling.

---

## Engineering Philosophy
- Constraints improve design. Clear boundaries usually produce better systems.
- Explicit contracts beat implicit behavior. Errors, interfaces, and validation should be predictable.
- Reliable delivery depends on repeatable workflows. Checks should be easy to run and hard to skip.

---

## AI Workflow
I use AI tools as part of a disciplined engineering loop, not as a replacement for verification. The goal is faster iteration with explicit validation, focused diffs, and lower operational risk.

### Tool roles

| Tool | Best for | Guardrails |
| --- | --- | --- |
| **Gemini CLI** | Research, exploration, alternative approaches, first-pass drafts | Treat outputs as input, verify claims, avoid copy-paste from external sources |
| **Codex CLI** | Code changes, refactors, local checks, focused implementation | Manual-first workflow, explicit commands, small reviewable diffs |
| **Antigravity** | Structured sessions, scoped agents, targeted task decomposition | Keep a single source of truth, use only what the task needs |
| **MCP** | Safe connections between tools, services, and project context | Least privilege, explicit boundaries, no unnecessary secret exposure |

### Typical loop
1. Explore the problem space with Gemini CLI.
2. Implement and validate with Codex CLI.
3. Use Antigravity when a task benefits from a specialized pass such as QA, debugging, or security review.
4. Close with explicit checks and a concrete summary of tradeoffs or remaining risks.

### Tooling links
- **Codex CLI** ([npm](https://www.npmjs.com/package/%40openai/codex), [overview](https://openai.com/codex/)) - local coding workflows, focused edits, and validation loops.
- **OpenAI Codex app** ([release](https://openai.com/index/introducing-the-codex-app/)) - structured coding sessions and project-oriented workflows.
- **Gemini CLI** ([docs](https://developers.google.com/gemini-code-assist/docs/gemini-cli), [repo](https://github.com/google-gemini/gemini-cli)) - terminal-first assistance for research, code iteration, and productivity.
- **Google Antigravity** ([announcement](https://developers.googleblog.com/build-with-google-antigravity-our-new-agentic-development-platform/), [download](https://antigravity.google/download)) - modular agent workflows and scoped sessions.
- **Model Context Protocol (MCP)** ([spec](https://modelcontextprotocol.io/specification/)) - safe, scoped tool connectivity across systems.

---

## MCP Stack
<p>
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-MCP-3FCF8E?style=flat&logo=supabase&logoColor=white" />
  <img alt="TestSprite" src="https://img.shields.io/badge/TestSprite-MCP-6B7280?style=flat" />
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-MCP-635BFF?style=flat&logo=stripe&logoColor=white" />
  <img alt="Sentry" src="https://img.shields.io/badge/Sentry-MCP-362D59?style=flat&logo=sentry&logoColor=white" />
  <img alt="Clerk" src="https://img.shields.io/badge/Clerk-MCP-000000?style=flat&logo=clerk&logoColor=white" />
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini-MCP-4285F4?style=flat&logo=google&logoColor=white" />
</p>

What I use these for:
- **Supabase** - schema iteration, RLS patterns, storage workflows, and local-to-prod feedback loops.
- **TestSprite** - automated test flows, CI-friendly validation, and coverage signals.
- **Stripe** - payment lifecycle experiments, webhooks, and test-mode checkout flows.
- **Sentry** - production debugging loops from issue to event to fix plan.
- **Clerk** - auth quickstarts and modern identity patterns across app frameworks.

---

## Technical Stack

| Category | Technologies |
| :------- | :----------- |
| **Languages & Runtime** | JavaScript (ES6+), TypeScript, Node.js |
| **Frontend** | React, Next.js, Tailwind CSS, shadcn/ui |
| **Backend** | Express.js, REST APIs, Clean Architecture |
| **Databases** | SQLite, PostgreSQL, Prisma |
| **Infra & Delivery** | Docker, Linux CLI, Git, GitHub, Vercel |

<p>
  <img alt="Docker" src="https://img.shields.io/static/v1?label=Docker&message=%20&color=2496ED&style=flat&logo=docker&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/static/v1?label=Linux&message=%20&color=FCC624&style=flat&logo=linux&logoColor=111827" />
  <img alt="Git" src="https://img.shields.io/static/v1?label=Git&message=%20&color=F05032&style=flat&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/static/v1?label=GitHub&message=%20&color=181717&style=flat&logo=github&logoColor=white" />
  <img alt="Vercel" src="https://img.shields.io/static/v1?label=Vercel&message=%20&color=000000&style=flat&logo=vercel&logoColor=white" />
</p>

---

## Featured Work
- [Petshop Small Breeds Premium](https://github.com/Allysson-Rodrigues/petshop-small-breeds-premium) - full-stack practice with admin dashboard, auth flows, booking requests, and Vercel deployment.
- [Voice Note AI](https://github.com/Allysson-Rodrigues/voice-note-ai) - Windows-first dictation app with Azure Speech-to-Text, safe text injection, and adaptive suggestions.
- [Clean Express API](https://github.com/Allysson-Rodrigues/clean-express-api) - architecture-first API patterns with validation, consistent errors, and TypeScript-first structure.
- [Backend TS Foundations](https://github.com/Allysson-Rodrigues/backend-ts-foundations) - disciplined Node.js and TypeScript practice with a focus on consistency and delivery basics.
- [TradingView Indicator](https://github.com/Allysson-Rodrigues/tradingview-indicator) - Pine Script experiments for structured technical analysis and trading automation.

---

## Roadmap (2026)
- Ship stronger end-to-end projects with auth, observability, deployment discipline, and secure backend defaults.
- Publish better API baselines with contract clarity, validation, and operational guardrails.
- Keep improving AI-assisted workflows without relaxing verification quality.

---


## Workspace Snapshot

A live view of my current local workspace architecture, optimized for agentic development:

```text
projetos/
├── 01-projetos/        # Active projects (frontend & backend apps)
├── 02-pacotes/         # Shared packages (e.g., UI kits, libraries)
├── 03-playground/      # Sandboxes and experiments
├── 04-docs/            # Auxiliary or legacy material
├── 05-arquivo/         # Historical, paused, and temporary material
├── 06-scripts/         # Workspace automation and CLI tooling
├── 07-github/          # Local mirror of external repositories
├── 08-operacional/     # Backups, artifacts, and operational logs
├── docs/               # Canonical documentation hub
├── tests/              # End-to-end and governance testing
├── tasks/              # Active sprint, lessons, and progress tracking
├── .agent/             # Antigravity/Gemini CLI agent rules and workflows
└── mcp-servers/        # Local Model Context Protocol servers
```

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
