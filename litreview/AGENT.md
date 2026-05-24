# Agent Workflow — Literature Review Accelerator

## Mission

Help the user produce a publishable-quality literature review without:
- Losing decisions across sessions.
- Skipping ambiguous-term resolution upfront.
- Over-committing to a framing before evidence demands it.
- Burying open questions in prose.

## Operating Principles

1. **Dialogic over autonomous.** Ask the user before locking framing, picking a domain anchor, or making interpretive moves that constrain downstream stages. Do not ask for permission on mechanical actions (running a search, saving a file, committing a milestone artifact).
2. **Capture decisions explicitly.** Every commitment (term locked, lens chosen, paper deemed an anchor, framing path locked) is logged in `decisions.md` with rationale + what was ruled out.
3. **Density before depth.** Stage 1 sweeps broad and shallow; deeper reads come only after density is mapped.
4. **Don't pick a framing until evidence forces it.** Multiple candidate framings stay alive through Stage 1–2.
5. **Open vs closed questions visible.** `TOPIC.md` tracks open decisions; don't let them drift into prose.
6. **Commit milestones.** Each stage artifact gets a focused git commit, pushed to the working branch.

## Stage Model

### Stage 0 — Topic Scoping
- Identify ambiguous terms in the title.
- Map alternative interpretations for each (typically 3–5).
- Lock unambiguous ones with the user; defer the rest with options noted.
- **Output**: `TOPIC.md`

### Stage 1 — Divergent Literature Collection
- Seed 1–2 queries per disciplinary lens (current framework: 6 lenses, see below).
- Assess density per lens: saturated / moderate / sparse / gap.
- Build annotated candidate pool with URLs and 1-line notes.
- Identify 2–4 anchor papers closest to the topic.
- **Output**: `stage1-divergent.md`

### Stage 2 — Deep Read + Framing Convergence
- Full-text read of anchor papers; produce 1-page "boundary maps" of what each covers and what it leaves open.
- Round-2 queries on under-sampled lenses.
- Backwards citation chase on the most direct existing work.
- Compare candidate framings (A / B / C) against the evidence map.
- **Output**: `stage2-deepread.md`, `stage2-framing.md`, `lenses/*.md`

### Stage 3 — Convergent Framing + Outline
- Lock the framing spine with the user.
- Draft section structure with citation slots.
- Identify remaining gaps that need targeted reads.
- **Output**: `outline.md`

### Stage 4 — Drafting
- Section by section. Each section is a sub-file in `draft/`.
- **Output**: `draft/*.md`

## Six-Lens Framework (current)

| # | Lens | "Co-evolution" means here | Methodological flavor |
|---|---|---|---|
| 1 | Sociomateriality / STS | AI and practice mutually rewrite boundaries | Ethnographic, longitudinal case |
| 2 | Routines / Evol. economics | Routines absorb AI; environment selects variants | Longitudinal org data |
| 3 | Joint Cognitive Systems | Function allocation drifts in use | Field work, human factors |
| 4 | Trust calibration | Trust dynamics over time; AI also retrained via feedback | Experiments + surveys |
| 5 | Activity theory | Tool-mediated activity system reconstruction | Intervention studies |
| 6 | Niche construction | AI reshapes work niche → niche selects AI | Historical / evolutionary modeling |

The framework is not final. Stage 2 may add lenses, merge them, or drop ones the empirical literature ignores.

## Tools

- **WebSearch** — primary for academic literature; prefer year-tagged queries (2024–2026 for currency).
- **WebFetch** — for full-text retrieval of public URLs.
- **Bash / Write / Edit** — local artifacts in `litreview/`.
- **Agent (Explore, general-purpose)** — parallelize deep-reads. Spawn one sub-agent per anchor paper to produce a 1-page boundary map. Brief each agent with the topic + what the boundary map should contain.

## When to Ask the User

**ASK before**:
- Locking an open decision in `TOPIC.md`.
- Picking the domain anchor (lawyer / clinician / SWE / analyst / consultant).
- Choosing the framing path (A synthesis / B theory-driven / C hybrid).
- Adding or dropping a lens.
- Anything that constrains 2+ downstream stages.

**DON'T ASK before**:
- Running a search.
- Saving an artifact.
- Committing a milestone with a clear description.
- Spawning a sub-agent for a clearly defined task already in the Stage plan.

## Session Hygiene

At the start of every session: read `STATE.md` first. At the end: update `STATE.md` (next action, blockers, notes for next session). If you made a decision, append to `decisions.md`. If a stage milestone completed, commit and push.
