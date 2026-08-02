# PAD-001 — Publication Arrangement Approval Decision

| Field | Value |
|---|---|
| Document status | **CONTROLLED PUBLICATION ARRANGEMENT DECISION** |
| Decision classification | **APPROVED GOVERNANCE** |
| Governance reference | **PAD-001** |
| Decision outcome | **APPROVE WITH CONDITIONS** |
| Decision status | **PE-2 REACHED — PUBLICATION ARRANGEMENT APPROVED WITH CONDITIONS; PE-3 NOT AUTHORISED** |
| Decision date | **2026-08-01** |
| Decision subject | **PAC-001 — Publication Arrangement Candidate 0.1** |
| Current readiness basis | **PRA-002 — READY FOR APPROVAL WITH CONDITIONS** |
| Deciding function | **Training Publication Arrangement Approver under AG-003** |
| Functional holder exercising the function | **Training Implementation Owner** |
| Training basis | **TA-02** — simulated role participation |
| Scope | **Training Baseline 0.1 publication arrangement only** |
| Source | **Orchestrator decision — Increment 8H** |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

> ## **ARRANGEMENT APPROVAL IS NOT PUBLICATION AUTHORISATION.**

> **This decision explicitly exercises AG-003** and **reaches PE-2 only**. It
> **does not reach or authorise PE-3**; **authorises no publication or
> exchange**; **authorises no package generation**; **authorises no container
> creation**; **assigns no implementation authority**; **assigns no recipient
> acceptance authority**; **creates no real project appointment or professional
> authority**; and **creates no Git tag or GitHub release**.

> **Subsequent status — 2026-08-02, Increment 8H-A.** **AG-004 established the
> `Training Baseline Publication Owner`** function required by **PM-2** (§4.2),
> with the **Training Implementation Owner** as functional holder under
> **TA-02** and **no personal holder recorded**. **PM-2's owner-function
> establishment residual is satisfied**; its status becomes **`APPROVED WITH
> CONDITIONS BY PAD-001 — OWNER FUNCTION ESTABLISHED UNDER AG-004`**.
> **Condition C1 (§5.1) is SATISFIED BY AG-004**, and **P6 step 2 (§8) is
> satisfied**. **P6 otherwise remains ACTIVE and the publication-package commit
> remains NOT PINNED.** **Publication / exchange authority remains UNRESOLVED**,
> **PE-3 remains not reached**, **publication remains NOT AUTHORISED** and **the
> publication hold remains ACTIVE**. **No decision section below is altered.**
> Decision:
> [`docs/Training-Baseline-Publication-Owner-Function-Decision.md`](Training-Baseline-Publication-Owner-Function-Decision.md).

---

## 1. Decision identification

### 1.1 Function exercised

> **The Training Publication Arrangement Approver, established by AG-003, is
> exercised here.**

Exercised by the **Training Implementation Owner** as functional holder, under
**TA-02**. **No personal holder is recorded.**

**This decision states which function is being exercised**, as AG-001 §9,
AG-002 §5.1 and AG-003 §5 require where one holder performs more than one
training function (BEP 5.11, 9.12). **AG-001 and AG-002 are not exercised
here.**

### 1.2 Readiness precondition satisfied

**AG-003 §4** permits approval only where a fresh controlled readiness
assessment concludes `READY FOR APPROVAL` or `READY FOR APPROVAL WITH
CONDITIONS`.

| Field | Value |
|---|---|
| Current readiness basis | **PRA-002** — `docs/Publication-Arrangement-Readiness-Reassessment.md` |
| PRA-002 outcome | **READY FOR APPROVAL WITH CONDITIONS** |
| PRA-002 blocker count | **Zero** |
| PRA-001 | **Historically valid**; **not the current basis** |

**The precondition is satisfied.**

## 2. Approval subject and snapshot control

### 2.1 Snapshots

| Role | Commit | PAC-001 substantive-body hash |
|---|---|---|
| **Substantive candidate snapshot assessed by PRA-002** | `532c4ec74f2013461f7fef637c0e6734a11b2dfb` | `4d67dcfcc7556665b3f93f2363b3dfd4` |
| **Decision-input repository state** | `48a50d31ebe6f4533499074c111b9a000c11208b` | `4d67dcfcc7556665b3f93f2363b3dfd4` |

### 2.2 Snapshot findings — recorded expressly

