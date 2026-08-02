# NPC-001 — Training Baseline Naming and Presentation Control Candidate

| Field | Value |
|---|---|
| Document status | **CONTROLLED CANDIDATE** |
| Classification | **PROPOSED GOVERNANCE — NOT APPROVED** |
| Candidate reference | **NPC-001** |
| Candidate status | **CANDIDATE PREPARED — NOT ASSESSED — NOT APPROVED** |
| Candidate date | **2026-08-02** |
| Source | **Orchestrator-directed proposal coordinated under AG-004 — Increment 8H-C** |
| Candidate scope | **Training Baseline 0.1 package-specific naming and presentation controls only** |
| Authority | **None** |
| Candidate-coordination function | **Training Baseline Publication Owner under AG-004** |
| Future decision function | **Training Publication Arrangement Naming and Presentation Approver under AG-005** |
| Source repository state reviewed | `09c04ff9d84e79d95317206b393e217e3fb209a5` |
| Training basis | **TA-02** — simulated role participation |

> ## **NPC-001 IS A PROPOSAL. IT IS NOT AN AG-005 DECISION.**
>
> **AG-005 is not exercised.** **C5 remains `CARRIED FORWARD`.** **P6 step 3
> remains pending.** **No filename, naming rule, container name or presentation
> rule becomes governing merely because it appears in NPC-001.** **No package
> file or container is created.** **No package commit is proposed or pinned.**
> **No publication is authorised.**

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

---

## 1. What this candidate is

**A controlled proposal of the minimum package-specific naming and presentation
controls required by PAD-001 condition C5.** It is prepared so that the
Training Publication Naming and Presentation Approver established by **AG-005**
has something defined to consider.

### 1.1 What it is not

NPC-001 is **not**:

- a decision;
- an approval;
- an assessment of its own readiness;
- an exercise of AG-005;
- an exercise of AG-004's coordination authority as though it were approval;
- a project-wide naming, coordinate, titleblock or template standard;
- an instruction to create, rename or generate anything;
- a publication authorisation.

### 1.2 Non-effect

NPC-001 does **not**:

- satisfy **C5**;
- satisfy **P6 step 3**;
- alter **PAD-001** or its approved package boundary;
- alter any of the seven approved source documents;
- create, rename, move or delete any file, folder or container;
- generate a rendition, manifest, digest or package;
- propose or pin a publication-package commit;
- select or test a PDF/A or upload route;
- verify CGD-001 live correspondence;
- assign publication / exchange, execution, CDE implementation or acceptance
  authority;
- reach or authorise **PE-3** or any later event.

---

## 2. Candidate owner and decision route

```text
Candidate coordination:
Training Baseline Publication Owner under AG-004

Readiness assessment:
Separate controlled Authority: None record — not yet performed

Decision:
Training Publication Naming and Presentation Approver under AG-005 —
not yet exercised
```

### 2.1 One holder, separate acts

**The Training Implementation Owner is the functional holder of both AG-004 and
AG-005 under TA-02.** That does **not** merge the functions:

| Rule | |
|---|---|
| **Candidate coordination and approval are separate acts** | AG-005 §12; AG-004 §4 item 7 |
| **This candidate record identifies AG-004 only** | AG-004 coordinates and may submit; it **does not approve** |
| **A later decision record must identify AG-005 only** | AG-005 §5 — every exercise must name AG-005 as its authority basis |
| **The same holder does not merge the functions** | BEP 5.11, 9.12; AG-005 §8 |

> **AG-004 is exercised here only as a coordination act. No approval act
> occurs.**

---

## 3. Approved package boundary — input only

**The boundary is PAD-001's** (PAD-001 §4.3.1). NPC-001 **names** what PAD-001
approved; it may not change it.

| Class | Count | Contents |
|---|---|---|
| **Authoritative files** | **8** | 7 × `PDF/A-2b` renditions + 1 × `UTF-8 JSON` manifest |
| **Subordinate source companions** | **7** | 7 × `UTF-8 Markdown` authoring sources |
| **Total package files** | **15** | |

**NPC-001 may name those files. It may not:**

- add a file class;
- remove a file class;
- merge the authoritative renditions;
- make a ZIP authoritative;
- make Markdown companions authoritative;
- change PAD-001.

---

## 4. Package identity tokens — candidate

