# Module 2 — Source Map, Role Inventory and Authority Inventory

**Status:** Traceability record for teaching material. **Not governance.**

Built from repository evidence. Every term below was located in the sources
rather than inferred from a role's name.

---

## 1. Source documents

| # | Path | Declared status |
|---|---|---|
| S1 | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |
| S2 | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |
| S3 | [`supporting/model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |
| S4 | [`supporting/information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |
| S5 | [`supporting/cde-workflow-state-strategy.md`](../../supporting/cde-workflow-state-strategy.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |
| S6 | [`supporting/coordination-review-strategy.md`](../../supporting/coordination-review-strategy.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |
| S7 | [`supporting/governance-decision-register.md`](../../supporting/governance-decision-register.md) | APPROVED WITH CONDITIONS — Training Baseline 0.1 |

All seven are **approved with conditions and not published**. Nothing cited here
is issued, delivered or accepted.

### Classification scheme

| Class | Meaning |
|---|---|
| **DIRECT** | Explicit source wording supports it |
| **INTERP** | Follows from source wording; the source does not phrase it this way |
| **SYNTH** | Teaching synthesis; no source support, not to be attributed |
| **UNRESOLVED** | An open project matter, presented as open |
| **EXCLUDED** | Considered and left out as unsupported |

---

## 2. Role inventory

**Terminology finding, stated first because it governs everything below.**

| Term | Occurrences in `bep/` + `supporting/` + `docs/` |
|---|---|
| `Owner / Appointing Party` | 7 |
| `Appointing Party` | 13 |
| `Lead Delivery Party` | 20 |
| `BIM Manager` | 23 |
| `BIM Coordinator` | 36 |
| `Task-Team Lead` | 32 |
| `CDE Administration` | 25 |
| `CDE Administrator` | 5 |
| **`lead appointed party`** | **0** |
| **`appointed party`** | **0** |

**`lead appointed party` and `appointed party` are not Harrismith terms.** They
must not be attributed to these sources. Module 3 territory.

**`CDE Administration` is the function; `CDE Administrator` is the
person-carrying variant.** The sources use the function form predominantly
(25 : 5), and the five `CDE Administrator` uses all appear where a *participant*
is being discussed — role combination (S1 §4.6, §5.11) and the list of roles that
do **not** automatically hold publication authority (S1 §9.7; S2 §3.6 note).
Teach the function form.

---

### 2.1 Owner / Appointing Party

| Field | Value |
|---|---|
| **Exact source term** | `Owner / Appointing Party`; also `Appointing Party` |
| **Source** | S1 §4.1, §4.2, §5.3; S2 §2 (column `AP`) |
| **Function** | Establishes or approves project information needs; defines intended information outcomes; receives identified exchanges; accepts information for identified purposes, where applicable |
| **Actions allocated** | S2: `Cs` on governance functions G1–G4; `Cs` on C1; `Cs` on D2; **`TBD`** on D4 and D7; `Cs`/`TBD` on A1, A2 |
| **Explicitly excluded** | Any established identity. S2 §4: holds "high-level information needs and outcomes; receipt and acceptance functions where established" — does **not** hold "any established identity — **TBD**" |
| **Related roles** | Lead Delivery Party; recipient function (`Rcp`) |
| **Named holder** | **Not established — TBD** (S1 §2.3, §5.3) |
| **Authority status** | Consultative on governance; **acceptance authority UNRESOLVED** (D7) |
| **Unresolved matter** | Identity; acceptance authority |
| **Presentation warning** | Do not equate with "the client" as an established fact. **No appointing party has been established**, and no acceptance workflow is defined |

Sourced statement worth quoting: *"Nothing in this section implies design
liability, contractual duty, or any obligation beyond what the training
information-management workflow requires."* (S1 §5.3)

### 2.2 Lead Delivery Party

| Field | Value |
|---|---|
| **Exact source term** | `Lead Delivery Party` |
| **Source** | S1 §4.1, §4.2, §5.4; S2 §2 (column `LDP`), §4; S6 §3 |
| **Function** | Coordinates project-level delivery across contributing task teams — consolidating delivery planning; coordinating task-team commitments; supporting project-level information readiness; coordinating delivery interfaces; ensuring required project-level IM processes are applied |
| **Actions allocated** | S2: `P Co` on D2 (coordinate project-level delivery planning); `Co` on D1, D3, D5; `Cs`/`In` widely; **`TBD`** on D4, A2 |
| **Explicitly excluded** | S1 §5.4 — **"Architecture is not automatically the Lead Delivery Party"** (that Architecture was the only populated production stream observed is an observation about files, not an appointment); **"The Lead Delivery Party is not automatically the BIM Manager"** — different functions, different concerns, may sit in different organisations. S2 §4: does not hold "automatic combination with the BIM Manager function" |
| **Related roles** | Owner / Appointing Party; BIM Manager; Task-Team Leads |
| **Named holder** | **TBD** (S1 §5.4; S2 §6; S6 §3) |
| **Authority status** | Coordinating; **not** an approval authority. Publication authority **not** automatically held (S1 §9.7) |
| **Unresolved matter** | Holder |
| **Presentation warning** | Do not conflate with the BIM Manager. Do not infer from which discipline has the most files in the CDE |

### 2.3 BIM Manager

| Field | Value |
|---|---|
| **Exact source term** | `BIM Manager` |
| **Source** | S1 §4.6, §5.5, §5.11, §9.7, §12.7; S2 §2 (column `BM`), §3.1, §3.7, §4; S6 §3 |
| **Function** | **The principal governance function.** Maintaining the BEP governance framework; maintaining the CDE strategy; coordinating information standards; maintaining the responsibility architecture; coordinating delivery-planning governance; managing governance decisions and controlled changes; supporting onboarding and BIM capability development; performing governance assurance; checking that approved governance is reflected in platform and process configuration |
| **Actions allocated** | S2: `P` on G1, G3, G5; `P Co` on G2, A1; `Co` on G4; `P` on C1; `P` on A5; **`Ck`** on C4, A4; `Cs` widely |
| **Explicitly excluded** | S1 §5.5 — **not automatically** a design approver, a discipline technical lead, a contractual decision-maker, the Appointing Party, or the Lead Delivery Party. S2 §4: does not hold design approval, publication authority, contractual decisions, or the AP/LDP function. S6 §3: **"Does not automatically approve technical design."** S1 §9.7: publication authority is **not** automatically the BIM Manager's. S2 §3.7 A2 note: **"unlimited authority is not assigned to the BIM Manager"** |
| **Related roles** | BIM Coordinator (distinct — §5.6); CDE Administration (may be combined — §5.11); Lead Delivery Party (distinct) |
| **Named holder** | **TBD** (S1 §5.5; S2 §2, §6) |
| **Authority status** | Governs *how information is managed*. **Authority over technical design, appointment and contract lies elsewhere and is not acquired by holding this function** |
| **Unresolved matter** | Holder; governance-change approval authority by change class (A2) |
| **Presentation warning** | **The single most important boundary in the module.** Do not present the BIM Manager as owning the BEP, approving design, or holding publication authority. Where the function identifies a problem outside its authority, the route is to raise and escalate — **not to decide it** |

### 2.4 BIM Coordinator

| Field | Value |
|---|---|
| **Exact source term** | `BIM Coordinator` |
| **Source** | S1 §5.6, §8; S2 §2 (column `BC`), §3.5, §4; S3 §3.4; S5 §3.2; S6 §3, §16, §19 |
| **Function** | **The operational multidisciplinary coordination function.** Organising coordination inputs; managing federation and coordination review cycles; running or coordinating clash and interface review; triaging coordination findings; coordinating assignment of issues; monitoring resolution; verifying that coordination findings have been addressed through the coordination process; escalating unresolved interface problems |
| **Actions allocated** | S2: `P Co` on X1, X2; `Ck` on X4; `P` on X5; `Co` on X3. S5 §3.2: the coordination **input inclusion** decision at T3. S3 §3.4: **Lead function** for `COORD-01` |
| **Explicitly excluded** | S1 §5.6 — does **not** take ownership of design solutions; verifying a closed clash confirms the coordination process was followed to its conclusion, **"it is not design approval and carries no technical endorsement"**. S6 §3: does **not** own discipline design solutions, become technical approver, or acquire publication authority through coordination. S6 §16: **"An Issue assigned to a task team does not make the BIM Coordinator responsible for designing the fix."** S2 §4: does not hold ownership of the technical design solution or design-approval authority |
| **Related roles** | BIM Manager (distinct functions; may be carried by the same participant, which does not merge them); Task-Team Leads (own the technical response) |
| **Named holder** | **TBD** (S1 §5.6; S2 §2, §6; S6 §3) |
| **Authority status** | Process authority only. **No design, publication or acceptance authority** |
| **Presentation warning** | Slide 8 exists for this. **Coordination responsibility is not design responsibility.** The originating task team retains responsibility for its technical solution, before and after coordination |

### 2.5 Task-Team Lead

| Field | Value |
|---|---|
| **Exact source term** | `Task-Team Lead` (hyphenated; `Task Team Lead` unhyphenated: **0 occurrences**) |
| **Source** | S1 §5.7, §9.4; S2 §2 (column `TTL`), §3.3, §4; S3 §3; S4 §3.2, §4.3, §6; S5 §3.2; S6 §3, §16, §18 |
| **Function** | Responsible for the team's own information production and readiness — organising task-team production; ensuring required information is produced; ensuring required checking occurs; resolving task-team quality issues; managing interfaces with other task teams; **authorising information from WIP for controlled sharing, where governance assigns that authority**; ensuring assigned coordination issues are addressed |
| **Actions allocated** | S2: **`Au`** on P4 and S3; `P Ck` on D3; `P` on D1, D5, X3; `Ck` on P2; `Co` widely. S4 §6: authorises controlled sharing for TRN-E01 and TRN-E02 |
| **Explicitly excluded** | S2 §4: does not hold project-level delivery authority or publication authority |
| **Related roles** | Author and Checker (within the team); BIM Coordinator (coordinates assignment, does not own the fix) |
| **Named holder** | **TBD for every task team** (S1 §5.7; S2 §6) |
| **Authority status** | **Established** for authorisation to share (S1 §9.4). Not established for publication |
| **Presentation warning** | S1 §5.7: **"Technical authority sits here, not with the BIM functions."** Neither the BIM Manager nor the BIM Coordinator acquires that responsibility by governing or coordinating the information that describes it |

### 2.6 Author

| Field | Value |
|---|---|
| **Exact source term** | `Author` |
| **Source** | S1 §5.8; S2 §2 (column `Aut`), §3.3, §3.4, §4, §5; S6 §3 |
| **Function** | Creates or modifies information; works within the task team's WIP environment; complies with project conventions; responds to assigned comments and issues. S6 §3: performs the technical and model correction in WIP |
| **Actions allocated** | S2: **`P`** on P1 (author information in WIP), S1 (execute controlled share), S2, S3; `Cs` on P2, P3, D1, D5, X1, X2 |
| **Explicitly excluded** | S1 §5.8 — **"Authors do not self-promote their own information."** S2 §4: does not hold self-authorisation of own work. **The Author does not appear in row P4 at all** |
| **Related roles** | Checker (may be combined, with the limitation recorded); Task-Team Lead (holds the authorisation) |
| **Named holder** | **TBD** (S2 §2, §6) |
| **Authority status** | Performs; **holds no authorisation** |
| **Presentation warning** | Having authored a container is not a reason to advance it. Progression requires the checking and authorisation defined by governance, **not the author's confidence in their work** |

### 2.7 Checker

| Field | Value |
|---|---|
| **Exact source term** | `Checker` |
| **Source** | S1 §5.8, §9.12; S2 §2 (column `Chk`), §3.3, §4, §5; S6 §3 |
| **Function** | Verifies information against the defined checking requirement; records or provides evidence of checking; identifies deficiencies before controlled progression |
| **Actions allocated** | S2: **`Ck`** on P2, P3, S2, X3, A4; `Cs` on P4 |
| **Explicitly excluded** | S2 §4: does not hold authorisation — **"checking is not authorising"** |
| **Related roles** | Author (may be combined); Task-Team Lead |
| **Named holder** | **TBD** (S2 §2, §6) |
| **Authority status** | Checks against a defined requirement; **permits no progression** |
| **Presentation warning** | On combination with Author (S1 §5.8, §9.12; S2 §5): the functional distinction remains — a self-check is still a checking act against a defined requirement; the combination is **recorded**; and **"independence is never claimed where it does not exist."** Overstating independence is worse than lacking it, because it removes the reader's ability to judge reliability |

### 2.8 CDE Administration

| Field | Value |
|---|---|
| **Exact source term** | `CDE Administration` (function); `CDE Administrator` (participant variant, 5 uses) |
| **Source** | S1 §4.6, §5.9, §5.11, §6.9, §9.7; S2 §2 (column `CDE`), §3.2, §4; S5 §14, §17; S6 §3 |
| **Function** | **Implements approved governance in the platform** — project membership administration; folder and space implementation; permissions; Design Collaboration team-space configuration; coordination-space configuration; platform workflow configuration; implementation of approved structural and configuration changes; checking platform configuration after an approved change |
| **Actions allocated** | S2: **`P`** on C2, C3, A3; **`P Ck`** on C4; `Ck` on A4; `Cs`/`In` elsewhere. S5 §3.2: may execute platform transmission functions at T5 |
| **Explicitly excluded** | S1 §5.9 — **"CDE Administration implements governance; it does not create it."** Changing the software does not make a decision. A configuration that was never approved is a **deviation**, however competently applied. **"Platform permission is not BEP authority"** — administrative rights confer the technical ability to change something and nothing more; not authority to decide who is responsible, to reassign responsibility, or to alter the organisational structure. S5 §14: platform access confers no authority to share, publication authority, technical approval authority or acceptance authority |
| **Related roles** | BIM Manager (may be combined — §5.11, which does not merge the functions) |
| **Named holder** | **TBD** (S1 §5.9; S2 §6) |
| **Authority status** | **Implements only.** Holds no governance authority |
| **Presentation warning** | Slide 10 exists for this. **Permission is not authority.** S5 §14: access is configured to *follow* approved responsibility — responsibility comes first and permission follows it; where the two diverge, the divergence is recorded as a **deviation**, not treated as a redefinition of who is responsible |

### 2.9 Receiving / recipient function

| Field | Value |
|---|---|
| **Exact source term** | `Receiving / recipient function`; column `Rcp` |
| **Source** | S1 §9.8, §10.11; S2 §2 (column `Rcp`), §3.6; S4 §6; S5 §3.2 |
| **Function** | Receives an exchange and decides acceptance or rejection for the stated purpose |
| **Actions allocated** | S2: **`P`** on D6 (receive exchange); **`TBD Ac`** on D7 (accept exchange for a stated purpose) |
| **Explicitly excluded** | S1 §9.8 — acceptance does **not** transfer technical responsibility from the originator, make the information suitable for unrelated purposes, or automatically approve the design |
| **Related roles** | Owner / Appointing Party (where established) |
| **Named holder** | **Not established.** S2 §2: *"`Rcp` is a generic function, not an organisation. It represents whoever receives a given exchange under the approved delivery arrangement, which does not yet exist"* |
| **Authority status** | Receipt allocated; **acceptance authority UNRESOLVED** |
| **Presentation warning** | S1 §9.8: **"No Appointing Party acceptance workflow is defined."** Where acceptance is exercised in the training workflow it is exercised **in a simulated capacity under TA-02** |

### 2.10 Training-only governance functions — a separate class

**These are not project delivery roles.** They govern the *documentation set*,
were established for the training implementation, and are recorded in S7.

| Ref | Function | Established |
|---|---|---|
| `AG-001` | Training Baseline Approver | 2026-08-01 |
| `AG-002` | Training CDE Governance Approver | 2026-08-01 |
| `AG-003` | Training Publication Arrangement Approver | 2026-08-01 |
| `AG-004` | Training Baseline Publication Owner | 2026-08-02 |
| `AG-005` | Training Publication Naming and Presentation Approver | 2026-08-02 |

| Field | Value |
|---|---|
| **Functional holder** | `Training Implementation Owner`, under **TA-02** |
| **Personal holder** | **Not recorded.** No personal name appears in any of them |
| **Authority status** | Training-only. S1 §9.10 on AG-001: limited to the training / reference baseline; carries **no** project publication / exchange authority, recipient acceptance authority, or professional design authority |
| **Presentation warning** | **Do not present these as project roles.** Mentioning them at all risks pulling questions toward publication planning, which is a paused programme and outside this module. Slide 13 may reference AG-001 as an example of an approval function being *established before* a decision was taken — nothing further |

---

## 3. Authority inventory

Status vocabulary: **ESTABLISHED** (the source defines who holds it) ·
**ALLOCATED** (assigned in the matrix) · **CONDITIONAL** (held only where
governance expressly allocates it) · **UNRESOLVED** (recorded as TBD) ·
**BLOCKED** (cannot currently be exercised) · **OUTSIDE EVIDENCE BASE**.

| # | Authority | Held by | Status | Source |
|---|---|---|---|---|
| 1 | **Authoring** | Author (`P` on P1) | **ALLOCATED** | S2 §3.3; S1 §5.8 |
| 2 | **Technical / content checking** | Checker (`Ck` on P2) | **ALLOCATED** | S2 §3.3; S1 §5.8 |
| 3 | **Information-quality / readiness checking** | Checker (`Ck` on P3) | **ALLOCATED** | S2 §3.3 |
| 4 | **Coordination (process)** | BIM Coordinator (`P Co` on X1, X2) | **ALLOCATED** | S2 §3.5; S6 §3 |
| 5 | **Authorisation for controlled sharing** | **Task-Team Lead** (`Au` on P4) | **ESTABLISHED** — S1 §9.4 defines it | S1 §9.4; S2 §3.3; S4 §6 |
| 6 | **Authorisation to consume Shared information** | Task-Team Lead (`Au` on S3) | **ALLOCATED** | S2 §3.4 |
| 7 | **Publication / exchange authorisation** | — | **UNRESOLVED**, and **BLOCKED** in the workflow | S1 §9.7; S2 §3.6 D4; S5 §3.1–3.3 (T4); S4 §5.1 |
| 8 | **Governance-change approval** | — | **UNRESOLVED**, class-dependent | S1 §12.7; S2 §3.7 A2 |
| 9 | **Technical / design approval** | Originating task team retains technical responsibility | **OUTSIDE the IM matrix** — no design-approval authority is allocated to any IM function | S1 §5.5, §5.6, §5.7; S6 §3 |
| 10 | **Receipt of exchange** | Receiving / recipient function (`P` on D6) | **ALLOCATED** | S2 §3.6 |
| 11 | **Acceptance for a stated purpose** | — | **UNRESOLVED** (`TBD Ac` on D7) | S1 §9.8; S2 §3.6 D7 |
| 12 | **Issue verification** | BIM Coordinator (`Ck` on X4) | **ALLOCATED** — and expressly **not** design approval | S2 §3.5; S6 §19 |
| 13 | **Issue closure** | Per the governed criteria, after re-coordination | **CONDITIONAL** — closure follows verification against reshared controlled information | S6 §15, §19 |
| 14 | **Implementation verification** | Varies by change type (`Ck` on A4 — BM, Chk, CDE) | **CONDITIONAL** — **no single universal verifier is defined** | S1 §12.9; S2 §3.7 |
| 15 | **Escalation of unresolved interfaces** | BIM Coordinator (`P` on X5) | **ALLOCATED** | S2 §3.5 |
| 16 | **Platform configuration implementation** | CDE Administration (`P` on C2, C3, A3) | **ALLOCATED** — implements only, creates no governance | S1 §5.9; S2 §3.2; S5 §17 |

### 3.1 The four unresolved authorities

These are the module's honest core, and Slide 13 exists to carry them.

| Authority | Recorded status |
|---|---|
| **Publication / exchange** | UNRESOLVED. Expressly **not** automatically the BIM Manager, BIM Coordinator, CDE Administrator or Architect. Depends on an approved delivery arrangement that does not yet exist |
| **Recipient acceptance** | UNRESOLVED / recipient-dependent. No appointing party established; no acceptance workflow defined |
| **Governance change, by class** | UNRESOLVED. Three conceptual levels defined; **"no single universal approver exists"** |
| **Implementation verification** | No single universal verifier defined; the verifying role varies by change type |

### 3.2 The one authority that is unambiguously established

**Authorisation to share.** S1 §9.4 states it directly: the Task-Team Lead — or
another role explicitly allocated that function by approved governance —
authorises information to progress from WIP to Shared.

This is the module's anchor example, because it demonstrates the whole model in
one row: an Author performs, a Checker checks, and a **third** function
authorises.

---

## 4. Statement classification — Slides 1–3

### Slide 1 — BIM roles exist to make decisions explicit

| Statement | Class | Source |
|---|---|---|
| Multidisciplinary delivery contains decisions at the interfaces between teams | **INTERP** | S1 §1.1, §5.1; S6 §1 |
| For any container it must be answerable who produced it, who checked it, who authorised it and for what purpose | **DIRECT** | S1 §5.1 — "Responsibility must be traceable" |
| Each information container should have a known originator, a known state, a known route to the next state, and a known role accountable for moving it there | **DIRECT** | S1 §1.1 |
| Where the BEP does not yet define something, the gap is recorded rather than left to local habit | **DIRECT** | S1 §1.1 |
| Authority is never inferred upward from platform configuration | **DIRECT** | S1 §1.5 |
| Reconfiguring a team, space, permission or mapping in the platform does not constitute a governance decision, and does not make itself legitimate by having been done | **DIRECT** | S1 §4.8 |
| "If responsibility is not assigned deliberately, the project still makes decisions — but through assumption, access or habit" | **SYNTH** | Teaching wording. Consistent with S1 §1.5, §4.8 and §5.9, but no source sentence says it |
| Harrismith as the worked example | **DIRECT** | S1 §2.2 |
| Any generic interface problem presented as a recorded Harrismith failure | **EXCLUDED** | The sources record observations, not failures. UD-001 is the only recorded discrepancy, and it is a mapping observation |

### Slide 2 — A role is not the same as a job title

| Statement | Class | Source |
|---|---|---|
| **"These are functions, not job titles and not people"** | **DIRECT** | S1 §4.6 — quotable verbatim |
| One participant may carry more than one function; in a larger project each might be carried by a different organisation | **DIRECT** | S1 §4.6 |
| **"Combining functions does not merge them"** — the participant must know which one they are performing | **DIRECT** | S1 §4.6, §5.11 |
| Approving a governance change as BIM Manager is a different act from applying it as CDE Administrator, even when performed by one person within a minute of each other | **DIRECT** | S1 §5.11 |
| The BIM Manager is not automatically the Appointing Party or the Lead Delivery Party | **DIRECT** | S1 §5.5, §5.4 |
| **Delegation must be explicit** — stated, scoped and recorded; **platform access is not delegation** | **DIRECT** | S1 §5.11 |
| Authority must come from the project's agreed arrangements, not from the title alone | **INTERP** | Follows from S1 §1.5, §4.6, §5.11; not one source sentence |
| The same job title may carry different authority on different projects | **SYNTH** | Teaching framing. The sources address one project |
| Any named person | **EXCLUDED** | No holder is established anywhere |

### Slide 3 — Function, organisation and named person

| Statement | Class | Source |
|---|---|---|
| Five concepts deliberately not interchangeable: **Party** (an organisation), **Task team** (the group producing a defined package), **Discipline** (a technical classification), **Autodesk collaboration team** (a platform construct), **IM role** (a governance function) | **DIRECT** | S1 §4.2 |
| **"These may map to one another — often they do — but a mapping is not an identity"**; each mapping is a decision to be recorded, not an assumption to be inherited | **DIRECT** | S1 §4.2 |
| Four IM functions established at organisation level: BIM Manager, BIM Coordinator, CDE Administration, Lead Delivery Party | **DIRECT** | S1 §4.6 |
| **"No names are populated. Role holders are TBD throughout Section 5"** | **DIRECT** | S1 §5.2 |
| The role model is a **conceptual functional model, not an appointment chart and not an organisation chart** | **DIRECT** | S1 §5.2 |
| The matrix allocates functions to **functional roles**, not to companies or people; no organisation is appointed and no individual is named | **DIRECT** | S2 preamble, §2 |
| The matrix **"does not demonstrate that separate people perform them, and it must not be read as evidence of independence"** | **DIRECT** | S2 §5 |
| The three-layer framing — function / organisation or party / named role holder | **INTERP** | Assembled from S1 §4.2, §4.6, §5.2 and S2 §2. No source presents three layers |
| Assigning functions before names is useful during planning; implementation eventually requires named holders | **SYNTH** | Teaching framing. The sources record the state, not its pedagogical value |
| That TBD holders make the framework invalid | **EXCLUDED** | Nothing supports it. S1 §5.2 and S2 §2 present unpopulated holders as the normal current state |

### Summary — Slides 1–3

| Slide | DIRECT | INTERP | SYNTH | UNRESOLVED | EXCLUDED | Rows |
|---|---:|---:|---:|---:|---:|---:|
| 1 | 5 | 1 | 1 | 0 | 1 | 8 |
| 2 | 6 | 1 | 1 | 0 | 1 | 9 |
| 3 | 7 | 1 | 1 | 0 | 1 | 10 |
| **Total** | **18** | **3** | **3** | **0** | **3** | **27** |

**Slides 1–3 are heavily source-supported.** The three synthesis statements are
each a framing device — the Slide 1 central message, the "same title, different
project" observation, and the planning-value argument on Slide 3.

---

## 5. Module 1 conclusions re-checked

Module 1's role positions were verified against the sources for this increment
rather than carried over unchecked.

| Module 1 position | Verification |
|---|---|
| Five functions: prepare, contribute, review, approve, implement | **Confirmed as INTERP, not DIRECT.** No source enumerates five. S1 §4.6 enumerates **four** IM functions at organisation level — BIM Manager, BIM Coordinator, CDE Administration, Lead Delivery Party. Module 2 uses the four-function source list where accuracy matters, and keeps the five-act framing only as teaching structure |
| G1: BIM Manager performs; AP, LDP, BC, TTL consulted | **Confirmed DIRECT** |
| "No single universal approver exists" | **Confirmed DIRECT** — S2 §3.7 A2 note |
| RACI expressly not adopted | **Confirmed DIRECT in two places** — S1 §5.12 and S2 §1, with the same reason given in both |
| `lead appointed party` / `appointed party` absent | **Confirmed — 0 occurrences** across `bep/`, `supporting/` and `docs/` |
| Permission is not authority | **Confirmed DIRECT**, and stronger than Module 1 recorded: S5 §14 adds that access is configured to *follow* approved responsibility, and that divergence is recorded as a **deviation** |
| CDE Administration implements, does not create | **Confirmed DIRECT in four places** — S1 §5.9, S2 §3.2, S5 §14 and §17, S6 §3 |

**One correction and two refinements**, recorded rather than silently applied:

1. **Correction.** The five-function framing is teaching structure. The source's
   organisation-level list has **four** functions. Module 2 says so. **Fully
   reconciled in §8 below.**
2. **Refinement.** The `CDE Administration` / `CDE Administrator` distinction was
   not recorded in Module 1. It is recorded here (§2.8).
3. **Refinement.** The AG-series training-only governance functions were treated
   in Module 1 as approval examples. Module 2 records them as a **separate
   class** that is not a project delivery role (§2.10).

---

## 6. Programme safeguards carried forward

| Safeguard | Where it bites in Module 2 |
|---|---|
| **No invented role holder** | Every role in §2 — all holders TBD |
| **No invented organisation** | §2.1, §2.2 — no party is appointed |
| **No invented date or milestone** | Throughout; the only dates used are the sourced AG/AD establishment dates |
| **No universal approver unless established** | §3 authorities 7, 8, 14 — none exists |
| **No BIM Manager-as-project-owner assumption** | §2.3 — the module's principal boundary |
| **No BIM Coordinator-as-designer assumption** | §2.4 — Slide 8 |
| **No permission-as-authority assumption** | §2.8 — Slide 10 |
| **No issue-closure-as-design-approval assumption** | §3 authorities 12, 13 |
| **No unsupported ISO definition** | No ISO wording is verifiable in this repository; `lead appointed party` and `appointed party` are excluded |
| **No unsupported Triviron fact** | *Triviron* appears nowhere in the sources; Slide 14 will be questions only |
| **Publication automation remains paused** | §2.10 — the AG-series is referenced minimally and the programme is not reopened |

---

## 7. Statement classification — Slides 4–9

Same scheme as §4.

### Slide 4 — Who governs the project information process?

| Statement | Class | Source |
|---|---|---|
| Four information-management functions at organisation level: BIM Manager, BIM Coordinator, CDE Administration, Lead Delivery Party | **DIRECT** | S1 §4.6 |
| Nine functional roles in the matrix: `AP`, `LDP`, `BM`, `BC`, `TTL`, `Aut`, `Chk`, `CDE`, `Rcp` | **DIRECT** | S2 §2 |
| Every holder is TBD or not established | **DIRECT** | S1 §2.3, §5.3–5.9; S2 §2, §6 |
| **"A conceptual functional model, not an appointment chart and not an organisation chart"** — it shows how functions relate, not who reports to whom contractually | **DIRECT** | S1 §5.2 |
| **"Technical authority sits here, not with the BIM functions"** | **DIRECT** | S1 §5.7 |
| The Lead Delivery Party is not automatically the BIM Manager — different functions, different concerns, may sit in different organisations | **DIRECT** | S1 §5.4 |
| `Rcp` is a generic function, not an organisation, representing whoever receives an exchange under a delivery arrangement that does not yet exist | **DIRECT** | S2 §2 |
| Five concepts deliberately not interchangeable — party, task team, discipline, platform team, IM role | **DIRECT** | S1 §4.2 |
| The seven-concern grouping — project authority / IM governance / technical production / technical checking / coordination / platform administration / recipient acceptance | **INTERP** | Assembled from S1 §4.6, §5.2–5.9 and S2 §2. No source groups them this way |
| "BIM governance is distributed by function, but each function must still have a defined boundary" | **INTERP** | Both halves sourced — S1 §4.6, §5.2 for distribution; S2 §4 for boundaries — but not as one sentence |
| Owner / Appointing Party identity | **UNRESOLVED** | S1 §2.3, §5.3 |
| Recipient acceptance authority | **UNRESOLVED** | S1 §9.8; S2 §3.6 D7 |
| Any corporate reporting hierarchy among the functions | **EXCLUDED** | S1 §5.2 expressly disclaims it |
| Any implication that BIM functions outrank discipline leads technically | **EXCLUDED** | S1 §5.7 states the opposite |

### Slide 5 — What does the BIM Manager actually do?

| Statement | Class | Source |
|---|---|---|
| The BIM Manager is **the principal governance function** for this BEP | **DIRECT** | S1 §5.5 |
| The nine-item responsibility list — framework, CDE strategy, standards coordination, responsibility architecture, delivery-planning governance, governance decisions and change, onboarding, assurance, configuration checking | **DIRECT** | S1 §5.5 |
| G1 — Maintain the BEP governance framework: `BM = P`; `AP`, `LDP`, `BC`, `TTL` all `Cs` | **DIRECT** | S2 §3.1 |
| G2 `P Co` · G3 `P` · G5 `P` · C1 `P` · A1 `P Co` · A5 `P` | **DIRECT** | S2 §3.1, §3.2, §3.7 |
| G4 — the BIM Manager only **coordinates** project information standards; the Task-Team Lead is marked `P Cs` | **DIRECT** | S2 §3.1 |
| C4 and A4 — the BIM Manager **checks** configuration and implementation after change | **DIRECT** | S2 §3.2, §3.7 |
| "Drafting is concentrated; agreement is distributed" | **INTERP** | Follows from G1's one-Perform-four-Consult pattern; not source wording |
| "The BIM Manager maintains the information-management framework; the project's other functions supply, review, authorise and implement the decisions within it" | **INTERP** | Assembled from G1, §5.5 and the separate allocation of authorisation and implementation |
| Any expansion of the function beyond the source list | **EXCLUDED** | The §5.5 list is used as written |

### Slide 6 — What the BIM Manager does not automatically do

| Statement | Class | Source |
|---|---|---|
| Not automatically the **Appointing Party** | **DIRECT** | S1 §5.5; S2 §4 |
| Not automatically the **Lead Delivery Party** | **DIRECT** | S1 §5.5, §5.4; S2 §4 |
| Not automatically a **design approver** | **DIRECT** | S1 §5.5; S2 §4; S6 §3 — *"Does not automatically approve technical design"* |
| Not automatically a **discipline technical lead** | **DIRECT** | S1 §5.5 |
| Not automatically a **contractual decision-maker** | **DIRECT** | S1 §5.5; S2 §4 |
| Not automatically the **publication authority** | **DIRECT** | S1 §9.7 — names the BIM Manager first among those it is not automatically held by |
| Not automatically the **recipient acceptance authority** | **DIRECT** | S1 §9.8; S2 §3.6 D7 |
| **"No single universal approver exists"**; **"unlimited authority is not assigned to the BIM Manager"** | **DIRECT** | S2 §3.7 A2 note; S1 §12.7 |
| Not automatically the **platform administrator** — CDE Administration is a separate function | **DIRECT** | S1 §4.6 lists them separately; §5.11 gives BIM Manager + CDE Administrator as two functions one participant *may* carry |
| Not **responsible for every model** | **INTERP** | S3 §3.1 allocates each container to an originating task team and S1 §5.7 places technical authority there — but no source excludes the BIM Manager from model responsibility by name |
| Where the function identifies a problem outside its authority, **"the route is to raise and escalate it, not to decide it"** | **DIRECT** | S1 §5.5 |
| "Expertise in BIM does not create contractual, technical or publication authority" | **SYNTH** | Teaching wording generalising the sourced exclusions |
| Authority here is **defined rather than diminished** | **SYNTH** | Teaching framing. The sources state the boundaries; the reassurance is the presenter's |
| Publication / exchange authority; recipient acceptance authority | **UNRESOLVED** | S1 §9.7, §9.8; S2 §3.6 D4, D7 |
| Any exclusion inferred because it seems logical | **EXCLUDED** | Each exclusion above was located in the source before use; the one that could not be was reclassified as INTERP |

### Slide 7 — What does the BIM Coordinator do?

| Statement | Class | Source |
|---|---|---|
| The BIM Coordinator is **the operational multidisciplinary coordination function** | **DIRECT** | S1 §5.6 |
| The activity list — organise inputs, identify required inputs, manage federation, manage and coordinate checks, triage findings, create and coordinate Issues where required, monitor assigned actions, coordinate re-review, verify disposition, escalate blockers, retain and report evidence | **DIRECT** | S1 §5.6; S6 §3 |
| X1 `P Co` · X2 `P Co` · X4 `Ck` · X5 `P` | **DIRECT** | S2 §3.5 |
| **X3 — the coordinator only `Co`; `TTL` and `Aut` are `P`** | **DIRECT** | S2 §3.5 |
| Does **not** own discipline design solutions, become technical approver, or acquire publication authority through coordination | **DIRECT** | S6 §3 |
| **Not every finding becomes an Issue** — creating one is a decision taken at triage | **DIRECT** | S6 §12; S1 §8.7 |
| **Federation does not merge ownership** — `COORD-01` does not merge authorship, transfer technical ownership, create a new design author, or replace the discipline containers | **DIRECT** | S6 §8; S3 §3.4 |
| *"May facilitate agreement between teams but does not author a discipline solution merely because they chair coordination"* | **DIRECT** | S6 §18 |
| "The BIM Coordinator manages the coordination process; the originating task teams remain responsible for their technical solutions" | **DIRECT** | S1 §5.6 — *"The originating task team retains responsibility for its technical solution, before and after coordination"* |
| The six-way separation table — coordination management / technical design / model authoring / task-team checking / authorisation for reshare / design approval | **INTERP** | Each element sourced; the grouping is teaching structure |
| Design approval is allocated to **no** information-management function | **INTERP** | No row of S2 allocates it; S1 §5.5–5.7 place technical responsibility with the task team. An absence, correctly read |
| Any claim that the coordination process is configured or running | **EXCLUDED** | S6 §7 — no Coordination Space observed configured; S6 §15 — status model not claimed to be configured |

### Slide 8 — Coordination responsibility is not design responsibility

| Statement | Class | Source |
|---|---|---|
| The coordination cycle: controlled Shared inputs → readiness check → federation → checks → findings → triage → create/assign Issues where required → originating task-team WIP correction → task-team check → authorise controlled reshare → Shared → re-coordinate → verify → close/disposition → retain evidence | **DIRECT** | S6 §17 |
| **"An Issue assigned to a task team does not make the BIM Coordinator responsible for designing the fix"** | **DIRECT** | S6 §16 |
| Where multiple task teams must change, **"each remains responsible for its own information"** — a jointly-agreed resolution is still a set of separate changes under separate responsibility | **DIRECT** | S6 §18 |
| **"Technical resolution occurs in the originating task team's WIP"** | **DIRECT** | S6 §18 |
| **"A material Issue is not closed solely because someone says it was fixed in WIP"** — closure follows re-coordination against reshared, controlled information; *"a change nobody can see in Shared information has not been demonstrated"* | **DIRECT** | S6 §19 |
| **"Verification does not equal design approval, professional certification, publication authority, or recipient acceptance"** | **DIRECT** | S6 §19; S1 §8.10, §9.5 |
| Verification occurs **after** the corrected information has been checked, authorised for reshare, returned to Shared and included in re-coordination | **DIRECT** | S6 §19 |
| The STR-01 / MEC-01 scenario | **DIRECT — and labelled illustrative by the source** | S6 §27: *"an educational workflow example only"* that *"does not describe an actual condition on the project"*, with no geometry, coordinates, Issue identifier, tolerance value or named person |
| If only MEC-01 changes, TRN-E02-MEC activates and TRN-E02-STR does not | **DIRECT** | S6 §27; S4 §4.2 |
| The eight-step teaching lifecycle | **INTERP** | A compression of S6 §17's sixteen steps |
| "The coordinator owns the process; the task team owns the technical response" | **INTERP** | Both halves sourced; the paired formulation is teaching wording |
| Any presentation of the STR-01 / MEC-01 example as a recorded live Harrismith clash | **EXCLUDED** | The source disclaims it about its own example |

### Slide 9 — Task-Team Leads, Authors and Checkers

| Statement | Class | Source |
|---|---|---|
| Author — creates or modifies information; works in the task team's WIP; complies with project conventions; responds to assigned comments and issues | **DIRECT** | S1 §5.8; S6 §3 |
| **"Authors do not self-promote their own information"** — having authored a container is not a reason to advance it | **DIRECT** | S1 §5.8 |
| **"An Author does not self-authorise merely because they authored the information"** | **DIRECT** | S2 §3.3 P1/P4 note |
| Checker — verifies against the defined checking requirement; records or provides evidence; identifies deficiencies before controlled progression | **DIRECT** | S1 §5.8 |
| **"Check is not Authorise"** — checking confirms readiness for the next controlled decision; it does not permit progression | **DIRECT** | S2 §3.3 P2/P3 note; S1 §9.3 |
| Task-Team Lead authorises information to progress from **WIP to Shared** — or another role explicitly allocated that function by approved governance | **DIRECT** | S1 §9.4; S2 §3.3 P4 |
| Rows P1–P4: `Aut` = `P`, `Cs`, `Cs`, `—`; `Chk` = `—`, `Ck`, `Ck`, `Cs`; `TTL` = `Co`, `Co Ck`, `Co`, **`Au`** | **DIRECT** | S2 §3.3 |
| Every TRN-E01 row: checking requirement = task-team technical/content check **and** information-quality/readiness check; authorisation requirement = **Task-Team Lead authorisation to share**; state = **Shared — coordination use only** | **DIRECT** | S4 §3.2 |
| Task-team checking covers technical/content, information quality, and interface/readiness | **DIRECT** | S1 §7.6, §9.3 |
| **"Authorisation to share is not authorisation to publish or exchange"** — separate decisions with wider consequences | **DIRECT** | S1 §9.4 |
| Authorisation to share does **not** mean suitable for construction, formally published, accepted by recipients, or technically approved for every downstream purpose | **DIRECT** | S1 §9.4 |
| Author and Checker may be combined — the functional distinction remains, a self-check is still a checking act, the combination is **recorded**, and **"independence is never claimed where it does not exist"** | **DIRECT** | S1 §5.8, §9.12; S2 §5 |
| **"Technical authority sits here, not with the BIM functions"** | **DIRECT** | S1 §5.7 |
| **RACI is not adopted** — it collapses checking from authorising and coordinating from performing; not to be introduced unless explicitly approved later | **DIRECT** | S1 §5.12; S2 §1 |
| The four-distinction framing — Perform ≠ Check ≠ Authorise ≠ Publish ≠ Accept | **INTERP** | Each distinction sourced; the four-way presentation is teaching structure |
| "Separation of duties prevents information from becoming reliable merely because its author says it is ready" | **INTERP** | S1 §5.8 states the principle — progression requires governance-defined checking and authorisation, *"not the author's confidence in their work"* — but not in this sentence |
| Publication / exchange authority | **UNRESOLVED** | S1 §9.7; S2 §3.6 D4; S5 §3.1–3.3 (T4 blocked) |
| Recipient acceptance authority | **UNRESOLVED** | S1 §9.8; S2 §3.6 D7 |
| Any arrow from Shared to Published in the sequence | **EXCLUDED** | Publication authority is unresolved and the transition is recorded as blocked |
| Any description of the three roles as RACI | **EXCLUDED** | Expressly prohibited by S1 §5.12 and S2 §1 |

### Summary — Slides 4–9

| Slide | DIRECT | INTERP | SYNTH | UNRESOLVED | EXCLUDED | Rows |
|---|---:|---:|---:|---:|---:|---:|
| 4 | 8 | 2 | 0 | 2 | 2 | 14 |
| 5 | 6 | 2 | 0 | 0 | 1 | 9 |
| 6 | 9 | 1 | 2 | 2 | 1 | 15 |
| 7 | 9 | 2 | 0 | 0 | 1 | 12 |
| 8 | 9 | 2 | 0 | 0 | 1 | 12 |
| 9 | 14 | 2 | 0 | 2 | 2 | 20 |
| **Total** | **55** | **11** | **2** | **6** | **8** | **82** |

**Slides 4–9 are the most heavily source-supported block in either module** —
two-thirds direct, and only two synthesis statements, both on Slide 6 and both
framing rather than substance. The reason is structural: BEP §5 and IM matrix §4
are themselves boundary statements, so the teaching material can quote rather
than construct.

### Module 2 running totals

| | DIRECT | INTERP | SYNTH | UNRESOLVED | EXCLUDED | Rows |
|---|---:|---:|---:|---:|---:|---:|
| Slides 1–3 (§4) | 18 | 3 | 3 | 0 | 3 | 27 |
| Slides 4–9 (§7) | 55 | 11 | 2 | 6 | 8 | 82 |
| **Total** | **73** | **14** | **5** | **6** | **11** | **109** |

---

## 8. Five-function versus four-function frames — reconciliation

**These two frames are not the same thing, and are not treated as identical
anywhere in this module.**

### 8.1 The two frames

| | Frame A — five functions | Frame B — four functions |
|---|---|---|
| **Content** | prepare and maintain · contribute · review · approve or authorise · implement | BIM Manager · BIM Coordinator · CDE Administration · Lead Delivery Party |
| **Origin** | Module 1, Slide 4 | `bep/Harrismith-Fire-Station-BEP.md` §4.6 |
| **Status** | **Presentation synthesis** | **Source terminology** |
| **What it enumerates** | **Acts** — five things that happen to a BEP | **Functions** — four organisation-level information-management roles |
| **Attributable to the sources?** | **No.** No source enumerates five | **Yes.** §4.6 lists exactly these four |

### 8.2 Why both exist

They answer different questions and are not competing versions of one list.

**Frame A asks: what happens to the BEP?** It was built for Module 1's Slide 4,
where the audience needed to see that drafting, agreeing, approving and operating
a BEP are separate acts. Its five items are **verbs**, and they span functions —
"contribute" is done by task teams, "implement" by everyone who touches project
information.

**Frame B asks: which information-management functions does the project
establish?** It is BEP §4.6's own list, introduced at organisation level and
defined in §5. Its four items are **functions**, each with a named concern.

They cannot be mapped one-to-one. `Approve or authorise` in Frame A corresponds
to no single Frame B function — on Harrismith it is held by the **Task-Team
Lead** for sharing, and is **unresolved** for publication. `Contribute` maps to no
Frame B function at all.

### 8.3 How each is used in Module 2

| Frame | Used | Not used |
|---|---|---|
| **A (five)** | Only as carried-forward Module 1 context, in [`README.md`](README.md) §6, explicitly labelled as Module 1's framing | **Never** presented as the Harrismith function list; never attributed to §4.6 |
| **B (four)** | On Slides 3 and 4, as the source's own list, with the count stated | — |

**Slide 3 and Slide 4 both say "four".** The speaker notes for Slide 3 carry an
explicit instruction not to say "five functions", precisely because Module 1's
framing is the more recent thing in the presenter's memory.

### 8.4 The standing rule

**Frame A is teaching synthesis and may be used as such. Frame B is source
terminology and is what the sources say.** Where a statement needs to be
defensible against the repository — a source-map entry, a slide footer, an answer
to "where does it say that?" — **use Frame B.**

Neither frame is wrong. Conflating them would be.

---

## 9. Statement classification — Slides 10–14

Same scheme as §4 and §7.

### Slide 10 — CDE Administration implements governance

| Statement | Class | Source |
|---|---|---|
| `CDE Administration` is the function; `CDE Administrator` is a participant carrying it | **DIRECT** | S1 §4.6 (function list), §5.9; §5.11 and §9.7 use the participant form |
| The eight responsibilities — membership, folder and space implementation, permissions, Design Collaboration team-space configuration, coordination-space configuration, platform workflow configuration, implementing approved changes, checking configuration after an approved change | **DIRECT** | S1 §5.9 |
| `P` on C2, C3, A3; **`P Ck`** on C4 | **DIRECT** | S2 §3.2, §3.7 |
| **"CDE Administration implements governance; it does not create it"** | **DIRECT** | S1 §5.9 |
| **"CDE Administration implements governance; it does not define it. Changing the software does not make a decision."** | **DIRECT** | S5 §14 |
| **"Platform permission is not BEP authority"** — administrative rights confer the technical ability to change something and nothing more | **DIRECT** | S1 §5.9 |
| Platform permission is **not** authority to share, authority to publish, or authority to accept | **DIRECT** | S1 §6.9 |
| Platform access does **not** confer authority to share, publication authority, technical approval authority or acceptance authority | **DIRECT** | S5 §14 |
| **"Access is configured to support approved responsibility — the responsibility comes first, and the permission follows it"** | **DIRECT** | S1 §6.9; S5 §14 |
| Where access and approved responsibility diverge, **"the divergence is a deviation to be recorded, not a redefinition of who is responsible"** | **DIRECT** | S1 §6.9; S5 §14 |
| **"A configuration that was never approved is a deviation, however competently it was applied"** | **DIRECT** | S1 §5.9 |
| Governance decision precedes configuration change; platform configuration reflects the approved BEP and does not redefine it | **DIRECT** | S5 §17; S1 §12.1 |
| The CDE Administrator is named among roles **not** automatically holding publication authority | **DIRECT** | S1 §9.7 |
| **"No user names are specified in this document"** | **DIRECT** | S1 §6.9 |
| The one-participant-two-functions example — approving as BIM Manager is a different act from applying as CDE Administrator | **DIRECT** | S1 §5.11 |
| "Access determines what a user can technically do; governance determines what they are authorised to decide" | **INTERP** | Both halves sourced — S1 §6.9, S5 §14 — but not as one sentence |
| CDE Administration holder | **UNRESOLVED** | S1 §5.9; S2 §6 |
| Any ACC permission screenshot | **EXCLUDED** | Would invite the permission-equals-authority inference the slide refutes |
| Any extension of the function beyond the §5.9 list | **EXCLUDED** | The list is used as written |

### Slide 11 — Check, authorise, publish, receive and accept

| Statement | Class | Source |
|---|---|---|
| The eight-act sequence — author, technical check, information-quality check, authorise share, consume/coordinate, authorise publication, receive, accept | **DIRECT** for each act | S2 §3.3, §3.4, §3.6; S1 §9.2–9.8, §10.10, §10.11; S5 §3 |
| **Only two of these are information-state transitions** — T1 (WIP → Shared) and T4 (Shared → Published) | **DIRECT** | S5 §3 |
| Consume, coordination input, deliver, receive and accept are **not** information states — they are an action, a use/context, an event, an event and a status | **DIRECT** | S5 §3, §13 |
| *"An event or a decision does not create a new information state unless the governed state-transition rule explicitly says it does"* | **DIRECT** | S5 §3, §13 |
| **Check ≠ authorise** — checking confirms readiness for the next controlled decision | **DIRECT** | S1 §9.3; S2 §3.3 P2/P3 note |
| **Authorise for Shared ≠ publish** — *"Authorisation to share is not authorisation to publish or exchange"* | **DIRECT** | S1 §9.4 |
| **Publish ≠ receive** — *"A transmission record is not the information"*; *"A transmittal is not technical approval"* | **DIRECT** | S1 §10.10 |
| **Receive ≠ accept** — the four-term table: Published · Delivered · Received · Accepted | **DIRECT** | S1 §10.11 |
| **"Delivery does not prove acceptance. Receipt does not prove suitability."** | **DIRECT** | S1 §10.11 |
| **Accept ≠ technical approval** — acceptance applies to the identified purpose and requirement *"and to nothing beyond it"*; it does not automatically approve the design | **DIRECT** | S1 §9.8, §10.11 |
| Controlled-sharing authority — **established with the Task-Team Lead** | **DIRECT** | S1 §9.4; S2 §3.3 P4 |
| Publication / exchange authority — **unresolved, and the transition is blocked** | **DIRECT** | S1 §9.7; S2 §3.6 D4; S5 §3.1, §3.3 |
| Recipient acceptance authority — **unresolved / recipient-dependent** | **DIRECT** | S1 §9.8, §10.11; S2 §3.6 D7 |
| **"No acceptance authorities are invented. Where the accepting role remains unresolved, it remains TBD."** | **DIRECT** | S1 §10.11 |
| Technical / design approval — **outside the information-management allocation** | **INTERP** | No row of S2 allocates it; S1 §5.5–5.7 place technical responsibility with the task team. An absence, correctly read |
| Governance-change approval — unresolved, dependent on change class | **DIRECT** | S1 §12.7; S2 §3.7 A2 |
| "'Approved' is too vague unless the project identifies what was decided, for which purpose and by which authority" | **INTERP** | Generalises S1 §9.1 — "approve" is used only where a defined approval decision is intended and is not a catch-all |
| A complete end-to-end authorised route | **EXCLUDED** | Two links have no holder; one is blocked |
| Any unresolved authority shown as an omitted administrative detail | **EXCLUDED** | Must appear as a visible unresolved node, dashed step or blocked transition |

### Slide 12 — One process, several distinct authorities

| Statement | Class | Source |
|---|---|---|
| Sixteen authority types, each with a holder or a recorded absence | **DIRECT** for each allocation | S2 §3.1–3.7, §6; S1 §9.4, §9.7, §9.8, §12.7, §12.9; S5 §3.2; S6 §19 |
| Authorisation for controlled sharing — the one **established** authority | **DIRECT** | S1 §9.4 |
| Publication / exchange — **UNRESOLVED + BLOCKED** | **DIRECT** | S1 §9.7; S2 §3.6 D4; S5 §3.3 |
| Recipient acceptance — **UNRESOLVED / RECIPIENT-DEPENDENT** | **DIRECT** | S1 §9.8, §10.11; S2 §3.6 D7 |
| Governance change — **UNRESOLVED**, by change class | **DIRECT** | S1 §12.7; S2 §3.7 A2 |
| Implementation verification — **CONDITIONAL**; **"No single universal verifier is defined"** | **DIRECT** | S1 §12.9; S2 §3.7 A4 note |
| Issue closure — **CONDITIONAL**; closure follows re-coordination against reshared controlled information | **DIRECT** | S6 §15, §19 |
| Issue-response verification — allocated to the BIM Coordinator, and expressly **not** design approval | **DIRECT** | S2 §3.5 X4; S6 §19 |
| Technical / design approval — **OUTSIDE IM AUTHORITY** | **INTERP** | No row allocates it; the originating task team retains technical responsibility (S1 §5.5–5.7) |
| **"No single universal approver exists"**; **"unlimited authority is not assigned to the BIM Manager"**; the required authority corresponds to the nature of the decision | **DIRECT** | S2 §3.7 A2 note; S1 §12.7 |
| The seven-row unresolved-allocations register | **DIRECT** | S2 §6 |
| The six-label status vocabulary — `ALLOCATED` · `CONDITIONAL` · `UNRESOLVED` · `BLOCKED` · `RECIPIENT-DEPENDENT` · `OUTSIDE IM AUTHORITY` | **INTERP** | The statuses are sourced individually; the vocabulary is teaching structure |
| The ten / two / three / one distribution | **INTERP** | Counted from the map; no source presents this tally |
| "A mature BIM governance model does not search for one universal approver; it defines the correct authority for each decision" | **SYNTH** | Teaching wording. The no-universal-approver position is sourced; the maturity framing is not |
| Any vertical hierarchy | **EXCLUDED** | S1 §5.2 |
| The BIM Manager placed at the top | **EXCLUDED** | It holds none of the sixteen as a decision right; S2 §3.7 — unlimited authority is not assigned to it |
| Any hidden unresolved authority | **EXCLUDED** | Rows 7, 9 and 11 must be visible |

### Slide 13 — Harrismith names functions but not role holders

| Statement | Class | Source |
|---|---|---|
| Role definitions — nine functional roles, four IM functions | **DIRECT** | S1 §4.6; S2 §2 |
| The responsibility grammar — seven terms | **DIRECT** | S1 §5.12; S2 §1 |
| Functional boundaries — a *Holds / Does not hold* position for each role | **DIRECT** | S2 §4 |
| Process allocations — 25 information-management functions | **DIRECT** | S2 §3.1–3.7 |
| Some authority allocations established | **DIRECT** | S1 §9.4; S2 §3.3 |
| Records of what remains unresolved | **DIRECT** | S2 §6; S3 §6; S4 §7; S5 §19 |
| **"No names are populated. Role holders are TBD throughout Section 5"** | **DIRECT** | S1 §5.2 |
| **"No user names are specified in this document"** | **DIRECT** | S1 §6.9 |
| No organisation appointed; party categories only | **DIRECT** | S1 §4.2, §4.1 (TA-03); S2 preamble |
| **"No real contractual signatory is assigned"** | **DIRECT** | S1 §9.10 |
| Publication authority incomplete | **DIRECT** | S1 §9.7 |
| Acceptance authority incomplete — **"No acceptance authorities are invented"** | **DIRECT** | S1 §10.11 |
| **"No single universal verifier is defined"** | **DIRECT** | S1 §12.9 |
| For any container it must be answerable **who produced it, who checked it, who authorised it and for what purpose** | **DIRECT** | S1 §5.1 |
| One person may carry several functions without merging them | **DIRECT** | S1 §4.6, §5.11 |
| The four "why functions before names is useful" arguments | **SYNTH** | Teaching framing. The sources record the state, not its pedagogical value |
| The five "why named holders are eventually necessary" arguments | **INTERP** | Each follows from a sourced requirement — accountability from §5.1, permissions from §6.9's ordering rule, evidence from §5.1 — but the argument is assembled |
| "A function can be defined before a person is appointed, but it cannot be implemented indefinitely without a named holder" | **SYNTH** | Teaching wording |
| Every role holder | **UNRESOLVED** | S1 §2.3, §5.3–5.9; S2 §6 |
| TBD holders as evidence the framework is invalid | **EXCLUDED** | S1 §5.2 and S2 §2 present unpopulated holders as the normal current state |
| The framework as implemented because the functions are documented | **EXCLUDED** | *"Approval is not implementation, and implementation is not verification"* — S10 §11 in Module 1's source map; S1 §12.3, §12.9 |

### Slide 14 — What must Triviron assign before delivery begins?

| Statement | Class | Source |
|---|---|---|
| Q — Owner / Appointing Party organisation | **DIRECT (derivation)** | S1 §2.3, §5.3 — identity **not established** |
| Q — Lead Delivery Party organisation | **DIRECT (derivation)** | S1 §5.4; S2 §6 — holder **TBD** |
| Q — BIM Manager, BIM Coordinator, CDE Administration holders | **DIRECT (derivation)** | S1 §5.5, §5.6, §5.9; S2 §6 — all **TBD** |
| Q — Task-Team Leads for each discipline | **DIRECT (derivation)** | S1 §5.7; S2 §6 — **TBD for every task team** |
| Q — who may author; who performs the required checks | **DIRECT (derivation)** | S1 §5.8; S2 §2 — **TBD** |
| Q — who authorises information for Shared | **DIRECT (derivation)** | S1 §9.4 — the function is established; the holder is not |
| Q — who holds publication / exchange authority | **DIRECT (derivation)** | S1 §9.7 — **UNRESOLVED** |
| Q — who receives; who may accept each delivery | **DIRECT (derivation)** | S1 §9.8, §10.11 — **UNRESOLVED**; *"No acceptance authorities are invented"* |
| Q — who holds technical or design approval authority | **DIRECT (derivation)** | Outside the IM allocation on Harrismith |
| Q — which permissions follow each responsibility | **DIRECT (derivation)** | S1 §6.9 — responsibility first, permission after |
| Q — which participants hold more than one function, and how they stay distinguishable | **DIRECT (derivation)** | S1 §5.11 — combination allowed, merging not |
| Q — who verifies the process is being implemented | **DIRECT (derivation)** | S1 §12.9 — **"No single universal verifier is defined"** |
| **Stage 5 ordering** — permissions configured *after* authorities are allocated | **DIRECT** | S1 §6.9: *"the responsibility comes first, and the permission follows it"* |
| The seven-stage assignment sequence | **INTERP** | Each stage's content is sourced; the sequence is teaching structure |
| "Harrismith gives us a functional model. Triviron must assign organisations, people and authority to that model before relying on it in delivery." | **SYNTH** | Teaching synthesis — the required closing message |
| The three closing takeaways | **SYNTH** | Teaching synthesis |
| **Every Triviron appointment, organisation, programme, information requirement or authority decision** | **EXCLUDED** | **None exists in this repository.** No Triviron fact may be asserted |
| Any claim about Triviron's actual organisation | **EXCLUDED** | The sequence is a checklist derived from Harrismith gaps, not a description |

### Summary — Slides 10–14

| Slide | DIRECT | INTERP | SYNTH | UNRESOLVED | EXCLUDED | Rows |
|---|---:|---:|---:|---:|---:|---:|
| 10 | 15 | 1 | 0 | 1 | 2 | 19 |
| 11 | 14 | 2 | 0 | 0 | 2 | 18 |
| 12 | 11 | 2 | 1 | 0 | 3 | 17 |
| 13 | 14 | 1 | 2 | 1 | 2 | 20 |
| 14 | 13 | 1 | 2 | 0 | 2 | 18 |
| **Total** | **67** | **7** | **5** | **2** | **11** | **92** |

### Module 2 final totals

| | DIRECT | INTERP | SYNTH | UNRESOLVED | EXCLUDED | Rows |
|---|---:|---:|---:|---:|---:|---:|
| Slides 1–3 (§4) | 18 | 3 | 3 | 0 | 3 | 27 |
| Slides 4–9 (§7) | 55 | 11 | 2 | 6 | 8 | 82 |
| Slides 10–14 (§9) | 67 | 7 | 5 | 2 | 11 | 92 |
| **Total** | **140** | **21** | **10** | **8** | **22** | **201** |

**Seventy per cent of classified statements rest on direct source wording.** The
ten synthesis statements cluster where the repository holds no evidence — the
Slide 1 central message, Slide 6's generalisation, Slide 12's maturity framing,
Slide 13's balance argument, and Slide 14's close.

---

## 10. Module-wide reconciliation

A single consolidated view. **Nothing here is resolved to make the summary look
complete.**

### 10.1 Every project role identified

| # | Exact source term | Established? | Named holder |
|---|---|---|---|
| 1 | `Owner / Appointing Party` | Function yes; **identity not established** | **None** |
| 2 | `Lead Delivery Party` | Function yes | **TBD** |
| 3 | `BIM Manager` | Function yes | **TBD** |
| 4 | `BIM Coordinator` | Function yes | **TBD** |
| 5 | `Task-Team Lead` | Function yes | **TBD for every task team** |
| 6 | `Author` | Function yes | **TBD** |
| 7 | `Checker` | Function yes | **TBD** |
| 8 | `CDE Administration` (function) / `CDE Administrator` (participant) | Function yes | **TBD** |
| 9 | `Receiving / recipient function` (`Rcp`) | Generic function; **not an organisation** | **Not established** |

Plus a **separate class**: the five training-only governance functions
(`AG-001`–`AG-005`), functional holder `Training Implementation Owner` under
TA-02, **no personal holder recorded**. These are **not project delivery roles**.

### 10.2 Every authority type identified — sixteen

| # | Authority | Status |
|---|---|---|
| 1 | Authoring | `ALLOCATED` — Author |
| 2 | Task-team technical / content checking | `ALLOCATED` — Checker |
| 3 | Information-quality / readiness checking | `ALLOCATED` — Checker |
| 4 | Coordination (process) | `ALLOCATED` — BIM Coordinator |
| 5 | Authorisation for controlled sharing | **`ALLOCATED` and ESTABLISHED** — Task-Team Lead |
| 6 | Authorisation to consume Shared information | `ALLOCATED` — Task-Team Lead |
| 7 | Publication / exchange | **`UNRESOLVED` + `BLOCKED`** |
| 8 | Technical / design approval | **`OUTSIDE IM AUTHORITY`** |
| 9 | Governance change, by class | **`UNRESOLVED`** |
| 10 | Receipt of exchange | `ALLOCATED` — recipient function |
| 11 | Acceptance for a stated purpose | **`UNRESOLVED` / `RECIPIENT-DEPENDENT`** |
| 12 | Issue-response verification | `ALLOCATED` — BIM Coordinator |
| 13 | Issue closure | `CONDITIONAL` |
| 14 | Implementation verification | `CONDITIONAL` — no universal verifier |
| 15 | Escalation of unresolved interfaces | `ALLOCATED` — BIM Coordinator |
| 16 | Platform configuration implementation | `ALLOCATED` — CDE Administration |

### 10.3 Allocated authorities — ten

1, 2, 3, 4, 5, 6, 10, 12, 15, 16.

**Only one is described by the sources as *established* rather than merely
allocated:** authorisation for controlled sharing (BEP §9.4).

### 10.4 Unresolved authorities — three

| Authority | Recorded status |
|---|---|
| **Publication / exchange** | UNRESOLVED; expressly **not** automatically the BIM Manager, BIM Coordinator, CDE Administrator or Architect; the T4 transition is **blocked** |
| **Recipient acceptance** | UNRESOLVED / recipient-dependent; no acceptance workflow defined; *"No acceptance authorities are invented"* |
| **Governance change, by change class** | UNRESOLVED; *"No single universal approver exists"* |

Two further authorities are **conditional** rather than unresolved: issue closure
(follows verification against reshared information) and implementation
verification (varies by change type; **no single universal verifier**).

### 10.5 Authority outside the information-management model — one

**Technical / design approval.** No row of the responsibility matrix allocates
it. The originating task team retains technical responsibility, before and after
coordination, under professional standards rather than under this document.

This is an **absence correctly read**, not a stated exclusion — classified
INTERPRETATION throughout.

### 10.6 Named-holder gaps — all nine

**Every project role holder is TBD or not established.** No organisation is
appointed to any party category. No contractual signatory is assigned. No user
names are specified anywhere in the BEP.

The Model / Information Responsibility Matrix adds that all its container
allocations are **PROPOSED GOVERNANCE under TA-03** — a training organisation
model, not an appointment structure.

### 10.7 Significant teaching-synthesis statements — ten

| Slide | Statement |
|---|---|
| 1 | "If responsibility is not assigned deliberately, the project still makes decisions — but through assumption, access or habit" |
| 2 | The same job title may carry different authority on different projects |
| 3 | Assigning functions before names is useful during planning |
| 6 | "Expertise in BIM does not create contractual, technical or publication authority" |
| 6 | Authority here is defined rather than diminished |
| 12 | "A mature BIM governance model does not search for one universal approver…" |
| 13 | The four "why functions before names is useful" arguments |
| 13 | "A function can be defined before a person is appointed, but it cannot be implemented indefinitely without a named holder" |
| 14 | "Harrismith gives us a functional model. Triviron must assign organisations, people and authority…" |
| 14 | The three closing takeaways |

Plus the module's **central teaching message**, recorded as teaching wording in
[`README.md`](README.md) §2.

**Each is labelled where it appears.** None is attributed to a Harrismith
document.