- **The substantive PAC-001 body is byte-identical at both commits.** Both hash
  to `4d67dcfcc7556665b3f93f2363b3dfd4`.
- **The intervening changes created PRA-002 and added status or traceability
  notes only** — 596 insertions, **zero deletions**, across five files.
- **This decision applies to the PAC-001 substantive content identified by that
  body hash**, not to a commit as such.
- **The commit created by Increment 8H will record this decision.**
- **None of these commits is the publication-package commit.**
- **The publication-package commit remains unpinned** (§8).

### 2.3 What is approved

> **The approval applies to the defined arrangement — not to a generated
> package, a CDE object, or a publication event.**

**Nothing has been generated, created, uploaded or published**, and this
decision changes none of that.

## 3. Decision

> ## **PAC-001 — APPROVE WITH CONDITIONS**
>
> The publication arrangement proposed by PAC-001, identified by substantive
> body hash `4d67dcfcc7556665b3f93f2363b3dfd4`, is **approved with conditions**
> as the governed publication arrangement for **Training Baseline 0.1**.

**All seven PM matters receive an explicit disposition** (§4). **Every condition
and prerequisite recorded by PRA-002 is disposed of or preserved** (§5, §6).

---

## 4. PM-1 to PM-7 decisions

### 4.1 PM-1 — Publication location

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |
| **Approved position** | A dedicated governance / management-baseline child container under **`03. Published`**, **provisionally identified** and **cross-referenced — not duplicated — from `0. Common Files / 02. BEP (BIM Execution Plan)`** |

**Conditions and limits:**

- **the final child-container name remains controlled but undecided**;
- **no container is created by PAD-001**;
- **CGD-001 live correspondence must be verified** (C6);
- **CDE implementation authority and an executor are required before creation**
  (P7);
- **no existing PDF, child folder or Published-area content is retrospectively
  authorised** (CGD-C02, CGD-C04).

### 4.2 PM-2 — Publication owner

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |
| **Approved position** | A distinct **`Training Baseline Publication Owner`** function **is required** for the approved arrangement |

**Recorded expressly:**

- **PAD-001 approves that the function should exist**;
- **PAD-001 does not establish the function**;
- **PAD-001 appoints or nominates no holder**;
- **a later authority-establishment decision is required**;
- **that later decision may use a new AG-family identifier only after scope and
  collision review**;
- **establishment of the function is required before the publication-package
  commit is pinned and before package assembly**;
- **the Publication Owner remains distinct from** the arrangement approver, the
  publication / exchange authoriser, the executor and the recipient acceptance
  authority.

> **After PAD-001, PM-2 must no longer be described as an undecided arrangement
> position.** Its residual status is:
>
> **`APPROVED WITH CONDITIONS — OWNER FUNCTION ESTABLISHMENT PENDING`**

### 4.3 PM-3 — Publication format and package boundary

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |

**Approved:**

- **seven separate `PDF/A-2b` authoritative renditions**;
- **one authoritative `UTF-8 JSON` manifest**;
- **`SHA-256` package-integrity controls**;
- **individually addressable files**;
- **no merged authoritative PDF**;
- **no ZIP as the authoritative package**.

#### 4.3.1 Source-companion decision

> **All seven `UTF-8 Markdown` authoring sources are expressly INCLUDED as
> subordinate source companions.**

**The approved package boundary is therefore:**

| Class | Count | Contents |
|---|---|---|
| **Authoritative files** | **8** | 7 × `PDF/A-2b` renditions + 1 × `UTF-8 JSON` manifest |
| **Subordinate source companions** | **7** | 7 × `UTF-8 Markdown` authoring sources |
| **Total package files** | **15** | |

**The Markdown companions:**

- **are non-authoritative**;
- **remain subordinate to their corresponding PDF/A-2b renditions**;
- **must be identified as source companions in the manifest**;
- **do not become governing merely because they are the authoring source**.

**This satisfies PRA-002 condition C3 at PE-2.** **C2 and C5 are preserved as
later conditions** (§5).

### 4.4 PM-4 — Publication metadata

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |
| **Approved position** | The **fourteen-field minimum governance set** |

**Recorded:**

- **the documents and the authoritative UTF-8 JSON manifest are the primary
  metadata record**;
- **ACC-side fields are optional and conditional**;
- **unsupported platform fields must not weaken the package record**;
- **final filename composition remains subject to the required naming controls**
  (C5).

