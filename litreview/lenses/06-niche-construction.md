# Lens 6 — Niche Construction / Co-evolution

## Anchor paper: Pedreschi et al. (2025) "Human-AI Coevolution"

### Citation

> Pedreschi, D., Pappalardo, L., Ferragina, E., Baeza-Yates, R., Barabási, A.-L., Dignum, F., Dignum, V., Eliassi-Rad, T., Giannotti, F., Kertész, J., Knott, A., Ioannidis, Y., Passarella, A., Pentland, A. S., Shawe-Taylor, J., & Vespignani, A. (2025). Human-AI coevolution. *Artificial Intelligence*, 339, 104244. https://doi.org/10.1016/j.artint.2024.104244

- **Type**: position / programmatic paper (introduces a new field)
- **Authors**: 17 high-prestige (Barabási, Pentland, Vespignani, Pedreschi, Eliassi-Rad, etc.)
- **Open versions**: arxiv 2306.13723; barabasi.com/media/2025-Pedreschi-Human-AI.pdf
- **Note on this boundary map**: full-text retrieval was blocked (HTTP 403 on all routes). Map below is assembled from indexed search snippets — high confidence on scope and definitions, lower confidence on exact section structure. **Flag for human verification.**

---

## Boundary Map

### 1. Their definition of "human-AI coevolution"

> "A process in which humans and AI algorithms continuously influence each other."

Mechanism: "the interaction between users and AI results in a potentially endless feedback loop, wherein users' choices generate data to train AI models, which, in turn, shape subsequent user preferences."

Framed as "understudied in artificial intelligence and complexity science literature."

### 2. AI systems in their scope

**Recommender systems and assistants** — "permeate many facets of daily life and influence human choices through online platforms."

### 3. Humans in their scope

**Consumers / platform users** making daily-life choices in online settings. Societal-aggregate level.

### 4. Theoretical framework

- **Complexity science** + feedback-loop dynamics is the explicit framing.
- They introduce **"Coevolution AI"** as a new field at the intersection of AI and complexity science.
- They propose **"society-centred AI"** as a 4th philosophical pillar alongside technology-centred, human-centred, and collective intelligence.
- **They do NOT invoke niche construction theory (Odling-Smee) by name** based on the snippets I could access. The biological-evolutionary analogy is loose, not the Odling-Smee formalism.

### 5. Methodology

Theoretical / programmatic. Not empirical. Not a systematic review. A position paper that maps the territory and calls for a research field.

### 6. Their key claims (top 4)

1. Human-AI coevolution is a distinct phenomenon, different from traditional human-machine interaction because the feedback loop is endless and the AI is itself updated by the human side.
2. Recommender systems are the canonical site for studying coevolution today.
3. The phenomenon needs a new field — "Coevolution AI" — combining AI and complexity science methods.
4. There are open challenges at three levels: scientific (measurement of feedback loops), legal, and socio-political (concentration of "means of recommendation").

### 7. Their stated future work / gaps

- A method to continually measure the impact of the feedback loop, e.g., tracking step-wise how outcomes shift each time the recommender is re-trained.
- Policy interventions to "redistribute the means of recommendation".
- Designing policies to avoid negative externalities of uncontrolled coevolution.

### 8. Coverage check vs. our topic

| Concept in our title | Covered by Pedreschi? | Notes |
|---|---|---|
| AI **agents** (embedded workflow) | **No** | Their AI = recommenders / assistants on consumer platforms. Not Copilot/Glean/Harvey-class. |
| **Domain experts** | **No** | Their humans = mass consumers, societal aggregate. Not professional experts in workflow. |
| **Enterprise work** | **No** | Their setting = online platforms, consumer markets, societal. |
| **Trust calibration** | No (not focal) | Their concern is preference shaping, not trust dynamics. |
| **Cognitive division of labor** | **No** | Not in their frame. Feedback is data ↔ preferences, not cognition allocation. |
| **Knowledge flow** | Partial | They have data-and-preference flow, not knowledge-as-expertise flow. Different conceptualization. |
| **Sustained / longitudinal** | Yes, implicitly | Their endless feedback loop is by definition sustained. |
| **Niche construction (Odling-Smee)** | **No** | Not invoked by name. Open theoretical opening. |

