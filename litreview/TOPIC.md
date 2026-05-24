# Topic Specification

## Title

**The Co-evolution of AI Agents and Domain Experts in Enterprise Work: How Trust, Cognitive Division of Labor, and Knowledge Flow Reshape Each Other Over Sustained Collaboration.**

---

## Locked Decisions

| Term | Decision | Session locked | Rationale |
|---|---|---|---|
| **AI Agents** | Embedded-in-workflow agents: Copilot, Glean, Harvey, Hebbia, enterprise in-house. NOT generic chat assistants. NOT multi-agent / agent-swarm systems. | 1 | User-specified narrowing ("嵌入工作流的 agent"). |

---

## Open Decisions

### O1. "Co-evolution" framing path
- **(A) Synthesis** — spine = lenses 2+3+4 (saturated empirical). **De-prioritized.** Pedreschi + JAIR GAE gave us a usable term + construct; pure synthesis wastes both.
- **(B) Theory-driven** — spine = lens 6 (niche construction). **RECOMMENDED.** NCT × AI × work is empty and Brynjolfsson/Dillon/Dell'Acqua already describe NCT-shaped mechanisms without naming them. See `stage2-framing.md` for full reasoning.
- **(C) Hybrid** — spine = lenses 5+6 (activity theory + NCT). Possible but marginal-return. Emerald 2025 already staked AT × GenAI conversational agents; AT contribution is small relative to lift cost. Better used as related-work citation in Lens 5.
- **Status**: **awaiting user lock**. Recommendation: B with AT as supporting related work.

### O2. Domain anchor
- Evidence base distributes across:
  - Customer support (Brynjolfsson 2025) — mass-empirical, lowest-expert
  - **Consulting (Dell'Acqua 2025) — paradigmatic enterprise expert, canonical paper. RECOMMENDED as primary anchor.**
  - Cross-industry knowledge work (Dillon 2025) — broadest, most diffuse
  - Specialized professions (lawyers/Harvey, clinicians/CDS, SWE/Copilot) — not in anchor papers; would need fresh empirical work
- Comparative across 2–3 domains also viable.
- **Status**: **awaiting user lock**.

### O3. "Cognitive Division of Labor" — operational definition
- Function allocation (human factors).
- Cognitive offloading.
- Distributed cognition (Hutchins).
- Decision-rights allocation.
- **Status**: depends on chosen lens. Defer.

### O4. "Knowledge Flow" — direction + decomposition
- Default leaning: bidirectional (expert → AI via feedback / prompting; AI → expert via outputs and pattern discovery).
- Optional decomposition: tacit vs explicit (Nonaka / Polanyi).
- **Status**: defer until lens 1 / 5 deepens.

### O5. "Sustained" — time horizon
- **Empirical reality (post-Stage 2)**: 6 months (Dillon per-worker), ~12 months staggered (Brynjolfsson rollout). One-shot (Dell'Acqua). No multi-year panel exists.
- Reframing options:
  - (a) Bounded duration — "across the early adaptation window (6–12 months)"
  - (b) **Process-based — "in the bidirectional feedback regime" (any horizon where both sides update at least once). RECOMMENDED — most NCT-consistent.**
  - (c) Re-title the paper.
- **Status**: **awaiting user lock**.

---

## Out of Scope (current)

- Multi-agent / agent-swarm settings.
- Consumer AI (ChatGPT-as-personal-assistant).
- Pure ML research workflow agents.
- Algorithmic management (top-down, no expert collaboration).
