# Module 7 — Exercises

**Status:** **`TEACHING CONTENT IN DEVELOPMENT — T7-E PENDING CHATGPT
GOVERNANCE REVIEW`**

**`TEACHING MATERIAL — NOT TRIVIRON GOVERNANCE`**

Practice and self-assessment for the developed slides. **Exercises exist for
Slides 1–8 (`E1`–`E14` for Slides 1–3, `ACCEPTED after T7-D-R`; `E15`–`E29`
for Slides 4–8, added in `T7-E`). Slides 9–14 are `NOT YET DEVELOPED` and have
no exercises.** The count is coverage-driven, not targeted.

**No exercise asks the learner to invent a Triviron answer**, and no expected
answer contains one.

---

## Slide 1 exercises — reference implementation and roadmap position

### E1

- **Prompt:** A colleague says: *"So in Module 7 we write the Triviron BEP."*
  Correct the statement precisely.
- **Expected reasoning / answer:** Module 7 develops a **translation
  framework** that supports the *future* development of a project-specific
  Triviron BEP. The framework is not the BEP; no Triviron BEP exists in this
  programme, and no project appointment may be claimed.
- **Basis:** Module 7 `README.md` §1–§2; outline Slide 1.
- **Misconception detected:** Framework confused with target artefact
  (`M7-S11`).

### E2

- **Prompt:** Why does Module 7 come after Module 6 rather than directly after
  Module 1?
- **Expected reasoning / answer:** Translation needs the full reference
  implementation first: what a BEP is (1), roles and authority (2), the
  standards frame (3), CDE states (4), allocation and delivery planning (5),
  and coordination/assurance (6). Module 7 converts *all* of that into
  questions and evidence requirements — it cannot translate what has not yet
  been understood.
- **Basis:** `../roadmap.md` module sequence; outline Slide 1.
- **Misconception detected:** Translation treated as independent of the
  reference material it translates.

### E3

- **Prompt:** Name the two things Slide 1 says about Harrismith's status in
  this programme, and the one thing it deliberately does not say.
- **Expected reasoning / answer:** It says Harrismith is the completed worked
  example (Modules 1–6) and the source of reference patterns for Module 7. It
  does not say — and must not say — that a Triviron project exists or that
  the programme is producing Triviron governance.
- **Basis:** Outline Slide 1 fields 6 and 11.
- **Misconception detected:** Roadmap position read as project reality
  (`M7-S10`).

## Slide 2 exercises — method transfers, answers do not

### E4

- **Prompt:** Classify each item as *may transfer as method* or *does not
  transfer as an answer*: (a) "check and authorise are different acts";
  (b) the twelve interface checks; (c) "every absence is typed"; (d) the
  `CI-07` identifier; (e) the four-area CDE topology; (f) "allocation is not
  performance".
- **Expected reasoning / answer:** Method: (a), (c), (f) — distinctions and
  discipline. Not transferable as answers: (b), (d), (e) — populated
  Harrismith values and arrangements.
- **Basis:** Module 7 `README.md` §6; outline Slide 2.
- **Misconception detected:** Values smuggled across as "obviously
  reasonable" defaults (`M7-S02`, `M7-S05`).

### E5

- **Prompt:** *"Harrismith's tolerances are all `TBD`, so Triviron's
  tolerances start as `TBD` too."* What is wrong with this sentence?
- **Expected reasoning / answer:** Even a status does not transfer. Harrismith's
  `TBD` records deferrals *within Harrismith's established check scope*. No
  Triviron check scope has been established **in this programme**, so there is
  nothing yet for a `TBD` to sit inside — the Triviron position is
  `NOT YET ESTABLISHED`, pending evidence and decisions. Copying the status
  would silently copy the scope.
- **Basis:** Register `TDR-011` fields 5–6; schema §4 (`TBD` requires an
  established scope).
- **Misconception detected:** Status values treated as scope-free and
  transferable (`M7-S06`, `M7-S13`).

### E6

- **Prompt:** The Slide 2 takeaway — *"A reference implementation gives us
  better questions. It does not give us another project's answers."* — is
  labelled teaching synthesis. What is the accepted controlled formulation
  behind it, and why does the label matter?
- **Expected reasoning / answer:** The accepted architecture states:
  *Harrismith supplies reference patterns, questions and governance
  distinctions. It does not supply Triviron's populated answers.* The label
  matters because teaching wording explains but never overrides accepted or
  controlled wording — synthesis must be traceable to what it synthesises.
