# Module 3 — Source Map, Mapping Method and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for the developed slides — **Slides 1–12** — the
method by which Harrismith may be mapped to ISO-associated concepts, and the list
of claims that **may not be made** in this module under any circumstances.

**Harrismith statements from Slide 4 onward carry a mapping sub-category**:
*analogue*, *gap or unverified*, or *excluded conformity inference*. See §5.
**Slide 8 additionally carries a vocabulary relationship register** — established,
possible, unverified or excluded — for every term compared.

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

## 4. Statement classification — Slides 1–12

**201 statements across twelve slides. 17 `PUBLIC-SOURCE`, 8 `GUIDANCE` (all UK),
72 `HARRISMITH`, 34 `INTERP`, 17 `SYNTH`, 13 `UNRESOLVED`, 40 `EXCLUDED`.**

| Slide | Statements | `PUB` | `GUID` | `HARR` | `INT` | `SYN` | `UNR` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 4 | 0 | 3 | 1 | 2 | 1 | 1 |
| 2 | 10 | 0 | 0 | 5 | 2 | 2 | 0 | 1 |
| 3 | 11 | 6 | 0 | 0 | 2 | 0 | 1 | 2 |
| **4** | **17** | **2** | **0** | **3** | **6** | **2** | **1** | **3** |
| **5** | **16** | **1** | **2** | **7** | **1** | **1** | **1** | **3** |
| **6** | **17** | **1** | **1** | **2** | **6** | **2** | **1** | **4** |
| **7** | **16** | **0** | **3** | **5** | **3** | **1** | **1** | **3** |
| **8** | **18** | **0** | **2** | **7** | **0** | **2** | **3** | **4** |
| **9** | **22** | **1** | **0** | **9** | **4** | **1** | **1** | **6** |
| **10** | **23** | **1** | **0** | **12** | **3** | **1** | **1** | **5** |
| **11** | **19** | **1** | **0** | **9** | **3** | **1** | **1** | **4** |
| **12** | **20** | **0** | **0** | **10** | **3** | **2** | **1** | **4** |
| **Total** | **201** | **17** | **8** | **72** | **34** | **17** | **13** | **40** |

**Five observations from the totals.**

**Harrismith carries the module, and increasingly so.** 72 of 201 statements,
against 17 public-source and 8 guidance. Sections D and E draw **31 of their 62
statements** from this project. That ratio is the honest shape of a module whose
subject is a document the programme does not hold: the principles are external,
and **every concrete illustration is this project's own**.

**Four slides have no `PUBLIC-SOURCE` statement at all** — Slides 2, 7, 8 and 12.
Each is built entirely from Harrismith evidence, UK guidance or presenter
framing, and each carries the same delivery obligation: **attribute, or the
audience hears ISO.**

**`GUIDANCE` appears on four slides only — 5, 6, 7 and 8 — and nowhere after.**
`X5` and `X6` register nothing about common data environments, delivery planning
or implementation evidence, so **Slides 10, 11 and 12 attribute nothing to them.**
An absence of guidance is recorded rather than filled.

**Slide 10 is the most Harrismith-dependent slide in the module** — 12 of 23
statements, and four of them gaps. It is also the slide where a **diagram can
overclaim without a word being spoken**; see prohibitions 34 and 36.

**`EXCLUDED` has grown faster than any other class** — 40 statements, plus 40
prohibited claims. In Sections D and E that is deliberate: the closer the module
gets to *how it is done*, the more of its content is a boundary.

### 4.0 Slides 1–3 — summary

**33 statements. 10 `PUBLIC-SOURCE`, 0 `GUIDANCE`, 8 `HARRISMITH`, 5 `INTERP`,
4 `SYNTH`, 2 `UNRESOLVED`, 4 `EXCLUDED`.**

**Of the ten `PUBLIC-SOURCE` statements, four are status statements about the
drafts** (`M3-S3-05`, `M3-S3-06`) or edition currency. Only six describe what the
published parts cover — and all six are scope, not requirement.

**No `GUIDANCE` statement appears in Slides 1–3.** UK BIM Framework material
(`X5`, `X6`) is held back until Slide 5, and does its heaviest work on Slides 7
and 8. Introducing it earlier would blur the ISO/guidance boundary at exactly the
moment the audience is forming its idea of what the standard is.

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

### Slide 4 — Information management runs across the asset life cycle

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S4-01` | Part 1's application **extends across the asset life cycle** | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S4-02` | Part 2 concerns the **delivery phase** — a narrower span than Part 1's | `X2` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S4-03` | The six phases — initiation, design and delivery, construction, commissioning and handover, operation and maintenance, alteration or end of life | `X1` | A4 | International | Published | **`INTERP`** |
| `M3-S4-04` | **These are neutral teaching labels, not ISO-defined phase names** | none | A4 | — | — | **`INTERP`** *(limitation)* |
| `M3-S4-05` | Each phase contains decisions that information serves | `X1` | A4 | International | Published | **`INTERP`** |
| `M3-S4-06` | *"The value of information is not confined to producing the model; it lies in supporting decisions throughout the life of the asset"* | `X1` | A4 | International | Published | **`INTERP`** |
| `M3-S4-07` | The asset outlives the delivery team; information must remain understandable beyond its authoring context | `X1` | A4 | International | Published | **`INTERP`** |
| `M3-S4-08` | Delivery-phase information contributes to later operational decisions | `X1`, `X2` | A4 | International | Published | **`INTERP`** |
| `M3-S4-09` | Information created without an identified future purpose has little lasting value | none | A5 | — | — | **`SYNTH`** |
| `M3-S4-10` | Life-cycle continuity is continuity of **managed information**, not the survival of one unchanged model | none | A5 | — | — | **`SYNTH`** |
| `M3-S4-11` | Harrismith places **asset management, handover and standards verification outside current scope** — *"not current requirements and not part of the current baseline scope"* | `H1` §3.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S4-12` | *Record / handover information* appears only as an **example purpose**, *"not current project milestones"* | `H1` §6.7, §10.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S4-13` | Harrismith's own *lifecycle* wording describes the **information container**, not the asset | `H1` §2.2, §7.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S4-14` | Any ISO-defined phase name, numbered stage or stage model | — | — | — | — | **`EXCLUDED`** |
| `M3-S4-15` | Any reproduced or reconstructed ISO life-cycle diagram | — | — | — | — | **`EXCLUDED`** |
| `M3-S4-16` | Any operational, facilities-management or asset-information requirement for Harrismith | — | — | — | — | **`EXCLUDED`** |
| `M3-S4-17` | What, if anything, the published parts require of the operational phase | — | — | — | — | **`UNRESOLVED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S4-01` | The slide's single external anchor | **Reach, not requirement.** It says where the framework applies, not what it demands there |
| `M3-S4-02` | The contrast that keeps Slide 3 straight | Do not re-teach Slide 3 |
| `M3-S4-03`–`05` | The ribbon's content | **Say "my words, not official phase names" while the visual is up.** Never number them |
| `M3-S4-06` | The required message | Supported interpretation. Not a quotation |
| `M3-S4-07` | The slide's take-away | The strongest point available; deliver it as reasoning, not as a requirement |
| `M3-S4-08` | Links Section B forward | — |
| `M3-S4-09` | Closes the argument | Teaching synthesis |
| `M3-S4-10` | **Kills the eternal-model misreading** | Must be said. An audience that keeps this belief will later accept a maintenance obligation nobody can meet |
| `M3-S4-11`–`12` | The Harrismith gap, delivered as a **deliberately drawn boundary** | **Not a failure and not non-conformity.** The BEP records the boundary rather than leaving it to be discovered |
| `M3-S4-13` | Precision, if the seconds exist | Conflating the two spans would put an asset-life-cycle claim into a document that makes none |
| `M3-S4-14`–`16` | — | **Excluded.** `M3-S4-16` matters most: a hypothetical operational requirement gets remembered as a plan |
| `M3-S4-17` | Answer: *"I don't know — that needs the standard"* | — |

