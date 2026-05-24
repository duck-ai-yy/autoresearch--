# Boundary Map — Dillon et al. (2025) "Shifting Work Patterns with Generative AI"

## Source provenance note

Full-text retrieval was blocked: arxiv HTML (`arxiv.org/abs/2504.11436`, `arxiv.org/html/2504.11436v1`) and ar5iv mirror both returned HTTP 403 to WebFetch. NBER PDF and HBS PDF mirrors not retrievable in this session. Map below is reconstructed from indexed search snippets across multiple queries (arxiv abstract page, ar5iv title-page metadata, NBER abstract, AEA AER:Insights abstract, SSRN abstract, and verbatim excerpts surfaced in snippets). **High confidence** on: authors, sample size, time horizon, headline claims, methodology shape, and the "complementary process innovations" framing. **Lower confidence** on: exact section structure and the precise wording of definitions. **Flag for human verification on the v1 text** — particularly the limitations / future work language.

---

## 1. Full citation

> Dillon, E. W., Jaffe, S., Immorlica, N., & Stanton, C. T. (2025). Shifting Work Patterns with Generative AI. arXiv:2504.11436 (v1, April 2025). Also issued as NBER Working Paper No. 33795 (May 2025); forthcoming in *American Economic Review: Insights* (10.1257/aeri.20250275).

- **Note on authorship**: The arxiv v1 title-page acknowledgement names Alexia Cambon and Sida Peng (Microsoft Customer Research Program) as collaborators who helped carry out the experiment, but they are NOT listed as authors of the paper itself. The four authors are Dillon (Microsoft Research, corresponding), Jaffe (Microsoft Research), Immorlica (Microsoft Research), and Stanton (Harvard Business School). The assignment-card author list "Dillon, Cambon, Peng, et al." appears to conflate the author list with the acknowledged Microsoft customer-research team. **Worth re-verifying against the v1 PDF.**
- **Companion paper**: arxiv 2504.11443 "Early Impacts of M365 Copilot" (Dillon et al., same research program — a shorter or earlier-cut version on overlapping data).

---

## 2. Key term definitions (from snippets, paraphrased unless quoted)

- **"Generative AI tool"** = "an integrated generative AI tool, Microsoft 365 Copilot (hereafter, Copilot)" — explicitly the workflow-embedded variant, not standalone ChatGPT.
- **"Knowledge workers"** (operational): "workers who regularly do the kinds of emailing and word processing tasks for which Copilot was designed … workers from varied occupations, but all did work that used the Microsoft Office tools into which Copilot was integrated (e.g., emailing, video meetings, chat, document creation)."
- **"Work patterns"** = operationalized as telemetry-measured time allocations: time reading emails, time in video meetings, time from creation to completion of documents, hours worked outside of regular hours, etc.
- **Implicit framing of "shifting"**: changes in (a) per-task time, (b) task composition / mix, (c) collaboration patterns with coworkers — the paper finds (a) but largely not (b) or (c) at the 6-month horizon.

---

## 3. AI systems in their scope — match with our topic

**Microsoft 365 Copilot, integrated into Outlook, Teams, Word, Excel, PowerPoint.**

- **Direct match with our locked scope.** This is the canonical embedded-in-workflow agent — same tier as Glean / Harvey / Hebbia, just at a much larger, cross-industry scale.
- NOT a standalone chatbot; the AI is invoked from inside the productivity surface the worker is already using.
- NOT a multi-agent system.
- This is the **single best AI-system fit** among our anchor papers for the "embedded workflow agent" pole of our title.

---

## 4. Humans in their scope — match with our topic

**Knowledge workers at 66 large firms, n = 7,137 workers studied (plus ~6,000 of those with telemetry).**

- **Cross-industry**, not anchored to a single profession. Sample is dominated by office-based knowledge workers who use Microsoft 365 daily. Specific occupational breakdown is not surfaced in snippets — likely a mix of managers, marketing, sales, operations, HR, finance, legal, etc., across multiple sectors. The sampling frame is **firm-level**, with each firm recruiting "at least 100 workers".
- **"Domain experts" — partial match.** Many participants are domain experts in their functional area (e.g., a financial analyst, a marketing lead), but the study does NOT stratify by domain-expertise depth, nor does it study a single profession in the way Harvey-lawyers or BCG-consultants studies do. Domain expertise is in the sample but not in the design.
- **Enterprise context — strong match.** 66 large firms, real production work, not a lab.

---

## 5. Theoretical framework / mechanism

**Predominantly descriptive empirical economics with a light theoretical scaffold from the GPT / complementary-investments literature.**

- Cited theoretical anchor: **Bresnahan, Brynjolfsson & Hitt (2002)** "Information Technology, Workplace Organization, and the Demand for Skilled Labor" — the canonical "ICT requires complementary organizational investment to realize productivity gains" argument. The paper invokes this to interpret the *absence* of broad task-composition shifts: "co-creation of work and process restructuring that the literature identifies as a pre-condition for effective technology adoption did not seem to take place under the individual-level rollout."
- Implicit framing: GPT (general purpose technology) productivity-J-curve logic — early phase, individual time savings precede the deeper organizational restructuring needed for output-level gains.
- **No invocation of**: trust calibration theory, cognitive load theory, distributed cognition, activity theory, niche construction, or human-AI coevolution. This is a labor-economics field experiment, not an HCI or organizational-cognition paper.

