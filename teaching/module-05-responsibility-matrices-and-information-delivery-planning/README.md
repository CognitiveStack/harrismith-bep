# Module 5 — Responsibility Matrices and Information-Delivery Planning

**Status:** **CURRENT — ACTIVE.** Established in **T5-A**; matrix distinctions
developed in **T5-B**.

**Slides 1–5 developed. Slides 6–14 are architecture only.** **The content
baseline is not complete.** No exercises, no visual specification, no visual
source, no assembly package and no PowerPoint exists.

**Teaching material. Not governance.** This module explains controlled Harrismith
resources; it governs nothing, decides nothing, and changes nothing.

---

## 1. Objective

**To be able to read the three Harrismith responsibility and delivery resources,
say precisely what each one governs or plans, and identify what each leaves
unresolved — without filling any of it in.**

The module connects the two before it:

| Module | Question |
|---|---|
| **Module 2** | Who holds each **role**, **function** and **authority**? |
| **Module 4** | How does information move through controlled **states** and **transitions**? |
| **Module 5** | **Which information must be produced or delivered, by whom, for which purpose or recipient, at which event, under which responsibility — and with what evidence?** |

**Classified `INTERP` — a supported interpretation.** No controlled source states
the module objective in these words, but the construction rests on cited
sources: `S1` §10.5, and the three resources' own purpose statements and
**population rules**. See [`source-map.md`](source-map.md) §5, `M5-S2-14`, and
the classification reconciliation at §5.1.

## 2. Central question

> **Which information must be produced, by which task team, for which event and
> recipient, for what purpose — and under which checks and authorisation?**

**Classification: `INTERP`.** Derived from `S1` §10.5, which records the eight
things each task team should understand: *what it must produce · for which event
· for whom · the purpose · the format · the required checks · the required
authorisation · its dependencies.* No source phrases this as a single question.

### 2.1 The provisional question was corrected

The increment proposed: *"Who is responsible for producing which information, for
whom, for what purpose, **and by when**?"*

**"By when" is not supported.** `S1` §10.5 asks *"for which event"*, not *when*.
`S4` records that *"No real delivery dates or client milestones have been
established"* and gives every event *"Event-triggered / `TBD`"*. The provisional
wording also omitted four of the BEP's eight fields — format, required checks,
required authorisation and dependencies.

Full reasoning: [`source-map.md`](source-map.md) §7.3, hypothesis `H-C1`.

## 3. The core conceptual distinction

**Allocation is not performance.**

A matrix records what someone is **responsible for**. It never records whether
they **did it**. The two questions need two different sources, and only one of
them exists in this repository as evidence.

`S2` §5 states it directly:

> *"This matrix allocates **functions to roles**. It does **not** demonstrate
> that separate people perform them, and it must not be read as evidence of
> independence."*

`S3` states the same about containers:

> *"This matrix describes what is intended to be produced… It is **not** an
> inventory of what currently exists in the CDE."*

## 4. The three principal resources

**They are three separately controlled resources answering three different
questions. They are not one RACI matrix**, and the refusal of RACI is controlled
governance (`S1` §5.12), not a stylistic choice.

| Resource | Answers — *in its own words* |
|---|---|
| [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) | *"who performs which information-management function?"* |
| [`supporting/model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md) | *"who produces and maintains which information container?"* |
| [`supporting/information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md) | *"what information is exchanged, at what event, to whom, why, in what form"* |

Full separate analysis: [`resource-comparison.md`](resource-comparison.md).

## 5. Source precedence

| Level | Source class |
|---|---|
| **1** | Approved Harrismith governance — the BEP |
| **2** | Approved supporting matrices, schedules and strategies |
| **3** | Controlled decision, approval and validation records |
| **4** | Completed teaching interpretation from Modules 1–4 |
| **5** | Teaching synthesis — labelled |

**The precedence is set by `S1` §1.5, not by this module.** Where controlled
sources differ, the difference is **recorded**, never harmonised. Full inventory:
[`source-inventory.md`](source-inventory.md).

## 6. Governance and implementation status