**Proposed controlled token dictionary:**

| Token | Proposed meaning |
|---|---|
| `HFS` | Harrismith Fire Station |
| `TB0P1` | Training Baseline 0.1 |
| document token | Identifies the controlled document (§6) |
| `AWC` | **Approved With Conditions** |
| `SOURCE` | Subordinate UTF-8 Markdown source companion |
| `MANIFEST` | Authoritative package manifest |

**Recorded expressly:**

- **`TB0P1` uses `P` to represent the decimal point in `0.1`**;
- **this avoids an additional period inside the filename stem**;
- **`AWC` must always be expanded in this token dictionary as
  `Approved With Conditions`**;
- **these are package-specific tokens only**;
- **they are not project-wide naming standards.**

---

## 5. Proposed filename grammar

### 5.1 Authoritative rendition

```text
HFS-TB0P1-<DOCUMENT>-AWC.pdf
```

### 5.2 Authoritative manifest

```text
HFS-TB0P1-MANIFEST-AWC.json
```

### 5.3 Subordinate source companion

```text
HFS-TB0P1-<DOCUMENT>-AWC-SOURCE.md
```

### 5.4 Character and format rules — candidate

1. **Filename stems use only** uppercase ASCII letters `A–Z`, digits `0–9` and
   the hyphen `-`.
2. **The hyphen is the only token separator.**
3. **No spaces** are permitted in package filenames.
4. **No underscores** are permitted.
5. **No leading or trailing hyphen** is permitted.
6. **No consecutive hyphens** are permitted.
7. **The only period is the one immediately before the extension.**
8. **Extensions are lowercase and fixed by class** — `.pdf`, `.json`, `.md`.
9. **Token order is fixed.**
10. **Every filename must be unique under a case-insensitive comparison.**
11. **A filename may not exceed 120 characters including its extension.**
12. **The source-companion relationship is represented only by the final
    `SOURCE` token before `.md`.**
13. **The status token is `AWC`**; the full human-readable status remains
    **`APPROVED WITH CONDITIONS`**.
14. **These controls apply only to the Training Baseline 0.1 package.**

---

## 6. Controlled document token map

**Proposed mapping:**

| # | Source document | Document token |
|---|---|---|
| 1 | `bep/Harrismith-Fire-Station-BEP.md` | `BEP` |
| 2 | `supporting/information-management-responsibility-matrix.md` | `IM-RESP-MATRIX` |
| 3 | `supporting/model-information-responsibility-matrix.md` | `MODEL-INFO-RESP-MATRIX` |
| 4 | `supporting/information-delivery-schedule.md` | `INFO-DELIVERY-SCHEDULE` |
| 5 | `supporting/cde-workflow-state-strategy.md` | `CDE-WORKFLOW-STATE-STRATEGY` |
| 6 | `supporting/coordination-review-strategy.md` | `COORDINATION-REVIEW-STRATEGY` |
| 7 | `supporting/governance-decision-register.md` | `GOVERNANCE-DECISION-REGISTER` |

> **The map is exhaustive for this package and does not create reusable project
> document codes.**

---

## 7. Exact fifteen-file candidate inventory

### 7.1 Seven authoritative `PDF/A-2b` renditions

1. `HFS-TB0P1-BEP-AWC.pdf`
2. `HFS-TB0P1-IM-RESP-MATRIX-AWC.pdf`
3. `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC.pdf`
4. `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC.pdf`
5. `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC.pdf`
6. `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC.pdf`
7. `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC.pdf`

### 7.2 One authoritative `UTF-8 JSON` manifest

8. `HFS-TB0P1-MANIFEST-AWC.json`

### 7.3 Seven subordinate `UTF-8 Markdown` source companions

9. `HFS-TB0P1-BEP-AWC-SOURCE.md`
10. `HFS-TB0P1-IM-RESP-MATRIX-AWC-SOURCE.md`
11. `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC-SOURCE.md`
12. `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC-SOURCE.md`
13. `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC-SOURCE.md`
14. `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC-SOURCE.md`
15. `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC-SOURCE.md`

> **These are proposed names for files that do not exist.** **No file is created
> by NPC-001.**

---

## 8. Companion-to-rendition relationship

**Proposed:**

- **every source companion shares the complete stem of its corresponding
  rendition**;
