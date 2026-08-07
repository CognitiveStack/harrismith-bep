# Module 7 — Exercises

**Status:** **`TEACHING CONTENT COMPLETE — T7-G PENDING CHATGPT GOVERNANCE
REVIEW`**

**`TEACHING MATERIAL — NOT TRIVIRON GOVERNANCE`**

Practice and self-assessment for the developed slides. **Exercises exist for
all fourteen slides** (`E1`–`E14` for Slides 1–3, `ACCEPTED after T7-D-R`;
`E15`–`E29` for Slides 4–8, `ACCEPTED after T7-E-R`; `E30`–`E45` for Slides
9–12, `ACCEPTED after T7-F-R`; `E46`–`E55` for Slides 13–14, added in
`T7-G`). The count is coverage-driven, not targeted.

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
  stated in a controlled document — evidenced by appointment/contract
  information, client / appointing-party information requirements, a project
  brief, and **a coordination requirement or governance decision record**
  stating the project's coordination purpose (either route can carry the
  purpose statement). A tool can execute checks; it cannot supply the
  project's reason for coordinating.
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

- **Prompt:** Suppose a future controlled source establishes that a project
  senior technologist configures the clash tool. May that fact alone allow
  the register to record that person as the check/tolerance approval
  authority?
- **Expected reasoning / answer:** No. That controlled source would establish
  only the fact it supports — that the person configures the tool — and
  nothing more. Authority fields accept only an exact source-grounded
  Triviron value or a typed absence — never an inference from a job title,
  software permission or tool role. Configuring a tool is not approving a
  governed check, and no authority holder is inferred automatically. Until a
  controlled responsibility/authority decision is identified, `TDR-012`
  records the required authority *kind* with holder `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-012` fields 5, 12; schema §5.
- **Misconception detected:** Approval authority inferred from role or tool
  access (`M7-S16`, `M7-S17`).

---

## Slide 9 exercises — Domain 5: findings, Issues and statuses

### E30

- **Prompt:** State the structural relationship between *finding*, *clash*
  and *Issue* that the accepted register records — and state what that
  relationship does **not** establish for Triviron.
- **Expected reasoning / answer:** A clash is **one kind of finding**; an
  Issue is a **governed record**; and **not every finding becomes an
  Issue** — that is the reusable structural distinction `TDR-013` records.
  What it does not establish: the governed Triviron definitions and the
  finding → Issue boundary are `NOT YET ESTABLISHED` in this programme, and
  the distinction is **not** a fuller taxonomy — it does not classify
  findings or clashes as inherently non-governance objects, and it does not
  say where any project must draw its lines.
- **Basis:** Register `TDR-013` fields 5–6, 18; outline Slide 9.
- **Misconception detected:** The three-term distinction inflated into a
  complete taxonomy or an adopted definition (`M7-S07`, `M7-S18`).

### E31

- **Prompt:** A clash tool reports 400 clashes. How many Issues exist?
- **Expected reasoning / answer:** Unknowable from the number alone. Issue
  creation is a governed triage decision with stated limbs — not an automatic
  consequence of detection — and dispositions other than "raise an Issue"
  must be governed too. For Triviron, no creation limbs or triage
  dispositions are established in this programme, so the question of *which*
  matters would become Issues is `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-014` field 5; outline Slide 9.
- **Misconception detected:** Detection count equated with Issue count
  (`M7-S07`, `M7-S15`).

### E32

- **Prompt:** A platform shows an Issue as "Closed". What does that label
  establish — technically and in governance terms?
- **Expected reasoning / answer:** By itself, neither. A status label is not
  technical evidence, and status *meanings* are governed, not
  platform-supplied — a platform's object types and labels establish no
  governance meaning. What "Closed" means, and what evidence closure
  requires, are governed decisions; for Triviron both are
  `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-015` field 5; outline Slide 9 field 7.