### Slide 5 — Information requirements come before information production

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S5-01` | Information-management requirements should be established **appointment by appointment** | **`X6`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S5-02` | Information management is intended to improve the **specification**, production, review and transfer of information | **`X5`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S5-03` | Part 1's framework covers exchanging, recording, versioning and organising information | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S5-04` | *"Production begins from a requirement, not from availability of time or tools"* | `H1` §7.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S5-05` | *"Information production is driven by **defined requirements**, not by assumption about what might be wanted"* | `H1` §7.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S5-06` | A requirement may specify the container, originator, intended recipient, purpose, format, the exchange it serves, the checking requirement, the authorisation requirement and dependencies | `H1` §7.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S5-07` | A delivery is tied to a need, a recipient, a purpose, timing, required content, format, readiness and authorisation | `H1` §10.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S5-08` | The six-step sequence: **decision or purpose → information need → defined requirement → planned production → checked delivery → use** | `H1` §7.1, §10.1 | A4 | This project | — | **`INTERP`** |
| `M3-S5-09` | *"No formal information requirements are available to this implementation"* | `H1` §7.3, §10.2 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S5-10` | Unavailable requirements **are not invented**; training-developed requirements are labelled **PROPOSED GOVERNANCE or TRAINING ASSUMPTION** | `H1` §7.3, §10.2 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S5-11` | *"Information production should be a response to an identified need — not an activity that searches for a purpose afterwards"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S5-12` | Procurement route, contract type, contractual milestones and final delivery programme are **not established — TBD** | `H1` §2.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S5-13` | Any information-requirement acronym, used as teaching vocabulary or defined | — | — | — | — | **`EXCLUDED`** |
| `M3-S5-14` | The six-step sequence presented as Part 2's process | — | — | — | — | **`EXCLUDED`** |
| `M3-S5-15` | Harrismith's absent requirements presented as ISO non-conformity | — | — | — | — | **`EXCLUDED`** |
| `M3-S5-16` | Whether the published standard itself requires requirements to be established appointment by appointment | — | — | — | — | **`UNRESOLVED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S5-01` | The slide's one guidance idea | **`OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT`.** Labelled on the slide and aloud. **Never** *"ISO requires this appointment workflow"* |
| `M3-S5-02` | Optional supporting framing | Same labelling obligation. Drop it under time pressure rather than deliver it unlabelled |
| `M3-S5-03` | The published framing for *specifying* | Scope, not requirement |
| `M3-S5-04`–`05` | The two quotable lines the slide is built on | **Harrismith wording.** Attribute — *"our BEP says"* |
| `M3-S5-06`–`07` | The seven requirement questions | Our BEP's fields, not a standard's. **This is not a template**, and building one is Module 5's territory at most |
| `M3-S5-08` | The sequence, and the visual `V4` | **Teaching structure.** Not Part 2's process |
| `M3-S5-09`–`10` | The gap, delivered as **discipline rather than deficiency** | Saying *we don't know* is harder than guessing, and BEP §1.5 means real requirements would take precedence over anything developed in their absence |
| `M3-S5-11` | The required message | Teaching synthesis |
| `M3-S5-12` | Why the delivery schedule uses event triggers and TBDs rather than dates | Do not invent a date to make an example work |
| `M3-S5-13` | — | **Excluded.** BEP §7.3 names some requirement documents **only to record that none was made available**. That is Harrismith noting an absence, **not this module defining vocabulary**. Do not explain what any of them contains |
| `M3-S5-14`–`15` | — | **Excluded.** `M3-S5-15` is the likeliest live error: *"we have no requirements"* invites *"so we're not compliant?"* |
| `M3-S5-16` | Answer: guidance says so; the standard has not been read | — |