- **the only additional source-companion token is `SOURCE`**;
- **removing `-SOURCE` and changing `.md` to `.pdf` yields the paired
  authoritative rendition filename**;
- **the authoritative manifest must record the relationship explicitly**;
- **filename similarity does not make the source companion authoritative**;
- **the `PDF/A-2b` rendition remains authoritative**.

### 8.1 Reconciliation table

| # | Authoritative rendition | Paired source companion | Shared stem |
|---|---|---|---|
| 1 | `HFS-TB0P1-BEP-AWC.pdf` | `HFS-TB0P1-BEP-AWC-SOURCE.md` | `HFS-TB0P1-BEP-AWC` |
| 2 | `HFS-TB0P1-IM-RESP-MATRIX-AWC.pdf` | `HFS-TB0P1-IM-RESP-MATRIX-AWC-SOURCE.md` | `HFS-TB0P1-IM-RESP-MATRIX-AWC` |
| 3 | `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC.pdf` | `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC-SOURCE.md` | `HFS-TB0P1-MODEL-INFO-RESP-MATRIX-AWC` |
| 4 | `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC.pdf` | `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC-SOURCE.md` | `HFS-TB0P1-INFO-DELIVERY-SCHEDULE-AWC` |
| 5 | `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC.pdf` | `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC-SOURCE.md` | `HFS-TB0P1-CDE-WORKFLOW-STATE-STRATEGY-AWC` |
| 6 | `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC.pdf` | `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC-SOURCE.md` | `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC` |
| 7 | `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC.pdf` | `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC-SOURCE.md` | `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC` |

**The manifest — `HFS-TB0P1-MANIFEST-AWC.json` — has no source companion**
(§11.4).

---

## 9. Proposed PM-1 child-container name

**Proposed exact name:**

```text
Training Baseline 0.1
```

**Proposed minimum controls:**

- **exact title case as shown**;
- **single spaces only**;
- **no leading or trailing space**;
- **numeric baseline form `0.1`**;
- **direct child of `03. Published`**;
- **no additional child or subfolder is authorised**;
- **the name is package-specific**;
- **the name does not establish a project-wide CDE naming standard.**

> **The container does not exist merely because NPC-001 proposes its name.**
> **No container is created or renamed.** **CDE administration or implementation
> authority remains required** (P7). **CGD-001 live correspondence remains
> unverified** (C6). **P7 and P8 remain active.**

**Note on form.** The container name uses spaces and a period, while package
*filenames* do not (§5.4). These are deliberately different objects — a CDE
container label and a package filename — and the container form follows the
as-found `03. Published` root convention adopted by CGD-001, whose naming
**remains provisional** (CGD-C05).

---

## 10. Minimum `PDF/A-2b` presentation markings — candidate

**A package-specific publication-control marking is proposed for each future
authoritative `PDF/A-2b` rendition.**

### 10.1 First-page control block

The future rendition would display:

| # | Item |
|---|---|
| 1 | `Harrismith Fire Station` |
| 2 | `Training Baseline 0.1` |
| 3 | The document's full human-readable title |
| 4 | `APPROVED WITH CONDITIONS` |
| 5 | Baseline approval reference **`AD-001`** |
| 6 | Publication-arrangement reference **`PAD-001`** |
| 7 | Package identifier `HFS-TB0P1` |
| 8 | The exact source repository commit — **populated only after later controlled pinning** |
| 9 | The rendition-generation date — **populated only during later authorised generation** |

### 10.2 Every-page footer

```text
HFS-TB0P1 | <DOCUMENT> | AWC | Page <x> of <y>
```

### 10.3 What this marking is not

**Recorded expressly:**

- **this is a package-specific publication marking**;
- **it is not a project titleblock standard**;
- **it does not establish a reusable sheet standard**;
- **no existing source document is modified by NPC-001**;
- **the marking is applied only during later authorised rendition generation.**

> **Items 8 and 9 are deliberately unpopulatable today.** No commit is pinned
> and no generation is authorised.

---

## 11. Manifest presentation and identity rule

**Proposed:**