### 4.5 PM-5 — Upload procedure

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |
| **Approved position** | The **nine-stage separated manual procedure**, as the **governance procedure** |

**Recorded:**

- **no technical upload mechanism is selected**;
- **PAD-001 does not authorise PE-3**;
- **PAD-001 does not authorise PE-4**;
- **upload-route confirmation (P1), implementation authority (P7), commit
  pinning (P6) and destination preparation (P8) remain prerequisites**.

### 4.6 PM-6 — Post-upload verification

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |
| **Approved position** | The **seven-check verification model** |

**The following remain required:**

- **PDF/A-2b validation**;
- **JSON manifest parsing**;
- **SHA-256 recomputation**;
- **destination identity and content checks**;
- **failure / stop handling**.

> **No verification is performed by PAD-001.**

### 4.7 PM-7 — Supersession and withdrawal

| Field | Value |
|---|---|
| **Decision** | **APPROVED WITH CONDITIONS** |
| **Approved position** | The **governance route** |

**The approved route requires:**

- **retained history**;
- **no silent deletion or replacement**;
- **a fresh publication-event authorisation**;
- **an explicit relationship to the superseded or withdrawn item**;
- **recorded verification**.

> **No technical route and no PE-S authority is established by PAD-001.**

### 4.8 Disposition summary

| PM | Matter | Decision | Residual |
|---|---|---|---|
| **PM-1** | Publication location | **APPROVED WITH CONDITIONS** | Name undecided; container not created; C6, P7, P8 |
| **PM-2** | Publication owner | **APPROVED WITH CONDITIONS** | **Owner function establishment pending** |
| **PM-3** | Format and package boundary | **APPROVED WITH CONDITIONS** | C2, C5; companions **included** |
| **PM-4** | Metadata | **APPROVED WITH CONDITIONS** | C4 enduring; C5; P4 |
| **PM-5** | Upload procedure | **APPROVED WITH CONDITIONS** | P1, P6, P7, P8; **no mechanism selected** |
| **PM-6** | Post-upload verification | **APPROVED WITH CONDITIONS** | P2, P3, P8; **none performed** |
| **PM-7** | Supersession / withdrawal | **APPROVED WITH CONDITIONS** | P5; **no PE-S authority** |

---

## 5. PRA-002 condition disposition

| ID | Condition | Disposition |
|---|---|---|
| **C1** | Publication Owner function | **SATISFIED AT PE-2 AS TO THE ARRANGEMENT POSITION; RESIDUAL CONDITION OPEN** |
| **C2** | PDF/A-2b format | **CARRIED FORWARD** |
| **C3** | Source companions | **SATISFIED AT PE-2** |
| **C4** | Metadata primacy | **CARRIED FORWARD — ENDURING** |
| **C5** | Naming and presentation controls | **CARRIED FORWARD** |
| **C6** | CGD-001 live correspondence | **CARRIED FORWARD** |

### 5.1 C1 — Publication Owner function

**`SATISFIED AT PE-2 AS TO THE ARRANGEMENT POSITION; RESIDUAL CONDITION OPEN`**

- **PM-2 position approved**;
- **no function established**;
- **no holder appointed**;
- **a later authority-establishment decision is required**.

### 5.2 C2 — PDF/A-2b format

**`CARRIED FORWARD`.** **Before PE-3:**

- **a conforming generation route must be demonstrated**;
- **a validation route must be demonstrated**;
- **conformance must not be inferred from a `.pdf` extension**.

### 5.3 C3 — Source companions

**`SATISFIED AT PE-2`.** **All seven UTF-8 Markdown source companions are
included as subordinate package files** (§4.3.1).

### 5.4 C4 — Metadata primacy

**`CARRIED FORWARD — ENDURING`.** **The documents and manifest remain primary**,
at every later event and thereafter.

### 5.5 C5 — Naming and presentation controls

**`CARRIED FORWARD`.** **Minimum controls must be established before package
assembly** — for the seven renditions, the manifest, the source companions and
the proposed child container.

### 5.6 C6 — CGD-001 live correspondence

**`CARRIED FORWARD`.** **Verification remains required before operational
reliance and PE-4.** **CGD-001 verification remains PENDING.**

---

## 6. Implementation prerequisites — preserved

**P1 … P8 are preserved in full, without weakening or reclassification.**