- **Misconception detected:** Platform label read as governed meaning or as
  evidence (`M7-S03`, `M7-S07`).

### E33

- **Prompt:** `TDR-013` is classified `METHOD` while its status is
  `NOT YET ESTABLISHED`. Is that a contradiction?
- **Expected reasoning / answer:** No — they are different axes. The
  classification says what kind of translation work the row contains: a
  reusable structural distinction (finding/clash/Issue). The status says the
  current governed Triviron position: the governed Triviron finding/clash/
  Issue definitions remain `NOT YET ESTABLISHED` in the current programme
  baseline. The distinction being reusable is not evidence Triviron has
  adopted Harrismith's definitions — or any definitions.
- **Basis:** Register `TDR-013` fields 10, 18; schema §3–§4.
- **Misconception detected:** Classification and status conflated;
  `METHOD` read as adoption (`M7-S13`, `M7-S18`).

## Slide 10 exercises — Domain 6: verification, evidence and completion

### E34

- **Prompt:** A matter is marked "Ready for Verification". What has been
  established?
- **Expected reasoning / answer:** Only that the matter's record has reached
  a readiness state — nothing has been verified. Verification is a separate
  act with governed prerequisites, and it examines **evidence**, not
  assertions. What those prerequisites are for Triviron is
  `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-016` field 5; outline Slide 10.
- **Misconception detected:** Readiness state read as verification
  (`M7-S15`).

### E35

- **Prompt:** What does a closed coordination matter prove?
- **Expected reasoning / answer:** Exactly what its closure evidence
  supports — no more. Closure requires evidence of disposition, not absence
  of complaint, and completion conditions keep their qualifiers
  (`as applicable`, `required`). A closed record is not proof of coordination
  quality, of other matters' states, or of anything unobserved.
- **Basis:** Register `TDR-017` field 5; outline Slide 10 field 7.
- **Misconception detected:** Closure inflated into general proof
  (`M7-S12`).

### E36

- **Prompt:** *"Every Issue is closed and the clash count is zero — the
  coordination cycle is complete."* Give both errors.
- **Expected reasoning / answer:** First, one closed matter — or all closed
  matters — is not a demonstrated cycle: a complete governed cycle is an
  evidenced end-to-end demonstration against a defined evidence set, which
  for Triviron is `NOT YET ESTABLISHED`. Second, completion is not zero
  clashes: completion is defined by governed conditions, not by a detector's
  count.
- **Basis:** Register `TDR-018` field 5; outline Slide 10 field 7.
- **Misconception detected:** Closure count or clash count read as cycle
  completion (`M7-S12`, `M7-S15`).

### E37

- **Prompt:** Harrismith's record keeps `GCR-006` open and describes its
  observed position as `PARTIALLY TRACEABLE / NOT YET DEMONSTRATED AS A
  COMPLETE CYCLE`. What does this evidence teach Module 7 — and what does it
  say about Triviron?
- **Expected reasoning / answer:** It is Harrismith evidence about Harrismith
  only: a project with provisioned capability and observed fragments still
  refusing to claim a complete cycle it cannot evidence — partial trace
  stays partial, and capability provisioning is not evidence a governed
  cycle ran. The *discipline* transfers. It says nothing about Triviron:
  Triviron inherits neither the condition nor the status, and no Triviron
  cycle may be implied to have run.
- **Basis:** Register `TDR-018` field 6; outline Slide 10 fields 6, 11.
- **Misconception detected:** Harrismith's condition or status projected
  onto Triviron; provisioning read as demonstration (`M7-S12`, `M7-S15`).

## Slide 11 exercises — Domain 7: publication and acceptance boundary

### E38

- **Prompt:** Is an information-delivery event the same thing as an
  information-state transition?
- **Expected reasoning / answer:** No. An event *uses* a transition but is
  not one; coordination use itself changes no information state; and
  rework/reshare requires governed event logic — not calendar habit or tool
  behaviour. Which events Triviron will govern, and what activates them, is
  `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-019` field 5; outline Slide 11 field 7.
