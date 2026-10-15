<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Avaya Sharma. I build production backends and the AI layer on top of them. Software engineer at Eastern Software Solutions from October 2024, founding engineer at EvidentlyAEO from October 2025, now open to new roles. Based in Delhi, India." src="assets/header-light.svg" width="100%">
</picture>

<br><br>

<a href="https://evidentlyaeo.com">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/evidentlyaeo-dark.svg">
  <img alt="EvidentlyAEO, where I was founding engineer from 2025 to 2026: daily collection of answers from ChatGPT, Google AI Overviews, Perplexity, Claude, Gemini, Copilot and Grok, LLM scoring, Postgres, then dashboards, an MCP server with 29 tools, and agency white-label." src="assets/evidentlyaeo-light.svg" width="100%">
</picture>
</a>

What I built as founding engineer. The code is private, so this is the shape of it:

- **Job system on Postgres.** Workers claim runs with an atomic update, so a second worker node shares the queue without double-processing. Stuck runs are detected, failed and alerted.
- **MCP server.** OAuth and API-key access, a tenant check on every call, and responses that flag missing data so assistants report gaps instead of inventing metrics.
- **Agency multi-tenancy.** Pooled quotas enforced in Postgres triggers under per-agency advisory locks.
- **Billing.** Stripe checkout and plan entitlements, with idempotent webhooks so a redelivery never provisions twice.

<br>

<a href="https://github.com/Avaya02/Relay">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/relay-dark.svg">
  <img alt="Relay, open source: the agent runs on your machine through the relayrun CLI, the server orders every event and holds the driver lock, and every browser sees the same sequence while control passes mid-task." src="assets/relay-light.svg" width="100%">
</picture>
</a>

[Source](https://github.com/Avaya02/Relay) · [relayrun.in](https://relayrun.in) · [`relayrun` on npm](https://www.npmjs.com/package/relayrun)

<br>

**Stack:** TypeScript, Node.js, React, Next.js, PostgreSQL, Prisma, Claude Agent SDK, MCP

[avayasharma.com](https://avayasharma.com) · [X](https://x.com/Avaya_002) · [LinkedIn](https://linkedin.com/in/avayasharma)
