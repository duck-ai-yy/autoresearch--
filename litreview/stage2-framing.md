# Stage 2 — Framing Convergence

## Inputs

| Artifact | Topic | Status |
|---|---|---|
| `lenses/05-activity-theory.md` | Lens 5 round-2 search | Round-2 ✅ |
| `lenses/06-niche-construction.md` | Lens 6: Pedreschi boundary + NCT foundations | Both rounds ✅ |
| `papers/brynjolfsson-2025-qje.md` | Customer support agents, QJE 2025 | ✅ |
| `papers/dellacqua-2025-orgsci.md` | BCG consultants × GPT-4, Org Sci 2025 | ✅ |
| `papers/dillon-2025-arxiv.md` | Microsoft Copilot RCT, AERI 2025 | ✅ |
| `papers/jair-gae.md` | Sowa & Przegalinska GAE taxonomy, JAIR 2025 | ✅ |

All built from indexed snippets (WebFetch was blocked HTTP 403 in this environment). Boundary maps flag confidence levels and items needing human verification.

---

## Cross-paper comparison

| Paper | AI type | Sample | Time horizon | Theoretical frame | Coevolution? | Niche construction? |
|---|---|---|---|---|---|---|
| **Pedreschi 2025 AIJ** | Recommenders (consumer) | n/a (theoretical) | Endless loop | Complexity science + feedback | **Yes (term)** | **No (not named)** |
| **Brynjolfsson 2025 QJE** | Embedded CS workflow agent | 5,179 CS agents | ~12 months staggered | Labor econ; tacit knowledge redistribution | No | **Loop described, not named** |
| **Dell'Acqua 2025 Org Sci** | Raw GPT-4 (substrate) | 758 BCG consultants | **One-shot** | Empirical/inductive; jagged frontier; centaur/cyborg | No | No |
| **Dillon 2025 AERI** | Microsoft 365 Copilot | 66 firms, 7,137 workers | **6 months** | Bresnahan-Brynjolfsson-Hitt complementarity | No | **Stalled adaptation described, not named** |
| **Sowa & Przegalinska 2025 JAIR** | Forward-looking GAEs | Conceptual | None | Abductive taxonomy | No | No |
| **Emerald 2025 IJILT** | GenAI conversational agents | (snippet-only) | (snippet-only) | Activity theory | No | No |

---

## Lens density: revised after Stage 2

| Lens | Stage 1 | Stage 2 | Current status |
|---|---|---|---|
| 1. STS / sociomateriality | Moderate | Unchanged | Mostly grey lit |
| 2. Routines / evol. econ. | **High** | **High** | Brynjolfsson, Dillon anchor |
| 3. Joint cognitive systems | **High** | **High** | Dell'Acqua jagged-frontier anchor |
| 4. Trust calibration | **High** | **High** | Dell'Acqua "falling asleep at the wheel" |
| 5. Activity theory | **Empty in enterprise** | **Partial** | Emerald 2025 staked AT × GenAI conversational |
| 6. Niche construction | **Empty + 1 adjacent** (Pedreschi) | **Still empty for our cell** | Pedreschi gave umbrella; nobody used Odling-Smee NCT on AI agents in work |

---

## The whitespace map (evidence × theory matrix)

> **Y axis** = theoretical frame; **X axis** = empirical AI type. ✅ = published anchor exists; ◐ = partial / adjacent; ⬜ = empty.

|  | Embedded workflow agents (Copilot/Glean/Harvey/Hebbia) | Customer-support copilots | Raw LLM substrate | Recommender systems |
|---|---|---|---|---|
| **Routines / evol. econ.** | ✅ Dillon 2025 | ✅ Brynjolfsson 2025 | ◐ Acemoglu/Restrepo line | ⬜ |
| **Joint cognitive systems** | ⬜ | ◐ Brynjolfsson tacit-knowledge mechanism | ✅ Dell'Acqua 2025 | ⬜ |
| **Trust calibration** | ◐ Dillon coworker spillovers (light) | ◐ Brynjolfsson adherence drift | ✅ Dell'Acqua "falling asleep at the wheel" | ⬜ |
| **Activity theory** | **⬜ OPEN** | ⬜ | ⬜ | ⬜ |
| **Niche construction** | **⬜ OPEN** | **⬜ OPEN** (Brynjolfsson describes the loop) | **⬜ OPEN** | ⬜ |
| **Coevolution (Pedreschi-style)** | **⬜ OPEN** | **⬜ OPEN** | **⬜ OPEN** | ✅ Pedreschi 2025 |
| **Taxonomic (GAE)** | ◐ Sowa & Przegalinska label our agents as "proto-GAE" | ⬜ | ⬜ | ⬜ |

**Reading**: the embedded-workflow-agent column has empirical anchors for routines/JCS/trust but **no theoretical entry for AT / NCT / coevolution**. The niche-construction row is empty across all AI types. **Intersection of "embedded workflow agents × niche construction" is doubly empty.**

---

## Three structural findings

### F1. The empirical literature describes NCT-shaped mechanisms without using the name

- Brynjolfsson identifies **adherence drift + model decay**: a tacit-knowledge-extraction mechanism (AI absorbs high performers' style → redistributes to novices → high performers' contribution evaporates → AI quality degrades → human practice degrades). **This is a niche-construction feedback loop with no theoretical name.**
- Dillon identifies that at 6 months **individual time savings are real but task composition has not shifted**. In NCT terms: organisms (workers) are modifying their micro-environment (time use) but the modified environment has not yet propagated as ecological inheritance to reshape the activity system around them. The paper invokes Bresnahan-Brynjolfsson-Hitt complementarity — the same phenomenon, framed in IT-economics rather than evolutionary terms.
- Dell'Acqua identifies that successful adapters operate as **centaurs or cyborgs** — i.e., they actively reconstruct the cognitive division of labor in the moment. NCT framing: agents (humans) are doing inceptive niche construction on the task-substrate, with feedback selecting which adaptations spread.

