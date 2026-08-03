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
   organisation-level list has **four** functions. Module 2 says so.
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
