# Literature Review — Academic Accelerator Workflow

A staged, dialogic workflow for producing a literature review without losing decisions or context across sessions.

> **New Claude session?** Read this file → then [`STATE.md`](STATE.md) → then [`AGENT.md`](AGENT.md). Do not restart from scratch; resume from `STATE.md`'s "Next action (queued)".
>
> This branch (`claude/academic-accelerator-agent-V4ySi`) repurposes the autoresearch repo as a literature-review acceleration agent. The original ML training files (`program.md`, `train.py`, `prepare.py`) are untouched — leave them alone on this branch.

## Topic

**The Co-evolution of AI Agents and Domain Experts in Enterprise Work** — see [`TOPIC.md`](TOPIC.md) for the full title, locked definitions, and open decisions.

## Files

| File | Purpose | Update frequency |
|---|---|---|
| `README.md` | This file. Entry point. | Rare. |
| `AGENT.md` | Methodology: stages, principles, lens framework, tools. | When workflow changes. |
| `TOPIC.md` | Topic spec — locked + open decisions for every ambiguous term. | When a decision is made or revisited. |
| `STATE.md` | Live state: current stage, last action, next action, blockers. | **Every session.** |
| `decisions.md` | Append-only decision log. | When a decision is made. |
| `stage1-divergent.md` | Stage 1 artifact: 6-lens divergent collection + density map. | Frozen. |
| `lenses/` *(not yet created)* | Stage 2+ per-lens deep notes. | Stage 2. |
| `draft/` *(not yet created)* | Stage 4 section drafts. | Stage 4. |

## How to resume next session

1. Open [`STATE.md`](STATE.md) — see current stage and next action.
2. Open [`TOPIC.md`](TOPIC.md) — refresh on locked / open decisions.
3. Skim [`AGENT.md`](AGENT.md) for the current stage's expected workflow.
4. Execute the next action — **OR** ask the user about an open decision if it blocks progress.

## Two rules that matter most

- **Don't lock framing before evidence demands it.** Multiple framings (A / B / C in `TOPIC.md`) stay alive through Stage 1–2.
- **Stay dialogic.** Even though scaffolding exists, ask the user before locking decisions, picking domain, or making interpretive moves that constrain downstream stages.
