# Module 7 — Exercises

**Status:** **`TEACHING CONTENT IN DEVELOPMENT — T7-D PENDING CHATGPT
GOVERNANCE REVIEW`**

**`TEACHING MATERIAL — NOT TRIVIRON GOVERNANCE`**

Practice and self-assessment for the developed slides. **Exercises exist for
Slides 1–3 only; Slides 4–14 are `NOT YET DEVELOPED` and have no exercises.**
The count is coverage-driven, not targeted.

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

## Coverage map

| Required distinction | Exercises |
|---|---|
| Reference implementation vs target governance | E1, E2, E3 |
| Transferable method vs non-transferable populated answer | E4, E5, E6, E7 |
| Evidence requirement vs evidence currently identified | E12, E14 |
| Harrismith fact vs Triviron fact | E5, E8, E10 |
| Typed absence vs invented content | E11, E13 |
| STOP before candidate decision | E9, E10, E14 |

## Status

| Field | Value |
|---|---|
| Exercises | **14** — `E1`–`E14`, Slides 1–3 only; coverage-driven |
| Slides 4–14 exercises | **None — `NOT YET DEVELOPED`** |
| Triviron answers requested or supplied | **None** |
| Publication automation | **`PAUSED`** |
