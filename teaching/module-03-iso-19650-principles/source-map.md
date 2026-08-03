# Module 3 — Source Map, Mapping Method and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for the developed slides, the method by which
Harrismith may be mapped to ISO-associated concepts, and the list of claims that
**may not be made** in this module under any circumstances.

Source identifiers `X1`–`X6`, `H1`–`H3` are defined in
[`external-source-register.md`](external-source-register.md).

---

## 1. Classification scheme

| Class | Meaning | Authority level |
|---|---|---|
| **`PUBLIC-SOURCE`** | Direct official public-source statement — ISO public metadata | **A1** |
| **`GUIDANCE`** | Official implementation guidance, jurisdiction-bound | **A2** |
| **`HARRISMITH`** | Harrismith project evidence, explicit in a controlled document | **A3** |
| **`INTERP`** | Supported interpretation — follows from the above; no source phrases it this way | **A4** |
| **`SYNTH`** | Teaching synthesis — presenter framing, no source support | **A5** |
| **`UNRESOLVED`** | An open matter, presented as open | — |
| **`EXCLUDED`** | Considered and deliberately left out as unsupported | — |

**Two rules govern the whole module.**

1. **`PUBLIC-SOURCE` is scope, not requirement.** Every A1 statement in this
   module describes *what a standard is stated to cover*. None describes what it
   requires, because the text has not been read.
2. **`GUIDANCE` is never promoted to `PUBLIC-SOURCE`.** A UK convention stays a
   UK convention no matter how sensible it sounds.

## 2. Source hierarchy in force

| Level | Class | May be overwritten by |
|---|---|---|
| 1 | `PUBLIC-SOURCE` | Nothing below it |
| 2 | `GUIDANCE` | Nothing below it |
| 3 | `HARRISMITH` | Nothing below it |
| 4 | `INTERP` | — |
| 5 | `SYNTH` | — |

**A lower level never silently overwrites a higher one.** Where a Harrismith
statement and a public-source statement appear to conflict, both are recorded and
the conflict is stated — it is not resolved by preferring the convenient one.

## 3. Fields recorded for each statement

| Field | |
|---|---|
| **ID** | `M3-S<slide>-<nn>` |
| **Statement** | What is taught |
| **Source** | Register identifier, or *none* |
| **Level** | A0–A5 |
| **Jurisdiction** | International · United Kingdom · This project · — |
| **Publication status** | Published · Draft · Living guidance · Approved with conditions · — |
| **Class** | From §1 |
| **Teaching use** | What it may be used for |
| **Warning** | The failure mode it invites |

---

## 4. Statement classification — Slides 1–3

**33 statements. 10 `PUBLIC-SOURCE`, 0 `GUIDANCE`, 8 `HARRISMITH`, 5 `INTERP`,
4 `SYNTH`, 2 `UNRESOLVED`, 4 `EXCLUDED`.**

**Of the ten `PUBLIC-SOURCE` statements, four are status statements about the
drafts** (`M3-S3-05`, `M3-S3-06`) or edition currency. Only six describe what the
published parts cover — and all six are scope, not requirement.

**No `GUIDANCE` statement appears in Slides 1–3.** UK BIM Framework material
(`X5`, `X6`) is reserved for Slides 5–8, where the functions-versus-job-titles
point belongs. Introducing it earlier would blur the ISO/guidance boundary at
exactly the moment the audience is forming its idea of what the standard is.