---

## What this means for our framing decision

**Pedreschi et al. legitimizes the "human-AI coevolution" terminology** at a top-tier AI journal with high-prestige authorship. That's a tailwind — the framing is no longer fringe.

**Their substantive scope leaves our cell of the matrix wide open.** Three independent dimensions where we differ:

1. AI type: recommenders (theirs) vs. embedded workflow agents (ours).
2. Human type: consumers (theirs) vs. domain experts (ours).
3. Mechanism: preference shaping (theirs) vs. cognitive collaboration / division of labor / trust / knowledge flow (ours).

**Theoretical opening**: they explicitly do NOT use niche construction theory. We can introduce Odling-Smee's niche construction as a sharper formalism for the *expert work* coevolution, distinct from Pedreschi's consumer-platform complexity-science framing.

### Framing path verdict

- **Path A (synthesis)** — safe but unnecessarily timid; leaves clear theory whitespace on the table.
- **Path B (theory-driven, niche construction spine)** — **now de-blocked.** Pedreschi gives the umbrella legitimacy without occupying our cell.
- **Path C (hybrid: activity theory + niche construction)** — **also de-blocked**, more ambitious, harder to execute.

**Recommendation to user**: lean toward **B or C**, with B being the safer of the two interesting options. Final decision should wait until lens 5 (activity theory in enterprise) gets its round-2 search — if activity theory has more enterprise traction than Stage 1 suggested, C becomes more attractive.

---

## Adjacent papers surfaced while reading Pedreschi

- **"From Expert Systems to Generative Artificial Experts"** (JAIR) — introduces "Generative Artificial Experts (GAEs)" for knowledge work. **Directly adjacent to our topic.** Need to add to candidate pool. https://jair.org/index.php/jair/article/view/17175
- **"The Enterprising and Elusive Prospects of Human-AI Collaboration"** (Springer 2025) — https://link.springer.com/chapter/10.1007/978-3-032-01940-0_7
- **"The urban impact of AI: modelling feedback loops in location-based recommender systems"** (Springer ML 2025) — applies Pedreschi-style feedback-loop modeling, narrower domain. https://link.springer.com/article/10.1007/s10994-025-06904-z
- **"System 0: Transforming Artificial Intelligence into a Cognitive Extension"** (Cyberpsych 2025) — frames AI as cognitive extension, relevant to lens 3 (joint cognitive systems) and lens 6. https://www.liebertpub.com/doi/full/10.1089/cyber.2025.0201

---

## Open follow-ups for Stage 2 continuation

