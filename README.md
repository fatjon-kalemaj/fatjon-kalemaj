# Fatjon (Tony) Kalemaj

Applied AI | I design Claude-based systems for private equity and hedge funds,
and I measure whether they work.

Applied AI Lead at [By The People](https://bythepeople.tech), New York.
We build AI workflows for alternative-investment firms: deal screening, diligence,
CRM, and internal operations. I spend most of my time on the part after the demo:
evals, failure modes, cost, and getting a team to trust the output.

## Featured

Four repos, one theme: AI systems a company can measure, govern and trust.

**[alt-invest-agent-evals](https://github.com/fatjon-kalemaj/alt-invest-agent-evals)** · *measure*
A Claude agent that screens private equity deal documents, and the eval harness
that measures it: planted red flags and decoys, a judge calibrated against hand
labels, paired regression checks in CI. One finding: a tuned prompt cut a small
model's false alarms from 57% to 21% and made no difference to a large one.

**[gatehouse](https://github.com/fatjon-kalemaj/gatehouse)** · *govern*
One governed door to a private repo of Claude agents. Employees reach a single
orchestrator. It runs versioned agents step by step and checks each report
before the next step. Every run lands in an append-only, hash-chained ledger
with a monitoring dashboard.

**[fieldtrial](https://github.com/fatjon-kalemaj/fieldtrial)** · *operate*
Outreach run as controlled experiments, packaged as a Claude Code plugin. One
hypothesis per cycle, randomized angles, winners declared only when the
statistics support it, and a human approval at every step. It never sends
anything itself.

**[accretion](https://github.com/fatjon-kalemaj/accretion)** · *understand*
A Claude Code plugin that maps a codebase into a knowledge graph with Graphify
and presents it at four levels: executive overview, service map, scenario
walkthrough and code.

<!-- Add when public:
**commonplace** · *remember* — company records into a linked local Obsidian vault
-->

## How I work

- Start with the simplest thing that works: one model call before a workflow, a workflow before an agent.
- Write the eval before arguing about the prompt.
- Separate what the model got wrong from what the plumbing got wrong.
- Keep client data out of the model's reach unless it needs it.

## Stack

Claude API · Claude Code (skills, subagents, hooks, plugins) · MCP ·
Python · TypeScript · Next.js · Postgres · Vercel

## Elsewhere

[LinkedIn](https://linkedin.com/in/fatjonkalemaj) · writing on AI and work at Human Element