### Slide 6 — The right information, not simply more information

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S6-01` | Information management is intended to improve the specification, production, **review and transfer** of information | **`X5`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S6-02` | Part 1's framework covers organising information across the life cycle | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S6-03` | Information is proportionate to the **decision, recipient, delivery event, asset or element, required reliability and context of use** | `H1` §6.1, §7.3, §10.1 | A4 | This project | — | **`INTERP`** |
| `M3-S6-04` | The **more information / right information** two-column comparison | `H1` §1.1, §6.1, §7.3 | A5 | — | — | **`SYNTH`** |
| `M3-S6-05` | **Completeness is purpose-dependent** — *complete for what* is the answerable question | `H1` §6.1 | A4 | This project | — | **`INTERP`** |
| `M3-S6-06` | More detail increases the coordination, checking, revision and maintenance burden | none | A4 | — | — | **`INTERP`** |
| `M3-S6-07` | Unnecessary information creates cost and ambiguity | none | A4 | — | — | **`INTERP`** |
| `M3-S6-08` | **Insufficient information creates decision risk** | none | A4 | — | — | **`INTERP`** |
| `M3-S6-09` | **Level of information need — *"Not defined"*.** It *"has not been established for any container"* and is *"recorded as an information gap"* | `H2` — model / information responsibility matrix §4 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S6-10` | Level of information need is *"**not** assumed from discipline convention or inferred from observed model content"* | `H2` — same §4 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S6-11` | *"The target is not maximum information. It is sufficient, reliable information for the stated purpose"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S6-12` | The **general concept** that required detail and reliability depend on purpose, in plain words | `H2` §4 | A4 | — | — | **`INTERP`** |
| `M3-S6-13` | Any **formal definition** of level of information need | — | — | — | — | **`EXCLUDED`** |
| `M3-S6-14` | Any geometric / alphanumeric / documentation breakdown, or any level, grade, scale or numbered tier | — | — | — | — | **`EXCLUDED`** |
| `M3-S6-15` | Any model-detail or production requirement invented for the fire station | — | — | — | — | **`EXCLUDED`** |
| `M3-S6-16` | That more detail means greater conformity | — | — | — | — | **`EXCLUDED`** |
| `M3-S6-17` | What the published standard's treatment of level of information need actually is | — | — | — | — | **`UNRESOLVED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S6-01` | Optional framing | **UK-labelled** if used. The slide works without it |
| `M3-S6-02` | The published framing | Scope, not requirement |
| `M3-S6-03` | The six proportionality factors | **No source lists these six.** Presenter's construction from our BEP's fields |
| `M3-S6-04` | The comparison, and visual `V5` | **Teaching examples, not ISO quotations, and not a conformity checklist** |
| `M3-S6-05`–`08` | The five things to say about proportion | **`M3-S6-08` must be said.** Without it the slide teaches minimalism, which is the opposite of proportion |
| `M3-S6-09`–`10` | The Harrismith position, quotable almost verbatim | `M3-S6-10` is the sharper half: **what is in the models is not what was required.** Same move as *folder names do not prove governance* |
| `M3-S6-11` | The required message | Teaching synthesis |
| `M3-S6-12` | **The only permitted treatment of the term** — plain concept, then stop | Anything beyond plain language is invented. *"I'd be making it up"* is the better answer |
| `M3-S6-13`–`14` | — | **Excluded.** The commonest live failure in this module: a half-remembered breakdown delivered with confidence |
| `M3-S6-15` | — | **Excluded.** An off-the-cuff detail example becomes a production expectation two meetings later |
| `M3-S6-16` | — | **Excluded.** Detail is not conformity, and no conformity assessment exists |
| `M3-S6-17` | Answer: *"there is a defined treatment; I don't have it, and that's a licensed-copy conversation"* | — |

### Slide 7 — Information-management functions are not automatically job titles

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S7-01` | The standard is explained in terms of **information-management functions rather than requiring new job titles** | **`X6`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S7-02` | The **appointing party** must ensure the information-management function is fulfilled | **`X6`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S7-03` | The **lead appointed party** must also ensure the relevant information-management function is fulfilled | **`X6`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S7-04` | Five layers held apart: required activity · project function · appointment · job title · individual participant | `X6`, `H1` §4.6 | A4 | — | — | **`INTERP`** |
| `M3-S7-05` | A function describes **what must be performed**, not who performs it or what they are called | `X6`, `H1` §4.6 | A4 | — | — | **`INTERP`** |
| `M3-S7-06` | One participant may carry more than one function | `H1` §4.6, §5.11 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S7-07` | *"Combining roles does not combine the functions"*; the participant must know **which function they are performing at each decision point** | `H1` §5.11 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S7-08` | Author and Checker may combine where independence is unavailable — the functional distinction remains, and **"independence is never claimed where it does not exist"** | `H1` §5.8 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S7-09` | **"Platform access is not delegation"** | `H1` §5.11 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S7-10` | Harrismith defines BIM Manager, BIM Coordinator, CDE Administration, Lead Delivery Party, Task-Team Lead, Author and Checker — and **populates no named holder for any of them** | `H1` §4.6, §5.7–§5.9 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S7-11` | A title alone does not prove the function has been formally assigned | `H1` §5.11 | A4 | — | — | **`INTERP`** |
| `M3-S7-12` | *"The important question is not whether a title exists; it is whether the information-management function is assigned, understood and performed"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S7-13` | *"ISO 19650 says no BIM Manager is required"* | — | — | — | — | **`EXCLUDED`** |
| `M3-S7-14` | Title equals function; person equals function | — | — | — | — | **`EXCLUDED`** |
| `M3-S7-15` | Any named holder, appointment or organisation invented for Harrismith | — | — | — | — | **`EXCLUDED`** |
| `M3-S7-16` | Whether the published standard itself requires any particular function or title | — | — | — | — | **`UNRESOLVED`** |

**No `PUBLIC-SOURCE` statement appears on this slide.** Its entire external basis
is UK guidance; everything concrete is Harrismith. Slide 2 has the same shape, and
the same delivery obligation: **attribute, or the audience hears ISO.**

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S7-01`–`03` | The slide's whole external basis | **`OFFICIAL IMPLEMENTATION GUIDANCE — UK CONTEXT`**, labelled on the slide and aloud. The obligation described is to **ensure a function is fulfilled**, not to create a post |
| `M3-S7-04`–`05` | The five-layer separation | Presenter's structure. Layers 1–3 must exist for a project to work; layer 4 is optional and layer 5 changes |
| `M3-S7-06`–`09` | The Harrismith illustration | **Our BEP's wording.** §5.11's one-person-one-minute example is the fastest route to the point |
| `M3-S7-10` | Functions defined, holders empty | **A deliberate planning state**, not an unfinished document — carried from Module 2 §8 |
| `M3-S7-11` | Closes the title question | — |
| `M3-S7-12` | The required message | Teaching synthesis |
| `M3-S7-13` | — | **Excluded — prohibition 21.** The likeliest over-extension in Section C. The guidance describes functions; it does not tell us what the standard requires about titles |
| `M3-S7-14` | — | **Excluded — prohibitions 22, 23** |
| `M3-S7-15` | — | **Excluded.** An invented example creates an appointment out of a teaching aid |
| `M3-S7-16` | Answer: *"I can't tell you — that's a licensed-copy question"* | — |

### Slide 8 — The parties, the teams and the vocabulary gap

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S8-01` | **appointing party** — an ISO-associated party term | **`X6`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S8-02` | **lead appointed party** — an ISO-associated party term | **`X6`** | **A2** | **UNITED KINGDOM** | Living guidance | **`GUIDANCE` — UK CONTEXT** |
| `M3-S8-03` | **appointed party** — named as an ISO-associated term; **no registered source defines it** | — | — | — | — | **`UNRESOLVED`** |
| `M3-S8-04` | **delivery team** and **task team** as ISO-associated team vocabulary — named; **no registered source defines either** | — | — | — | — | **`UNRESOLVED`** |
| `M3-S8-05` | Harrismith uses `Owner / Appointing Party` and `Appointing Party` — **19 occurrences** | `H1` §4.2; verified across `bep/`, `supporting/`, `docs/` | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S8-06` | Harrismith uses `Lead Delivery Party` — **20 occurrences** | `H1` §4.2, §5.4 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S8-07` | **`lead appointed party` and `appointed party` occur ZERO times** across `bep/`, `supporting/` and `docs/` | Verified count | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S8-08` | `task team` occurs **164 times** and is a defined structure — including that Mechanical, Electrical and Plumbing are **three task teams within one MEP Consultant party** | `H1` §4.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S8-09` | `delivery team` appears **once**, incidentally in prose (`H1` IM-08), and is **not a defined Harrismith term** | Verified count | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S8-10` | Harrismith function terms: `BIM Manager`, `BIM Coordinator`, `Task-Team Lead`, `Author`, `Checker`, `CDE Administration` | `H1` §4.6, §5.5–§5.9 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S8-11` | `Lead Delivery Party` is **not established** as *lead appointed party* | `H1`; absence of any mapping decision | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S8-12` | *"Similar words do not establish equivalent appointments; project terminology must be mapped deliberately"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S8-13` | *Possible conceptual relationship ≠ verified terminological identity* | none | A5 | — | — | **`SYNTH`** |
| `M3-S8-14` | `Lead Delivery Party` = *lead appointed party* | — | — | — | — | **`EXCLUDED`** |
| `M3-S8-15` | consultant = *appointed party*; contractor = *appointed party* | — | — | — | — | **`EXCLUDED`** |
| `M3-S8-16` | `Task-Team Lead` = *lead appointed party* | — | — | — | — | **`EXCLUDED`** |
| `M3-S8-17` | Shared task-team terminology as proof of ISO conformity | — | — | — | — | **`EXCLUDED`** |
| `M3-S8-18` | Whether **any** Harrismith term is equivalent to **any** ISO-associated term | — | — | — | — | **`UNRESOLVED`** |

**Vocabulary relationship register — the required record for every comparison**

| ISO-associated term | Harrismith term | Relationship |
|---|---|---|
| appointing party | `Owner / Appointing Party` · `Appointing Party` | **POSSIBLE** — wording close, **not identical; equivalence not established** |
| lead appointed party | `Lead Delivery Party` | **UNVERIFIED** — conceptually adjacent; **identity excluded** (`M3-S8-14`) |
| appointed party | *(none)* | **NO COUNTERPART** — zero occurrences; **absence shown, not filled** |
| delivery team | *(none defined)* | **NO COUNTERPART** — one incidental prose use is not a defined term |
| task team | `task team` | **SHARED WORD, UNVERIFIED** — same word, different defined content; **shared vocabulary is not established equivalence** |
| *(none registered)* | `BIM Manager` · `BIM Coordinator` · `Task-Team Lead` · `Author` · `Checker` · `CDE Administration` | **NOT COMPARED** — no ISO-associated counterpart is registered |