### Slide 1 — ISO 19650 is an information-management framework

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S1-01` | `ISO 19650-1:2018` is the current published edition of Part 1, and concerns concepts and principles for information management using BIM | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S1-02` | Its framework covers exchanging, recording, versioning and organising information | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S1-03` | Its application extends across the asset life cycle | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S1-04` | The framework can be applied across asset types, organisations and procurement strategies | `X2` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S1-05` | *"ISO 19650 is about managing information so that the right people can rely on the right information for the right purpose"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S1-06` | The five-point framing — information for decisions, how it is specified, produced, managed, exchanged and recorded | `X1`, `X2` | A4 | International | Published | **`INTERP`** |
| `M3-S1-07` | The module's central message — a structured approach for defining, producing, exchanging and managing information to support decisions across the life cycle | `X1`, `X2` | A5 | — | — | **`SYNTH`** |
| `M3-S1-08` | Harrismith is **not** ISO-compliant; no compliance is claimed, established or assessed | `H1` §11.2, §13.4 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S1-09` | **No ISO 19650 filename pattern is imposed** on this project | `H1` §11.3 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S1-10` | No copyrighted standards content is reproduced in this repository | `H1` §13.4 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S1-11` | The standard has not been read for this programme; what is taught is public scope | none | — | — | — | **`UNRESOLVED`** |
| `M3-S1-12` | *Any* clause-level requirement of Part 1 | — | — | — | — | **`EXCLUDED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S1-01`–`04` | State in paraphrase what each part is stated to cover | **Scope is not requirement.** Do not extend into obligations, definitions or clauses |
| `M3-S1-05` | The one-line hook that opens the module | **Not an ISO quotation.** If asked "is that from the standard?", the answer is no |
| `M3-S1-06` | The five-point structure of the slide | The wording *information needed for decisions* is the presenter's framing, not a published phrase |
| `M3-S1-07` | The module's spine, repeated at Slides 1 and 14 | Teaching wording derived from supported scope. Never introduced as "ISO says" |
| `M3-S1-08` | The honesty anchor for the whole module | Must be said **on Slide 1**, not saved for Slide 13. An audience that assumes compliance for twelve slides has already learned the wrong thing |
| `M3-S1-09` | Defeats "ISO 19650 is a naming standard" | Do not extend to "ISO has no naming provisions" — unknown |
| `M3-S1-10` | Explains why no ISO text appears in any teaching file | — |
| `M3-S1-11` | Said once, plainly, early | Do not over-apologise. State it and continue |
| `M3-S1-12` | — | **Excluded absolutely.** No clause number appears anywhere in this module |

### Slide 2 — It governs information, not a software platform

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S2-01` | A CDE is an **information-management process supported by technology**; *"it is not a folder tree"* | `H1` §6.1 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S2-02` | Permissions, folder access and platform roles **support** the process; they *"do not create professional or governance authority"* | `H1` §6.9 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S2-03` | State, version, revision, status and suitability are five separate properties; a new platform version *"creates none of the others"* | `H1` §6.8 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S2-04` | Decision precedes configuration — platform change follows a governance decision, not the reverse | `H1` §12.1 | A3 | This project | Approved with conditions | **`HARRISMITH`** |
| `M3-S2-05` | *"Folder names do not themselves prove ISO 19650 governance"* | `H3` | A3 | This project | Controlled record | **`HARRISMITH`** |
| `M3-S2-06` | Technology should implement agreed information-management arrangements | `H1` §6.1, §12.1 | A4 | This project | — | **`INTERP`** |
| `M3-S2-07` | The Module 1 / 2 / 3 connection — method, functions, framework | Modules 1–2 | A4 | This project | — | **`INTERP`** |
| `M3-S2-08` | *"A platform can hold your information. It cannot decide who may rely on it, or for what."* | none | A5 | — | — | **`SYNTH`** |
| `M3-S2-09` | The trap: *"We bought the platform, so we have a CDE"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S2-10` | That any of `M3-S2-01`–`05` is an **ISO** definition or requirement | — | — | — | — | **`EXCLUDED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S2-01`–`04` | The four distinctions the slide is built from, quotable as Harrismith wording | **Harrismith wording, not ISO wording.** The standard may phrase these differently, similarly, or not at all — unverified. Attribute aloud: *"this project's own BEP puts it this way"* |
| `M3-S2-05` | The sharpest single line available on the platform question | Evidence that **this project holds the position** — no evidence about what the standard requires. Both halves must be said |
| `M3-S2-06` | Closes the slide | Presenter's formulation |
| `M3-S2-07` | Fifteen seconds of orientation | **Do not re-teach Modules 1 or 2.** Three lines, then move |
| `M3-S2-08` | The slide's take-away line | Teaching synthesis |
| `M3-S2-09` | Names the misconception out loud | Keep descriptive, not mocking. Half the room has said it |
| `M3-S2-10` | — | **Excluded.** The most likely accidental overclaim in the module: five crisp Harrismith statements about platforms sound exactly like a standard |

