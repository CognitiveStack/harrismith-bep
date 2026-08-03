# Module 3 — External Source Register

**Status:** Source-control record for teaching material. **Not governance.**

This register controls what Module 3 is permitted to teach and from what. **A
statement with no entry here has no source**, and must be classified as
interpretation or synthesis in [`source-map.md`](source-map.md) or removed.

**Baseline date: 2026-08-03.** The source-status baseline below was supplied by
the teaching orchestrator. **No external research was performed by this
repository's specialist**, and no external site was fetched during increment
T3-A.

---

## 1. Why this register exists

Modules 1 and 2 needed no external source. Every statement traced to a controlled
Harrismith document held in this repository.

**Module 3's subject is not held here.** ISO 19650 is a copyrighted international
standard; this repository contains none of its text, and it has not been read for
this programme. What is available is:

- **official public metadata** — scope summaries published by ISO;
- **official implementation guidance** — UK BIM Framework material;
- **Harrismith repository evidence** — which illustrates, and proves nothing about
  the standard.

Teaching from those three without labelling them would produce confident
statements that nobody can trace. This register is the control.

## 2. Authority levels

| Level | Meaning | May be taught as |
|---|---|---|
| **A1** | Published international standard — official public metadata only | What the standard is stated to cover |
| **A2** | Official implementation guidance, jurisdiction-bound | What that jurisdiction's guidance says |
| **A3** | Harrismith repository evidence | What this project's controlled documents say |
| **A4** | Supported interpretation | A conclusion drawn from A1–A3, labelled |
| **A5** | Teaching synthesis | Presenter framing, labelled |
| **A0** | Draft — **non-normative** | Recorded status only; **never a requirement** |

**A lower level never overwrites a higher one.** An A2 convention is not an A1
requirement. An A3 term is not an A1 term.

## 3. Source categories in use

| Category | Applied to |
|---|---|
| `PUBLISHED INTERNATIONAL STANDARD — PUBLIC METADATA ONLY` | X1, X2 |
| `DRAFT INTERNATIONAL STANDARD — NON-NORMATIVE` | X3, X4 |
| `OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` | X5, X6 |
| `HARRISMITH PROJECT SOURCE` | H1, H2 |
| `TEACHING SYNTHESIS` | Applied to statements, not sources — see [`source-map.md`](source-map.md) |

---

## 4. Register

### X1 — ISO 19650-1:2018

| Field | Value |
|---|---|
| **Source identifier** | `X1` |
| **Organisation** | International Organization for Standardization (ISO) |
| **Title** | *Organization and digitization of information about buildings and civil engineering works, including building information modelling (BIM) — Information management using building information modelling — Part 1: Concepts and principles* |
| **Edition / status** | **`ISO 19650-1:2018` — current published edition of Part 1** as at 2026-08-03 |
| **Source type** | `PUBLISHED INTERNATIONAL STANDARD — PUBLIC METADATA ONLY` |
| **Jurisdiction** | International |
| **Authority level** | **A1** |
| **Information available** | Title; edition; publication status; **official public scope summary only** — that it concerns concepts and principles for information management using BIM; that its framework covers exchanging, recording, versioning and organising information; that its application extends across the asset life cycle |
| **Information NOT available** | **The standard text.** No clause wording, clause numbering, definitions, requirements, tables, figures or annexes. Not held in this repository and **not read for this programme** |
| **Permitted teaching use** | Naming the standard and its edition; stating the publicly summarised scope in paraphrase; stating that Part 1 provides concepts and principles |
| **Prohibited inference** | Any clause-level requirement; any definition attributed to it; any statement that a project conforms to it; any reconstruction of its figures; treating the scope summary as the complete set of requirements |
| **Review date** | **2026-11-03**, or before first delivery of Module 3, **whichever is sooner** |
| **Supersession risk** | **HIGH** — a revision project is under development (see `X3`). The 2018 edition remains current until a replacement is published |

**Verification note.** Everything above is *metadata*. A statement of what a
standard covers is not a statement of what it requires. Module 3 teaches the
first and never the second.

### X2 — ISO 19650-2:2018