1. **the manifest filename is exactly `HFS-TB0P1-MANIFEST-AWC.json`**;
2. **the manifest remains authoritative for package identity and integrity**;
3. **it must record the exact fifteen-file inventory**;
4. **it must record the authoritative or subordinate role of each file**;
5. **it must record each source-companion-to-rendition relationship**;
6. **it must carry the exact package identifier `HFS-TB0P1`**;
7. **it must carry the full status `APPROVED WITH CONDITIONS`**;
8. **it must carry the later pinned source commit**;
9. **it must use PAD-001's approved PM-4 metadata set**;
10. **NPC-001 does not change or enlarge that approved metadata set**;
11. **no manifest is generated in this increment.**

### 11.1 Traceability to PM-4

**PAD-001 §4.4 approved the fourteen-field minimum governance set** and recorded
that **"final filename composition remains subject to the required naming
controls (C5)"**. NPC-001 proposes that composition and **adds no field, removes
no field and changes no field's carrier**.

**One matter is recorded for the later readiness assessment, not resolved here.**
PAC-001 §5.1 marks fields 1–4 (project identifier, package / baseline
identifier, document title, revision / version) as filename-carried, and marks
field 5 (status) as carried **in the document and manifest**, not in the
filename. **The `AWC` token proposed at §4 places the status token in the
filename as well.** NPC-001 records this as **additive**, not substitutive — the
document and manifest carriers are unchanged — but **whether it is within C5's
scope is a readiness question** (§14, question 15) and **is not determined
here**.

---

## 12. Source-companion presentation rule

**Proposed:**

- **the seven packaged Markdown companions remain byte-faithful copies of the
  later pinned source files**;
- **NPC-001 requires no inserted heading, front matter, footer or content
  mutation**;
- **their subordinate status is communicated through**:
  - **the `SOURCE` filename token**;
  - **their `.md` extension**;
  - **the authoritative manifest relationship and role fields**;
- **no source companion may override its `PDF/A-2b` rendition.**

> **Byte-faithfulness is why no marking is proposed inside the Markdown.** The
> presentation markings at §10 apply to the renditions only.

---

## 13. Collision and ambiguity assessment

**A factual candidate assessment. It is not a readiness assessment** (§15).

| # | Statement | Position |
|---|---|---|
| 1 | All fifteen proposed filenames are unique | **Confirmed** — §7, fifteen distinct stems |
| 2 | They remain unique under case-insensitive comparison | **Confirmed** — all stems are uppercase ASCII; no two differ only by case |
| 3 | Every rendition has exactly one source companion | **Confirmed** — §8.1, seven pairs |
| 4 | The manifest has no source companion | **Confirmed** — §8.1 closing; the manifest is generated, not authored |
| 5 | `IM-RESP-MATRIX` and `MODEL-INFO-RESP-MATRIX` are distinct | **Confirmed** — differing leading tokens; neither is a prefix of the other at a token boundary |
| 6 | `TB0P1` cannot be confused with a file extension | **Confirmed** — it is not preceded by a period; the only period precedes the extension (§5.4 rule 7) |
| 7 | `SOURCE` appears only on subordinate companions | **Confirmed** — §7.3 only; absent from all eight authoritative names |
| 8 | `AWC` has one controlled meaning | **Confirmed** — §4, `Approved With Conditions`; no other expansion is proposed |
| 9 | Only one period appears in each filename | **Confirmed** — §5.4 rule 7; `TB0P1` encodes `0.1` without a period |
| 10 | Extensions identify the file class | **Confirmed** — `.pdf` rendition, `.json` manifest, `.md` companion |
| 11 | The proposed container name is distinct from the four CDE root areas | **Confirmed** — `Training Baseline 0.1` differs from `0. Common Files`, `01. WIP`, `02. Shared`, `03. Published` |
| 12 | No proposed rule changes the approved package boundary | **Confirmed** — §3; 8 + 7 = 15 unchanged |
| 13 | No proposed rule establishes a project-wide standard | **Confirmed** — §4, §5.4 rule 14, §6, §9, §10.3, §14 |

**Longest proposed filename** — `HFS-TB0P1-COORDINATION-REVIEW-STRATEGY-AWC-SOURCE.md`
and `HFS-TB0P1-GOVERNANCE-DECISION-REGISTER-AWC-SOURCE.md`, **52 characters
including extension**, within the 120-character rule (§5.4 rule 11).

> **Platform compatibility has not been tested.** No claim is made that any
> platform accepts, preserves or displays these names. Testing would require
> acts NPC-001 does not authorise.

---

## 14. Scope boundary

