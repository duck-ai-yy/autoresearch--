# Boundary Map — Brynjolfsson, Li & Raymond (2025) "Generative AI at Work"

## 1. Full citation

> Brynjolfsson, E., Li, D., & Raymond, L. (2025). Generative AI at Work. *The Quarterly Journal of Economics*, 140(2), 889–942. https://doi.org/10.1093/qje/qjae044
>
> - NBER WP 31161 (April 2023, revised). https://www.nber.org/papers/w31161
> - arXiv:2304.11771. https://arxiv.org/abs/2304.11771
> - SSRN 4426942.

**Note on source provenance**: WebFetch was blocked (HTTP 403) on all PDF and HTML routes (danielle.li, arxiv, qje, nber). This boundary map is assembled from indexed search-engine snippets of the published QJE version, the NBER WP, and the arxiv preprint, plus secondary commentary (MIT Sloan, Stanford GSB, ResearchGate). All direct quotes below appear in multiple independent snippets; section-level descriptions are paraphrased. **Flag for human verification** before quoting verbatim in final write-up.

---

## 2. Key term definitions (verbatim where retrievable)

- **The AI tool studied**: "a generative AI-based conversational assistant" — "built on a recent version of the Generative Pre-trained Transformer (GPT) family of large language models developed by OpenAI." It "monitors customer chats and provides agents with real-time suggestions for how to respond." Designed to augment agents, "who remain responsible for the conversation and are free to ignore or edit the AI's suggestions."
- **Productivity**: measured as "issues resolved per hour" (resolutions per hour, RPH). Quality measured via customer sentiment (NLP on chat transcripts), resolution rate, handle time, escalation rate.
- **Tacit knowledge mechanism (the paper's interpretive frame)**: GPT models "can implicitly identify characteristics or patterns of behavior that distinguish high and low performers, including subtleties rooted in tacit knowledge"; the AI "disseminates the potentially tacit knowledge of more able workers and helps newer workers move down the experience curve."
- **Adherence**: degree to which an agent follows the AI's suggested response. Higher adherence is associated with larger productivity gains, except in the highest-skill stratum, where high adherence marginally reduces quality.

---

## 3. AI systems in their scope — are embedded enterprise workflow agents IN or OUT?

**IN — and they study exactly an exemplar of this class.**

The AI here is an **enterprise, in-workflow, single-agent** real-time copilot:
- deployed inside a customer-support workflow at a Fortune 500 enterprise-software company,
- built on GPT (so generative, not classical ML),
- single-agent assistant (not multi-agent),
- always-on, sits beside the agent in the chat tool,
- non-autonomous (human keeps decision rights, may ignore).

This is **directly inside our locked scope** ("Copilot, Glean, Harvey, Hebbia, enterprise in-house"). The studied product is best classed as an enterprise in-house copilot for support agents — closest analog in our scope is the Microsoft / GitHub Copilot family or in-house contact-center copilots (Salesforce Einstein Copilot, Cresta, ASAPP).

Out of scope for them: multi-agent swarms, autonomous agents, consumer chatbots.

---

## 4. Humans in their scope — are domain experts in enterprise settings IN or OUT?

**IN, but with one caveat that matters for our framing.**

- **In-scope axis**: they study *professional knowledge workers in an enterprise* (customer-support agents performing technical product support for business-process software). The work is non-routine, dialog-based, requires diagnostic reasoning over a product knowledge base.
- **Caveat — "domain expert" stratification**: their sample spans the *full skill distribution*, from novices to the top decile of experienced agents. The headline finding is about *heterogeneity by skill*. So they cover domain experts but their unit of analysis is the worker × tenure × baseline-skill cell, not the expert qua expert. Pure domain experts (top-decile, high-tenure) are a *subgroup* in their data, and the subgroup where AI delivers near-zero (or slightly negative) value.

Whether "customer-support agents" count as "domain experts in enterprise work" in our title is a judgment call. They are domain-trained workers performing skilled cognitive work; they are not credentialed professionals like lawyers (Harvey) or doctors. **For our purposes, treat as adjacent enterprise expertise** — a useful endpoint of the expertise spectrum.

---

## 5. Theoretical framework / mechanism

Two stacked frames:

**(a) Labor economics — heterogeneous treatment effects of a general-purpose technology (GPT in both senses):**
- The classical "experience curve" / "learning curve" frame: AI compresses learning time.
- Skill-biased technical change inverted: this technology is *skill-leveling* (or even skill-compressing) rather than skill-biased. The 15% average gain hides a roughly 34% gain for the bottom skill quintile and ~0% for the top quintile.

**(b) Knowledge-management / tacit-knowledge frame (their interpretive mechanism):**
- High-performer behaviors contain tacit knowledge that pre-AI was un-codifiable and thus un-transferable.
- A generative model trained on the firm's chat history implicitly extracts these patterns.
- Real-time suggestions then push that distilled tacit knowledge back to the lower-skilled worker at the moment of action.
- This is a **codification-then-redistribution** story (Polanyi / Nonaka in spirit, though the paper does not cite them by name in the snippets I saw).

**No explicit theory of trust, co-evolution, niche construction, distributed cognition, or activity theory.** The paper is firmly inside labor-econ + KM mechanisms.

---

## 6. Methodology

- **Setting**: a Fortune 500 enterprise software firm; customer-support function.
- **Sample**: 5,172–5,179 customer-support agents (the count varies slightly across versions — QJE final says 5,179).
- **Data**: chat-level transcripts + agent-level outcomes (RPH, handle time, resolution rate, customer sentiment, retention).
- **Identification**: staggered rollout of the AI tool. Difference-in-differences with cohort/staggered-adoption robust estimators (e.g., Callaway-Sant'Anna or similar; they discuss heterogeneous treatment-effect bias explicitly).
- **Time horizon**: rollout primarily fall 2020 through 2021. AI access share grew from ~5% (Oct 2020) to ~70% (Jan 2021). Panel extends through 2021. **Observation window per worker ≈ months, not years.** This matters for our "sustained" criterion: they observe *medium-term* effects but not multi-year co-evolution.
- **Outcome dimensions**: productivity (RPH), quality (resolution + sentiment), worker outcomes (retention), behavioral (AI adherence).
- **No qualitative / ethnographic complement.** Pure observational quantitative.

---

## 7. Their key claims (top 5)

1. **Average productivity gain ≈ 14–15%** (RPH) from AI assistance, identified via staggered rollout.
2. **Skill-leveling effect**: gains concentrate among novice and low-skill workers (~34% for the bottom skill stratum); near-zero or slightly negative quality effect for top performers. AI compresses the experience curve — "agents with two months of experience perform like agents with six months without AI."
3. **Mechanism = tacit-knowledge dissemination**: the model implicitly encodes the behaviors of high performers and redistributes them in real time to lower performers; this is offered as the best explanation of the heterogeneity pattern.
4. **Spillover outcomes**: improved customer sentiment, higher employee retention, suggestive evidence of worker learning (skill transfer from AI to human over time — not only AI substitution).
5. **Caveats / second-order concerns**: top workers' adherence to AI suggestions rises even when those suggestions marginally hurt quality; settings with rapidly changing products may see different gains; long-run skill, wage, and job-design effects are not identified.

---

## 8. Their stated gaps / future work (from snippets of the discussion / conclusion)

- **External validity**: "as a general-purpose technology, generative AI may not generalize across all firms and production processes." Their setting had a relatively stable product line; effects could differ in fast-changing environments.
- **Long-run outcomes not identified**: skill demand, job design, wages, customer demand, and re-design of the support function itself are not in the panel window.
- **Decision-quality concern with hybrid human-AI**: cite earlier evidence that human-AI hybrid decisions can underperform either alone. Raises the open question of *whether workers can distinguish good from bad AI suggestions* — i.e., a **calibration/trust gap** they flag but do not study.
- **Model decay / training-data drift**: if top workers increasingly adhere to AI even when AI is marginally wrong, the labeled data going forward shifts toward AI-influenced behavior, potentially degrading future model iterations. **This is an explicit feedback-loop / co-evolution flag in their own discussion.**
- **Complementary investments**: they note efficacy depends on workplace structures, skill development, business-process redesign — not studied here.

---

## 9. Coverage check vs. our topic

| Concept in our title | Covered by Brynjolfsson et al.? | Notes |
|---|---|---|
| **AI agents (embedded workflow)** | **Yes** | Their AI = exactly this class — single-agent, in-workflow, enterprise GPT copilot. |
| **Domain experts in enterprise** | **Partial** | Enterprise knowledge workers, full skill distribution. "Domain experts" appear as the top-decile subgroup, but they are not credentialed professionals. |
| **Trust calibration** | **Partial / flagged** | Not studied directly. They flag that top workers may over-adhere to AI even when suggestions are marginally wrong — a trust-miscalibration finding, but not theorized. |
| **Cognitive division of labor** | **Partial / implicit** | "Adherence" is a behavioral proxy for who drives the decision. They do not frame this as division of labor; they treat it as a control variable / mechanism check. No Hutchins, no function-allocation literature. |
| **Knowledge flow** | **Yes — central** | Tacit-knowledge dissemination is their headline mechanism. Direction = expert → AI training data → novice. **Mostly unidirectional in their frame**; novice → AI feedback loop is mentioned only as a future concern. |
| **Sustained / longitudinal collaboration** | **Partial** | Panel ≈ several months to ~1 year per worker. Medium-term, not multi-year. Co-evolutionary dynamics flagged in discussion (model decay, adherence drift) but not measured. |
| **Enterprise contexts** | **Yes** | Fortune 500 software firm, internal deployment. Cleanly in scope. |
| **Niche construction theory (Odling-Smee)** | **No** | Not invoked. No biological/coevolutionary framing at all. |
| **Co-evolution as theoretical lens** | **No (but the seeds are there)** | The discussion of model decay from adherence drift is *substantively* a coevolution finding — humans changing AI which changes humans — but they do not name it or theorize it. **Important opening for us.** |

---

## 10. Implications for framing decision (A / B / C)

This paper is a **load-bearing anchor** for our topic: it is the highest-citation, top-journal empirical study of exactly the class of AI agents and exactly the class of enterprise work that our title locks in. Whatever path we take, we cite it as foundational empirical evidence.

But it also leaves room — in ways that are different from Pedreschi's:

- **Pedreschi gives umbrella legitimacy** for "coevolution" framing but at the wrong scope (consumers × recommenders × societal).
- **Brynjolfsson gives the right scope** (enterprise × workflow agent × knowledge workers) but the wrong frame (labor-econ + KM, no coevolution theory, mostly unidirectional knowledge flow).

So together they triangulate our cell:

> **Whitespace = the right scope (Brynjolfsson's) with the right frame (Pedreschi's coevolution / our niche construction extension), tested over a longer horizon than Brynjolfsson's panel and at expertise levels above customer-support agents (lawyers, clinicians, SWEs).**

**Path implications:**

- **Path A (synthesis)**: Brynjolfsson is the empirical centerpiece — but a pure synthesis paper would mostly *restate* their findings plus Dell'Acqua and Dillon, with limited theoretical contribution. Path A becomes weak when so much of the empirical story is already told.
- **Path B (niche-construction spine)**: **Strongly de-blocked.** Brynjolfsson's own discussion of (a) tacit-knowledge codification flowing expert → AI → novice, (b) adherence drift changing the training distribution, and (c) model decay from human-altered behavior is *literally* niche construction logic in labor-econ language. We can re-read their findings through Odling-Smee's frame and extract a coevolutionary mechanism they describe but do not name. High-leverage move.
- **Path C (hybrid: activity theory + niche construction)**: Brynjolfsson does not engage activity theory; the support-agent setting is poorly suited to activity-theory's unit (collective object-oriented activity systems). Path C gains less from this paper than Path B does.

**Verdict from this anchor**: Brynjolfsson strengthens **Path B** specifically, because the paper's own unstated feedback loop (humans → AI training data → AI suggestions → humans → ...) is the niche-construction loop in our title. We can claim novelty by *naming and modeling* what Brynjolfsson empirically observed but framed only as KM dissemination.

---

## Notes for the broader project

- This paper's empirical findings (15% / 34% / skill-leveling / tacit-knowledge dissemination) are the **most-cited single result** in the entire workflow-AI literature. Any framing must engage with them.
- Their **trust / adherence finding is under-developed**: top workers over-adhere even when AI is marginally wrong. This is a calibration failure that maps directly onto our "trust" axis. A follow-up paper that explicitly studies trust calibration in this setting would be highly citable.
- Their **time horizon (~1 year)** is the same ceiling we keep hitting (Dillon Microsoft is similar). "Sustained" in our title may need to be operationalized as "≥ 12 months" rather than "multi-year," for empirical realism.
- The **adherence-drift / model-decay loop** they raise in the discussion is essentially our co-evolution mechanism. We should quote this passage directly when motivating Path B.