| Field | Value |
|---|---|
| **Source identifier** | `X2` |
| **Organisation** | International Organization for Standardization (ISO) |
| **Title** | *Organization and digitization of information about buildings and civil engineering works, including building information modelling (BIM) — Information management using building information modelling — Part 2: Delivery phase of the assets* |
| **Edition / status** | **`ISO 19650-2:2018` — current published edition of Part 2** as at 2026-08-03 |
| **Source type** | `PUBLISHED INTERNATIONAL STANDARD — PUBLIC METADATA ONLY` |
| **Jurisdiction** | International |
| **Authority level** | **A1** |
| **Information available** | Title; edition; publication status; **official public scope summary only** — that it concerns the information-management process during the delivery phase of assets; that it includes the information exchanges within that phase; that the framework can be applied across asset types, organisations and procurement strategies |
| **Information NOT available** | **The standard text.** No clause wording, no numbered process activities, no definitions, no tables or figures, no annexes. Not held in this repository and **not read for this programme** |
| **Permitted teaching use** | Naming the standard and its edition; stating the publicly summarised scope in paraphrase; stating that Part 2 applies an information-management process to the delivery phase |
| **Prohibited inference** | Any numbered delivery-phase activity; any clause-level requirement; any claim that a project has executed its process; treating the scope summary as the complete requirement set |
| **Review date** | **2026-11-03**, or before first delivery of Module 3, **whichever is sooner** |
| **Supersession risk** | **HIGH** — a revision project is under development (see `X4`). The 2018 edition remains current until a replacement is published |

**Boundary note.** X2's stated applicability *across organisations, assets and
procurement strategies* is a statement about the framework's reach. It is **not**
a statement that any particular organisation has applied it, and never evidence
about Harrismith.

### X3 — ISO 19650-1 revision project

| Field | Value |
|---|---|
| **Source identifier** | `X3` |
| **Organisation** | International Organization for Standardization (ISO) |
| **Title** | Revision project for Part 1 of `ISO 19650` |
| **Edition / status** | **Under development.** A draft, at whatever stage it has reached, is **not a published requirement** |
| **Source type** | `DRAFT INTERNATIONAL STANDARD — NON-NORMATIVE` |
| **Jurisdiction** | International |
| **Authority level** | **A0 — non-normative** |
| **Information available** | **That a revision project exists.** Nothing more is recorded here |
| **Information NOT available** | Draft text; draft stage code; draft scope; draft changes; expected publication date. **None of these has been established for this programme, and none is to be invented** |
| **Permitted teaching use** | Stating that Part 1 is under revision, and that the 2018 edition remains the current published edition until a replacement is published |
| **Prohibited inference** | Teaching any draft wording as a requirement; describing what the revision will change; predicting a publication date; using the revision to displace the 2018 edition anywhere in this module |
| **Review date** | **2026-11-03**, and at every module increment thereafter |
| **Supersession risk** | **This entry *is* the supersession risk for `X1`.** When a replacement publishes, `X1` must be restated and every Module 3 statement re-verified |

### X4 — ISO 19650-2 revision project

| Field | Value |
|---|---|
| **Source identifier** | `X4` |
| **Organisation** | International Organization for Standardization (ISO) |
| **Title** | Revision project for Part 2 of `ISO 19650` |
| **Edition / status** | **Under development.** A draft, at whatever stage it has reached, is **not a published requirement** |
| **Source type** | `DRAFT INTERNATIONAL STANDARD — NON-NORMATIVE` |
| **Jurisdiction** | International |
| **Authority level** | **A0 — non-normative** |
| **Information available** | **That a revision project exists.** Nothing more is recorded here |
| **Information NOT available** | Draft text; draft stage code; draft scope; draft changes; expected publication date. **None established; none to be invented** |
| **Permitted teaching use** | Stating that Part 2 is under revision, and that the 2018 edition remains the current published edition until a replacement is published |
| **Prohibited inference** | Teaching any draft wording as a requirement; describing what the revision will change; predicting a publication date; using the revision to displace the 2018 edition anywhere in this module |
| **Review date** | **2026-11-03**, and at every module increment thereafter |
| **Supersession risk** | **This entry *is* the supersession risk for `X2`** |