---

## 6. Methodology — sample, design, time horizon

- **Design**: cross-industry randomized field experiment. Each of 66 firms recruited at least 100 workers; within-firm random assignment to Copilot license (treatment) or no license / status quo (control). Firms were asked to maintain randomization for 6 months.
- **Sample**: 66 firms, 7,137 workers total; ~6,000 with telemetry coverage.
- **Outcome measurement**: Microsoft product telemetry (time spent reading email, time in meetings, time creation-to-completion of documents, out-of-hours work) plus survey instruments.
- **Calendar window**: rollout took place between September 2023 and October 2024 — i.e., the assignment card's "first-year-of-broad-use data" phrasing refers to the calendar window of data collection, not to a single 12-month exposure per worker.
- **Time horizon per worker**: 6 months of randomized post-treatment observation. The paper does split into "first half" vs. "second half" of the experiment to observe within-treatment dynamics, with the headline effect (≈2 fewer email hours/week) emerging in the second half.
- **Critical for our review**: the per-worker horizon is **6 months, not 12.** The assignment card's "longitudinal" descriptor is justified relative to the 1-shot RCT norm in this literature, but it is *not* a multi-year panel. For our title's "sustained collaboration" framing, this is the longest enterprise-RCT horizon currently available, but it is still short of what "co-evolution" would ideally require.

---

## 7. Their key claims (top 5)

1. **Individual time savings are real and grow over the 6-month window.** Among the ~80% of treated workers who used Copilot at least once a week, weekly email time fell by about 2 hours (≈25% reduction in some cuts; 18% / 30 min in others), out-of-hours work fell, and documents the worker was primary editor on completed about half a day faster — full day for regular users.
2. **The strongest effects are in collaborative documents** (where the studied worker is primary editor but at least one coworker also contributes), with completion time reductions of ~20% / >2 days. This pattern, the authors note, "suggests behavior shift beyond casual experimentation with a new tool."
3. **Task composition and quantity did NOT shift** at the individual level. Workers reallocated saved time, but the mix of tasks and the volume of output the experiment can measure did not change meaningfully.
4. **No detectable team-level or firm-level reorganization at 6 months.** Workers with more treated close coworkers, or workers in higher-firm-adoption settings, did not show qualitatively different patterns — implying "larger shifts in responsibilities require time and broad institutional efforts, not just local team coordination."
5. **Modest positive coworker spillovers, no negative spillovers.** Treated workers' close coworkers (treated or control) did not see degraded work patterns, suggesting time savings are not extracted from coworker effort. This rebuts a key concern that AI-assisted output dumps cognitive load onto colleagues.

---

## 8. Stated gaps / future work

From the snippets that surfaced limitations / interpretive caveats:

- The 6-month window is **"the early adoption stage"**; the authors explicitly position the absence of process / role restructuring as expected at this horizon, and flag that **"complementary process innovations and organizational restructuring that drive larger changes in workflow had not yet taken place."** Implicit call: longer-horizon studies that capture the post-restructuring phase.
- **Individual-level rollout is a binding constraint.** The experimental design (within-firm randomization of individuals) cannot capture firm-level reorganization effects. Future work could study firms that restructure roles around Copilot.
- **Heterogeneity by occupation / domain expertise is largely unexplored** in the snippets surfaced — though the paper does some occupational cuts, it does not deeply theorize how domain expertise mediates uptake.
- No stated future work on trust calibration, knowledge transfer, or expert-AI co-adaptation per se — these are simply outside the paper's empirical frame.

---

## 9. Coverage check vs. our topic

| Concept in our title | Covered by Dillon et al.? | Notes |
|---|---|---|
| AI **agents** (embedded workflow) | **Yes — gold standard match** | Microsoft 365 Copilot is the paradigm case. |
| **Domain experts** | **Partial** | Knowledge workers, varied occupations, includes domain experts but does not stratify on expertise depth or single-profession. |
| **Enterprise work** | **Yes — strongly** | 66 large firms, real production work, cross-industry. The best enterprise-context fit in our pool. |
| **Trust calibration** | **No** | Not measured. The collaborative-document result hints at differential comfort ("workers may feel more comfortable using GenAI on collaborative tasks than for drafting") but this is not operationalized as trust. |
| **Cognitive division of labor** | **Partial / indirect** | Time-reallocation evidence is consistent with offloading email comprehension to the agent, but the paper does not theorize task allocation between human and AI. No decision-rights framework. |
| **Knowledge flow** | **No** | Not measured. The paper tracks time, not knowledge transfer between expert and agent in either direction. |
| **Sustained / longitudinal collaboration** | **Partial** | 6-month per-worker exposure, with within-window dynamics (effects grow in second half). Longest enterprise-RCT to date in our pool, but not multi-year. |
| **Niche construction (Odling-Smee)** | **No** | Not invoked. No evolutionary or coevolutionary framing. |
| **Co-evolution framing** | **No** | The paper's interpretive frame is "GPT + complementary investments" (Bresnahan/Brynjolfsson/Hitt), which is a *one-directional* "tech requires org restructuring" story, NOT a *bidirectional* coevolution story. |