- **Misconception detected:** Event and transition collapsed (`M7-S02`,
  `M7-S13`).

### E39

- **Prompt:** A user's platform permissions allow moving files into a
  published area. What authority does that establish?
- **Expected reasoning / answer:** None. Ability to move a file is not
  authority to change its information state. Publication/exchange requires
  an identified authorising function, established by a controlled
  responsibility/authority decision — and an unresolved authority is typed
  and blocks the route visibly. No controlled Triviron publication/exchange
  authority allocation is currently identified in this programme, so the
  register position is `NOT YET ESTABLISHED`.
- **Basis:** Register `TDR-020` fields 5, 12; outline Slide 11.
- **Misconception detected:** Tool permission read as publication authority
  (`M7-S09`, `M7-S16`).

### E40

- **Prompt:** Order and distinguish: completion, publication, recipient
  acceptance. Which act implies which?
- **Expected reasoning / answer:** None implies another. Completion of
  coordination is one act; publication/exchange is a separately authorised
  act; recipient acceptance is a third act performed by the recipient after
  delivery. Verification and authorisation are likewise distinct. A document
  can be complete and unpublished, published and unaccepted — and one word
  ("accepted") used for two different acts must never collapse them.
- **Basis:** Register `TDR-021` field 5; outline Slide 11 field 7.
- **Misconception detected:** The four acts merged; completion read as
  delivery (`M7-S09`, `M7-S13`).

### E41

- **Prompt:** Harrismith's own publication authority is unresolved. May
  Slide 11 therefore say "Triviron has no publication authority"?
- **Expected reasoning / answer:** No, twice over. Harrismith's unresolved
  authority is a Harrismith fact — it transfers only as the discipline of
  typing an unresolved authority visibly, never as a Triviron absence. And
  the programme's evidence position permits only: no controlled Triviron
  publication/exchange authority allocation is currently identified **in
  this programme** — `NOT YET ESTABLISHED`, which asserts nothing about
  reality in either direction. `TDR-021`'s `METHOD` classification likewise
  records a reusable distinction, not adoption.
- **Basis:** Register `TDR-020` field 6, `TDR-021` field 10; outline Slide 11
  fields 6, 11.
- **Misconception detected:** A Harrismith gap projected onto Triviron;
  `NOT YET ESTABLISHED` hardened into an existence claim (`M7-S09`,
  `M7-S12`, `M7-S18`).

## Slide 12 exercises — what the evidence lets you say

### E42

- **Prompt:** Eighteen rows are `EVIDENCE REQUIRED`. Does that mean eighteen
  Triviron arrangements are missing in reality?
- **Expected reasoning / answer:** No. `EVIDENCE REQUIRED` means the
  controlled Triviron evidence needed to responsibly frame the matter has
  not been identified sufficiently — in this programme. It does not mean the
  arrangement does not exist: `NONE IDENTIFIED` is not `NONE EXISTS`, and
  the register speaks only to the programme's controlled evidence position.
- **Basis:** Schema §3; outline Slide 12 field 6.
- **Misconception detected:** `EVIDENCE REQUIRED` read as non-existence
  (`M7-S12`).

### E43

- **Prompt:** Sketch the five classifications as a project timeline. What is
  wrong with the request itself?
- **Expected reasoning / answer:** The five labels are not a maturity
  ladder, chronological pipeline or schedule. Each later label has a
  *precondition*, not a date: `DECISION REQUIRED` needs sufficiently
  identified evidence; `PROPOSAL` needs an expressly authorised proposal
  stage; `ESTABLISHED` needs a controlled Triviron source or authorised
  decision. A row may properly remain `METHOD` or `EVIDENCE REQUIRED`
  indefinitely — and none is guaranteed to advance at all.
- **Basis:** Schema §3; outline Slide 12 field 7.
- **Misconception detected:** Classification treated as a timetable
  (`M7-S13`, `M7-S18`).