| ID | Prerequisite | Required before | Status |
|---|---|---|---|
| **P1** | Upload mechanism | **PE-4** | **Unconfirmed** |
| **P2** | PDF/A generation and validation toolchain | Package assembly and **PE-3** | **Not selected, not tested** |
| **P3** | Integrity recomputation and destination retrieval | Source now; destination before **PE-5** | **Destination unconfirmed** |
| **P4** | ACC metadata support | Reliance on ACC fields | **Unconfirmed** |
| **P5** | Supersession and withdrawal technical mechanism | **PE-S** | **Unconfirmed** |
| **P6** | Publication-package commit pinning | Generation and **PE-3** | **Not pinned** |
| **P7** | Child-container implementation authority and executor | **PE-4** | **Authority not established** |
| **P8** | Destination verification | Publication execution | **Not performed** |

> **PAD-001 approves governance only. It does not satisfy an implementation
> prerequisite merely by naming it.**

---

## 7. GCR-005

### 7.1 Closure position

> **`CLOSED BY PAD-001 — SEVEN PUBLICATION-ARRANGEMENT PARAMETERS DEFINED;
> IMPLEMENTATION CONDITIONS AND PREREQUISITES REMAIN`**

**GCR-005 is closed at the governance-definition level.** Its seven matters are
now defined by approved arrangement positions.

### 7.2 Seven-matter mapping

| GCR-005 matter | Approved PM position |
|---|---|
| Publication location | **PM-1** — dedicated child container under `03. Published`, provisionally identified |
| Publication owner | **PM-2** — Training Baseline Publication Owner function required; **establishment pending** |
| Publication format | **PM-3** — 7 × PDF/A-2b + 1 × UTF-8 JSON manifest + SHA-256; 7 Markdown companions included |
| Publication metadata | **PM-4** — fourteen-field minimum set, document and manifest primary |
| Upload procedure | **PM-5** — nine-stage separated manual procedure |
| Post-upload verification | **PM-6** — seven-check verification model |
| Supersession or withdrawal route | **PM-7** — governance route with retention and fresh event authorisation |

### 7.3 Historical wording preserved

**GD-001 §6 and AD-001 §6 record the same seven matters in slightly different
words.** **Neither historical wording is rewritten by PAD-001.** The variance is
preserved as recorded, and PAD-001 operationalises the **common seven-matter
substance** using the stable **PM-1 … PM-7** identifiers.

### 7.4 What closure does not mean

- **Defining the parameters does not authorise publication.**
- **The publication hold remains ACTIVE.**
- **GCR-006 remains OPEN** — no governed coordination cycle has been exercised
  or evidenced.
- **UD-001 remains unresolved.**
- **Every condition in §5 and prerequisite in §6 remains.**

---

## 8. Publication-package commit

**No publication-package commit is pinned.**

**P6 controls the later pinning sequence.** The package commit may be pinned
**only after**:

1. **PAD-001 and its register entry exist**;
2. **the Training Baseline Publication Owner function has been separately
   established**;
3. **any required naming and presentation controls are established**.

**Pinning occurs before generation and before PE-3.**

> **No publication commit is pinned during Increment 8H**, and **no package
> artefact exists** — no rendition, no manifest, no digest.

---

## 9. PE-event status

| Ref | Event | Position |
|---|---|---|
| **PE-1** | Planning the arrangement | **Reached previously** — PAC-001 |
| **PE-2** | Approving the arrangement | **REACHED BY PAD-001** |
| **PE-3** | Authorising a publication event | **Not reached** |
| **PE-4** | Executing the publication | **Not reached** |
| **PE-5** | Verifying the published result | **Not reached** |
| **PE-6** | Delivering | **Not reached** |
| **PE-7** | Receiving | **Not reached** |
| **PE-8** | Accepting | **Not reached** |
| **PE-S** | Superseding or withdrawing | **Not reached** |

> ## **ARRANGEMENT APPROVAL IS NOT PUBLICATION AUTHORISATION.**

**PE-3 requires a publication / exchange authority that does not exist**, and
**PAD-001 does not create one**.

---

## 10. Authority separation

**PAD-001 confers no:**

- **publication / exchange authority**;
- **PE-3 authority**;
- **upload or execution authority**;
- **CDE administration or implementation authority**;
- **recipient acceptance authority**;
- **PE-S authority**;
- **design or professional approval authority**.

**The Training Publication Arrangement Approver is exercised only within
AG-003's PE-2 scope.**

