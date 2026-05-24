# Boundary Map — Dell'Acqua et al. (2025), *Organization Science*

## 1. Full citation

> Dell'Acqua, F., McFowland III, E., Mollick, E. R., Lifshitz-Assaf, H., Kellogg, K., Rajendran, S., Krayer, L., Candelon, F., & Lakhani, K. R. (2025). Navigating the Jagged Technological Frontier: Field Experimental Evidence of the Effects of Artificial Intelligence on Knowledge Worker Productivity and Quality. *Organization Science*. https://doi.org/10.1287/orsc.2025.21838

- **Type**: Pre-registered field experiment (empirical, quantitative + qualitative supplements)
- **Setting**: 758 Boston Consulting Group consultants × GPT-4 × 18 realistic consulting tasks
- **Authors**: 9 (Harvard / Wharton / NYU / MIT-adjacent / BCG). High prestige.
- **Earlier versions**: HBS Working Paper 24-013 (Sept 2023); SSRN id 4573321.
- **Note on source provenance**: All retrieval routes to the full PDF returned HTTP 403 in this environment (HBS, MIT Sloan mirror, Org Sci, SSRN, Working Knowledge, Mollick's blog). This map is assembled from indexed search snippets, abstracts, secondary summaries (Big Think, Lokad, Innovative Human Capital, EDRM, MindStudio), and the team's own commentary (Mollick "One Useful Thing", Prof. KL substack). **High confidence on headline findings, definitions, and design; lower confidence on the exact text of the limitations / future-work section. Flag for human verification.**

---

## 2. Key term definitions

### "Jagged frontier" / "jagged technological frontier"

> A concept describing "the uneven impact of artificial intelligence (AI) capabilities, where AI assistance improves performance for some tasks but worsens it for others, even within the same knowledge workflow and with a seemingly similar level of difficulty."

The frontier is "jagged" because AI capability is non-monotonic in task difficulty: two tasks that look similar to a human can lie on opposite sides of the capability boundary. Critically — workers cannot tell ex ante which side a task is on.

### "Inside the frontier" vs. "outside the frontier"

- **Inside**: tasks AI can perform reliably; AI assistance improves human performance.
- **Outside**: tasks AI cannot perform reliably; AI output is fluent but wrong, and degrades human performance.

### "Centaurs" vs. "Cyborgs" (from companion essay; the concepts are central to the paper's interpretation)

- **Centaur**: "a clear line between person and machine... strategic division of labor, switching between AI and human tasks, allocating responsibilities based on the strengths and capabilities of each entity." Granularity = whole-subtask.
- **Cyborg**: "blend machine and person, integrating the two deeply... don't just delegate tasks but intertwine their efforts with AI, moving back and forth over the jagged frontier, with bits of tasks handed to the AI." Granularity = sub-subtask, sentence-level.

(These two terms are popularized in Mollick's "Centaurs and Cyborgs on the Jagged Frontier" essay and used in the paper to describe the two successful adaptation strategies observed among high-performing consultants.)

### "Falling asleep at the wheel"

The team's label for over-reliance / mis-calibrated trust: when AI produces fluent-but-wrong output for outside-frontier tasks, consultants accept it without scrutiny because nothing in the output signals its incorrectness.

---

## 3. AI systems in their scope

**AI = GPT-4 (raw, via web interface), September 2023.** Two treatments:
- GPT-4 access only.
- GPT-4 access + a short prompt-engineering overview.

**Embedded enterprise workflow agents (Copilot, Glean, Harvey, Hebbia) — OUT of frame.** Their AI is the base model accessed directly. It is not embedded in a workflow tool, not retrieval-augmented over enterprise data, not deployed inside a CRM / DMS / document repository. The task harness is a research experiment platform, not a production knowledge-management agent.

This matters for our topic: Dell'Acqua et al. test the **substrate** (large language model) that today's embedded agents are built on, but not the **agent layer** that defines our scope (Copilot/Glean/Harvey-class). Their findings about jaggedness should transfer to embedded agents, but the agent layer adds retrieval, tool use, and workflow context that may smooth or relocate the frontier.

---

## 4. Humans in their scope

**Humans = 758 BCG consultants** (~7% of BCG's individual-contributor consulting workforce). Designed and validated by senior BCG MDs/partners as reflecting "core competencies evaluated in BCG recruiting and performance reviews."

**Are domain experts in enterprise settings IN their frame?** **PARTIAL — flag.**
- **YES, consultants are domain experts in enterprise work.** Management consultants are a paradigmatic professional / knowledge-worker population. Their tasks are real BCG work artifacts (strategy, creative ideation, market analysis, business problem solving).
- **CAVEAT**: consultants are *generalist* knowledge workers compared to lawyers (Harvey), clinicians (CDS), or SWEs (Copilot). The "domain" is consulting itself — a relatively horizontal expertise. So while the population qualifies as enterprise domain experts, it is the *most generalizable / least domain-bound* of the candidate professions we are considering as our anchor domain.
- The participants are doing tasks **as individuals**, not embedded in their normal team workflow. So the "enterprise context" is partially synthetic.

---

## 5. Theoretical framework / mechanism

**Primary framework**: empirical/inductive. The paper is theory-building from a randomized field experiment, not theory-testing of a prior named framework.

**Implicit theoretical scaffolds invoked**:
- **Capability frontier / task-allocation** logic (echoes of Acemoglu & Restrepo's task framework; Brynjolfsson on AI-as-prediction-machine; Susskind on tasks vs jobs).
- **Behavioral / over-reliance** mechanism: "mis-calibrated trust" + "falling asleep at the wheel" — workers over-trust AI on outside-frontier tasks (because fluency masks error) and under-use AI on inside-frontier tasks. This sits in the automation-bias / cognitive-offloading literature.
- **Two-mode adaptation** (centaur / cyborg): describes *how* high performers structure cognitive division of labor at task vs. sub-task granularity. This is closest to a distributed-cognition / function-allocation frame, though it is not labeled as such in the paper.

**No mention** (per accessible snippets) of: niche construction theory, activity theory, Nonaka tacit/explicit knowledge, Hutchins distributed cognition by name. The paper's contribution is the **jagged-frontier construct itself** plus two behavioral findings (productivity uplift inside; performance decay outside; centaur/cyborg adaptation).

---

## 6. Methodology

| Element | Value |
|---|---|
| Design | Pre-registered randomized field experiment, 3 arms |
| Sample | 758 BCG consultants (~7% of IC workforce) |
| Treatments | (1) no AI; (2) GPT-4 access; (3) GPT-4 + prompt-engineering overview |
| Tasks | 18 realistic consulting tasks designed and validated by senior BCG MDs/partners; spanning creative, analytical, writing, persuasion. Plus 1 separately-designed "outside the frontier" task that combined a tricky statistical issue with misleading data. |
| Outcomes | Productivity (% tasks completed, speed), quality (human-rated and LLM-rated), correctness on the outside-frontier task. |
| Pre-task baseline | Yes — individual baseline measured on similar tasks before treatment. |
| **Time horizon** | **One-shot / single session.** Participants complete tasks in one experimental window. **Not longitudinal.** No follow-up over weeks/months/years. **This is a critical scope limit for our topic.** |
| Setting | Online experimental platform, individual (not team) work, not embedded in normal consulting workflow. |

---

## 7. Their key claims (top 5)

1. **AI capability is jagged**: within a single knowledge workflow, tasks of seemingly similar difficulty can lie on opposite sides of an uneven AI-capability boundary, and workers cannot reliably tell which side ex ante.
2. **Inside the frontier**: consultants with GPT-4 completed 12.2% more tasks, 25.1% faster, and with significantly higher quality. Performance gains were largest for below-average performers (skill leveling).
3. **Outside the frontier**: consultants with GPT-4 were ~19 percentage points *less* likely to reach the correct answer on a managerial task seeded with misleading data — going from ~84% correct (no-AI) to 60–70% correct (AI). Fluent-but-wrong output induces "falling asleep at the wheel."
4. **Two successful adaptation modes (centaur, cyborg)**: high performers either strategically delegate whole subtasks (centaur) or interleave with AI at sub-sentence granularity (cyborg). The naive "use AI for everything" pattern fails.
5. **Organizational implication**: firms should not adopt AI at the *job* level but at the *task* level, mapping each task to its frontier position and choosing a different human-AI configuration per task.

---

## 8. Their stated gaps / future work

Based on commentary, secondary summaries, and the team's follow-up papers (which signal what the original left open), the gaps acknowledged are:

- **Frontier is moving**: the frontier shifts with each model release; the specific tasks they classified as outside today may be inside tomorrow. Calls for ongoing measurement.
- **Sustained / longitudinal effects unmeasured**: the experiment is one-shot. The paper does not address how trust, skill, division of labor, or productivity evolve over months/years of use. Their own follow-up work ("Cyborgs, Centaurs and Self-Automators", SSRN 4921696; "Persuasion Bombing", HBS WP 26-021) explicitly extends this gap.
- **Deskilling risk** flagged but not measured: if workers over-rely on AI inside the frontier, what happens to their independent skill over time?
- **Task-position discovery**: workers need a way to learn (organizationally or individually) where the frontier lies for their work. No mechanism proposed.
- **Embedded / workflow agents**: not addressed. Their GPT-4 is raw chat; how the same dynamics play in Copilot/Harvey/Glean-class embedded agents is an open question.
- **Team-level / collaborative effects**: experiment is individual-only.
- **Training and new role design**: explicitly identified as future research.

---

## 9. Coverage check vs. our topic

| Concept in our title | Covered by Dell'Acqua et al.? | Notes |
|---|---|---|
| **AI agents (embedded workflow — Copilot/Glean/Harvey)** | **No** | Their AI = raw GPT-4 chat. Substrate, not agent layer. |
| **Domain experts** | **Partial — yes for consultants, with caveat** | Consultants count as enterprise knowledge workers, but they are generalist; not lawyers/clinicians/SWEs. |
| **Enterprise work** | **Partial** | Tasks are real BCG work but performed in an experimental harness, individually, outside normal team workflow. |
| **Trust calibration** | **Yes (central)** | "Mis-calibrated trust" + "falling asleep at the wheel" are core empirical findings. **Strongest contribution from this paper to our topic.** |
| **Cognitive division of labor** | **Yes (central, as centaur/cyborg)** | Two-mode typology of how cognitive work is split with AI at task vs. sub-task granularity. **Second-strongest contribution.** |
| **Knowledge flow** | **No** | Knowledge transfer between expert and AI (tacit/explicit, bidirectional flow) is not in their frame. Output quality is measured; knowledge transmission is not. |
| **Sustained / longitudinal collaboration** | **No — explicit gap** | One-shot experimental session. **This is the single biggest gap relative to our topic's "co-evolution over sustained collaboration" framing.** |
| **Niche construction theory (Odling-Smee)** | **No** | Not invoked. Their theoretical move is the jagged-frontier construct, not coevolutionary niche construction. |

---

## 10. Implications for framing decision (A / B / C)

Dell'Acqua et al. is a **foundational empirical anchor** for our review, but it explicitly **does not** cover the longitudinal / coevolutionary axis of our topic. This shapes the A/B/C decision as follows:

### What Dell'Acqua gives us (regardless of path)
- A canonical empirical reference for **trust calibration** ("mis-calibrated trust", "falling asleep at the wheel").
- A canonical empirical reference for **cognitive division of labor** (centaur/cyborg typology).
- A canonical task-level performance gradient (inside vs. outside the frontier).
- An enterprise-flavored domain (consulting) and a high-prestige publication venue we can cite for legitimacy.

### What Dell'Acqua does NOT give us
- Sustained / longitudinal dynamics. One-shot only.
- Knowledge flow between expert and AI as a phenomenon (not measured).
- Embedded workflow agents (their AI = raw GPT-4, not Copilot-class).
- A theoretical framework for *coevolution*. They build a static-snapshot construct ("jagged frontier"), not a dynamic-change framework.

### Path verdict

- **Path A (synthesis of lenses 2+3+4)**: Dell'Acqua is the strongest single empirical pillar. A synthesis path leans heavily on this paper plus Brynjolfsson and Dillon. But the static, one-shot, raw-GPT-4, individual-task design means a pure synthesis would inherit Dell'Acqua's blind spots — exactly the axes (sustained, embedded, coevolutionary) our title foregrounds. **Path A under-uses our title's verbs.**
- **Path B (niche-construction spine)**: Dell'Acqua's gaps map almost perfectly onto where niche construction adds value — temporal dynamics, mutual reshaping, sustained collaboration. Dell'Acqua becomes the *static cross-section* that a niche-construction lens then makes longitudinal. **Path B is reinforced.**
- **Path C (activity theory + niche construction hybrid)**: Centaur/cyborg modes are essentially descriptions of activity-theoretic mediation structures (different ways the AI tool mediates the subject-object relation). This paper gives Path C empirical grounding for the activity-theory side as well. **Path C is reinforced.**

**Net effect on framing decision**: Dell'Acqua reinforces the same conclusion the Pedreschi map produced — paths B and C remain attractive, path A is unnecessarily timid. Dell'Acqua doesn't occupy our coevolutionary cell; it provides the empirical baseline against which we will argue that coevolution and sustained collaboration are under-theorized.

### Specific paragraphs Dell'Acqua should support in our review

1. **Introduction / motivation**: cite as evidence that AI effects on knowledge work are real, substantial, and non-uniform — but that the literature has not yet asked what happens over time.
2. **Trust calibration section** (lens 2 / mechanism 1 of our title): primary empirical reference.
3. **Cognitive division of labor section** (lens 3 / mechanism 2 of our title): primary empirical reference for the centaur/cyborg distinction.
4. **Gap argument**: this is the canonical "the field has measured one-shot productivity, not sustained co-evolution" reference. Useful for framing the contribution.

---

## Adjacent papers surfaced while reading Dell'Acqua

- **Randazzo, Lifshitz-Assaf, Kellogg, Dell'Acqua, Mollick, Candelon, Lakhani — "Cyborgs, Centaurs and Self-Automators: The Three Modes of Human-GenAI Knowledge Work and Their Implications for Skilling and the Future of Expertise"** (SSRN 4921696, HBS WP 26-036, 2025). Direct follow-up. Adds a third mode ("self-automator") and explicitly frames skilling and expertise. **Add to candidate pool — almost certainly relevant.**
- **Randazzo, Joshi, Kellogg, Lifshitz, Dell'Acqua, Lakhani — "GenAI as a Power Persuader: How Professionals Get Persuasion Bombed When They Attempt to Validate LLMs"** (HBS WP 26-021). Extends trust calibration mechanism. **Add to candidate pool.**
- **Mollick, E. — "Centaurs and Cyborgs on the Jagged Frontier"** (oneusefulthing.org). Companion essay; primary source for the centaur/cyborg verbatim definitions.
- **BCG — "How People Create and Destroy Value with Generative AI"** (2023). Industry-side write-up of the same study. Useful for triangulation.

---

## Open follow-ups for Stage 2 continuation

1. Read the **Randazzo et al. "Cyborgs, Centaurs and Self-Automators"** follow-up paper — likely materially extends Dell'Acqua on our axes (skilling = sustained; three modes = division of labor).
2. Read the **"Persuasion Bombing"** working paper — directly extends the trust-calibration mechanism.
3. Cross-reference Dell'Acqua's centaur/cyborg taxonomy with activity theory (lens 5 round-2) — they appear isomorphic and may strengthen Path C.
4. Verify the limitations / future-work section against the published Org Sci PDF when access is available — the snippets-only provenance of section 8 is the weakest part of this map.
