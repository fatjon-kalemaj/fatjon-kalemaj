# Fatjon (Tony) Kalemaj

Applied AI · I design Claude-based systems for private equity and hedge funds,
and I measure whether they work.

Applied AI Lead at [By The People](https://bythepeople.tech), New York.
We build AI workflows for alternative-investment firms: deal screening, diligence,
CRM, and internal operations. I spend most of my time on the part after the demo:
evals, failure modes, cost, and getting a team to trust the output.

## Featured

**[alt-invest-agent-evals](https://github.com/fatjon-kalemaj/alt-invest-agent-evals)**
A Claude agent that screens private equity deal documents, and the eval harness
that measures it. Synthetic CIMs with planted red flags and decoys, a judge
calibrated against hand labels, and paired regression checks in CI.
One finding: a tuned prompt cut a small model's false alarms from 57% to 21%
and made no difference to a large one.

<!-- Add as each repo goes public:
**commonplace** — company records into a linked local Obsidian vault
**governed-agent-pipeline** — central orchestrator, versioned agents and skills, usage and governance logs with a dashboard
**acquisition** — Claude Code plugin that maps a codebase into a knowledge graph and presents it at every level
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
