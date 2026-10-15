### I build AI products that hold up in production.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img alt="GitHub contributions in the last year and longest streak" src="assets/stats-light.svg" width="420">
</picture>

<a href="https://evidentlyaeo.com">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/evidentlyaeo-dark.svg">
  <img alt="EvidentlyAEO, founding engineer since 2025: answers from seven AI assistants are collected daily, scored by an LLM and stored in Postgres, then feed dashboards, a grounded content engine and a 29-tool MCP server." src="assets/evidentlyaeo-light.svg" width="100%">
</picture>
</a>

<details>
<summary><b>What I built at EvidentlyAEO</b></summary>
<br>

- **AI answer engine.** Collects answers every day from 7 AI assistants and scores each one with an LLM for brand position, sentiment and cited sources. Retries tell temporary errors apart from bad rows. Temporary errors back off with jitter, and each row has an attempt cap, so a row the model can't handle stops costing calls.
- **Job system on Postgres.** Runs 13 job types. Workers claim each run with an atomic update, so a second worker node shares the queue without double-processing. Stuck runs are detected, failed and alerted.
- **Grounded content engine.** Turns gaps against competitors in AI answers into recommendations and drafts. The writer works from an evidence pack: the AI answer being targeted, its cited sources, competitor data and the brand's documents. It logs any claim it can't support, and a revision is kept only if it scores higher without just getting longer.
- **MCP server for AI assistants.** 29 tools let customers query their data from Claude and other assistants. Every call checks the customer and their plan, and missing data comes back flagged, so the assistant reports a gap instead of inventing a number.

</details>

<a href="https://github.com/Avaya02/Relay">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/relay-dark.svg">
  <img alt="Relay, an open-source side project: the agent runs on your machine through the relayrun CLI, the server orders every event and holds the driver lock, and every viewer sees the same sequence while control passes mid-task." src="assets/relay-light.svg" width="100%">
</picture>
</a>
