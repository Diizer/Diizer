# Dmitry Zeleniak — Senior Full-Stack Engineer

**Go · Node.js · Angular · React · AI coding agents**

I build billing, payments and booking products end to end, and I build them with AI coding agents. I share what actually works: harness setup, agent orchestration and token economics.

**Experience:** 9+ years in software engineering  
**Domains:** telecom billing SaaS, payments, booking platforms, third-party integrations  
**Open to:** remote full-stack roles and freelance collaborations

[LinkedIn](https://www.linkedin.com/in/diizer/) · [Upwork](https://www.upwork.com/freelancers/~011dcf6c552a5453f9)

## What I do

- **Ship products end to end.** Angular and React frontends, Go and Node.js services, SQL databases, CI/CD.
- **Modernize codebases that are already in production.** Recent example: an eight-phase migration of a legacy React 16 portal to React 19, TypeScript, Redux Toolkit and Vite, including its first automated tests.
- **Integrate with everything.** 20+ integrations across accounting and PSA (Xero, ConnectWise, Autotask, HaloPSA), tax (Avalara, CereTax) and payments (Stripe, Authorize.Net, Nuvei, GoCardless).

## How I work with AI agents

I use Claude Code and Codex every day, and I treat the setup around them as engineering work of its own.

- **Context agents can actually use.** Modular project guides loaded on demand, one source shared by Claude Code, Codex and Cursor, plus scripts that fail CI when the code drifts from the documented conventions.
- **Custom subagents and guard hooks.** A subagent that keeps a live dashboard for long agent tasks, with token usage per step, and a hook that limits what that subagent can touch.
- **Fewer tokens for the same work.** Code knowledge graphs, so agents query a graph before they grep and read whole files; effort and turn limits chosen by task type.
- **Agents in parallel.** Separate branches in git worktrees, one agent per task.

I define the scope, review the output and verify behavior. Architecture, correctness and security stay my responsibility.

## What I'm working on in public

- [claude-code-live-dashboard](https://github.com/Diizer/claude-code-live-dashboard): a subagent that keeps a live dashboard for long agent tasks, and the hook that fences it in.
- Measuring token usage with and without a code knowledge graph on a real codebase.
- Learning herdr for orchestrating agent sessions, and writing down what works and what does not.

## Stack

| Area | Technologies |
| --- | --- |
| Frontend | Angular, React, Next.js, TypeScript, RxJS, Redux Toolkit, AG Grid, Tailwind CSS |
| Backend | Go, Node.js (Express, NestJS), Python (Django REST Framework), REST, OpenAPI |
| Data | PostgreSQL, Microsoft SQL Server, Redis |
| Delivery | AWS, Docker, GitHub Actions, Bitbucket Pipelines |
| Testing | Playwright, Vitest, Mocha, Cypress |
| AI engineering | Claude Code, Codex, subagents, hooks, skills, context engineering, token optimization |

## Selected repositories

- [claude-code-live-dashboard](https://github.com/Diizer/claude-code-live-dashboard) — Claude Code subagent with a live progress dashboard, token usage per step and a guard hook.
- [voice_poc](https://github.com/Diizer/voice_poc) — Python speaker-verification prototype with voice activity detection.
- [languages-cards](https://github.com/Diizer/languages-cards) — language learning flashcards built with Vue 3, TypeScript and Pinia.
- [v0-rm-autoturbo-website](https://github.com/Diizer/v0-rm-autoturbo-website) — multilingual Next.js site in four languages.

**Have a product to build or a codebase to improve?** Connect on [LinkedIn](https://www.linkedin.com/in/diizer/) or reach out through [Upwork](https://www.upwork.com/freelancers/~011dcf6c552a5453f9).

![GitHub stats](https://awesome-github-stats.azurewebsites.net/user-stats/Diizer?cardType=level-alternate&theme=tokyonight&preferLogin=false)