**Every statement about an allocation or a schedule row carries both.**

The three resources do **not** share one status:

| Resource | Document status | Content classification |
|---|---|---|
| IM Responsibility Matrix | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **Split rule** — proposal *"unless the BEP already expressly establishes the allocation"* |
| Model / Information Responsibility Matrix | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **All §3 allocations `PROPOSED GOVERNANCE`** (`TA-03`) |
| Information Delivery Schedule | APPROVED WITH CONDITIONS — Training Baseline 0.1 | **All entries `PROPOSED GOVERNANCE`** |

All three: approved through **`AD-001`, 2026-08-01**; conditions active;
**publication NOT AUTHORISED**.

**The only implementation evidence available is `S9`**, which declares
**`Authority: None`** and states that it *"resolves no decision, assigns no
authority, and approves nothing."*

## 7. Positions fixed for this module

Carried forward from Module 4 and confirmed against the sources in T5-A.
**None may be changed by teaching need.**

- **Publication / exchange authority is UNRESOLVED.** Not held automatically by
  the BIM Manager, BIM Coordinator, CDE Administrator or Architect.
- **Recipient acceptance authority is UNRESOLVED.**
- **`T4` remains blocked. Information remains Shared.**
- **`TRN-E03` is blocked on five independent matters** — publication authority,
  acceptance authority, recipient identity, required formats, deliverable set.
  **Resolving one would release none of the others.**
- **`TRN-E03` is a delivery event. It is not `T4`.**
- **Published, Delivered, Received and Accepted remain four distinct objects.**
- **Governance definition and implementation evidence remain separate.**
- **No complete governed workflow cycle has been demonstrated** — `GCR-006` is
  open.
- **Absence of observation is not observation of absence.**

### 7.1 Two findings recorded in T5-A

**No controlled Harrismith matrix or schedule contains a blank field.** Every
absence is typed — `TBD`, `—`, `Not defined`, `Not established`, `Not
applicable`, `Conditional`, `BLOCKED`. **Module 5 must not present Harrismith as
having blanks to interpret.** See [`source-map.md`](source-map.md) §7.2 `H-D11`.

**"Publication" carries two unrelated senses in this repository**, and one is
resolved while the other is not. A publication-**arrangement** approval
(`PAD-001`, scope *"Training Baseline 0.1 publication arrangement only"*) does
**not** resolve project publication authority under `S1` §9.7. See
[`source-inventory.md`](source-inventory.md) §5.

## 8. Scope

### 8.1 Module 5 owns

Purposes of responsibility matrices · distinctions between the matrix and
schedule resources · row, column and cell grammar · assignment boundaries ·
responsibility allocation · information-delivery planning · delivery-event
structure · schedule interpretation · the relationship between planned
information and controlled transitions · unresolved, conditional and blocked
fields · traceability across the three resources · **the distinction between a
planned requirement and evidence of performance**.

### 8.2 Module 5 does not own

**Module 6** — coordination-cycle mechanics, model federation, clash detection,
finding and issue triage, escalation, technical review procedures, approval
workflow mechanics, assurance sampling, coordination evidence, issue closure,
and complete review or acceptance cycles.

**Module 5 may identify that a review, coordination, approval or acceptance
function is required. It must not teach that function's operational workflow.**

**Module 4** retains state definitions, the eight controlled steps, `T1`/`T4`
classification, gates and evidence, and the five container properties.

**Module 7** owns the Triviron translation. Slide 14 poses questions and answers
none.

Full deferral register: [`source-map.md`](source-map.md) §10.

## 9. Relationship to Modules 1–4

Modules 1–4 are cited as **teaching interpretation at precedence level 4**, never
as controlled Harrismith governance. Where a Module 5 statement carries forward a
Module 2 or Module 4 position, the **original controlled source is retained**
alongside it.

## 10. Deliverable

A **20-minute, fourteen-slide** presentation.

**Timing: `20.0 minutes allocated — not measured`** — in this and every module.

**No PowerPoint exists in this repository, in any module.** Decks are produced
externally and are not committed.

## 11. Module files