- **Basis:** Module 7 `README.md` §4; outline Slide 2 field 8.
- **Misconception detected:** Teaching phrasing mistaken for source evidence.

### E7

- **Prompt:** Why does Slide 2 forbid an arrow between its two columns?
- **Expected reasoning / answer:** An arrow from a Harrismith item toward a
  Triviron question or answer is a recommendation drawn as a line — it would
  depict exactly the value-transfer the module prohibits. The accepted source
  map allows no `HARRISMITH VALUE → TRIVIRON VALUE` edge anywhere.
- **Basis:** `source-map.md` §1 and §4; outline Slide 2 field 11.
- **Misconception detected:** Layout treated as neutral when it asserts
  (`M7-S15`).

### E8

- **Prompt:** Does the right-hand column of Slide 2 tell you anything about
  how the real Triviron organisation works?
- **Expected reasoning / answer:** No. It lists what this programme refuses to
  *transfer*. It makes no claim about what Triviron actually does or has —
  that would require controlled Triviron evidence, of which none is currently
  identified.
- **Basis:** Outline Slide 2 field 7; `source-inventory.md` §7.
- **Misconception detected:** An exclusion list read as an existence claim
  (`M7-S12`).

## Slide 3 exercises — the chain and the STOP

### E9

- **Prompt:** Recite the translation chain in order and place the STOP rule.
- **Expected reasoning / answer:** Reference pattern → translation question →
  Triviron evidence required → evidence available / missing → **STOP RULE** →
  candidate decision → authority required → recorded status → candidate
  destination. The STOP sits immediately **before** candidate decision.
- **Basis:** `translation-framework.md` §1; outline Slide 3.
- **Misconception detected:** STOP remembered as an end-of-chain check rather
  than a gate before candidacy.

### E10

- **Prompt:** State the STOP rule and its reason in your own words.
- **Expected reasoning / answer:** No Triviron candidate decision may be
  derived solely from a populated Harrismith value — because a Harrismith
  value is evidence *about Harrismith*, not evidence that Triviron should
  adopt the same value. Candidacy needs an independently established Triviron
  basis plus an expressly authorised proposal stage.
- **Basis:** `translation-framework.md` §2.5; schema §7.
- **Misconception detected:** "It worked there" treated as evidence for
  "adopt it here" (`M7-S15`).

### E11

- **Prompt:** The register shows evidence available `NONE IDENTIFIED` in all
  21 rows. A reader concludes: *"So Triviron has no BIM arrangements at
  all."* Diagnose the error.
- **Expected reasoning / answer:** `NONE IDENTIFIED` is a census/evidence
  position: no controlled Triviron source has been identified *in this
  repository*. It is not `NONE EXISTS` and proves nothing about real-world
  Triviron arrangements. The correct status for such matters is
  `NOT YET ESTABLISHED`, not `NOT ESTABLISHED`.
- **Basis:** Register header and §10; schema §4; `source-inventory.md` §7.
- **Misconception detected:** Absence of identified evidence inflated into
  evidence of absence (`M7-S12`, `M7-S13`).

### E12

- **Prompt:** Distinguish *Triviron evidence required* (chain step 3) from
  *Triviron evidence currently available* (chain step 4), using `TDR-020` as
  the worked case.
- **Expected reasoning / answer:** Step 3 names the **kind** of controlled
  source that would be needed — for `TDR-020`, an acceptance/publication
  authority decision or appointment information. Step 4 records what class F
  actually holds against that requirement — currently `NONE IDENTIFIED`. The
  requirement existing does not make the evidence exist.
- **Basis:** Register `TDR-020` fields 7–9; `translation-framework.md`
  §2.3–§2.4.
- **Misconception detected:** A named requirement mistaken for satisfied
  evidence.

### E13

- **Prompt:** Every register row currently ends in typed absences
  (`NONE IDENTIFIED`, `NOT YET ESTABLISHED`, `NOT POPULATED — PROPOSAL STAGE
  NOT AUTHORISED`). Is that a failure of the method?
- **Expected reasoning / answer:** No — it is the method succeeding. The chain
  makes every unknown visible and typed instead of filled by guesswork; the
  zeros are the controlled state of work that has not yet earned its
  answers. Inventing content to look complete is the failure mode.
- **Basis:** Outline Slide 3 field 11; register §10; Module 7 `README.md` §9
  (`M7-S18`).
- **Misconception detected:** Typed absence read as incompleteness to be
  papered over.

### E14