**Standing rule for X3 and X4.** A draft is recorded so that the module is not
surprised by it. It is never taught. If an audience member has read a draft and
quotes it, the safe answer is in [`speaker-notes.md`](speaker-notes.md), Slide 3.

### X5 — UK BIM Framework overview / about material

| Field | Value |
|---|---|
| **Source identifier** | `X5` |
| **Organisation** | UK BIM Framework |
| **Title** | UK BIM Framework overview / about material |
| **Edition / status** | Live guidance material, revised by its publisher without notice to this repository |
| **Source type** | `OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` |
| **Jurisdiction** | **United Kingdom** |
| **Authority level** | **A2** |
| **Information available** | That information management is intended to improve the specification, production, review and transfer of information; that information-management requirements should be established **appointment by appointment** |
| **Information NOT available** | ISO clause text; any South African applicability; any statement about this project |
| **Permitted teaching use** | Explaining *how the framework is implemented in the UK*, **explicitly attributed to the guidance and explicitly labelled UK** |
| **Prohibited inference** | Presenting it as ISO text; presenting it as a universal national annex; asserting South African applicability; using it as evidence that Harrismith conforms to anything |
| **Review date** | **2026-11-03**, or before first delivery, whichever is sooner |
| **Supersession risk** | **MEDIUM** — living guidance, and it will move when the ISO revisions publish |

### X6 — UK BIM Framework FAQ / terminology guidance

| Field | Value |
|---|---|
| **Source identifier** | `X6` |
| **Organisation** | UK BIM Framework |
| **Title** | UK BIM Framework FAQ / terminology guidance |
| **Edition / status** | Live guidance material, revised by its publisher without notice to this repository |
| **Source type** | `OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT` |
| **Jurisdiction** | **United Kingdom** |
| **Authority level** | **A2** |
| **Information available** | That the standard uses the concept of **information-management functions rather than requiring new job titles**; that the **appointing party** must ensure the information-management function is fulfilled; that the **lead appointed party** must also ensure the relevant information-management function is fulfilled |
| **Information NOT available** | The ISO definitions of those terms; clause references; how the functions are to be discharged in any specific jurisdiction or contract |
| **Permitted teaching use** | **Slides 7 and 8** — the functions-not-job-titles point and the party terminology, in both cases attributed to the guidance and labelled UK |
| **Prohibited inference** | Quoting these as ISO definitions; asserting that a named job title discharges a function; mapping `lead appointed party` onto Harrismith's `Lead Delivery Party` |
| **Review date** | **2026-11-03**, or before first delivery, whichever is sooner |
| **Supersession risk** | **MEDIUM** |

**X6 is the module's highest-value external source and its highest-risk one.** It
supplies the functions-versus-job-titles point that connects Module 3 to Module 2
— and it is the one an audience will most readily mistake for the standard
itself. Every use of X6 is attributed aloud.

**Clarification recorded in T3-B — no source added.** `X6`'s
*appointment-by-appointment* statement is now in use on **Slide 5**, one slide
earlier than the *"Slides 7 and 8"* note above anticipated. The permitted use is
unchanged; only its first appearance has moved, and Slide 5 is where the module's
UK-labelling convention is therefore established. See
[`source-map.md`](source-map.md) `M3-S5-01`.

**A limit worth stating explicitly, because Slides 5 and 6 press on it.** Neither
`X5` nor `X6` provides **definition-level** material. In particular, **no
registered source defines**:

- any client-, exchange-, asset- or project-level **information-requirement
  document**;
- **level of information need**, in any form.

Those terms may be referred to as concepts where a Harrismith source uses them,
and **may not be defined, abbreviated into teaching vocabulary, or broken into
categories, levels or tiers** — see [`source-map.md`](source-map.md) §7.2,
prohibitions 16 and 17.

**Second clarification, recorded in T3-C — no source added.** `X6`'s party
terminology is now in use on **Slides 7 and 8**. Its registered content supports
**two party terms only**:

| Term | Status in this programme |
|---|---|
| **appointing party** | **Registered** — `X6`, A2, UK guidance |
| **lead appointed party** | **Registered** — `X6`, A2, UK guidance |
| *appointed party* | **Named, not defined.** No registered source defines it |
| *delivery team* | **Named, not defined.** No registered source defines it |
| *task team* | **Named, not defined.** No registered source defines it |