1. ✅ Boundary map of Pedreschi — this file.
2. ⏳ Boundary maps of remaining anchor papers (Brynjolfsson QJE, Dell'Acqua Org Sci, Dillon arxiv) — parallel sub-agents OK.
3. ✅ Round-2 search on lens 6 (niche construction foundations) — see below.
4. ⏳ Round-2 search on lens 5 (activity theory × enterprise AI agents) — see `lenses/05-activity-theory.md`.
5. ⏳ Read JAIR "Generative Artificial Experts" paper — it's closer to our cell than Pedreschi.

---

# Round-2: Niche Construction Theory Foundations

Search added 2026-05 to confirm the theoretical backbone for framing path B (NCT-spine).

## Canonical sources

- **Odling-Smee, F. J., Laland, K. N., & Feldman, M. W.** (2003). *Niche Construction: The Neglected Process in Evolution* (Princeton/MIT). The foundational monograph. https://mitpress.mit.edu/9780262548168/niche-construction/
- **Laland, Odling-Smee, & Feldman** (2001). "Cultural niche construction and human evolution." *Journal of Evolutionary Biology*, 14(1): 22–33. Key for the *cultural* extension of NCT — central to applying it to AI in human work. https://onlinelibrary.wiley.com/doi/full/10.1046/j.1420-9101.2001.00262.x
- **Laland, Odling-Smee, & Feldman** (2001 PhilPapers entry). "Niche construction, biological evolution, and cultural change." https://philpapers.org/rec/LALNCB
- **Royal Society Interface Focus** (2017). "Niche construction, sources of selection and trait coevolution." https://royalsocietypublishing.org/rsfs/article/7/5/20160147/64175/Niche-construction-sources-of-selection-and-trait

## Bridge from biology to technology

- **W. Brian Arthur** (2009). *The Nature of Technology: What It Is and How It Evolves.* Free Press / Penguin. The natural intellectual bridge: technology as combinatorial evolution, where novel technologies emerge by integrating earlier ones. Not NCT by name, but compatible in spirit.
- Notable: Giovanni Dosi (2024 Schumpeter Prize) extensively references Arthur in *The Foundations of Complex Evolving Economies* — bridge from tech evolution to economic evolution.

## Critical finding: NCT × AI × Work is empty

Searches for "niche construction theory" + "AI" + "work practice" / "cultural evolution" / "artificial intelligence":
- Returned generic NCT biology/ecology results, plus unrelated "AI in construction industry" hits.
- **No paper applies NCT (Odling-Smee) by name to AI agents in work settings.**
- Pedreschi et al. (2025) — closest existing coevolution paper — does NOT invoke NCT terminology (confirmed via search snippets).

This is genuine theoretical whitespace.

## What NCT contributes if we use it as spine

The Odling-Smee formalism gives us four moves:

1. **Inceptive niche construction** — agents (here: AI + experts together) actively modify the work environment.
2. **Counteractive niche construction** — modifications partly offset environmental change (e.g., AI absorbs routine load so experts can take on novel cases).
3. **Ecological inheritance** — modified environments persist as a legacy for subsequent generations of work practice (workflows reshape; new hires learn the reshaped routine).
4. **Selection-modification feedback** — the modified niche reshapes which behaviors/roles get selected next (e.g., AI capabilities reshape what counts as expert competence).

These map cleanly onto our title's "Trust, Cognitive Division of Labor, and Knowledge Flow Reshape Each Other Over Sustained Collaboration."

## Implications for framing decision

**Path B (NCT-spine) status: theoretically robust and empirically open.**

- The theory has 25+ years of formalism in biology + a published cultural-evolution extension.
- The Arthur bridge to technology evolution is well-cited.
- No competitor has staked the AI-agent-in-work cell with NCT terminology.
- Risk: NCT is biological; reviewers in management / HCI may find it foreign. Need to lean on the cultural-evolution branch (Laland et al.) and the technology branch (Arthur) as bridges.

**Path B vs Path C (now post-round-2):**

| Path | Lens | Whitespace status | Bridge work needed |
|---|---|---|---|
| B | NCT spine | Empty cell, fully open | Heavy: bring biological NCT into management/HCI |
| C | NCT + Activity Theory hybrid | Lens 5 has one published paper (Emerald 2025) — partial competition | Medium: differentiate from Emerald + bring NCT |

Path B is theoretically purer. Path C is methodologically lower-risk but novelty is shared.

**Recommendation (preliminary, awaiting remaining boundary maps)**: lean B; treat the Emerald 2025 AT paper as a related-work citation rather than a co-spine.

Sources for this round:
- [Niche Construction monograph (MIT Press)](https://mitpress.mit.edu/9780262548168/niche-construction/)
- [Cultural niche construction and human evolution — Laland, Odling-Smee, Feldman (2001)](https://onlinelibrary.wiley.com/doi/full/10.1046/j.1420-9101.2001.00262.x)
- [Niche construction, sources of selection and trait coevolution — Royal Society Interface Focus (2017)](https://royalsocietypublishing.org/rsfs/article/7/5/20160147/64175/Niche-construction-sources-of-selection-and-trait)
- [Brian Arthur — The Nature of Technology (PhilPapers entry)](https://philpapers.org/rec/ARTTNO)
- [Brian Arthur — STIAS seminar on combinatorial evolution](https://www.stias.ac.za/seminars/combinatorial-evolution-a-theory-of-evolution-for-technology/)
- [Number Analytics — The Future of Niche Construction Research](https://www.numberanalytics.com/blog/future-niche-construction-research)