```text
NPC-001 applies only to:

- the Training Baseline 0.1 fifteen-file package; and
- its proposed PM-1 child container.

NPC-001 is not:

- the Harrismith project naming standard;
- a general CDE naming standard;
- a titleblock standard;
- a template standard;
- a coordinate standard;
- a reusable naming convention for other packages.
```

**The project-wide naming, coordinate, titleblock and template standards
remain:**

> **`NOT ESTABLISHED`**

---

## 15. Candidate readiness questions — unanswered

**Recorded for the later `Authority: None` readiness assessment.** **None is
answered in Increment 8H-C.**

| # | Question | Status |
|---|---|---|
| 1 | Does NPC-001 cover all eleven AG-005 candidate-precondition matters? | **Unanswered** |
| 2 | Are all fifteen filenames complete and unique? | **Unanswered** |
| 3 | Is every source companion paired unambiguously with one rendition? | **Unanswered** |
| 4 | Does the manifest filename and role remain coherent? | **Unanswered** |
| 5 | Is `TB0P1` an unambiguous representation of Training Baseline 0.1? | **Unanswered** |
| 6 | Is `AWC` adequately controlled by its token definition? | **Unanswered** |
| 7 | Are the document tokens distinct and traceable to the seven source documents? | **Unanswered** |
| 8 | Are the character, case, separator and extension rules internally coherent? | **Unanswered** |
| 9 | Does the proposed container name remain package-specific? | **Unanswered** |
| 10 | Do the PDF presentation markings identify the document and governance status adequately? | **Unanswered** |
| 11 | Does the source-companion rule preserve byte-faithful subordinate sources? | **Unanswered** |
| 12 | Do the controls preserve PAD-001's package boundary? | **Unanswered** |
| 13 | Are collision and ambiguity risks adequately addressed? | **Unanswered** |
| 14 | Are the controls clearly barred from becoming project-wide standards? | **Unanswered** |
| 15 | Does any proposed rule require authority that NPC-001 does not possess? | **Unanswered** |
| 16 | Is NPC-001 ready to be submitted to AG-005 for a decision? | **Unanswered** |
| 17 | Would approval satisfy C5? | **Unanswered** |
| 18 | Would approval satisfy P6 step 3, or would a residual condition remain? | **Unanswered** |

> **§13's collision assessment is a factual statement by the candidate about
> itself. It is not an answer to question 13, and it is not a readiness
> finding.**

---

## 16. Required next gate

> **A separate controlled `Authority: None` readiness assessment is required
> before AG-005 may be exercised against NPC-001.**

**This is the orchestrator-directed workflow for NPC-001.** It:

- **adds no authority to NPC-001**;
- **does not alter AG-005**;
- **does not imply the candidate is ready**;
- **prevents the candidate-preparation record from becoming its own approval
  justification.**

> **The assessment is not created in Increment 8H-C.**

---

## 17. Effect on condition C5

> **`C5 — CANDIDATE PREPARED; NOT ASSESSED; NOT APPROVED`**

**C5's overall status is preserved:**

> **`CARRIED FORWARD`**

| Statement | |
|---|---|
| **The decision route exists under AG-005** | AG-005 §4, §10 |
| **NPC-001 now exists** | This record |
| **The readiness assessment has not occurred** | §16 |
| **AG-005 has not been exercised** | AG-005 §5 |
| **Package assembly remains blocked** | PAD-001 §5.5 |

---

## 18. Effect on prerequisite P6

```text
P6 step 1: SATISFIED
P6 step 2: SATISFIED BY AG-004
P6 step 3: CANDIDATE PREPARED — NOT ASSESSED — NOT SATISFIED
P6 step 4: NOT PERFORMED
P6 step 5: SEQUENCE UNCHANGED
```

**P6 overall status is preserved:**

> **`ACTIVE — PUBLICATION-PACKAGE COMMIT NOT PINNED`**

> **No repository commit is the publication-package commit.** The state recorded
> in this document's header identifies **the repository state reviewed**, not a
> package commit.

---

## 19. Effect on current governance matters