**These three findings together describe a niche-construction process unfolding across the technology adoption — none of them theorize it as such.**

### F2. "Sustained" must be honestly bounded

The best longitudinal evidence we have is:
- Dillon: 6 months per-worker.
- Brynjolfsson: ~12 months staggered rollout (and the model itself was updated mid-study; "model decay" appears precisely because the underlying AI changed).
- Dell'Acqua: one-shot — no time dimension.

**Our title's "sustained collaboration" cannot mean "multi-year panel."** It must mean either:
- (a) "across the early adaptation window" (6–12 months), explicitly bounded
- (b) "in the bidirectional feedback regime" (any time horizon where both sides update at least once)
- (c) re-titled

Option (b) is most NCT-honest: niche construction is defined by the *process*, not the duration.

### F3. JAIR GAE is friend, not foe

Sowa & Przegalinska's GAE construct is a **static taxonomy** (7 traits, AI-side description). They explicitly say GAEs "do not yet exist but are emerging" — naming today's Harvey/Glean/Copilot as proto-GAEs. They do **not** theorize coevolution, time, or mutual reshaping. **Their construct gives us a clean AI-side definitional anchor** — we can write "we study coevolution between domain experts and Sowa-Przegalinska-style proto-GAEs deployed in enterprise workflows."

---

## Framing decision: paths A / B / C

Reassessed with full Stage 2 evidence:

| Path | Spine | Whitespace | Theoretical lift | Evidence fit | Recommended? |
|---|---|---|---|---|---|
| **A** (synthesis) | Lenses 2 + 3 + 4 | Low — saturated already | Low | Strong (all 3 anchor papers fit cleanly) | **NO**. Leaves money on the table. Pedreschi gave us the term, JAIR gave us the construct — would waste both. |
| **B** (theory-driven) | Lens 6 (NCT) | **High** — empty cell | High — bridge biology to sociotechnical | **Excellent** — Brynjolfsson + Dillon literally describe NCT loops without naming them; reinterpretation is the contribution | **YES (recommended)** |
| **C** (hybrid) | Lenses 5 + 6 (AT + NCT) | Medium — Emerald 2025 partly staked AT × GenAI | Very high — two bridges | Good, but AT contribution overlaps Emerald | Possible but marginal-return |

### Recommendation: **Path B**

**Spine**: niche construction theory (Odling-Smee, Laland, Feldman) extended via Brian Arthur's combinatorial tech-evolution bridge, applied to embedded workflow AI agents in enterprise expert work.

**Citation architecture**:
- Pedreschi 2025 → cited as umbrella legitimization of "human-AI coevolution"; differentiated as recommender-systems-focused (not our cell).
- Sowa & Przegalinska 2025 → cited for AI-side construct (proto-GAE).
- Brynjolfsson 2025 → re-read through NCT: adherence drift + model decay = niche-construction feedback loop.
- Dell'Acqua 2025 → re-read through NCT: centaur/cyborg = inceptive niche construction at task substrate.
- Dillon 2025 → re-read through NCT: "no org restructuring at 6 months" = ecological inheritance not yet established.
- Emerald 2025 (Lens 5) → related work; activity theory as an alternative framing we acknowledge but do not adopt as spine.

**Contribution slot**: bring NCT into the AI/work literature as the missing theoretical scaffold. The contribution is *theoretical reinterpretation* of an already-rich empirical literature, with one or more empirical anchors to a specific domain.

### Why not Path C

Path C adds activity theory as a co-spine. Emerald 2025 already staked the AT × GenAI cell. Marginal novelty from C is small, complexity cost is double. AT is better used as a related-framework citation in Lens 5, not as a co-pillar.

### Honest risks of Path B

1. **NCT is biological.** Management / HCI reviewers may find it foreign. *Mitigation*: lean on Laland et al. (cultural NCT) and Arthur (combinatorial tech evolution) as bridges; treat NCT as a *family* of theories that has already been extended beyond biology.
2. **"Sustained" claim must be bounded.** *Mitigation*: explicit framing in introduction; defend as "process-based" not "duration-based" coevolution.
3. **Without empirical contribution, paper is theoretical only.** *Mitigation*: pick one anchor domain, do a focused secondary analysis or case study to ground NCT claims.

---

## Open decision still on user

### O2 — Domain anchor

The evidence base distributes across:
- **Customer support** (Brynjolfsson 5,179 agents) — strongest mass-empirical, but lowest-skilled population, weakest "expert" framing.
- **Consulting** (Dell'Acqua 758 BCG) — paradigmatic enterprise domain expert; canonical paper.
- **Cross-industry knowledge work** (Dillon 7,137 across 66 firms) — broadest, but most diffuse.
- **Specialized professions** (lawyers/Harvey, clinicians/CDS, SWE/Copilot) — not represented in our anchor papers.

**Recommendation**: lead with **consulting** (Dell'Acqua anchor), with Brynjolfsson + Dillon as supporting cross-population evidence. Alternative: comparative across 2–3 domains.

---

## Next stage

**Stage 3 — Outline drafting.** Awaiting user decision on:
1. Approve Path B as framing spine? (Or push to C / A?)
2. Domain anchor: consulting / customer support / Copilot cross-industry / comparative?
3. "Sustained" interpretation: bounded duration / process-based / re-titled?

Once these are locked, Stage 3 produces `outline.md`: section-by-section structure with citation slots.