**No relationship in this register is `ESTABLISHED`.** That is the finding, and
Slide 8 exists to make it visible rather than to resolve it.

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S8-01`–`02` | The two registered ISO-associated terms | **UK guidance, labelled.** `X1`/`X2` public metadata supplies **no** party definitions and must not be presented as doing so |
| `M3-S8-03`–`04` | Named, not defined | Say the distinction aloud — it is unusual, honest, and it explains why the slide will not map anything |
| `M3-S8-05`–`06`, `08`, `10` | The Harrismith column | **Exact source terms only.** No substitution, no modernisation, no "equivalent to" |
| `M3-S8-07` | **The slide's central fact** | Independently verified. It is the reason no mapping can be asserted |
| `M3-S8-09` | The `delivery team` finding | One incidental use in prose is **not** adoption of a term |
| `M3-S8-11` | The answer to the question that will be asked | *Not established* — not *no*, and not *probably yes* |
| `M3-S8-12`–`13` | The slide's message and governing rule | Teaching synthesis |
| `M3-S8-14`–`17` | — | **Excluded — prohibitions 24, 25, 26.** `M3-S8-14` is the module's single likeliest live error, and **layout alone can commit it** |
| `M3-S8-18` | Answer: a mapping decision nobody has taken | — |

### Slide 9 — Information containers make responsibility manageable

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S9-01` | Part 1's framework covers exchanging, recording, versioning and **organising** information | `X1` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S9-02` | Working description — a **managed unit of information for which responsibility, status, revision and permitted use can be controlled** | `H1` §1.1, §6.8, §7.2 | A4 | This project | — | **`INTERP`** |
| `M3-S9-03` | Examples — model, drawing, schedule, specification, report, data file — **illustrative, not exhaustive and not normative** | `H1` §10.4 | A4 | This project | — | **`INTERP`** |
| `M3-S9-04` | Origination chain: `party → task team → discipline → information container` | `H1` §7.2 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-05` | **Originator responsibility remains with the producing task team** through sharing, consumption, coordination and publication — *"no downstream act relieves it"* | `H1` §7.2 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-06` | **"Authorship is not inferred from folder location. Where a container sits tells you where it sits. The originator is recorded, not deduced."** | `H1` §7.2 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-07` | **"Federation does not merge authorship or responsibility"** — each contributed container *"keeps its originator, its state and its technical responsibility"* | `H1` §6.6 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-08` | Federation does not merge authorship, transfer technical ownership, create a new design author, or turn discipline models into one jointly-owned model; it is *"a lens"* | `H1` §8.5 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-09` | **"Consumption does not transfer originator technical responsibility"**; the receiver remains responsible for how it uses the information; *"both responsibilities exist at once"* | `H1` §7.9, §6.5 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-10` | Container classes `ARC-01`, `STR-01`, `MEC-01`, `ELE-01`, `PLM-01`, `FIR-01`, each with a recorded originating party and task team | `H2` — model / information responsibility matrix §3.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-11` | Every allocation is **PROPOSED GOVERNANCE**; no organisation appointed, no holder established; the matrix is *"intended governance, not live inventory"* | `H2` §3, purpose statement | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S9-12` | A model is **one possible container**, not the whole information environment | `H1` §10.4 | A4 | This project | — | **`INTERP`** |
| `M3-S9-13` | An information container is **not necessarily a single file** in every implementation | none | A4 | — | — | **`INTERP`** |
| `M3-S9-14` | *"By managing information in identifiable containers, the project can assign responsibility, control use and retain traceability without treating all project information as one undifferentiated model"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S9-15` | Controlled states **exist** — brief callback only | `H2` CDE strategy | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S9-16` | Any formal ISO definition of *information container* | — | — | — | — | **`EXCLUDED`** |
| `M3-S9-17` | *Information container* = a Revit file in every case | — | — | — | — | **`EXCLUDED`** |
| `M3-S9-18` | A federated model merging ownership | — | — | — | — | **`EXCLUDED`** |
| `M3-S9-19` | Folder location proving status | — | — | — | — | **`EXCLUDED`** |
| `M3-S9-20` | Controlled sharing transferring technical responsibility | — | — | — | — | **`EXCLUDED`** |
| `M3-S9-21` | CDE state mechanics, transition authority, metadata schemas, naming syntax, revision coding, suitability coding, container breakdown structures | — | — | — | — | **`EXCLUDED` — Modules 4 and 5** |
| `M3-S9-22` | Whether Harrismith's containers correspond to the standard's | — | — | — | — | **`UNRESOLVED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S9-01` | The one external statement, framing only | Scope, not requirement |
| `M3-S9-02` | The working description | **Not a definition, and not quoted.** The term appears in both vocabularies; **shared vocabulary is not established equivalence** |
| `M3-S9-03` | The examples | **Say *illustrative* aloud.** Six items on a slide read as a closed set otherwise |
| `M3-S9-04`–`06` | The origination chain and the folder line | **Our BEP's wording.** §7.2's *"the originator is recorded, not deduced"* is the sharpest line on the slide |
| `M3-S9-07`–`08` | The federation point | The most surprising item for most audiences, and the one that prevents a federated view being treated as a deliverable |
| `M3-S9-09` | Consumption | Both responsibilities exist at once. Audiences get this wrong in **both** directions |
| `M3-S9-10` | The container classes | Note `MEC`/`ELE`/`PLM` sit in **one** MEP Consultant party — three task teams, not three companies |
| `M3-S9-11` | The honesty marker | **Intended governance, not live inventory.** The matrix says what is intended to be produced, not what exists in the CDE |
| `M3-S9-12`–`13` | The two containment cautions | — |
| `M3-S9-14` | The required message | Teaching synthesis |
| `M3-S9-15` | One sentence, then stop | **The module boundary.** *States exist* is permitted; how a container moves is Module 4 |
| `M3-S9-16`–`20` | — | **Excluded — prohibitions 27–30** |
| `M3-S9-21` | — | **Excluded.** Slide 9 sits one sentence from Module 4 throughout. If a sentence begins *"and then it goes to…"*, stop |
| `M3-S9-22` | Answer: unverified, and unverifiable from available material | — |

