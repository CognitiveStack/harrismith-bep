# Module 3 — Source Map, Mapping Method and Prohibited Claims

**Status:** Traceability record for teaching material. **Not governance.**

Statement-level classification for the developed slides — **Slides 1–6** — the
method by which Harrismith may be mapped to ISO-associated concepts, and the list
of claims that **may not be made** in this module under any circumstances.

**Harrismith statements in Slides 4–6 carry a mapping sub-category**: *analogue*,
*gap or unverified*, or *excluded conformity inference*. See §5.

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

## 4. Statement classification — Slides 1–6

**83 statements across six slides. 14 `PUBLIC-SOURCE`, 3 `GUIDANCE` (all UK),
20 `HARRISMITH`, 18 `INTERP`, 9 `SYNTH`, 5 `UNRESOLVED`, 14 `EXCLUDED`.**

| Slide | Statements | `PUB` | `GUID` | `HARR` | `INT` | `SYN` | `UNR` | `EXC` |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 12 | 4 | 0 | 3 | 1 | 2 | 1 | 1 |
| 2 | 10 | 0 | 0 | 5 | 2 | 2 | 0 | 1 |
| 3 | 11 | 6 | 0 | 0 | 2 | 0 | 1 | 2 |
| **4** | **17** | **2** | **0** | **3** | **6** | **2** | **1** | **3** |
| **5** | **16** | **1** | **2** | **7** | **1** | **1** | **1** | **3** |
| **6** | **17** | **1** | **1** | **2** | **6** | **2** | **1** | **4** |
| **Total** | **83** | **14** | **3** | **20** | **18** | **9** | **5** | **14** |

**Two observations from the Section B statements.**

**Slide 5 is the module's most Harrismith-dependent slide** — seven of sixteen
statements, four analogue and three gaps. Its external basis is one guidance idea
and one scope framing. Nothing on it should be delivered as ISO wording.

**`GUIDANCE` enters the module at Slide 5 and stays rare** — three statements out
of eighty-three. Every one is UK-labelled in the tables below, on the slide, and
aloud.

### 4.0 Slides 1–3 — summary

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

**Items 10 and 11 are different in kind.** They are not gaps in this programme's
evidence — they are **open decisions on a live project**, recorded as such by the
project itself. They resolve by decision, not by research.

**Item 1 is the honest headline of this module.** Everything Module 3 teaches
about ISO 19650 is scope, guidance or analogy. **If the audience needs the
requirement, they need the standard.**

## 9. Status

| Field | Value |
|---|---|
| Statements classified | **Slides 1–6 — 83 statements** |
| `PUBLIC-SOURCE` | 14 |
| `GUIDANCE` — **all UK** | **3** — entering at Slide 5 |
| `HARRISMITH` | 20 — the **12 in Slides 4–6 are sub-categorised: 5 analogue, 7 gap or unverified**. The 8 in Slides 1–3 predate the sub-categorisation and are not retrofitted |
| `INTERP` | 18 |
| `SYNTH` | 9 |
| `UNRESOLVED` | 5 statement-level, plus 11 module-level (§8) |
| `EXCLUDED` | 14 statement-level, plus **20 prohibited claims** (§7, §7.1, §7.2) |
| Slides 7–14 | **Not classified.** Not developed |
| Mapping method | **Established (§5)**, extended in T3-B; applied fully at Slide 13 |
| Clause references used | **Zero** |
| Requirement acronyms used | **Zero** |
| Level-of-information-need definitions given | **Zero** — plain concept only |
