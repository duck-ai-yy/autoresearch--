# Current State

**Last updated**: 2026-05-18 (Session 1, late)
**Branch**: `claude/academic-accelerator-agent-V4ySi`

## Current stage

**Stage 2 — Deep Read + Framing Convergence (in progress).**

## Last completed actions

- Stage 0: topic scoping → `TOPIC.md`.
- Stage 1: divergent collection across 6 lenses → `stage1-divergent.md`.
- Scaffolding committed → `README.md`, `AGENT.md`, `TOPIC.md`, `STATE.md`, `decisions.md`.
- **Stage 2.a: Pedreschi et al. (2025) boundary map** → `lenses/06-niche-construction.md`.
  - Full-text was blocked (HTTP 403 on all known URLs); map assembled from indexed search snippets, flagged for verification.
  - Verdict: Pedreschi's scope (recommenders × consumers × societal) does NOT overlap our topic (workflow agents × domain experts × cognitive collaboration). Their paper legitimizes the "coevolution" terminology without occupying our cell.
  - Framing paths B (theory-driven niche construction) and C (hybrid) are now de-blocked.

## Next action (queued)

**Stage 2.b — three parallel sub-tasks, then framing recommendation to user.**

1. **Round-2 search on lens 5** (activity theory × enterprise AI agents). Stage 1 found this near-empty; confirm whether truly a gap or whether queries were just too narrow.
2. **Round-2 search on lens 6 foundations** (niche construction theory × technology — Odling-Smee, Brian Arthur, Ackermann). Build theoretical backbone for potential path B.
3. **Boundary maps for the remaining 3 anchor papers** — Brynjolfsson (QJE), Dell'Acqua (Org Sci), Dillon (arxiv). Spawn one sub-agent per paper using the same boundary-map template as `lenses/06-niche-construction.md`.

4. **NEW candidate flagged during 2.a**: "From Expert Systems to Generative Artificial Experts" (JAIR) — directly adjacent to our cell, may be the closer competitor than Pedreschi. Add to anchor papers and produce boundary map.

After 2.b: present user with evidence-backed recommendation between framing paths B and C (A is now de-prioritized).

## Blocked on user

- **O2 (domain anchor)** — still open. Becomes blocking before domain-specific search round.
- **O1 (framing path)** — converging toward B or C; final decision waits on Stage 2.b results.

## Notes for next session

- Pedreschi boundary map is based on snippets, not full text. If full text becomes accessible, re-verify section 4 (theoretical framework) and section 8 (coverage table) — these are the highest-stakes claims.
- New anchor paper to read: JAIR "Generative Artificial Experts" — likely closer to our topic than Pedreschi.
- `lenses/` subdirectory exists now; per-lens boundary maps go there with naming `NN-<lens-slug>.md`.
- Stage 2.b can be parallelized — spawn multiple sub-agents in a single message.