### Slide 10 — The CDE controls permitted use and exchange

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S10-01` | Part 2 concerns the information-management process during the delivery phase, **including the information exchanges within it** | `X2` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S10-02` | A CDE supports controlled availability, traceability, version awareness, defined purposes of use, managed exchange, and **separation of information under development from information permitted for broader reliance** | `H1` §6.1 | A4 | This project | — | **`INTERP`** |
| `M3-S10-03` | A CDE is *"an information-management process supported by technology… it is not a folder tree"* | `H1` §6.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-04` | **Platform ≠ CDE governance** | `H1` §6.1 | A4 | This project | — | **`INTERP`** |
| `M3-S10-05` | **Folder location ≠ information status** | `H1` §7.2, §6.8 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-06` | **Access permission ≠ authority** — permissions *"do not create professional or governance authority"* | `H1` §6.9 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-07` | **Technical movement ≠ authorised state transition** — decision precedes configuration | `H1` §12.1, §6.8 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-08` | Information can exist in a platform **without being authorised for the next purpose** — *presence is not trust*; visibility of WIP is not permission to rely on it | `H1` §6.1, §7.5 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-09` | The four states — **WIP · Shared · Published / Authorised · Record / Retained** — and what each is for | `H2` CDE strategy §1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-10` | **`WIP → Shared` (T1)** has an established authorising function — the **Task-Team Lead** | `H2`; `H1` §9.4 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-11` | **`Shared → Published / Authorised` (T4) is BLOCKED.** Publication / exchange authority is **UNRESOLVED — TBD** | `H2` §11; `H1` §9.7; IM matrix D4 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S10-12` | *"Transition **T4** therefore has **no available authorising function**, and information remains **Shared**"* | `H2` §11 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S10-13` | **`TRN-E03` is PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS** | `H2` delivery schedule §5 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S10-14` | *"The block is represented deliberately and is a feature of the model, not a gap in it: **governance can intentionally stop a workflow**. A route that cannot legitimately proceed should visibly halt, rather than complete itself by borrowing an authority nobody granted."* | `H2` §11 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S10-15` | **Record / Retained is a conceptual state and a retention requirement — *"not necessarily a folder"*.** **No mandatory CDE root named `04 Archive` is required or approved**; the retention approach is **TBD** | `H2` §1; `H1` §6.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S10-16` | The Modules 1 / 2 / 3 connection — the BEP records the method; assigned functions hold authority; the CDE implements those arrangements | Modules 1–2; `H1` §5.9 | A4 | This project | — | **`INTERP`** |
| `M3-S10-17` | *"A CDE does not merely store information; it controls the conditions under which information may be used and exchanged"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S10-18` | Any **complete operating `Shared → Published` route** | — | — | — | — | **`EXCLUDED`** |
| `M3-S10-19` | ACC or any platform automatically being a conforming CDE | — | — | — | — | **`EXCLUDED`** |
| `M3-S10-20` | Shared automatically meaning **approved** | — | — | — | — | **`EXCLUDED`** |
| `M3-S10-21` | Record / Retained shown as an `04 Archive` folder | — | — | — | — | **`EXCLUDED`** |
| `M3-S10-22` | Transition mechanics, transition authority, evidence requirements, naming or suitability codes, metadata, folder-by-folder workflows, the complete state diagram | — | — | — | — | **`EXCLUDED` — Module 4** |
| `M3-S10-23` | Whether the published standard requires any particular state model or CDE structure | — | — | — | — | **`UNRESOLVED`** |

**No `GUIDANCE` statement appears on this slide.** `X5` and `X6` register nothing
about common data environments or state models, and nothing is attributed to them.

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S10-01` | The framing | Scope, not requirement. **No ISO CDE definition exists in this programme's material** |
| `M3-S10-02` | The six capabilities | **Not an ISO definition.** Built from our BEP's CDE principles |
| `M3-S10-03`–`08` | The six distinctions | **Harrismith wording.** Attribute — *"our BEP says"* |
| `M3-S10-09` | The four states | **`LOCAL ANALOGUE OR INTERPRETATION`.** They resemble ISO-associated practice; **conformity has not been demonstrated**, and no ISO state model has been seen |
| `M3-S10-10` | The one route that works | Established authority — say so, or the whole model reads as blocked |
| `M3-S10-11`–`13` | **The mandatory blocked-transition treatment** | **Must appear.** A solid route through Published claims a workflow this project cannot operate |
| `M3-S10-14` | **The best line on the slide** | Converts an apparent deficiency into the clearest demonstration of the principle. **Do not remove the block to tidy the diagram** |
| `M3-S10-15` | The Record / Retained caution | **Not a folder.** Drawing an archive folder invents an unapproved requirement |
| `M3-S10-16` | Three lines of orientation | Do not re-teach Modules 1 or 2 |
| `M3-S10-17` | The required message | Teaching synthesis |
| `M3-S10-18`–`21` | — | **Excluded — prohibitions 31, 33, 34, and the `04 Archive` case** |
| `M3-S10-22` | — | **Excluded.** Delivery test: **if the slide explains exactly how a state transition is performed, stop** |
| `M3-S10-23` | Answer: *"I don't know — that needs the standard"* | — |

### Slide 11 — Information delivery must be planned

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S11-01` | Part 2 concerns the delivery phase and **includes the exchanges of information within it** | `X2` | A1 | International | **Published** | **`PUBLIC-SOURCE`** |
| `M3-S11-02` | The chain: **purpose → required information → responsible originator → planned event → checked and authorised delivery → intended recipient and use** | `H1` §10.1, §7.3 | A4 | This project | — | **`INTERP`** |
| `M3-S11-03` | Planned delivery addresses what information, why, who originates, who checks or authorises, who receives, when or at what event, what use it supports, and what dependencies must be satisfied | `H1` §10.1, §7.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S11-04` | **"Presence in Published does not establish a delivery."** Information in a published location has not been delivered to anyone; **delivery is an act with a recipient and a purpose, not a location** | `H1` §10.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S11-05` | **Published, Delivered, Received and Accepted are four distinct states** | `H2` §5.3; `H1` §10.10, §10.11 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S11-06` | *"Delivery does not prove acceptance. Receipt does not prove suitability. Acceptance applies only to the identified purpose, and does not transfer technical responsibility from the originator."* | `H2` §5.3 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S11-07` | **Controlled sharing ≠ publication** | `H2`; `H1` §6.5, §6.7 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S11-08` | **A schedule entry is not evidence that the information exists** | none | A4 | — | — | **`INTERP`** |
| `M3-S11-09` | Planned delivery ≠ completed delivery; a target date ≠ acceptance; an event identifier ≠ an automated trigger; a planned recipient ≠ an established acceptance authority | `H2` | A4 | This project | — | **`INTERP`** |
| `M3-S11-10` | *"Real delivery milestones and dates — **None established.** All timing event-triggered or TBD"* | `H2` delivery schedule §7 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S11-11` | `TRN-E03` remains **BLOCKED**; publication-dependent delivery cannot proceed while publication authority is unresolved | `H2` §5, §5.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S11-12` | Recipient identity **not established**; recipient acceptance authority **UNRESOLVED — TBD** | `H2` §5.1, §6; `H1` §9.8, §10.11 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S11-13` | *"An entry that cannot proceed is recorded as blocked. **Assigning a plausible authority to make the row look finished would manufacture governance that does not exist.**"* | `H2` §5.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S11-14` | *"Planning defines what should be delivered and why; evidence is still required to prove that delivery occurred"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S11-15` | A planned schedule entry proving actual delivery | — | — | — | — | **`EXCLUDED`** |
| `M3-S11-16` | A date proving acceptance | — | — | — | — | **`EXCLUDED`** |
| `M3-S11-17` | Any invented programme date, milestone, recipient or acceptance authority | — | — | — | — | **`EXCLUDED`** |
| `M3-S11-18` | The schedule's field structure, row construction, purpose and suitability mechanics, and the responsibility matrices read row by row | — | — | — | — | **`EXCLUDED` — Module 5** |
| `M3-S11-19` | Whether the published standard requires any particular delivery-planning instrument | — | — | — | — | **`UNRESOLVED`** |

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S11-01` | The framing | Scope, not requirement |
| `M3-S11-02` | The chain, and visual `V9` | **Teaching structure**, not Part 2's process |
| `M3-S11-03` | The planning questions | **A set of questions, not a schedule schema** |
| `M3-S11-04` | The line the slide is built on | Our BEP's wording |
| `M3-S11-05`–`07` | The four states and the sharing/publication split | **Do not re-run Module 2's authority chain.** Name them, show they differ, move |
| `M3-S11-08`–`09` | The planned-versus-actual distinctions | The slide's actual content |
| `M3-S11-10` | **No dates exist** | Say it plainly. Everything is event-triggered or TBD |
| `M3-S11-11`–`12` | The blocked event and the unestablished recipient | Consistent with `M3-S10-11`–`13`. **A timeline drawn as operable contradicts Slide 10** |
| `M3-S11-13` | The discipline behind the gap | Harder than filling in a name, and the reason the schedule is credible |
| `M3-S11-14` | The required message | Teaching synthesis |
| `M3-S11-15`–`17` | — | **Excluded — prohibitions 36, 37.** No tick, no completed item, no progress bar, no invented date |
| `M3-S11-18` | — | **Excluded.** Delivery test: **if the slide explains how to populate a schedule row, stop** |
| `M3-S11-19` | Answer: not established from available material | — |

