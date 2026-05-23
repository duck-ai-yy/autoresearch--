# Decision Log (append-only)

Each entry: decision made, what was ruled out, rationale, downstream impact. Never edit past entries — append corrections as new entries instead.

---

## 2026-05-18 — Session 1

### D1. AI Agents = embedded-in-workflow agents
- **Decision**: scope limited to Copilot-class, Glean, Harvey, Hebbia, enterprise in-house agents.
- **Ruled out**: generic chat assistants (consumer ChatGPT), multi-agent / swarm systems, ML research agents.
- **Rationale**: user-specified narrowing ("嵌入工作流的 agent").
- **Impact**: Stage 1+ search queries include "copilot", "embedded", "enterprise"; exclude "ChatGPT consumer" and "agent swarm".

### D2. Divergent search first; no early framing commitment
- **Decision**: collect across 6 disciplinary lenses (sociomateriality, routines, joint cognitive systems, trust calibration, activity theory, niche construction) before picking a framing spine.
- **Ruled out**: picking a single theoretical lens upfront.
- **Rationale**: user wanted cross-disciplinary inspiration before commitment.
- **Impact**: Stage 1 ran all 6; framing locked at end of Stage 2.

### D3. Persistent multi-file scaffolding under `litreview/`
- **Decision**: README + AGENT + TOPIC + STATE + decisions + stage artifacts, plus root `CLAUDE.md` pointer.
- **Ruled out**: ad-hoc single-file note; merging methodology into the topic file.
- **Rationale**: user wants any future session to resume on the skeleton without re-deriving context.
- **Impact**: every session reads `STATE.md` first; every decision goes here; every stage gets its own artifact.

### D4. Don't touch `program.md` or ML autoresearch code on this branch
- **Decision**: leave `program.md`, `train.py`, `prepare.py` as-is.
- **Ruled out**: subsuming the original autoresearch agent program; renaming files.
- **Rationale**: branch name says "academic-accelerator-agent" but the user did not authorize replacing the existing ML workflow. The new workflow coexists.
- **Impact**: `litreview/AGENT.md` is the academic-accelerator entry point; `program.md` remains for ML autoresearch.

### D6. Pedreschi et al. (2025) does not occupy our cell; framing paths B and C de-blocked
- **Decision**: Pedreschi et al. is cited as terminology legitimization but is NOT the substantive competitor.
- **Ruled out**: framing path A (synthesis-only) is de-prioritized; treating Pedreschi as a direct competitor that closes the topic.
- **Rationale**: their scope = recommenders × consumers × societal-aggregate × preference shaping. Our scope = embedded workflow agents × domain experts × enterprise × cognitive collaboration. Three independent dimensions of separation. They also do NOT invoke niche construction theory by name — theoretical opening confirmed.
- **Caveat**: boundary map built from search snippets, not full text (403 on all routes). High-stakes claims flagged for re-verification if full text becomes accessible.
- **Impact**: framing decision now between paths B and C; Stage 2.b round-2 searches and remaining anchor maps will inform the final pick.

### D5. No root-level `CLAUDE.md` pointer; rely on `litreview/` directory discoverability
- **Decision**: orientation lives at `litreview/README.md`. No root pointer file.
- **Ruled out**: root `CLAUDE.md` (gitignored — launchers regenerate per-session, would be overwritten); modifying root `README.md` (upstream Karpathy file); top-of-`program.md` annotation (makes ML program branch-aware).
- **Rationale**: `.gitignore` includes `CLAUDE.md` and `AGENTS.md` because launchers own those files. Any non-launcher orientation needs a different name or location.
- **Impact**: a new Claude session is expected to (a) see `litreview/` in `ls`, (b) open `litreview/README.md`. If launcher-generated `CLAUDE.md` exists, it should be augmented to reference `litreview/` — but that augmentation is launcher-side, not committed here.