### Slide 3 — Part 1 and Part 2 answer different questions

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S3-01` | `ISO 19650-1:2018` is the current published edition of Part 1 | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S3-02` | `ISO 19650-2:2018` is the current published edition of Part 2 | `X2` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S3-03` | Part 2 concerns the information-management process during the **delivery phase**, including the information exchanges within that phase | `X2` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S3-04` | Part 1 provides concepts and principles; its reach is the whole asset life cycle | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S3-05` | Both published editions have **revision projects under development** | `X3`, `X4` | A0 | International | **Draft — non-normative** | **`PUBLIC-SOURCE`** *(status only)* |
| `M3-S3-06` | A Draft International Standard is **not** a current published requirement | `X3`, `X4` | A0 | International | **Draft — non-normative** | **`PUBLIC-SOURCE`** *(status only)* |
| `M3-S3-07` | *"Part 1 explains the conceptual framework; Part 2 applies an information-management process to asset delivery"* | `X1`, `X2` | A4 | International | Published | **`INTERP`** |
| `M3-S3-08` | The *different questions* framing of the comparison | `X1`, `X2` | A4 | International | Published | **`INTERP`** |
| `M3-S3-09` | Draft stage, draft scope, draft content, expected publication dates | — | — | — | — | **`UNRESOLVED`** |
| `M3-S3-10` | Any listing of Part 2's delivery-phase process activities | — | — | — | — | **`EXCLUDED`** |
| `M3-S3-11` | Any other part of the `ISO 19650` series | — | — | — | — | **`EXCLUDED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S3-01`–`04` | The two-column comparison | Scope statements only. **Do not turn either column into a requirement list** |
| `M3-S3-05`–`06` | The required warning, said aloud | Record the revisions; **teach neither**. Do not speculate about content or dates |
| `M3-S3-07`–`08` | The slide's message and framing | Supported interpretation — neither part states it in these words |
| `M3-S3-09` | Answer to *"what's in the new version?"* — **"not established here"** | **Inventing a stage code, a scope or a date is a fabrication.** None is available |
| `M3-S3-10` | — | **Excluded.** A numbered process invented for a slide would be the worst failure in this module: plausible, memorable, and wrong |
| `M3-S3-11` | — | **Excluded.** Other parts exist and are not registered. Name only what `external-source-register.md` holds |

## 5. Harrismith mapping method

The method for Slide 13 and for every later Harrismith reference. **Four
categories. Every mapped item takes exactly one.**

| Category | Meaning | Evidence required |
|---|---|---|
| **`DIRECTLY EVIDENCED ALIGNMENT`** | A Harrismith source **itself states** the relationship to ISO 19650 | An explicit sentence in a controlled document |
| **`LOCAL ANALOGUE OR INTERPRETATION`** | A Harrismith arrangement **illustrates** a principle that public scope supports, without established equivalence | The Harrismith wording, plus a public-scope statement — **and an explicit "this is an analogy"** |
| **`GAP OR UNVERIFIED`** | The relationship cannot be established from available material | A statement of what would be needed to establish it |
| **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | A claim that must not be made | The reason, recorded |

### 5.1 The finding this method produces

**Only one item qualifies as `DIRECTLY EVIDENCED ALIGNMENT`, and it is not an
alignment of practice.**

| Item | Category | Evidence |
|---|---|---|
| ISO 19650 principles **inform** Harrismith's information-management approach | **`DIRECTLY EVIDENCED ALIGNMENT`** | `H1` §11.2, §13.4 — the project states it itself, and states in the same breath that **no compliance is claimed, established or assessed** |

That is a statement about **influence on the approach**, evidenced because the
project made it. Everything else is analogue, gap or exclusion.

**This is the module's central finding and Slide 13's content.** It is not a
weakness in Harrismith — a training implementation that claims influence and
declines to claim conformity is behaving correctly. It is a weakness only in any
presentation that implies more.

### 5.2 Worked mapping — the items requiring most caution

| Harrismith item | ISO-associated concept | Category | Why |
|---|---|---|---|
| `Owner / Appointing Party` (`H1` §4.2) | appointing party | **`LOCAL ANALOGUE OR INTERPRETATION`** | The wording is **not identical**, and no equivalence has been established. Similar concepts, different terms |
| `Lead Delivery Party` (`H1` §4.2, §5.4) | lead appointed party | **`GAP OR UNVERIFIED`** | **Must not silently become `lead appointed party`.** Module 2 recorded `lead appointed party` at **zero** occurrences across `bep/`, `supporting/` and `docs/` |
| *(no Harrismith term)* | appointed party | **`GAP OR UNVERIFIED`** | Absent from the sources. Absence is recorded, not filled |
| `WIP` / `Shared` / `Published / Authorised` / `Record / Retained` (`H2`) | ISO-associated state language | **`LOCAL ANALOGUE OR INTERPRETATION`** | **Resembles** ISO-associated practice; conformity **has not been demonstrated**. Note also that Harrismith uses *Record / Retained*, not *Archived* |
| Responsibility matrices (`H2`) | information-management responsibility allocation | **`LOCAL ANALOGUE OR INTERPRETATION`** | Illustrates the principle; proves nothing about conformity. Every role holder is **TBD** |
| Information delivery schedule (`H2`) | planned information exchange | **`LOCAL ANALOGUE OR INTERPRETATION`** | Illustrates planning. `TRN-E03` is **blocked** — publication authority unresolved — so it illustrates a *plan*, not a working exchange |
| Information container (`H1` §1.1, §6.8) | information container | **`LOCAL ANALOGUE OR INTERPRETATION`** | The term is used in both vocabularies. **Shared vocabulary is not established equivalence** — the ISO definition has not been read |
| Clause-by-clause conformity | — | **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | **No such assessment exists**, and none can be produced from available material |
| Autodesk platform configuration | ISO conformity | **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | No software configuration evidences conformity with anything |

### 5.3 Presentation form

**No green compliance checklist. No ticks. No traffic lights. No percentage.**

A checklist is read as a score, and a score is a conformity claim in a friendlier
typeface. The required form is the four labelled categories, with
`GAP OR UNVERIFIED` and `EXCLUDED` **visibly present and equally weighted** — see
[`visual-demonstration-plan.md`](visual-demonstration-plan.md), visual `V11`.

## 6. Terminology control

**No Harrismith term is replaced by an ISO-associated term anywhere in this
module.**

| Rule | |
|---|---|
| 1 | A Harrismith term is **not** relabelled as ISO terminology because the concepts appear similar |
| 2 | Where both vocabularies appear, they appear in **two visibly separate columns** |
| 3 | Substituting a term is a **mapping decision**. No such decision has been taken, and this module does not take one |
| 4 | Where a Harrismith term has no ISO-associated counterpart — or vice versa — **the gap is shown, not filled** |

**Carried from Module 2** (`module-02-roles-and-responsibilities/source-map.md`
§2): `lead appointed party` and `appointed party` occur **zero** times across
`bep/`, `supporting/` and `docs/`. Module 2 deferred them to Module 3. Module 3
introduces them as **ISO-associated terminology from `X6`, jurisdiction-labelled
UK guidance** — and does not attribute them to Harrismith.

## 7. Prohibited claims

**These may not be made in Module 3, in any file, on any slide, or in answer to
any question.** Not softened, not hedged, not implied.

| # | Prohibited claim | Why it is prohibited |
|---|---|---|
| 1 | **Harrismith conforms to ISO 19650** | `H1` §11.2 and §13.4 expressly claim no compliance; none has been established or assessed |
| 2 | **Autodesk software certifies compliance** | No software certifies conformity with any standard; nothing in `X1`–`X6` supports it |
| 3 | **The UK BIM Framework is ISO itself** | `X5`, `X6` are implementation guidance, **UK jurisdiction**, level A2 |
| 4 | **Draft revisions are current standards** | `X3`, `X4` are non-normative. The 2018 editions are current |
| 5 | **Public abstracts provide complete requirements** | A1 metadata is scope, not requirement |
| 6 | **A role title automatically creates an ISO information-management function** | `X6` states the opposite — functions, not new job titles |
| 7 | **ISO terminology may be substituted into Harrismith without a mapping decision** | §6. No mapping decision has been taken |
| 8 | **Any clause-level requirement not supported by an authorised source** | No clause has been read. **No clause reference appears in this module** |

### 7.1 Additional exclusions recorded in this increment

| # | Excluded | Why |
|---|---|---|
| 9 | Any invented clause number, stage code, draft date or process-activity list | Fabrication. Plausibility makes it worse, not better |
| 10 | Any ISO diagram, table or figure, reproduced or reconstructed | Copyright, and the originals have not been seen |
| 11 | Any quotation from ISO text longer than a brief phrase | Copyright control — [`README.md`](README.md) §6 |
| 12 | Any claim that a Harrismith delivery exchange has occurred | `TRN-E03` is blocked; `T4` cannot proceed while publication authority is unresolved (`H2`) |
| 13 | Any South African implementation requirement | **None registered.** `H1` §13.4: no SANS applicability is asserted |
| 14 | Any Triviron project fact | **No Triviron project information exists in this repository.** Slide 14 asks questions only |

## 8. Unresolved matters carried forward

| # | Unresolved | Resolved by |
|---|---|---|
| 1 | What Parts 1 and 2 actually **require** | A licensed copy of the standard |
| 2 | Whether Harrismith's terms are equivalent to ISO-associated terms | A licensed copy, plus a recorded mapping decision |
| 3 | The content, stage and timing of the revisions (`X3`, `X4`) | Publication, or an authorised source |
| 4 | Whether any South African implementation guidance exists | External research — **outside this specialist's boundary** |
| 5 | Whether Harrismith's state model corresponds to the standard's | A licensed copy; a conformity assessment |
| 6 | What Triviron's jurisdiction, appointments and requirements will be | The Triviron project, when it exists |

**Item 1 is the honest headline of this module.** Everything Module 3 teaches
about ISO 19650 is scope, guidance or analogy. **If the audience needs the
requirement, they need the standard.**

## 9. Status

| Field | Value |
|---|---|
| Statements classified | **Slides 1–3 — 33 statements** |
| `PUBLIC-SOURCE` | 10 — of which **6 describe scope**, 4 record edition or draft status |
| `GUIDANCE` | **0** — reserved for Slides 5–8 |
| `HARRISMITH` | 8 |
| `INTERP` | 5 |
| `SYNTH` | 4 |
| `UNRESOLVED` | 2 statement-level, plus 6 module-level (§8) |
| `EXCLUDED` | 4 statement-level, plus 14 prohibited claims (§7) |
| Slides 4–14 | **Not classified.** Not developed |
| Mapping method | **Established (§5)** — applied fully at Slide 13 |
| Clause references used | **Zero** |
</content>
</invoke>