### Slide 12 — A principle is not a platform configuration

| ID | Statement | Source | Level | Jurisdiction | Publication status | Class |
|---|---|---|---|---|---|---|
| `M3-S12-01` | The translation chain: **principle → project-specific requirement → agreed governance arrangement → assigned function and authority → process rule → platform configuration → implementation evidence** | none | A5 | — | — | **`SYNTH`** |
| `M3-S12-02` | Principles describe **what effective information management is trying to achieve** | `X1` | A4 | International | Published | **`INTERP`** |
| `M3-S12-03` | The project must translate principles into **requirements and decisions** | `X1`, `H1` | A4 | — | — | **`INTERP`** |
| `M3-S12-04` | The BEP and supporting controls **record the agreed project method** | `H1` §1.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-05` | Functions and authorities must be **assigned** | `H1` §4.6, §5 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-06` | **Decision precedes configuration** — platform change follows a governance decision, not the reverse | `H1` §12.1 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-07` | Three things held apart: **as-found configuration** (evidence) · **intended governance** (a controlled decision) · **implemented configuration** (the operational result of a decision) | `H1` §4.7 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-08` | *"Implemented configuration is legitimate **only when it traces back to an approved decision**"* | `H1` §4.7 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-09` | **"A change is not complete because a document was edited or a setting was clicked."** Verification covers implementation, workflow behaviour, clear responsibilities, unintended consequences and updated records | `H1` §12.9 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-10` | The assurance chain — assess change → authorise → implement → **verify implementation** → retain decision and change evidence | `H2` IM matrix §3.7 (A1–A5) | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-11` | **Authorise governance change (A2) is `TBD` against every function.** *"No single universal approver exists"*, and unlimited authority is not assigned to the BIM Manager | `H2` IM matrix §3.7 | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S12-12` | Six things kept separate: standard or principle · **implementation guidance** · project governance · platform configuration · evidence of operation · **conformity assessment** | none | A4 | — | — | **`INTERP`** |
| `M3-S12-13` | Harrismith's position — principles stated as informing the approach; governance documents and planned controls exist; **several authorities and appointments unresolved**; **implementation evidence incomplete or absent**; **no conformity assessment performed** | `H1` §11.2, §13.4, §2.3; `H2` | A3 | This project | Approved with conditions | **`HARRISMITH` — `GAP OR UNVERIFIED`** |
| `M3-S12-14` | *"Presence is not maturity"*; *"configuration is not correctness"* | `H1` §2.4 | A3 | This project | Approved with conditions | **`HARRISMITH` — analogue** |
| `M3-S12-15` | *"The standard supplies principles; the project must turn them into authorised arrangements, configuration and evidence"* | none | A5 | — | — | **`SYNTH`** |
| `M3-S12-16` | That **completing the translation chain proves ISO conformity** | — | — | — | — | **`EXCLUDED`** |
| `M3-S12-17` | That **Harrismith has completed the chain** | — | — | — | — | **`EXCLUDED`** |
| `M3-S12-18` | That a **configured platform proves ISO conformity** | — | — | — | — | **`EXCLUDED`** |
| `M3-S12-19` | Any maturity ladder, compliance score, percentage, traffic light or certification badge | — | — | — | — | **`EXCLUDED`** |
| `M3-S12-20` | Whether the published standard prescribes any translation sequence | — | — | — | — | **`UNRESOLVED`** |

**This slide has no `PUBLIC-SOURCE` and no `GUIDANCE` statement.** It is the
fourth such slide — 2, 7, 8 and 12 — and carries the same obligation:
**attribute, or the audience hears ISO.**

**Teaching use and warnings**

| ID | Teaching use | Warning |
|---|---|---|
| `M3-S12-01` | The chain, and visual `V10` | **Teaching synthesis.** **Not an ISO-prescribed sequence** — no source presents one |
| `M3-S12-02`–`03` | What the first two steps are for | Interpretation |
| `M3-S12-04`–`08` | The middle of the chain | **Harrismith wording.** §4.7's three concepts are the structural version of the same point |
| `M3-S12-09` | **The line that carries the last step** | The step everyone skips. Say it verbatim |
| `M3-S12-10` | The assurance chain | **Concept only.** Assurance procedure is **Module 6** |
| `M3-S12-11` | A2 is TBD | A real, recorded gap at the authorisation step |
| `M3-S12-12` | **Why this is not a conformity model** | Conformity assessment is the sixth separated item and a **different activity** |
| `M3-S12-13` | Harrismith's position, row by row | **Not a scorecard.** Its value is that the last two rows are empty |
| `M3-S12-14` | The configuration caution | — |
| `M3-S12-15` | The required message | Teaching synthesis |
| `M3-S12-16`–`19` | — | **Excluded — prohibitions 38, 39, 40.** Delivery test: **if the slide begins scoring compliance, stop** |
| `M3-S12-20` | Answer: not established; no sequence has been read | — |

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
| Production driven by defined requirements (`H1` §7.1, §7.3) | requirements precede production | **`LOCAL ANALOGUE OR INTERPRETATION`** | Illustrates the principle in this project's own wording. **Not the standard's phrasing**, which has not been read |
| **Asset management, handover and standards verification — outside current scope** (`H1` §3.3) | life-cycle reach of Part 1 | **`GAP OR UNVERIFIED`** | A **deliberately drawn boundary**, recorded rather than left to be discovered. Harrismith is a delivery-governance implementation. **Not a failure and not non-conformity** |
| **No formal information requirements available** (`H1` §7.3, §10.2) | information requirements | **`GAP OR UNVERIFIED`** | The project records the absence and **refuses to invent them**. Training-developed requirements are labelled PROPOSED GOVERNANCE or TRAINING ASSUMPTION |
| **Level of information need — not defined** (`H2` matrix §4) | level of information need | **`GAP OR UNVERIFIED`** | Not established for any container; **not inferred from observed model content**; recorded as an information gap. An **open project decision**, and no detail requirement is to be invented |
| Harrismith's *lifecycle* wording (`H1` §2.2, §7.1) | asset life cycle | **`GAP OR UNVERIFIED`** | Harrismith's word describes the **information container's** span. **Two different spans sharing one word** — do not read an asset-life-cycle claim into it |
| Harrismith's recorded gaps | ISO non-conformity | **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | A gap is a **project state**, not an audit finding. **No assessment exists in either direction** — neither conformity nor non-conformity may be claimed |
| Functions defined without job titles (`H1` §4.6, §5.11) | information-management functions rather than new job titles | **`LOCAL ANALOGUE OR INTERPRETATION`** | Harrismith organises itself around functions and names no holder. That **illustrates** the guidance's framing; it is **not** evidence that the model is an ISO implementation |
| `task team` (`H1` §4.3) | task team | **`LOCAL ANALOGUE OR INTERPRETATION`** | **The one word appearing in both vocabularies** — and even that is not an established identity. Harrismith's is defined here and carries this project's structure |
| **`delivery team`** | delivery team | **`GAP OR UNVERIFIED`** | **One incidental use in prose** (`H1` IM-08). Not a defined Harrismith term, and one prose use is not adoption |
| Container classes `ARC-01`–`FIR-01` (`H2` §3.1) | information container | **`LOCAL ANALOGUE OR INTERPRETATION`** | Containers with recorded originators and task teams. **All allocations are PROPOSED GOVERNANCE**, and the matrix is *"intended governance, not live inventory"* |
| Federation not merging responsibility (`H1` §6.6, §8.5) | originator responsibility | **`LOCAL ANALOGUE OR INTERPRETATION`** | This project's position, clearly stated. **Not verified against the standard**, which has not been read |
| Harrismith's container arrangement | a verified ISO information-container system | **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | No verification exists. The shared term proves nothing |
| The four CDE states (`H2`) | ISO-associated state language | **`LOCAL ANALOGUE OR INTERPRETATION`** | Resembles ISO-associated practice; **conformity has not been demonstrated**, and **no ISO state model has been seen**. Note *Record / Retained*, not *Archived* |
| **`Shared → Published` (T4) blocked** (`H2` §11) | authorised exchange | **`GAP OR UNVERIFIED`** | **No available authorising function.** The block is **deliberate governance evidence** — *"a route that cannot legitimately proceed should visibly halt"* — and must not be removed to tidy a diagram |
| **`TRN-E03` blocked** (`H2` §5) | planned information exchange | **`GAP OR UNVERIFIED`** | Recipient, formats, deliverable set and acceptance authority all unestablished. **Nothing has been delivered on this project** |
| **Record / Retained** (`H2` §1) | information archiving | **`GAP OR UNVERIFIED`** | *"A conceptual state and a retention requirement — not necessarily a folder."* **No `04 Archive` root is required or approved**; retention is **TBD** |
| The translation chain (Slide 12) | an ISO-prescribed implementation sequence | **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | **Teaching synthesis.** No source presents such a sequence, and **completing the chain would not establish conformity** — assessment is a separate act |
| Harrismith's position on the chain | a conformity or maturity score | **`EXCLUDED — CONFORMITY CLAIM NOT SUPPORTED`** | **Not a scorecard.** Several authorities unresolved, implementation evidence incomplete, **no conformity assessment performed** |
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