> **Holding several training functions does not merge them.** The Training
> Implementation Owner holds the Training Baseline Approver (AG-001), the
> Training CDE Governance Approver (AG-002) and the Training Publication
> Arrangement Approver (AG-003). **Only the third is exercised here.**

### 10.1 Unresolved authorities — unchanged

| Authority | Status |
|---|---|
| Project publication / exchange authority | **UNRESOLVED** |
| Recipient acceptance authority | **UNRESOLVED** |
| CDE administration / implementation authority | **Not established** |
| Training Baseline Publication Owner | **Required by PM-2; not established** |

---

## 11. Explicit non-effects

PAD-001 does **not**:

- authorise publication, exchange, issue, delivery, receipt or acceptance;
- lift or vary the **publication hold**;
- reach or authorise **PE-3** or any later PE event;
- establish the **Training Baseline Publication Owner** function, or appoint a
  holder;
- establish publication / exchange, recipient acceptance, CDE administration or
  implementation authority;
- create, rename, move or delete any folder or container;
- generate any PDF/A rendition, manifest or digest;
- assemble a package;
- pin a publication-package commit;
- select or test an upload, generation, validation or retrieval route;
- verify the live Autodesk configuration;
- perform supersession or withdrawal;
- close **GCR-006**;
- resolve **UD-001**;
- establish the naming, coordinate, titleblock or template standards;
- create a real project appointment, professional or contractual authority;
- create a Git tag or GitHub release.

---

## 12. Status after PAD-001

| Item | Status |
|---|---|
| **PAD-001** | **APPROVE WITH CONDITIONS** |
| **PAC-001** | **Approved by PAD-001**; retained as the **historical proposal record** |
| **PRA-002** | **Historical readiness basis** |
| **AG-003** | **Exercised through PAD-001**; remains an established function |
| **PM-1 … PM-7** | **APPROVED WITH CONDITIONS** |
| **PM-2** | **Owner function establishment pending** |
| **GCR-005** | **CLOSED BY PAD-001** — governance-definition level |
| **GCR-006** | **OPEN** |
| **UD-001** | **Unresolved** |
| **CGD-001 verification** | **Pending** |
| **Publication** | **NOT AUTHORISED** |
| **Publication hold** | **ACTIVE** |
| Publication / exchange authority | **UNRESOLVED** |
| Recipient acceptance authority | **UNRESOLVED** |
| CDE implementation authority | **Not established** |
| Project standards | **Not established** |
| **PE-2** | **Reached** |
| **PE-3 … PE-S** | **Not reached** |
| Package artefact | **None** |
| Publication-package commit | **Not pinned** |

---

## 13. Decision statement

> ## **PAD-001 — APPROVE WITH CONDITIONS**
>
> **PE-2 REACHED — PUBLICATION ARRANGEMENT APPROVED WITH CONDITIONS; PE-3 NOT
> AUTHORISED.**
>
> The arrangement proposed by **PAC-001**, substantive body hash
> `4d67dcfcc7556665b3f93f2363b3dfd4`, is **approved with conditions**. All seven
> PM positions are approved with conditions; **the seven Markdown source
> companions are included as subordinate files**; **GCR-005 is closed at the
> governance-definition level**.
>
> **Conditions C1 … C6 and prerequisites P1 … P8 remain in force.**
>
> ## **ARRANGEMENT APPROVAL IS NOT PUBLICATION AUTHORISATION.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** Candidate — [`docs/Publication-Arrangement-Candidate-0.1.md`](Publication-Arrangement-Candidate-0.1.md).
Readiness basis — [`docs/Publication-Arrangement-Readiness-Reassessment.md`](Publication-Arrangement-Readiness-Reassessment.md).
Authority — [`docs/Training-Publication-Arrangement-Approver-Function-Decision.md`](Training-Publication-Arrangement-Approver-Function-Decision.md).
CGD-001 — [`docs/CDE-Structure-Governance-Decision.md`](CDE-Structure-Governance-Decision.md).
Original assessment — [`docs/Publication-Arrangement-Readiness-Assessment.md`](Publication-Arrangement-Readiness-Assessment.md).
Baseline approval — [`docs/Training-Baseline-0.1-Approval-Decision.md`](Training-Baseline-0.1-Approval-Decision.md).
Gate C — [`docs/Training-Baseline-0.1-Gate-C-Decision.md`](Training-Baseline-0.1-Gate-C-Decision.md).