### E44

- **Prompt:** Suppose future increments identify sufficient controlled
  Triviron evidence for one matter. May its row then move directly to
  `PROPOSAL`?
- **Expected reasoning / answer:** No. Evidence sufficiency may support
  `DECISION REQUIRED`, but `PROPOSAL` additionally requires an **expressly
  authorised proposal stage** — none is authorised in the current baseline —
  and any candidate would be labelled `PROPOSED — NOT APPROVED` with its
  authority identified or its absence typed. `ESTABLISHED` needs more still:
  a controlled Triviron source establishing the fact, or an authorised
  decision establishing the arrangement. Evidence arrival changes the
  available/missing position; it authorises nothing by itself, and this
  hypothetical populates no actual row.
- **Basis:** Schema §3, §5, §7; `translation-framework.md` §2.5–§2.6.
- **Misconception detected:** Classification steps skipped; evidence treated
  as authorisation (`M7-S15`, `M7-S17`, `M7-S18`).

### E45

- **Prompt:** In one sentence each, state what the register's current
  position lets you say about (a) the translation method, (b) Triviron
  evidence, (c) Triviron governance.
- **Expected reasoning / answer:** (a) A complete questioning method exists:
  21 typed translation problems across seven domains, three of them carrying
  reusable structural distinctions (`METHOD`). (b) No controlled Triviron
  evidence has been identified in this programme — `NONE IDENTIFIED`, which
  is not `NONE EXISTS`. (c) No Triviron governance position is established,
  proposed or decided in this programme — every populated answer remains
  `NOT YET ESTABLISHED`. Saying exactly this — no more and no less — is the
  slide's point.
- **Basis:** Register §9–§10; outline Slide 12.
- **Misconception detected:** Overstatement in any of the three directions
  (`M7-S12`, `M7-S18`).

---

## Slide 13 exercises — unknowns are controlled work

### E46

- **Prompt:** Harrismith's assurance-sampling method is `NOT ESTABLISHED`; a
  Triviron publication authority is `NOT YET ESTABLISHED`. Explain why the
  two matters carry different statuses.
- **Expected reasoning / answer:** `NOT ESTABLISHED` requires **positive
  evidential support**: Harrismith's controlled sources were examined and
  positively record that no method is defined within the governed scope.
  `NOT YET ESTABLISHED` marks an insufficient controlled basis: `T7-A`
  identified no controlled Triviron source establishing the matter — a
  census finding, not proof of absence. Missing evidence is never evidence
  of absence, so the Triviron matter can never carry `NOT ESTABLISHED` on
  current evidence.
- **Basis:** Schema §4 worked contrast; outline Slide 13.
- **Misconception detected:** Absence of identified evidence upgraded into
  evidence of absence (`M7-S12`, `M7-S13`).

### E47

- **Prompt:** Distinguish an *unknown* matter from an `UNRESOLVED` one.
- **Expected reasoning / answer:** `UNRESOLVED` is not mere ignorance: it
  marks a matter that has been **recognised and considered** and remains
  open through disagreement, dependency, conflict, ambiguity or a pending
  decision — an active open matter. A matter that has simply not been
  examined is not `UNRESOLVED`; in this programme's Triviron rows the
  unexamined-evidence position is `NOT YET ESTABLISHED`.
- **Basis:** Schema §4; outline Slide 13 field 6.
- **Misconception detected:** Every unknown labelled `UNRESOLVED`
  (`M7-S13`).

### E48

- **Prompt:** Why can no Triviron register row carry `TBD` today, when
  Harrismith's tolerance table is full of them?
- **Expected reasoning / answer:** `TBD` marks an **intentional deferral
  inside an already established governance scope**. Harrismith's tolerance
  `TBD`s sit inside its established check scope — Harrismith evidence about
  Harrismith. No Triviron governance scope has been established in this
  programme, so there is nothing to defer within: a Triviron `TBD` would be
  a generic blank wearing a precise label, which the vocabulary forbids.