**The distinction is taught, not hidden.** Slide 8 shows which terms are sourced
and which are merely in circulation, because that difference is the reason the
slide declines to map anything. See [`source-map.md`](source-map.md) `M3-S8-03`,
`M3-S8-04` and the vocabulary relationship register.

**And a third limit, for Slide 9.** **No registered source defines *information
container*.** The term appears in both vocabularies; Slide 9 uses a **working
description drawn from `H1`**, explicitly labelled as such. Shared vocabulary is
not established equivalence — prohibition 27.

### H1 — Harrismith Fire Station BEP

| Field | Value |
|---|---|
| **Source identifier** | `H1` |
| **Organisation** | Harrismith Fire Station training / reference implementation |
| **Title** | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) |
| **Edition / status** | **APPROVED WITH CONDITIONS — Training Baseline 0.1.** Not published; not issued; non-contractual |
| **Source type** | `HARRISMITH PROJECT SOURCE` |
| **Jurisdiction** | This project only |
| **Authority level** | **A3** |
| **Information available** | The project's own information-management arrangements; §4.6 information-management functions; §6.1 CDE principles; §6.8 the five separated properties; **§11.2 and §13.4 — the project's own statement about ISO 19650** |
| **Information NOT available** | Any ISO text; any conformity assessment; any named role holder; any appointed organisation |
| **Permitted teaching use** | Worked **analogy** for principles; the project's own influence statement; illustrating what a project-level decision looks like |
| **Prohibited inference** | That Harrismith conforms to ISO 19650; that its terms are ISO terms; that describing a process evidences its operation |
| **Review date** | Reviewed at each increment against the controlled document |
| **Supersession risk** | **LOW** — controlled in this repository; changes are visible in Git |

**The load-bearing sentences.** BEP §11.2: ISO 19650 principles inform the
information-management approach — *"This is a statement about influence. **No
formal compliance with ISO 19650 is claimed**, and none has been established or
assessed."* BEP §13.4 adds: *"No copyrighted standards content is reproduced in
this repository."*

**The project says it itself.** Slide 13's honesty is not the presenter's
caution — it is the source's own position, quoted.

### H2 — Harrismith supporting governance documents