### 7.1 Additional exclusions recorded in T3-A

| # | Excluded | Why |
|---|---|---|
| 9 | Any invented clause number, stage code, draft date or process-activity list | Fabrication. Plausibility makes it worse, not better |
| 10 | Any ISO diagram, table or figure, reproduced or reconstructed | Copyright, and the originals have not been seen |
| 11 | Any quotation from ISO text longer than a brief phrase | Copyright control — [`README.md`](README.md) §6 |
| 12 | Any claim that a Harrismith delivery exchange has occurred | `TRN-E03` is blocked; `T4` cannot proceed while publication authority is unresolved (`H2`) |
| 13 | Any South African implementation requirement | **None registered.** `H1` §13.4: no SANS applicability is asserted |
| 14 | Any Triviron project fact | **No Triviron project information exists in this repository.** Slide 14 asks questions only |

### 7.2 Additional prohibitions recorded in T3-B

Six more, arising from Slides 4–6. They carry the same weight as §7.

| # | Prohibited | Why |
|---|---|---|
| 15 | **Any copied or reconstructed ISO life-cycle diagram** | Copyright, and the original has not been seen. Slide 4's ribbon is an **original teaching visual with neutral labels** — `visual-demonstration-plan.md` `V2` |
| 16 | **Any information-requirement acronym** — the client-, exchange-, asset- or project-level requirement abbreviations | **No definition-level source is registered.** `H1` §7.3 names some **only to record that none was made available**; that is Harrismith noting an absence, not this module defining vocabulary |
| 17 | **Any formal definition of level of information need** | **No authorised source.** The plain-language concept is permitted (`M3-S6-12`); a definition, a geometric / alphanumeric / documentation breakdown, or any level, grade, scale or tier is not |
| 18 | **That more detail means greater conformity** | Detail is not conformity. No assessment exists, and proportionality runs both ways — `M3-S6-08` |
| 19 | **A single eternal BIM model travelling the whole life cycle** | Life-cycle continuity is continuity of **managed information**. Containers are superseded, replaced and re-authored — `M3-S4-10` |
| 20 | **Harrismith's gaps presented as proof of non-conformity** | A gap is a project state. **No clause-by-clause assessment exists in either direction**, so neither conformity nor non-conformity may be claimed |

**Prohibition 20 is the mirror of prohibition 1**, and both must hold at once.
Module 3 may not claim Harrismith conforms, and may not claim it fails. The
honest position is that **nobody has assessed it**.

### 7.3 Additional prohibitions recorded in T3-C

Ten more, arising from Slides 7–9. Same weight as §7.

| # | Prohibited | Why |
|---|---|---|
| 21 | **"ISO 19650 requires a BIM Manager"** — or that it requires no BIM Manager | **No authorised source establishes either.** `X6` describes information management in terms of **functions**, as **UK guidance**; it does not tell us what the standard requires about titles, and the standard has not been read |
| 22 | **Title equals function** | A job title is an organisational label. A function is a defined project responsibility. `H1` §5.11: **"platform access is not delegation"** — and neither is a business card |
| 23 | **Person equals function** | One participant may carry several functions; **combining them does not merge their authorities** (`H1` §5.11, §5.8) |
| 24 | **`Lead Delivery Party` = *lead appointed party*** | **Not established.** *lead appointed party* occurs **zero** times across `bep/`, `supporting/` and `docs/`. Mapping would require the appointment structure, the contractual context and the standard's definition — **none of the three is available** |
| 25 | **consultant = *appointed party*; contractor = *appointed party*** | **Not established**, and *appointed party* has **no Harrismith counterpart at all**. A commercial position is not an information-management party term |
| 26 | **Shared task-team terminology as proof of ISO conformity** | `task team` appears in both vocabularies. **Shared vocabulary is not established equivalence** — Harrismith's is defined in `H1` §4.3 and carries this project's own structure |
| 27 | **Information container = a Revit file in every case** | A container is not necessarily a single file, and a model is **one** container among drawings, schedules, specifications, reports and data files (`H1` §10.4) |
| 28 | **A federated model merging ownership** | `H1` §6.6 and §8.5: federation *"does not merge authorship or responsibility"*; each contributed container **keeps its originator, its state and its technical responsibility**; *"nobody becomes responsible for another team's content by appearing alongside it"* |
| 29 | **Folder location proving status** | `H1` §7.2: *"Authorship is not inferred from folder location. Where a container sits tells you where it sits. The originator is recorded, not deduced."* State, version, revision, status and suitability remain five separate properties (§6.8) |
| 30 | **Controlled sharing transferring technical responsibility** | `H1` §7.9: *"Consumption does not transfer originator technical responsibility."* The receiver acquires responsibility for **its own use**; *"both responsibilities exist at once; neither cancels the other"* |

**Prohibition 24 is the one a layout can commit without a word being spoken.**
An aligned two-column table on Slide 8 asserts the mapping the slide exists to
refuse — which is why `V6`'s offset rows, labelled gutter and empty space are
recorded as **content**, not styling.

### 7.4 Additional prohibitions recorded in T3-D

Ten more, arising from Slides 10–12. Same weight as §7.