- **Basis:** Schema §4; outline Slide 13 fields 6, 11.
- **Misconception detected:** `TBD` used as a scope-free blank (`M7-S06`,
  `M7-S13`).

### E49

- **Prompt:** A reviewer suggests upgrading a few register statuses "so the
  module looks further along". What does the discipline of typed absence say?
- **Expected reasoning / answer:** Statuses are never upgraded or
  substituted to make a document appear complete. A typed absence is a
  positive information-management result: it records exactly why the answer
  is not held and prevents false certainty. Guessed or cosmetically upgraded
  content is the failure mode the vocabulary exists to prevent — a blank or
  a flattering label is inferior to an accurate typed absence.
- **Basis:** Outline Slide 13 field 7; register §10.
- **Misconception detected:** Completeness prioritised over evidential
  accuracy (`M7-S18`).

### E50

- **Prompt:** Do the four terms — `NOT YET ESTABLISHED`, `NOT ESTABLISHED`,
  `UNRESOLVED`, `TBD` — form a sequence a matter passes through?
- **Expected reasoning / answer:** No. They are **semantic states, not
  stages**: each answers "why is this not known/decided?" differently —
  insufficient basis; positively evidenced absence; recognised-but-open;
  intentionally deferred within an established scope. A matter moves between
  them only when its evidential situation genuinely changes, in any
  direction — there is no chronological ladder.
- **Basis:** Schema §4; outline Slide 13 field 7.
- **Misconception detected:** Status vocabulary read as a timeline
  (`M7-S13`).

## Slide 14 exercises — from decision backlog to BEP workshop

### E51

- **Prompt:** After a future successful workshop programme, what would the
  register's relationship to the Triviron BEP be — and what is it today?
- **Expected reasoning / answer:** Today the register is a **decision
  backlog**: 21 typed questions, zero BEP content — a future BEP
  *destination* is a conceptual class, not a populated document. In future
  governed work, BEP, matrix, schedule and appendix content would be
  populated **only when earned** — evidence identified, authority engaged,
  decision taken and recorded with status. The backlog never becomes BEP
  content by relabelling.
- **Basis:** Outline Slide 14 field 6; register §10; schema §8.
- **Misconception detected:** Backlog mistaken for, or ripened into, BEP
  content (`M7-S11`, `M7-S14`).

### E52

- **Prompt:** In the future workflow, why are *evidence gathering* and
  *decision-making* separate stages — and why does gathered evidence not
  decide?
- **Expected reasoning / answer:** Evidence gathering fills the
  available/missing position with controlled class F sources; deciding is a
  governance act by the appropriate authority. Evidence informs — it does
  not itself decide, and it does not identify or create the authority.
  Sufficient evidence may make a matter decidable; only the engaged
  authority makes it decided.
- **Basis:** Outline Slide 14 field 7; `source-map.md` §4;
  `translation-framework.md` §2.4, §2.7.
- **Misconception detected:** Evidence conflated with authority (`M7-S16`,
  `M7-S17`).

### E53

- **Prompt:** In the future workflow, a candidate decision has been framed
  under an authorised proposal stage. Is the matter now `ESTABLISHED`?
- **Expected reasoning / answer:** No — this hypothetical stops at
  `PROPOSED — NOT APPROVED`. A candidate is a proposal carrying no approved
  authority; `ESTABLISHED` requires a controlled Triviron source
  (for a fact) or an authorised governance decision (for an arrangement).
  Candidate ≠ decision ≠ established position — and no stage happens
  automatically. This scenario is hypothetical and populates no actual row.
- **Basis:** Schema §3–§4, §7; outline Slide 14 field 7.
- **Misconception detected:** Proposal treated as establishment
  (`M7-S18`).

### E54