| Field | Value |
|---|---|
| **Source identifier** | `H2` |
| **Organisation** | Harrismith Fire Station training / reference implementation |
| **Title** | The six supporting resources in [`supporting/`](../../supporting/) — [`information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md), [`model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md), [`information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md), [`cde-workflow-state-strategy.md`](../../supporting/cde-workflow-state-strategy.md), [`coordination-review-strategy.md`](../../supporting/coordination-review-strategy.md), [`governance-decision-register.md`](../../supporting/governance-decision-register.md) |
| **Edition / status** | **APPROVED WITH CONDITIONS — Training Baseline 0.1** each. Not published; not issued |
| **Source type** | `HARRISMITH PROJECT SOURCE` |
| **Jurisdiction** | This project only |
| **Authority level** | **A3** |
| **Information available** | The CDE state set and its transitions; responsibility allocation across functions; planned delivery events and their conditions; recorded governance decisions and unresolved matters |
| **Information NOT available** | Any ISO mapping; any conformity evidence; any named holder; any executed exchange |
| **Permitted teaching use** | Illustrating containers, states, planned exchanges and responsibility allocation **as this project arranged them** |
| **Prohibited inference** | That these arrangements satisfy ISO 19650; that state names resembling ISO-associated language demonstrate conformity; that a scheduled delivery event has occurred |
| **Review date** | Reviewed at each increment against the controlled documents |
| **Supersession risk** | **LOW** — controlled in this repository |

**Caution recorded for later slides.** The delivery schedule's `TRN-E03` event is
**blocked** — publication/exchange authority is unresolved — and the CDE strategy
records transition `T4` as currently unable to proceed for the same reason. A
slide that shows the state model without this reads as a working system.

### H3 — Harrismith increment and decision records

| Field | Value |
|---|---|
| **Source identifier** | `H3` |
| **Organisation** | Harrismith Fire Station training / reference implementation |
| **Title** | The controlled records in [`docs/`](../../docs/) — in particular [`Increment-7C-Live-Validation-Record.md`](../../docs/Increment-7C-Live-Validation-Record.md) |
| **Edition / status** | Controlled records; each declares its own status. Not published; not issued |
| **Source type** | `HARRISMITH PROJECT SOURCE` |
| **Jurisdiction** | This project only |
| **Authority level** | **A3** |
| **Information available** | Recorded observations of the as-found environment, including the finding that *"folder names do not themselves prove ISO 19650 governance"*; recorded governance decisions and their conditions |
| **Information NOT available** | Any ISO text; any conformity finding; any assessment against the standard |
| **Permitted teaching use** | **Slide 2** — the folder-names observation, attributed to this project's own validation record |
| **Prohibited inference** | That the observation establishes what ISO 19650 requires; that a live-environment observation is a conformity assessment |
| **Review date** | Reviewed at each increment against the controlled documents |
| **Supersession risk** | **LOW** — controlled in this repository |

**The distinction this source teaches.** It records that *folder names do not
prove governance* — evidence that **this project holds that position**, and no
evidence at all about what the standard requires. Both halves are said aloud.

---

## 5. Register summary

| ID | Source | Category | Level | Jurisdiction | Supersession risk |
|---|---|---|---|---|---|
| `X1` | ISO 19650-1:2018 | Published standard — public metadata only | A1 | International | **HIGH** |
| `X2` | ISO 19650-2:2018 | Published standard — public metadata only | A1 | International | **HIGH** |
| `X3` | Part 1 revision project | **Draft — non-normative** | A0 | International | *is* the risk for X1 |
| `X4` | Part 2 revision project | **Draft — non-normative** | A0 | International | *is* the risk for X2 |
| `X5` | UK BIM Framework overview | Implementation guidance | A2 | **United Kingdom** | MEDIUM |
| `X6` | UK BIM Framework FAQ / terminology | Implementation guidance | A2 | **United Kingdom** | MEDIUM |
| `H1` | Harrismith BEP | Harrismith project source | A3 | This project | LOW |
| `H2` | Harrismith supporting documents | Harrismith project source | A3 | This project | LOW |
| `H3` | Harrismith increment and decision records | Harrismith project source | A3 | This project | LOW |

**Nine sources. Two are the standards themselves — and neither has been read.**
That asymmetry is the honest position of this module and is stated in delivery.

## 6. Jurisdiction finding

| Jurisdiction | Sources | Consequence for teaching |
|---|---|---|
| International | X1, X2, X3, X4 | The framework is international; **its implementation is not** |
| United Kingdom | X5, X6 | Everything drawn from these is labelled **UK guidance**, aloud and on the slide |
| **South Africa** | **None** | **No South African implementation guidance is registered.** None is assumed, and no SANS applicability is asserted — consistent with BEP §11.2 and §13.4 |
| This project | H1, H2, H3 | Illustration only |

**The gap is deliberate and must be stated.** Harrismith is a South African
project with **no registered national implementation guidance**. UK guidance is
not a substitute for it. This is an open matter for Triviron — see Slide 14 when
developed — and not something this module resolves.

## 7. Review protocol

| Trigger | Action |
|---|---|
| **2026-11-03**, or before first delivery of Module 3 | Re-verify X1–X6 against their publishers |
| A revision of Part 1 or Part 2 publishes | Restate `X1` / `X2`; re-verify **every** Module 3 statement; the draft entry closes |
| UK BIM Framework material changes | Re-verify X5, X6; guidance is living material |
| A licensed copy of the standard becomes available | **Re-open the module.** Statements classified as interpretation may become verifiable — or may be found wrong |
| A Harrismith controlled document changes | Re-verify H1, H2, H3 against Git |

**Re-verification is not optional before delivery.** Two of the nine sources
carry HIGH supersession risk, and both are the standards themselves.

## 8. What this register does not do

- It does **not** authorise reproduction of any ISO content.
- It does **not** establish that any standard applies to any project.
- It does **not** make Harrismith conformant with anything.
- It does **not** substitute for reading the standard where the exact requirement
  matters.
- It carries **no governance authority**. It controls teaching material only.