- **Prompt:** A future increment identifies a genuine controlled Triviron
  organisation chart. Which chain steps change for `TDR-004`, and which do
  not change automatically?
- **Expected reasoning / answer:** **Step 3 — Triviron evidence required —
  does not change.** The recorded requirement stands unless the new evidence
  shows the requirement itself was incorrectly framed. **Step 4 — evidence
  available / missing — changes**: the controlled organisation chart, if
  genuinely admitted through a governed route with its status and authority
  recorded, becomes identified evidence, so `NONE IDENTIFIED` no longer
  describes the whole row's evidence position. But `TDR-004` requires more
  than a chart — appointment/contract information and a responsibility /
  authority decision allocating the coordination function — so **those gaps
  stay explicitly recorded as missing**, and the row may well remain
  `EVIDENCE REQUIRED` while the evidence needed to responsibly frame a
  candidate remains incomplete. The **STOP rule still applies**: no candidate
  decision follows automatically, and no decision authority or owner follows
  automatically. A controlled factual source establishes only the facts it
  actually supports — a chart does not allocate the coordination function,
  identify an authority or owner, or authorise any governed arrangement.
  **Evidence arrival does not itself decide.**
- **Basis:** `translation-framework.md` §2.3–§2.5; schema §5, §7; register
  `TDR-004` fields 7–13; `source-map.md` §4 ("informs — evidence does not
  itself decide").
- **Misconception detected:** Evidence arrival treated as decision authority
  (`M7-S16`, `M7-S17`).

---

## Slide 4 exercises — the decision backlog

### E15

- **Prompt:** A reviewer skims the register and says: *"Twenty-one populated
  rows — so the Triviron BEP is about a third written."* Correct them.
- **Expected reasoning / answer:** The register is an evidence-and-decision
  **backlog**, not BEP content. A populated row records the translation
  problem — pattern, question, evidence required, typed gaps — never a
  Triviron answer. Zero candidate decisions exist, so zero BEP content exists;
  the register's own reconciliation says its existence makes the future BEP
  neither complete nor partially complete.
- **Basis:** Register §1, §10; outline Slide 4.
- **Misconception detected:** Backlog mistaken for populated BEP (`M7-S11`).

### E16

- **Prompt:** The five translation classifications are `METHOD`,
  `EVIDENCE REQUIRED`, `DECISION REQUIRED`, `PROPOSAL`, `ESTABLISHED`. Is this
  a maturity ladder every row climbs over time?
- **Expected reasoning / answer:** No. Progression is neither automatic nor
  inevitable: `DECISION REQUIRED` needs identified evidence, `PROPOSAL` needs
  an expressly authorised proposal stage, `ESTABLISHED` needs a controlled
  Triviron source or authorised decision. A row may legitimately remain
  `METHOD` or `EVIDENCE REQUIRED` indefinitely — the classification records
  the current basis, not a schedule.
- **Basis:** Schema §3; outline Slide 4 field 7.
- **Misconception detected:** Classification read as a timetable
  (`M7-S18`).

### E17

- **Prompt:** Why does Slide 4 call zero candidate decisions "controlled
  progress, not failure"?
- **Expected reasoning / answer:** The module's method makes unknowns visible
  and typed instead of guessed. With zero identified controlled Triviron
  evidence, the only defensible register state is questions with typed
  absences. Producing candidate answers now would violate the STOP rule —
  that would be the failure. The zeros describe the programme's evidence
  position only, never real-world Triviron arrangements.
- **Basis:** Register §9–§10; `translation-framework.md` §2.5; outline Slide 4.
- **Misconception detected:** Progress equated with populated answers
  (`M7-S12`, `M7-S15`).

## Slide 5 exercises — Domain 1: coordination governance

### E18

- **Prompt:** *"Our clash-detection tool defines what coordination is for."*
  Diagnose against `TDR-001`.
- **Expected reasoning / answer:** Software capability is not coordination
  purpose. `TDR-001` requires the purpose to be explicitly governed and
  stated in a controlled document — evidenced by appointment/brief/requirement
  material and a governance decision. A tool can execute checks; it cannot
  supply the project's reason for coordinating.
- **Basis:** Register `TDR-001` fields 5, 7; outline Slide 5.
- **Misconception detected:** Purpose delegated to software (`M7-S15`).

### E19

- **Prompt:** Harrismith's BEP expressly defers coordination detail to its
  coordination strategy, and states that reference does not constitute
  approval. What transfers to `TDR-002`, and what does not?
- **Expected reasoning / answer:** Transfers as method: a governing document
  must be identified; it may expressly defer detail to a subordinate resource
  that declares its own status; referencing a document never approves it.
  Does not transfer: Harrismith's document set, the BEP/strategy split itself,
  and any document title or architecture — Triviron's document architecture
  is its own future decision.
- **Basis:** Register `TDR-002` fields 5–6; BEP §8.13, §13.6 pattern.
- **Misconception detected:** Governing document confused with referenced
  supporting document; architecture inherited by habit (`M7-S14`).

### E20

- **Prompt:** *"Coordination runs fortnightly — that's just how the software
  schedules it."* What does `TDR-003` say about this?
- **Expected reasoning / answer:** A cycle trigger is a governance decision —
  event basis or frequency chosen and recorded by the project — not a
  software rhythm or default schedule. And what constitutes *one* cycle must
  itself be defined as a governed sequence. Both remain
  `NOT YET ESTABLISHED` for Triviron, with no frequency imported from
  anywhere.
- **Basis:** Register `TDR-003` fields 5–6; outline Slide 5.
- **Misconception detected:** Cycle trigger mistaken for software frequency
  (`M7-S15`).

## Slide 6 exercises — Domain 2: roles and authority

### E21

- **Prompt:** Distinguish the three objects in `TDR-004`: the coordination
  *function*, its *allocation*, and its *holder*. Which can exist without the
  others?
- **Expected reasoning / answer:** A function is defined work (coordinating);
  an allocation assigns that function within a governance structure; a holder
  is the person/organisation filling it. A function can be defined with no
  allocation; an allocation can exist with the holder recorded as a typed
  absence. None may be inferred from a job title or login — and naming a
  holder without evidence is prohibited.
- **Basis:** Register `TDR-004` fields 5–6, 12–13; outline Slide 6.
- **Misconception detected:** Function, allocation and holder collapsed into
  one (`M7-S04`, `M7-S16`).

### E22

- **Prompt:** During a future cycle, who fixes a wall-services clash — the
  coordinator or the originating team — and what does a matrix cell about
  that allocation prove?
- **Expected reasoning / answer:** As method: the coordinating function
  manages the process; the originating team owns the technical response in
  its own working environment — coordination transfers no technical
  authorship. And an allocation cell proves only responsibility assignment,
  never that the activity occurred: allocation is not performance. For
  Triviron both the team structure and the allocation are
  `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-005` field 5; outline Slide 6 field 7.
- **Misconception detected:** Coordinator as designer; allocation read as
  performance evidence (`M7-S01`).

### E23

- **Prompt:** `TDR-006` contains two separate decisions, not one. Name them,
  and explain why Harrismith cannot settle either for Triviron.
- **Expected reasoning / answer:** (1) *Who* verifies — the verification
  function and its allocation; (2) *when* verification is required — the
  mandatoriness/trigger decision. Harrismith itself carries an unresolved
  variance ("may verify" vs a defined step) and records no universal
  verifier — a variance to be carried visibly, not resolved by convenience,
  and certainly not resolved on Triviron's behalf.
- **Basis:** Register `TDR-006` fields 4–6; outline Slide 6.
- **Misconception detected:** Verification function and verification trigger
  merged; a source variance quietly harmonised (`M7-S13`, `M7-S16`).

## Slide 7 exercises — Domain 3: inputs and federation

### E24

- **Prompt:** A model is visible in the shared environment. Is it a
  coordination input?
- **Expected reasoning / answer:** Not by visibility. Cycle inputs are a
  governed, registered set with recorded originators, and readiness must be
  established before federation: visible ≠ selected ≠ suitable ≠ ready.
  Consuming an input for coordination also changes no information state.
  Which containers qualify, and what "ready" means, are Triviron decisions —
  `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-007`–`TDR-008` field 5; outline Slide 7.
- **Misconception detected:** File availability mistaken for input readiness
  (`M7-S02`).

### E25

- **Prompt:** Complete and justify: federation is not ______, not ______, and
  not ______.
- **Expected reasoning / answer:** Not authorship transfer, not approval, not
  publication. Federation is a lens — it changes what can be seen together,
  while authorship, technical ownership and deliverable status stay with the
  originator. Approval and publication are separate governance acts with
  their own authorities, and software federation capability establishes no
  project governance.
- **Basis:** Register `TDR-009` field 5; outline Slide 7 field 7.
- **Misconception detected:** Federation read as responsibility, approval or
  status transfer (`M7-S03`).

### E26

- **Prompt:** `TDR-009` is classified `METHOD`. Does that mean Triviron has
  adopted the federation-responsibility rule?
- **Expected reasoning / answer:** No. `METHOD` records that a structural
  distinction is *reusable* — nothing more. Adoption would need a controlled
  Triviron coordination requirement or governance decision (the row's field 7
  evidence), which is `NONE IDENTIFIED`. Reusability is not adoption
  evidence, and the row frames no candidate decision.
- **Basis:** Register `TDR-009` fields 7–10, 20; schema §3.
- **Misconception detected:** A `METHOD` classification read as an
  established Triviron position (`M7-S18`).

## Slide 8 exercises — Domain 4: checks and tolerances

### E27

- **Prompt:** *"Start Triviron with the twelve Harrismith checks and adjust
  later."* Why does the register prohibit this, and what is the governed
  alternative?
- **Expected reasoning / answer:** The twelve checks, their `CI-`
  identifiers and the six types are populated Harrismith values — expressly
  excluded from transfer, even as a starter set. The governed alternative:
  identify *this project's* interfaces from its own discipline structure,
  then select check types against them as a governed choice recorded in a
  controlled artefact. The interface matrix is a controlled artefact, not a
  software output.
- **Basis:** Register `TDR-010` fields 5–6, 20; outline Slide 8.
- **Misconception detected:** Inherited check set replacing interface
  identification (`M7-S05`, `M7-S15`).

### E28

- **Prompt:** Why is a Triviron tolerance today `NOT YET ESTABLISHED` rather
  than `TBD` — when Harrismith's own tolerances are `TBD`?
- **Expected reasoning / answer:** `TBD` marks an intentional deferral
  *inside an established governance scope*: Harrismith has an established
  check scope, so its per-check deferrals are `TBD`. No Triviron check scope
  has been established in this programme, so there is no scope to defer
  within — the position is `NOT YET ESTABLISHED`. And in neither case is a
  software default a project tolerance: a tolerance is a governed decision
  recorded per check.
- **Basis:** Register `TDR-011` fields 5–6; schema §4; outline Slide 8.
- **Misconception detected:** `TBD` used as a scope-free blank; defaults
  standing in for decisions (`M7-S06`, `M7-S13`).

### E29

- **Prompt:** The project's senior technologist configures the clash tool.
  May the register record them as the check/tolerance approval authority?
- **Expected reasoning / answer:** No. Authority fields accept only an exact
  source-grounded Triviron value or a typed absence — never an inference from
  a job title, software permission or tool role. Configuring a tool is not
  approving a governed check. Until a controlled responsibility/authority
  decision is identified, `TDR-012` records the required authority *kind*
  with holder `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-012` fields 5, 12; schema §5.
- **Misconception detected:** Approval authority inferred from role or tool
  access (`M7-S16`, `M7-S17`).

---

## Coverage map

| Required distinction | Exercises |
|---|---|
| Reference implementation vs target governance | E1, E2, E3 |
| Transferable method vs non-transferable populated answer | E4, E5, E6, E7 |
| Evidence requirement vs evidence currently identified | E12, E14 |
| Harrismith fact vs Triviron fact | E5, E8, E10 |
| Typed absence vs invented content | E11, E13 |
| STOP before candidate decision | E9, E10, E14 |

**Slides 4–8 coverage (T7-E):**

| Required distinction | Exercises |
|---|---|
| Backlog vs populated BEP | E15 |
| Classification vs answer | E16, E26 |
| Coordination purpose vs software capability | E18 |
| Governing document vs referenced supporting document | E19 |
| Cycle trigger vs software frequency | E20 |
| Function vs holder | E21 |
| Coordination vs technical ownership | E22 |
| Allocation vs performance | E22 |
| Verification function vs verification trigger | E23 |
| Input readiness vs mere file availability | E24 |
| Federation vs authorship/approval/status transfer | E25 |
| Interface identification vs inherited check set | E27 |
| Project tolerance vs software default | E28 |
| `TBD` vs `NOT YET ESTABLISHED` | E28 |
| Approval authority vs assumed job title | E29 |
| Zeros vs real-world nonexistence | E17 |

## Status

| Field | Value |
|---|---|
| Exercises | **29** — `E1`–`E14` (Slides 1–3, `ACCEPTED after T7-D-R`) · `E15`–`E29` (Slides 4–8, T7-E); coverage-driven |
| Slides 9–14 exercises | **None — `NOT YET DEVELOPED`** |
| Triviron answers requested or supplied | **None** |
| Publication automation | **`PAUSED`** |