- **Prompt:** *"The workshop will be quick — we'll take Harrismith's BEP and
  adapt the names."* Diagnose against the Module 7 method.
- **Expected reasoning / answer:** That is *copy Harrismith into Triviron* —
  precisely what the workshop is not. The STOP rule survives into every
  future stage: no Triviron candidate may be derived solely from a populated
  Harrismith value. A workshop is a controlled decision-making process in
  which questions, required evidence, authority and status are explicit —
  and attendance approves nothing automatically. Harrismith supplies the
  method and the questions; the answers must be earned from Triviron
  evidence and Triviron decisions.
- **Basis:** Outline Slide 14 field 6; `translation-framework.md` §2.5.
- **Misconception detected:** Workshop as fill-in-the-blanks copying; a
  meeting as automatic approval (`M7-S15`).

### E55

- **Prompt:** Slide 14 names Module 8 — BEP workshop facilitation. What may
  the audience conclude about workshops from that?
- **Expected reasoning / answer:** Only that facilitation method is the next
  *teaching* subject. No workshop has occurred or been scheduled; no
  Triviron project appointment, participant, decision owner or authority is
  known in this programme; and Module 8 itself will teach facilitation — it
  will not create or approve Triviron governance. The bridge is a roadmap
  statement, not an event.
- **Basis:** Outline Slide 14 fields 6, 11; `../roadmap.md` Module 8 row.
- **Misconception detected:** A roadmap bridge read as an actual workshop or
  appointment (`M7-S10`, `M7-S17`).

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

**Slides 9–12 coverage (T7-F):**

| Required distinction | Exercises |
|---|---|
| Finding vs clash vs Issue | E30 |
| Finding detection vs Issue creation | E31 |
| Governed status meaning vs platform label | E32 |
| Status vs technical evidence | E32 |
| Ready-for-verification vs verified | E34 |
| Assertion vs evidence | E34 |
| Closure vs proof | E35 |
| Closed matter vs complete cycle | E36 |
| Complete cycle vs zero clashes | E36 |
| Partial trace vs demonstrated cycle | E37 |
| Event vs transition | E38 |
| Tool permission vs publication authority | E39 |
| Completion vs publication | E40 |
| Publication vs recipient acceptance | E40 |
| `METHOD` vs adoption | E33, E41 |
| `EVIDENCE REQUIRED` vs non-existence | E42 |
| Classification vs maturity ladder | E43 |
| Proposal-stage authorisation | E44 |
| Conditions for `ESTABLISHED` | E44, E45 |

**Slides 13–14 coverage (T7-G):**

| Required distinction | Exercises |
|---|---|
| `NOT YET ESTABLISHED` vs `NOT ESTABLISHED` | E46 |
| Missing evidence vs evidence of absence | E46 |
| `UNRESOLVED` vs unknown | E47 |
| `TBD` vs generic blank | E48 |
| `TBD` requiring established scope | E48 |
| Typed absence vs guessed content | E49 |
| Whether four statuses form a chronological sequence | E50 |
| Decision backlog vs BEP content | E51 |
| Future BEP destination vs current populated BEP | E51 |
| Evidence gathering vs decision-making | E52 |
| Evidence vs authority | E52 |
| Authority vs candidate decision | E53 |
| Candidate decision vs established position | E53 |
| Workshop vs automatic approval | E54 |
| Harrismith method vs Triviron answer | E54 |
| Module 8 bridge vs claim that a workshop exists | E55 |

## Status

| Field | Value |
|---|---|
| Exercises | **55** — `E1`–`E14` (Slides 1–3, `ACCEPTED after T7-D-R`) · `E15`–`E29` (Slides 4–8, `ACCEPTED after T7-E-R`) · `E30`–`E45` (Slides 9–12, `ACCEPTED after T7-F-R`) · `E46`–`E55` (Slides 13–14, T7-G); coverage-driven |
| Triviron answers requested or supplied | **None** |
| Publication automation | **`PAUSED`** |