| File | Contains |
|---|---|
| [`README.md`](README.md) | This file — objective, central question, status, scope, **T5-A validation and increment status** (§13) |
| [`source-inventory.md`](source-inventory.md) | Source hierarchy · `S1`–`S15` with exact paths and declared statuses · why each was consulted · **`E1`–`E8` exclusions with reasons** · the two senses of *publication* |
| [`resource-comparison.md`](resource-comparison.md) | **The three principal resources analysed separately** — 37 recorded fields each · overlaps · differences · terminology variance · relationships |
| [`source-map.md`](source-map.md) | Classification scheme and its **T5-B reconciliation** · source-authority register · **84 classified statements, Slides 1–5** · terminology register · **25 tested hypotheses** · unresolved register · **59 prohibited claims** · boundary deferrals |
| [`presentation-outline.md`](presentation-outline.md) | Timing structure · **fourteen-slide architecture** · Slides 6–14 **architecture only** · **Slides 1–5 developed content** |
| [`speaker-notes.md`](speaker-notes.md) | Presenter notes — **Slides 1–5 only** |

### Reading order

1. [`source-inventory.md`](source-inventory.md) — what the sources are and what
   they may be used for
2. [`resource-comparison.md`](resource-comparison.md) — what the three principal
   resources actually say
3. [`source-map.md`](source-map.md) — what may and may not be taught
4. [`presentation-outline.md`](presentation-outline.md) — the architecture and
   Slides 1–3
5. [`speaker-notes.md`](speaker-notes.md) — how to deliver Slides 1–3

## 12. Increment sequence

| Increment | Scope | Status |
|---|---|---|
| **T5-A** | Module establishment · source inventory and hierarchy · three-resource comparison · hypothesis testing · fourteen-slide architecture · **Slides 1–3** | ✅ **COMPLETE** |
| **T5-B** | Responsibility-matrix purposes and distinctions — **Slides 4–5** · classification reconciliation · `teaching/README.md` correction | ✅ **COMPLETE** |
| **T5-C** | Matrix-cell grammar and allocation boundaries — Slides 6–8 | **NEXT — outstanding** |
| T5-D | Delivery events and schedule construction — Slides 9–12 | Outstanding |
| T5-E | Slides 13–14 and the complete content baseline | Outstanding |
| T5-F | Visual specifications and visual-source set | Outstanding |
| T5-G | Presentation assembly package | Outstanding |
| T5-H | External PowerPoint production — **outside this repository** | Outstanding |

## 13. Increment status and validation

### 13.1 What T5-A and T5-B produced

| Output | After T5-A | **After T5-B** |
|---|---|---|
| Module files | 6 | **6 — unchanged** |
| Source hierarchy | Established; traced to `S1` §1.5 | Unchanged |
| Sources consulted / excluded | **15** (`S1`–`S15`) / **8 groups** (`E1`–`E8`) | Unchanged — **the T5-A inventory was not reopened** |
| Three principal resources | Analysed separately, 37 fields each | Unchanged |
| Hypotheses tested | **25** | Unchanged |
| Registers | **Six** | Unchanged |
| Classified statements | 43 (Slides 1–3) | **84 (Slides 1–5)** |
| Prohibited claims | 50 | **59**, plus 4 standing programme-status prohibitions |
| Slide architecture | 14 slides · **20.0 minutes allocated — not measured** | Unchanged; total re-verified at **20.0** |
| Slides developed | 1, 2, 3 | **1, 2, 3, 4, 5** |
| Remaining architecture only | Slides 4–14 | **Slides 6–14** — eight recorded fields each |
| Classification scheme | `SYNTH` defined as *"no source support"* | **Reconciled** — see §13.5 |

### 13.2 Scope compliance — T5-B