| Matter | Effect of NPC-001 |
|---|---|
| **PAD-001** | **Unchanged** — not modified |
| **PAC-001**, **PRA-001**, **PRA-002**, **CGD-001**, **AD-001**, **GD-001** | **Unchanged** |
| **AG-001, AG-002, AG-003** | **Unchanged; none exercised** |
| **AG-004** | **Unchanged in substance** — a dated subsequent-status note only; coordination act performed |
| **AG-005** | **Unchanged in substance** — a dated subsequent-status note only; **not exercised** |
| **The seven approved source documents** | **Unchanged in content**; none renamed |
| **PM-1 … PM-7** | **APPROVED WITH CONDITIONS BY PAD-001 — unchanged** |
| **C1** | **SATISFIED BY AG-004 — unchanged** |
| **C2, C4, C6** | **CARRIED FORWARD — unchanged** |
| **C3** | **SATISFIED AT PE-2 — unchanged** |
| **C5** | **CARRIED FORWARD** — **candidate prepared; not assessed; not approved** (§17) |
| **P1 … P8** | **Active — unchanged.** **P6 step 3 remains pending** (§18) |
| **GCR-005** | **CLOSED at the governance-definition level — unchanged** |
| **GCR-006** | **OPEN — unchanged** |
| **UD-001** | **Unresolved — unchanged** |
| **CGD-001 verification** | **Pending — unchanged** |
| Publication / exchange authority | **UNRESOLVED — unchanged** |
| Technical executor | **Unassigned — unchanged** |
| Recipient acceptance authority | **UNRESOLVED — unchanged** |
| CDE implementation authority | **Not established — unchanged** |
| Project standards | **Not established — unchanged** |
| **PE-2** | **Reached — unchanged** |
| **PE-3 … PE-S** | **Not reached — unchanged** |
| Package artefact | **None** |
| Publication-package commit | **Not pinned** |
| **Publication** | **NOT AUTHORISED — unchanged** |
| **Publication hold** | **ACTIVE — unchanged** |

---

## 20. Identifier-family note

**NPC-001 opens the `NPC-` family** — *Naming and Presentation Control
Candidate*. **`NPC-001` was unused before this record**, and the prefix collides
with none of the established families: `AD-`, `AG-`, `CGD-`, `EC-`, `GCR-`,
`GD-`, `OC-`, `OF-`, `PAC-`, `PAD-`, `PE-`, `PM-`, `PPER-`, `PPQ-`, `PRA-`,
`ROA-`, `TA-`, `UD-`.

**The family is expressly limited to package-specific naming and presentation
control candidates.**

> **`NPC-` is a candidate family, not a decision or authority family.** **No
> `NPC-` record carries authority, approves anything, or reaches any PE event.**

**Later use of the family still requires a controlled scope and collision
review** — **no future candidate belongs to it automatically.**

---

## 21. Candidate statement

> ## **NPC-001 — TRAINING BASELINE NAMING AND PRESENTATION CONTROL CANDIDATE**
>
> **CANDIDATE PREPARED — NOT ASSESSED — NOT APPROVED.**
>
> **Classification: PROPOSED GOVERNANCE — NOT APPROVED. Authority: None.**
>
> NPC-001 proposes package-specific naming and presentation controls for the
> **fifteen-file Training Baseline 0.1 package** and its **proposed PM-1 child
> container**, coordinated under **AG-004** for a later decision by **AG-005**.
>
> **A separate controlled `Authority: None` readiness assessment is required
> before AG-005 may be exercised.**
>
> **AG-005 is not exercised. C5 remains `CARRIED FORWARD`. P6 step 3 remains
> pending. No file, container, rendition, manifest or digest exists. No package
> commit is proposed or pinned. No project-wide standard is established.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** AG-005 — [`docs/Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md`](Training-Publication-Naming-and-Presentation-Approver-Function-Decision.md).
AG-004 — [`docs/Training-Baseline-Publication-Owner-Function-Decision.md`](Training-Baseline-Publication-Owner-Function-Decision.md).
Arrangement decision — [`docs/Publication-Arrangement-Approval-Decision.md`](Publication-Arrangement-Approval-Decision.md).
Candidate arrangement — [`docs/Publication-Arrangement-Candidate-0.1.md`](Publication-Arrangement-Candidate-0.1.md).
Readiness reassessment — [`docs/Publication-Arrangement-Readiness-Reassessment.md`](Publication-Arrangement-Readiness-Reassessment.md).
CGD-001 — [`docs/CDE-Structure-Governance-Decision.md`](CDE-Structure-Governance-Decision.md).