---

## 10. Implications for framing decision (A / B / C)

### Does Dillon's longitudinal evidence support or undermine the "sustained co-evolution" framing in our title?

**Both — and that tension is itself useful.**

- **Supports** the framing in two ways:
  1. It empirically establishes that effects of an embedded workflow agent are *dynamic over months*, not static — the second-half-of-experiment effect amplification is direct evidence that adaptation is sustained, not instantaneous.
  2. The "complementary process innovations had not yet taken place" finding *is itself evidence that coevolution is in progress but unfinished* at 6 months. The paper essentially documents the leading edge of a longer coevolutionary process that has not yet completed its second loop (work routines → AI usage → new work routines).

- **Undermines / pressures** the framing in two ways:
  1. At 6 months, the paper detects no shifts in task composition, division of labor, or organizational structure. If "co-evolution" implies bidirectional mutual reshaping, Dillon shows the *human-side reshaping has barely begun* at the horizon currently observable in the literature. Our title's "sustained collaboration" needs to be honest about this empirical ceiling — current evidence reaches ~6–12 months, not years.
  2. The paper's preferred theoretical frame is **uni-directional (tech → org via complementary investments)**, not coevolutionary. A reviewer could fairly ask: "if the leading empirical paper interprets its data through Bresnahan/Brynjolfsson/Hitt complementarity, why do you need a coevolution lens?" We need a clear answer — likely: because the complementarity frame is silent on the AI-side adaptation (RLHF, prompt-pattern learning, agent re-fitting to workflow) which the niche-construction frame captures.

### Framing path implications

- **Path A (synthesis spine, lenses 2+3+4)**: Dillon is the headline anchor. Safe, immediately fundable, but cedes the theoretical opening.
- **Path B (niche construction spine)**: Dillon becomes the empirical evidence that the *human* side of niche construction is sluggish at the 6-month horizon; we frame the gap as a research agenda for capturing the next 1–3 years. This works **only if** we explicitly position Dillon's "complementary investments not yet visible" finding as a *prediction made by niche-construction theory* (the inheritance / modified-environment loop takes generations of routine cycles to manifest). That move is defensible.
- **Path C (hybrid: activity theory + niche construction)**: Dillon's collaborative-document finding (effects strongest where multiple coworkers edit) is **prime activity-theory material** — the mediating role of the artifact (the document) in a multi-subject activity system. Plus the niche-construction layer for the longer-horizon AI-side adaptation. Strongest theoretical leverage on Dillon's data, highest writing risk.

### Net verdict

Dillon **strengthens path B and especially path C** by providing the cleanest empirical anchor for "embedded workflow agent at enterprise scale, observed over a meaningful but bounded horizon." The paper's own "not yet" framing of organizational restructuring is *exactly the kind of partial, in-progress evidence that a coevolution lens is built to interpret*. The honest caveat we owe the reader: current longitudinal evidence tops out around 6–12 months per worker, so "sustained" in our title should be defined as "months-to-a-year scale, with theoretical extrapolation beyond" rather than "multi-year observational panel."

---

## Adjacent papers / leads surfaced while reading Dillon

- **Companion**: arxiv 2504.11443 "Early Impacts of M365 Copilot" (Dillon et al.) — likely overlapping or precursor cut of the same data. Worth a quick boundary check to avoid double-counting.
- **Bresnahan, Brynjolfsson & Hitt (2002)** — the theoretical anchor Dillon invokes. Needs to be in our lens-2 (productivity / complementarity) reading list if not already.
- **Productivity J-Curve** (Brynjolfsson, Rock, Syverson) — adjacent theoretical frame Dillon implicitly leans on.
- The **UK DBT Copilot pilot** (gov-sector replication) surfaced in snippets — possible secondary empirical evidence point.

---

## Open follow-ups for Stage 2 continuation

1. **Verify v1 author list against the actual v1 PDF** — the assignment card lists "Dillon, Cambon, Peng, et al." but indexed metadata shows the authors as Dillon / Jaffe / Immorlica / Stanton, with Cambon and Peng as acknowledged Microsoft customer-research collaborators. This matters for citation accuracy and for understanding which "Microsoft Research" the paper represents (Research lab vs. Customer Research Program).
2. Pull the actual limitations / future work section from the v1 PDF when retrieval is possible — section 9 above is reconstructed from snippets, not directly read.
3. Cross-check with the companion paper (2504.11443) to confirm we are mapping the right artifact for our citation.
4. Once path A/B/C is selected, decide whether Dillon is the *headline* anchor or one of several — likely headline for any path because it is uniquely the embedded-workflow-agent × enterprise × longitudinal combination in our pool.