| Check | Result |
|---|---|
| Paths modified | **Only** this README, `presentation-outline.md`, `speaker-notes.md`, `source-map.md`, [`../roadmap.md`](../roadmap.md) and [`../README.md`](../README.md) |
| [`source-inventory.md`](source-inventory.md) and [`resource-comparison.md`](resource-comparison.md) | **Unchanged.** No contradiction with a controlled source was found |
| Controlled sources modified | **None.** `bep/`, `supporting/`, `docs/`, `guidance/`, `standards/`, `working/`, `output/` unchanged |
| Modules 1–4 modified | **None** |
| `teaching/assets/`, `teaching/shared/` modified | **None** |
| PowerPoint, PDF or office file created | **None** |
| Visual specification, visual source or rendered asset created | **None** |
| Presentation assembly package or exercise set created | **None** |
| Autodesk or ACC activity | **None.** Not authorised, not attempted |
| Publication automation | **Untouched. Remains `PAUSED`** |
| T5-C or later work performed | **None** |

### 13.3 Safeguards verified intact

| Safeguard | State at end of T5-B |
|---|---|
| Publication authority | **UNRESOLVED** — unchanged |
| Acceptance authority | **UNRESOLVED** — unchanged |
| `TRN-E03` recipient identity | **Not established** — unchanged |
| `TRN-E03` required formats | **Not established** — unchanged |
| `TRN-E03` deliverable set | **Not defined** — unchanged |
| `T4` | **BLOCKED** — unchanged |
| Information state | **Remains Shared** — unchanged |
| `UD-001` | **Unresolved, not corrected** — unchanged |
| `GCR-006` | **OPEN** — unchanged |
| Governance ≠ implementation | Preserved; both statuses recorded per statement |

**No unresolved field was populated in any controlled source or in any teaching
statement.**

### 13.4 Known residual work

- **Slides 6–14 have no content**, no visual specification and no assets.
- **The content baseline is not complete.**
- **The module has no exercises.** Modules 1–4 carry an `exercises.md`; Module 5
  does not yet, and one is expected in a later increment.
- **The module has no visual-demonstration plan.** Deferred to T5-F.
- **Timing has never been measured**, for this or any module.

### 13.5 Classification reconciliation — completed in T5-B

**A contradiction between this README and
[`source-map.md`](source-map.md) was found and resolved.**

The classification scheme defined `SYNTH` as *"Teaching synthesis; no source
support"*, and `M5-S2-14` — the learning objective — recorded its source as
`none`. **This README recorded the same objective as derived from `S1` §10.5 and
the three resources' purpose statements.** Both could not be right.

**The evidence supports this README.** The objective's substance is
source-supported on both halves: the three resources each state their own
question and exclusions, and **all three carry an express population rule
forbidding invention**.

**Resolution:**

1. `M5-S2-14` is reclassified **`INTERP`** at authority level 4, with its
   supporting sources recorded.
2. **`SYNTH` was redefined** so the ambiguity cannot recur — the class now turns
   on whether a source is cited, not on whether the wording is original. **A
   statement with a source reference is never `SYNTH`.**
3. §2 of this README no longer describes the objective as teaching synthesis.

**Effect:** `INTERP` 6 → 9; `SYNTH` 1 → **0**. **No count was changed to reach a
preferred figure.** The refinement applies to **Module 5's scheme only**;
Modules 1–4 hold their own schemes and are unchanged. Full record:
[`source-map.md`](source-map.md) §5.1.

### 13.6 Teaching-programme README — reconciled in T5-B

[`../README.md`](../README.md) was **outside T5-A's permitted paths** and was
reported rather than changed. **T5-B was authorised to correct it, and did.** It
now records Module 4 as produced with review and rehearsal deferred, Module 5 as
the sole active module with its six files and their functions, Slides 1–5
developed, Slides 6–14 architecture only, and the absence of any Module 5 asset
directory or presentation package.

### 13.7 Status

| Field | Value |
|---|---|
| Increment | **T5-B — COMPLETE** |
| Module status | **CURRENT — ACTIVE** |
| Content baseline | **NOT complete** — Slides 6–14 outstanding |
| Next increment | **T5-C** — Slides 6–8, matrix-cell grammar and allocation boundaries |
| Timing | **`20.0 minutes allocated — not measured`** |
| Visual specifications, assets, assembly package | **None** |
| PowerPoint | **None**, in this or any module |
| Publication automation | **PAUSED** |