| # | Prohibited | Why |
|---|---|---|
| 31 | **ACC — or any platform — automatically being a conforming CDE** | `H1` §6.1: a CDE is *"an information-management process supported by technology… it is not a folder tree"*. Purchasing is procurement; a CDE is a process, and **no conformity assessment exists in any case** |
| 32 | **Folder position proving information status** | `H1` §7.2, §6.8. **Restates prohibition 29 in the CDE context** — recorded separately because Slide 10 is where a folder diagram is most likely to make the claim visually |
| 33 | **Shared automatically meaning approved** | `H2`: *"**Shared does not mean** published, accepted, or suitable for every purpose."* Shared is a state with a stated purpose, not a quality rating |
| 34 | **A complete operating `Shared → Published` route** | **T4 has no available authorising function**; publication authority is **UNRESOLVED — TBD**; information **remains Shared**. A solid route claims a workflow this project cannot operate |
| 35 | **`TRN-E03` being deliverable** | **PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS.** Recipient not established, formats not established, deliverable set not defined, acceptance authority unresolved |
| 36 | **A planned schedule entry proving actual delivery** | `H1` §10.1: *"Presence in Published does not establish a delivery… delivery is an act with a recipient and a purpose, not a location."* **Nothing has been delivered on this project** |
| 37 | **A date proving acceptance** | Published, Delivered, Received and Accepted are **four distinct states**. *"Delivery does not prove acceptance. Receipt does not prove suitability."* And **no real dates exist** — all timing is event-triggered or TBD |
| 38 | **A configured platform proving ISO conformity** | Configuration is the sixth step of seven and downstream of every decision that matters. `H1` §12.1: **decision precedes configuration**. §2.4: *"presence is not maturity"*, *"configuration is not correctness"* |
| 39 | **Harrismith having completed the translation chain** | **Several authorities unresolved** (A2 is `TBD` against every function); **implementation evidence incomplete or absent**; **no conformity assessment performed** |
| 40 | **Any visual maturity or compliance score** | No score, percentage, level, traffic light, tick or certification badge. A scorecard **is** a conformity claim, whatever the caption says — and it would breach prohibitions 1 and 20 at once |

**Prohibitions 34 and 36 are the two a diagram commits silently.** A tidy state
model that completes through Published, or a timeline that reads as progress,
each assert something this project cannot support — **without a word being
spoken.** `V8` and `V9` record the design requirements that prevent it.

## 8. Unresolved matters carried forward

| # | Unresolved | Resolved by |
|---|---|---|
| 1 | What Parts 1 and 2 actually **require** | A licensed copy of the standard |
| 2 | Whether Harrismith's terms are equivalent to ISO-associated terms | A licensed copy, plus a recorded mapping decision |
| 3 | The content, stage and timing of the revisions (`X3`, `X4`) | Publication, or an authorised source |
| 4 | Whether any South African implementation guidance exists | External research — **outside this specialist's boundary** |
| 5 | Whether Harrismith's state model corresponds to the standard's | A licensed copy; a conformity assessment |
| 6 | What Triviron's jurisdiction, appointments and requirements will be | The Triviron project, when it exists |
| 7 | What, if anything, the published parts require of the **operational phase** | A licensed copy |
| 8 | Whether the standard itself requires requirements to be established **appointment by appointment** — `X6` says so as **UK guidance** | A licensed copy |
| 9 | The standard's treatment of **level of information need** | A licensed copy |
| 10 | Harrismith's own level of information need | **An open project decision** — `H2` matrix §4 records it as an information gap to be developed as PROPOSED GOVERNANCE |
| 11 | Harrismith's formal information requirements | Requirements being established or made available; `H1` §1.5 means they would then take precedence over anything developed in their absence |

**Items 7–9 are the Section B version of item 1.** Each is a question an audience
will ask on Slides 4–6, and each has the same answer: **the concept is teachable,
the requirement is not available.**

| 12 | Whether the published standard requires any particular **function or title** | A licensed copy |
| 13 | The definitions of ***appointed party***, ***delivery team*** and ***task team*** as ISO-associated terms | A licensed copy. **`X6` registers only *appointing party* and *lead appointed party*** |
| 14 | Whether **any** Harrismith term is equivalent to **any** ISO-associated term | A licensed copy, **plus the appointment and contractual context, plus a recorded mapping decision** — none of the three exists |
| 15 | The standard's definition of ***information container***, and whether Harrismith's containers correspond to it | A licensed copy |

**Items 10 and 11 are different in kind.** They are not gaps in this programme's
evidence — they are **open decisions on a live project**, recorded as such by the
project itself. They resolve by decision, not by research.

| 16 | Whether the published standard requires any particular **state model or CDE structure** | A licensed copy |
| 17 | Whether the published standard requires any particular **delivery-planning instrument** | A licensed copy |
| 18 | Whether the published standard prescribes any **translation sequence** from principle to evidence | A licensed copy. The Slide 12 chain is **teaching synthesis** |
| 19 | **Harrismith's publication / exchange authority** | **An open project decision** — BEP §9.7; IM matrix D4. Until then `T4` and `TRN-E03` remain blocked |
| 20 | **Harrismith's recipient identity and acceptance authority** | **An open project decision** — BEP §9.8, §10.11; IM matrix D7 |
| 21 | **Harrismith's governance-change approval authority by change class** (IM matrix `A2`) | **An open project decision.** *"No single universal approver exists"* |
| 22 | Harrismith's **retention approach**, and whether any record structure is required | **An open project decision** — BEP §6.3. **No `04 Archive` root is approved** |
| 23 | Harrismith's **implementation evidence** | Verification activity that has not been performed — BEP §12.9; IM matrix `A4` |

**Items 19–23 are the Sections D and E gaps, and all five are open project
decisions.** They resolve by someone deciding and recording, not by research —
and until they do, the blocked routes on Slides 10 and 11 stay blocked. **That is
the module's most useful demonstration of the principle it teaches**: governance
can intentionally stop a workflow, and a route that cannot legitimately proceed
should visibly halt.

**Item 14 is the Section C headline, and it needs three things, not one.** A
licensed copy would give the standard's definitions. It would **not** give the
appointment structure or the contractual context that makes a party what it is,
and it would not constitute the mapping decision itself. **Terminology mapping is
a project decision that someone takes and records** — it is not a research
finding, and Module 3 does not take it.

**Item 1 is the honest headline of this module.** Everything Module 3 teaches
about ISO 19650 is scope, guidance or analogy. **If the audience needs the
requirement, they need the standard.**

## 9. Status

| Field | Value |
|---|---|
| Statements classified | **Slides 1–12 — 201 statements** |
| `PUBLIC-SOURCE` | 17 |
| `GUIDANCE` — **all UK** | **8** — on Slides 5–8 only; **nothing after Slide 8** |
| `HARRISMITH` | 72 — the **64 in Slides 4–12 are sub-categorised: 43 analogue, 21 gap or unverified**. The 8 in Slides 1–3 predate the sub-categorisation and are not retrofitted |
| `INTERP` | 34 |
| `SYNTH` | 17 |
| `UNRESOLVED` | 13 statement-level, plus 23 module-level (§8) |
| `EXCLUDED` | 40 statement-level, plus **40 prohibited claims** (§7, §7.1–§7.4) |
| Slides with **no** `PUBLIC-SOURCE` statement | **2, 7, 8 and 12** |
| Vocabulary relationships recorded | **6** — Slide 8. **None is `ESTABLISHED`** |
| Blocked routes recorded | **`T4` and `TRN-E03`** — Slides 10 and 11. **Both must remain visibly blocked** |
| Slides 13–14 | **Not classified.** Not developed |
| Mapping method | **Established (§5)**, extended in T3-B, T3-C and T3-D; applied fully at Slide 13 |
| Clause references used | **Zero** |
| Requirement acronyms used | **Zero** |
| Level-of-information-need definitions given | **Zero** — plain concept only |
| ISO definitions of *information container* quoted | **Zero** — working description only |
| Named holders, appointments or organisations | **Zero** |
