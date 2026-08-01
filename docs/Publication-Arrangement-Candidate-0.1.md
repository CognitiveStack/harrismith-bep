# Publication Arrangement Candidate 0.1

| Field | Value |
|---|---|
| Candidate ID | **PAC-001** |
| Document status | **PROPOSED GOVERNANCE — NOT APPROVED** |
| Authority | **None** |
| Status | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| Scope | **Training Baseline 0.1 and its controlled publication package only** |
| Phase / increment | Phase 8 — Publication Planning; Increment 8F |
| Date | 2026-08-01 |
| Baseline context | Training Baseline 0.1 — **APPROVED WITH CONDITIONS** (**AD-001**, 2026-08-01) |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

> **This is a proposal.** It is **not approved governance**, **not a publication
> decision**, and **not a publication-event authorisation**. It **assigns no
> authority**, **performs no implementation**, and **cannot be executed** unless
> it is later approved *and* a publication event is separately authorised.

> **Controlled refinement — 2026-08-01, Increment 8F-A.** The Increment 8F-R
> read-only review returned **30 consistency checks PASS and 1 FAIL**: the
> authoritative human-readable file format was not explicitly named.
> **Increment 8F-A completes that previously unspecified PM-3 format position**
> — naming **PDF/A-2b**, **UTF-8 JSON**, **UTF-8 Markdown** and **SHA-256**
> (§4). **The candidate's classification and status are unchanged**: it remains
> **PROPOSED GOVERNANCE — NOT APPROVED**, **CANDIDATE ARRANGEMENT PREPARED —
> NOT APPROVED**, **Authority: None**. **No approval and no authority follows
> from this refinement.** All other PM candidate positions are **unchanged**,
> apart from consequential cross-references in §1, §5, §7, §9 and §15.
>
> **The format selection is a governance candidate selection.** It is **not**
> derived from EC-3 observational evidence, and no observation supports or
> supplies it.

> **Subsequent status — 2026-08-01, Increment 8G.** A readiness assessment,
> **PRA-001**, was completed against this candidate. **Outcome: NOT READY FOR
> APPROVAL.** The reason is **PRA-B01** — PM-1's publication-location position
> depends on **OF-001**, which records the intended CDE structure as undefined.
> **PAC-001 remains prepared and NOT APPROVED. It is not rejected**, **no
> candidate position is amended by the assessment**, and **no approval or
> authority follows from it**. **PE-2 remains not reached.** The candidate text
> below — including the Increment 8F-A refinement — is **unchanged**.
> Assessment:
> [`docs/Publication-Arrangement-Readiness-Assessment.md`](Publication-Arrangement-Readiness-Assessment.md).

> **Subsequent status — 2026-08-01, Increment 8G-B.** **CGD-001 adopted the
> as-found four-area root topology with conditions** as the intended training
> CDE governance. **PAC-001's proposed `03. Published` child-container position
> is retained**, and **no substantive PM-1 revision is currently required**.
> **PAC-001 remains prepared and NOT APPROVED** — the adopted topology supports
> the position but **does not approve it**. **No child container was created**,
> **naming remains provisional** (CGD-C05), and **arrangement approval and
> implementation authority remain separate and unheld**. **Readiness must be
> reassessed before PE-2.** **No PM section or decision-table row below is
> rewritten by this note.** Decision:
> [`docs/CDE-Structure-Governance-Decision.md`](CDE-Structure-Governance-Decision.md).

> **Subsequent status — 2026-08-01, Increment 8G-C.** **AG-003 established the
> Training Publication Arrangement Approver** — the function that **may take a
> later PE-2 arrangement-approval decision** on this candidate. **PAC-001
> remains prepared and NOT APPROVED**; **no candidate position changed**; **no
> PM matter was approved**; and **PAC-001 itself assigns no authority** — its
> Authority remains **None**. **The fresh readiness assessment remains
> required** before AG-003's approval power may be exercised, and **PE-2 remains
> not reached**. Function decision:
> [`docs/Training-Publication-Arrangement-Approver-Function-Decision.md`](Training-Publication-Arrangement-Approver-Function-Decision.md).

---

## 0. How to read this candidate

**Evidence informed this candidate; it did not choose it.** The Increment 8D
observation was assessed **INSUFFICIENT** against every matter it touched
(PPER-004 … PPER-009). Where a position is selected below, the selection rests on
a **governance argument**, with observation used only to bound feasibility and to
show what would have to be confirmed later.

**Nothing here is selected because it was visible in ACC.**

### 0.1 Relationship to GCR-005

**GCR-005** is recorded in two places with slightly different wording — **GD-001
§6** and **AD-001 §6, Condition 2**. Both state the same seven matters.

**Neither historical decision is rewritten, and neither is altered by this
candidate.** This candidate operationalises the **common seven-matter
substance** using the stable control identifiers **PM-1 … PM-7** established in
the Increment 8A framework §3.

---

## 1. Package identity and boundary

### 1.1 What the candidate package represents

**One point-in-time, controlled rendition of Training Baseline 0.1** — the
governance baseline approved with conditions by **AD-001 §4**, at an identified
repository commit.

**It is not "the repository".** It is not everything in `docs/`, and it is not a
running mirror of `main`.

### 1.2 Authoritative publication files — candidate

> **The authoritative package files are eight in total: seven `PDF/A-2b`
> renditions and one `UTF-8 JSON` manifest** (§4).

| # | Authoritative package file | Generated from — authoritative **source** document |
|---|---|---|
| 1 | PDF/A-2b rendition | `bep/Harrismith-Fire-Station-BEP.md` |
| 2 | PDF/A-2b rendition | `supporting/information-management-responsibility-matrix.md` |
| 3 | PDF/A-2b rendition | `supporting/model-information-responsibility-matrix.md` |
| 4 | PDF/A-2b rendition | `supporting/information-delivery-schedule.md` |
| 5 | PDF/A-2b rendition | `supporting/cde-workflow-state-strategy.md` |
| 6 | PDF/A-2b rendition | `supporting/coordination-review-strategy.md` |
| 7 | PDF/A-2b rendition | `supporting/governance-decision-register.md` |
| 8 | **UTF-8 JSON manifest** | — (describes the package; see §4.4) |

**The right-hand column identifies the seven core governance documents approved
by AD-001 §4** — the **authoritative source documents from which the seven
renditions would later be generated**.

> **Those Markdown source files are not themselves the authoritative
> publication renditions.** Where they are carried in the package at all, they
> are **optional source companions** (§1.3, §4.1), subordinate to the
> corresponding PDF/A-2b rendition.

The manifest is **authoritative for package identity and integrity** (§4.4).

### 1.3 Classification of everything else

| Class | Contents | Candidate treatment |
|---|---|---|
| **Supporting / source** | The seven **UTF-8 Markdown (`.md`)** sources | **Optional source companions.** Carried for traceability, **subordinate** to the corresponding PDF/A-2b rendition, identified as source companions in the manifest, and **never the authoritative rendition**. Included **only if the later arrangement approval expressly includes them** (§4.1) |
| **Companion — Authority: None** | `working/README.md`; `guidance/BIM-Delivery-Guide.md` | **Excluded.** AD-001 §4.1 records these as companions with **Authority: None**; they were not approved as governance and **must not become governing by being packaged with material that was** |
| **Repository-only records** | AG-001, GD-001, AD-001, ROA-001, this candidate, the Phase 8 framework and register, `working/`, `standards/` | **Excluded from the package.** These are the repository's own governance and control history |
| **Evidence — repository-only** | `docs/Increment-7C-Live-Validation-Record.md`; `docs/Increment-8D-…-Observation-Record.md` | **Excluded.** These are **evidence**, not publishable baseline content, and publishing them would risk their being read as project-facing statements about the live system |
| **Not established** | `standards/naming/`, `standards/coordinates/`, `standards/titleblocks/`, `standards/templates/` | **Excluded — they do not exist** (AD-001 §4.1) |

> **Not every repository file belongs in the package**, and nothing is included
> merely because it is in `docs/`.

### 1.4 A note on document 7

`supporting/governance-decision-register.md` is both an approved baseline
document **and** a live register that continues to accumulate entries. The
candidate therefore publishes **a snapshot at the identified commit**, and the
manifest records that commit. **Divergence between the published snapshot and a
later repository state is expected and legitimate** (BEP §13.5).

### 1.5 Not created here

**No package is created, generated, exported or assembled by this increment.**
§1 defines what a package *would* contain if the arrangement were later approved
and a publication event separately authorised.

---

## 2. PM-1 — candidate publication location

| Field | Value |
|---|---|
| **Governing question** | Which governed destination holds the published Training Baseline package, and on what basis it is *the* governed destination rather than merely an available one |
| **Controlling repository source** | Increment 8A §3; BEP §13.5, §6.10; CDE Workflow & State Strategy §3.1 (T4), §5 |
| **Assessed evidence** | **PPER-004** — visible structure to depth 3, **ASSESSED — INSUFFICIENT** |
| **Limitations** | Depth 3 only; single account's visibility; one point in time; **absence of observation is not observation of absence** |

### 2.1 Options considered

| Option | Summary |
|---|---|
| **A** | `0. Common Files / 02. BEP (BIM Execution Plan)` — observed, empty, topically matched |
| **B** | The existing `03. Published / Drawings - PDF` folder |
| **C** | A **dedicated new child container under `03. Published`**, holding governance/management baselines only |

### 2.2 Candidate position — Option C

> **Candidate: a dedicated new child container under `03. Published`, holding
> the governance / management baseline package only, provisionally identified,
> and cross-referenced — not duplicated — from `0. Common Files / 02. BEP (BIM
> Execution Plan)`.**

### 2.3 Rationale

- **Information state before topic.** Under the approved workflow, **T4**
  transitions information to **Published / Authorised** (CDE Workflow & State
  Strategy §3.1). A baseline that has passed arrangement approval and
  event authorisation *is* Published / Authorised information, and the candidate
  places it with other Published / Authorised information rather than in a
  general reference area whose information state is undefined.
- **Separation from design deliverables.** The observed `03. Published` children
  are organised around **design deliverables** — `Construction Documents - PDF`,
  `Drawings - PDF`, `Models - IFC`, `Models - RVT`, `Specifications`. A
  management baseline is a different kind of information; a dedicated sibling
  keeps it from being read as a design deliverable.
- **No reliance on existing content.** The candidate **does not use, overwrite,
  replace, supersede or depend on** the pre-existing drawing PDF (§10).

### 2.4 What this rationale does not claim

> **The folder is not proposed because it is called `Published`.** An area named
> after an information state is **evidence of naming only** (BEP 6.3;
> Increment 7C §4).

**This candidate proposes that the intended CDE structure adopt that
correspondence.** It does not assert that the correspondence already holds.

### 2.5 Unresolved

- **The intended CDE structure is not defined** — **OF-001** records the
  as-found root areas and states expressly that the intended state is **not
  defined**. **PM-1 cannot be finally decided ahead of, or in contradiction to,
  that undecided matter.**
- **Provisional naming.** Any container name is **provisional**, because **no
  project naming standard exists** (§13). The candidate deliberately proposes no
  literal folder name.
- **Creation of a new container is an implementation act** requiring **separate
  implementation authority**. **None exists**, and this candidate creates
  nothing.

---

## 3. PM-2 — candidate publication-owner function

| Field | Value |
|---|---|
| **Governing question** | Which **function** owns the publication act, and under what authority that function exists |
| **Controlling repository source** | AG-001 §9; BEP 9.7, 9.8, 10.11; Increment 8A §4.1 |
| **Assessed evidence** | **None, and none is possible.** PM-2 was **excluded from observation entirely** (register §6, §10.3) |
| **Limitations** | **No observation can supply this.** Register §5.2 records "resolve" as **No** for observation across all seven matters, and PM-2 as not even informable by it |

### 3.1 Candidate position

> **Candidate: propose a distinct functional role — a *Training Baseline
> Publication Owner* — as a training-implementation function, to be established
> (or refused) by a separate authority decision.**

**No holder is appointed or nominated.** The function is **proposed only**.

### 3.2 Four functions kept distinct

| Function | Candidate position |
|---|---|
| **Candidate publication owner** | **Proposed** by this candidate. Owns package identity and readiness for a proposed publication |
| **Publication / exchange authoriser** | **UNRESOLVED.** Authorises a specific publication event (PE-3). **Not proposed here** |
| **Technical uploader / executor** | **UNRESOLVED.** Performs the upload (PE-4). A performing function, **not an authorising one** |
| **Recipient acceptance authority** | **UNRESOLVED.** A **recipient-side** function (PE-8). Cannot be created by the publishing side at all |

> **These four are not collapsed.** Owning a package is not authorising its
> publication; authorising is not executing; and none of the three is
> acceptance.

### 3.3 What provides no appointment evidence

Permissions, folder or account ownership, project or team membership,
administrative access, and previous publication or Transmittal activity
(Increment 8A §4.1; ROA-001 §2.1). **Evidence of authority would be EC-9, and
no EC-9 record exists.**

### 3.4 Unresolved

- **Project publication / exchange authority — UNRESOLVED.**
- **Recipient acceptance authority — UNRESOLVED.**
- Whether a *Training Baseline Publication Owner* should exist at all is
  **itself the decision**, and it is **not taken here**.
- The function, if established, would operate under **TA-02** — simulated role
  participation — and would be **no real project appointment**.

---

## 4. PM-3 — candidate publication format

| Field | Value |
|---|---|
| **Governing question** | What artefact form is published, and how it is generated from the authoring source |
| **Controlling repository source** | BEP §13.5 (generated project-facing artefact route); README §3.4 (`output/`); README §7 (controlled resources declare their own status) |
| **Assessed evidence** | **PPER-005** — sampled formats and existing derivatives, **ASSESSED — INSUFFICIENT** |
| **Limitations** | Two sampled items; content never retrieved, so format is observable **only as declared**; **a derivative is not a deliverable** |

### 4.1 Candidate position

> **Candidate: seven `PDF/A-2b` renditions, one authoritative `UTF-8 JSON`
> manifest, optional `UTF-8 Markdown (.md)` source companions, and `SHA-256`
> integrity digests.**

**`PDF/A-2b` is selected as the candidate fixed human-readable record format.**

| Layer | Candidate format | Candidate content | Rationale |
|---|---|---|---|
| **Authoritative human-readable output** | **`PDF/A-2b`** | **One rendition per controlled document — seven in total**, not one merged file | A **fixed, self-contained, archival** record. Each controlled resource **declares its own status, version and authority** (README §7); merging them would produce a single artefact with seven conflicting status blocks |
| **Package manifest** | **`UTF-8 JSON`** | One manifest — see §4.4 | Package identity, contents, provenance, format declaration and integrity in one addressable, machine-checkable place |
| **Optional source companion** | **`UTF-8 Markdown (.md)`** | The seven authoring sources | Traceability to the authoring source. **Optional and subordinate** — see §4.1.2 |
| **Integrity record** | **`SHA-256`** | One digest per package file, recorded in the manifest | The destination did not expose checksum or size (PPER-008), so integrity must be carried **by the package**, not relied on from the platform |

#### 4.1.1 Required package treatment — renditions

- **one separate PDF/A-2b rendition for each of the seven approved core
  governance documents**;
- **seven authoritative rendition files in total**;
- **no merged authoritative PDF**;
- **every rendition individually addressable**;
- **every rendition associated with exactly one source document**;
- **every rendition recorded separately in the package manifest**.

#### 4.1.2 Optional source companions

The Markdown source companions are:

- **optional**;
- **subordinate** to the corresponding authoritative PDF/A-2b rendition;
- **included only if the later arrangement approval expressly includes them**;
- **clearly identified in the manifest as source companions**;
- **not governing merely because they are the authoring source**.

#### 4.1.3 Integrity rules

- **one SHA-256 digest for every authoritative rendition**;
- **one SHA-256 digest for every included optional source companion**;
- **the digest algorithm and value recorded in the manifest**;
- **digests computed from the final package files before publication**;
- **recomputed during source-package verification** (§7.1).

> **No digest has been calculated**, and none is calculated by this increment.

#### 4.1.4 Package structure

The candidate package is a **set of individually addressable files**. It is
**not** a single merged PDF, **not** a ZIP archive, **not** one opaque package
item, and **not** a live mirror of the repository.

### 4.2 Why per-document renditions rather than one archive

A single archive would be one opaque CDE item: individually addressable
documents can be versioned, referenced and superseded on their own terms, which
the supersession route (§8) depends on.

### 4.3 What is deliberately not selected on evidence

> **No format is proposed because it exists in the live project.** `SVF` and
> `SVF2` were observed as **platform-generated derivatives of a PDF and an RVT**
> (PPER-005). They are **viewer derivatives, not deliverable formats**, they do
> not apply to text documents, and **their existence is not approval of any
> deliverable form**.

### 4.4 Manifest — candidate format and contents

**Candidate format: `UTF-8 JSON`.**

The manifest is **authoritative** for:

- **package identity**;
- **package contents**;
- **source-to-rendition mapping**;
- **provenance**;
- **file-format declaration**;
- **integrity records**.

**Required per-file entries — at minimum:**

| # | Field |
|---|---|
| 1 | **Source repository path** |
| 2 | **Published filename** |
| 3 | **Package role** — authoritative rendition, manifest, or source companion |
| 4 | **Media or rendition format** |
| 5 | **Source repository commit** |
| 6 | **Digest algorithm** — `SHA-256` |
| 7 | **Digest value** |

**Package-level contents:** package identifier and version; source repository
and **exact commit**; the approval decision relied upon (**AD-001**); the
arrangement approval reference; the publication-event authorisation reference;
generation method and date; and an explicit statement of what the package **is
not** — not approval, not delivery, not receipt, not acceptance.

> **No manifest has been generated**, and none is generated by this increment.

### 4.5 Format versus toolchain

> **PM-3 now selects the candidate output formats. It does not select how the
> files will be produced.**

- **The rendition-generation toolchain remains unselected.**
- **Selecting PDF/A-2b does not establish how the files will be generated.**
- **The later technical route must be capable of producing valid PDF/A-2b.**
- **Conformance must be verified before any publication event** (§7.1).
- **No generation, and no conformance validation, occurs in Increment 8F-A.**

**No PDF/A rendition has been generated, no toolchain has been selected, no
conformance has been tested, and the format has not been approved.**

### 4.6 Unresolved

- **The rendition toolchain is not selected**, and generation is **not
  performed** here.
- **Titleblock and template standards are not established** (§13). Their absence
  affects **layout, styling, front matter and document-control presentation** —
  **it does not leave the candidate file format undefined**, which §4.1 now
  names.
- Whether source companions are included at all remains an **open question for
  review** (§15).
- Whether **PDF/A-2b**, **UTF-8 JSON** and **SHA-256** are the right selections
  is itself a matter **for review, not settled here** (§15).

---

## 5. PM-4 — candidate metadata

| Field | Value |
|---|---|
| **Governing question** | What identity, version and status metadata a published artefact must carry, and how each field is populated and checked |
| **Controlling repository source** | Increment 8A §3; BEP §13.6 (reference status and version control) |
| **Assessed evidence** | **PPER-006** — metadata surface returned, **ASSESSED — INSUFFICIENT** |
| **Limitations** | The Data Management item surface returned only `id`, `tip_version_id`, `versionNumber`; the RVT manifest exposed embedded authoring properties, several being **defaults or placeholders**; **populatability was not established, because testing it would require a write** |

### 5.1 Candidate position

> **Candidate minimum metadata set — a governance requirement, not a platform
> field list.**

| # | Field | In document | In filename | In manifest | In ACC if supported |
|---|---|---|---|---|---|
| 1 | Project identifier | ● | ● | ● | ○ |
| 2 | Package / baseline identifier | ● | ● | ● | ○ |
| 3 | Document title | ● | ● | ● | ○ |
| 4 | Revision / version | ● | ● | ● | ○ |
| 5 | Status | ● | | ● | ○ |
| 6 | Approval-decision reference (**AD-001**) | ● | | ● | ○ |
| 7 | Publication-arrangement reference | ● | | ● | ○ |
| 8 | Publication-event-authorisation reference | ● | | ● | ○ |
| 9 | Publication date | ● | | ● | ○ |
| 10 | Publisher / executing **function** | ● | | ● | ○ |
| 11 | Source repository commit | ● | | ● | ○ |
| 12 | Supersedes / replaces reference | ● | | ● | ○ |
| 13 | Recipient / exchange reference, where applicable | | | ● | ○ |
| 14 | Digest / manifest reference — **`SHA-256`** | | | ● | ○ |

● = candidate requirement  ○ = **only if the platform supports it** — see §5.3

**The manifest carrying these fields is `UTF-8 JSON`** (§4.4), and field 14's
digest algorithm is **`SHA-256`** (§4.1.3).

### 5.2 Why the document carries most of it

**Metadata that lives only in the platform is lost the moment the file leaves
it.** A published artefact should state its own identity, status and provenance,
so that a copy remains self-describing. Platform fields are **additional**, never
the primary record.

### 5.3 Populatability is unconfirmed

> **PPER-006 could not establish that any ACC field accepts a value.**
> Determining that requires a write, which ROA-001 §3 prohibited and which no
> current authorisation permits.

Every **○** above is therefore **conditional**, and confirming them is an
approval-readiness question (§15).

### 5.4 Unresolved

- **No naming standard exists** (§13), so filename composition (fields 1–4)
  **remains provisional** — naming the file *formats* does not name the files.
- Field 12 depends on the supersession route (§8).
- Fields 7, 8 and 13 cannot be populated until the corresponding decisions and
  events exist — **and they do not**.

---

## 6. PM-5 — candidate upload procedure

| Field | Value |
|---|---|
| **Governing question** | The controlled sequence by which an authorised publication is executed, with pre-conditions and stop conditions |
| **Controlling repository source** | BEP §13.5, §6.10 — **manual controlled publication is the approved initial model; no publication automation is approved**; README §2.1 — Desktop Connector / ACCDocs tree out of bounds |
| **Assessed evidence** | **PPER-007** — exposed connector operation surface, **ASSESSED — INSUFFICIENT** |
| **Limitations** | 41 operations exposed, 40 non-mutating; the **only** exposed state-changing operation concerned **Forma proposal creation**. **No ACC document-upload route was exposed.** The exposed surface may be narrower than the platform's capability |

### 6.1 Candidate position — a nine-stage separated sequence

> **Candidate: a manual, controlled, human-performed procedure, drafted at
> planning level only.**

| Stage | Event | What must be true first | Status |
|---|---|---|---|
| 1 | **Arrangement approval** (PE-2) | A reviewed candidate exists | **Not reached** |
| 2 | **Publication-event authorisation** (PE-3) | Arrangement approved; a **publication / exchange authority exists** | **Not reached — authority UNRESOLVED** |
| 3 | **Pre-upload package preparation** | Stages 1–2 complete; commit identified; renditions generated; manifest written | **Not reached** |
| 4 | **Identity and metadata verification** — source side | Package matches the authorised content and carries §5 metadata | **Not reached** |
| 5 | **Technical upload execution** (PE-4) | Stages 1–4 complete; an implementation route **confirmed and authorised** | **Not reached — route unconfirmed (§6.2)** |
| 6 | **Post-upload verification** (PE-5) | Upload executed | **Not reached** — see §7 |
| 7 | **Evidence recording** | Verification performed | **Not reached** |
| 8 | **Delivery, if later authorised** (PE-6) | A delivery requirement and recipient exist | **Not reached — neither exists** |
| 9 | **Receipt and acceptance, if applicable** (PE-7, PE-8) | Delivery executed; **recipient acceptance authority exists** | **Not reached — authority UNRESOLVED** |

> **This is not an approved or executable procedure.** It is a proposed shape.
> **No stage may be performed**, and reaching one stage never entitles anyone to
> the next.

### 6.2 The implementation route is not proposed

> **The Increment 8D connector exposed no ACC document-upload route.**

Accordingly:

- **the observed connector is not nominated as the upload mechanism**;
- **no mechanism is nominated at all**;
- **the implementation route remains subject to later technical confirmation and
  separate authorisation**;
- the absence of an exposed upload operation is a **technical limitation of the
  inspected surface — not a governed prohibition, and not evidence that ACC
  lacks the capability** (PPER-007).

**Manual controlled publication remains the only model contemplated** (BEP
§13.5). **No automation, symlink, bind-mount or live-sync model is proposed**,
and the Desktop Connector / ACCDocs tree remains **out of bounds** (README §2.1).

### 6.3 Stop conditions — candidate

Stop and report, rather than proceed, if: the authorised content and the prepared
package differ; required metadata cannot be carried; the destination does not
exist or differs from the authorised one; the route would require a workaround,
elevated access or an unapproved mechanism; or **any stage would be performed
without its own authorisation**.

---

## 7. PM-6 — candidate post-upload verification

| Field | Value |
|---|---|
| **Governing question** | How it is confirmed that the published result is the authorised content, correctly identified — and what happens when it is not |
| **Controlling repository source** | BEP 12.9 (verification after change), 9.11 (evidence and traceability) |
| **Assessed evidence** | **PPER-008** — sampled version and approval attributes, **ASSESSED — INSUFFICIENT** |
| **Limitations** | **Creation timestamp, file size and checksum / hash were not returned** by the inspected routes. Approval-status values were returned but establish nothing about approval |

### 7.1 Candidate checklist

| # | Check | Candidate method | Known limitation |
|---|---|---|---|
| 1 | **Source-package verification, before upload** | **Five checks (§7.1.1)** — presence of all seven authoritative files; PDF/A-2b validation of each; manifest JSON parse; complete source-to-rendition mappings; SHA-256 recomputation and match | Fully within repository control, **but the validation toolchain is unselected** (§4.5) |
| 2 | **Destination identity** | Confirm the destination is the **authorised** container, by identifier not by name | Depends on PM-1 and on a recorded authorisation |
| 3 | **Destination version** | Confirm the expected version number exists for each item | Version number **was** returned — this check is feasible |
| 4 | **Visible metadata** | Confirm §5 fields visible in the destination match the manifest | **Only for fields the platform proves able to carry** (§5.3) |
| 5 | **Derivative / viewability**, where relevant | Confirm the item opens or renders | A derivative's existence is **not** approval of it (PPER-005) |
| 6 | **Approval / reference checks** | Confirm the package cites AD-001, the arrangement approval and the event authorisation | Not a check that approval occurred elsewhere |
| 7 | **Evidence capture** | Record what was checked, by which function, when, and the result | Evidence is **not** decision, implementation or verification unless the event and authority are separately recorded |

#### 7.1.1 Source-package verification — candidate checks

Performed **before upload**, entirely within repository control:

| # | Check |
|---|---|
| 1 | **All seven authoritative files are present** |
| 2 | **Each file validates as `PDF/A-2b`** |
| 3 | **The `UTF-8 JSON` manifest parses correctly** |
| 4 | **The source-to-rendition mappings are complete** — each rendition maps to exactly one source document, and every source document has a rendition |
| 5 | **`SHA-256` digests recompute and match the manifest** — for every authoritative rendition and every included source companion |

> **These are candidate checks. None has been performed**, and **the exact
> validation toolchain remains unselected** (§4.5).

**The destination-side limitations in §7.1 and §7.2 are unchanged.** These five
checks verify the **source package**, and establish nothing about the
destination.

### 7.2 Integrity where the platform does not expose it

> **Because checksum, size and timestamp were not returned (PPER-008), integrity
> cannot be verified from the destination through the inspected routes.**

**Candidate alternative control:** carry per-file digests **in the package
manifest**, computed at source, so that integrity is verifiable by recomputation
from a retrieved copy rather than by querying platform metadata.

**This control is proposed, not executed, and its feasibility depends on a
retrieval route that has not been confirmed** (§15).

### 7.3 What must not be treated as verification

> **An `IN_REVIEW` field is not proof that approval occurred.** Increment 8D
> observed two records with `approval_value: IN_REVIEW` against the pre-existing
> drawing PDF; that is a **field value**, not an approval event, and not a
> verification (§10).

**An empty approval result is not evidence that no relationship exists** — only
that none was returned.

### 7.4 Unresolved

The verification **method** remains undefined until PM-1, PM-3, PM-4 and PM-5
are decided, and its **authority** — who performs and who accepts the
verification — is not assigned here.

---

## 8. PM-7 — candidate supersession and withdrawal route

| Field | Value |
|---|---|
| **Governing question** | How published information is superseded or withdrawn, by whom, with what record, and with what retention |
| **Controlling repository source** | BEP 7.10, 9.9, 12.10 — **superseded material is retained, not deleted**; CDE Workflow & State Strategy §3.1 (T8) |
| **Assessed evidence** | **PPER-009** — non-observability of successive-version relationships, **ASSESSED — INSUFFICIENT** |
| **Limitations** | **PPQ-006 was NOT OBSERVABLE WITHIN THE BOUNDED SESSION** — no eligible multi-version item was visible. No supersession, withdrawal, archive or removal operation appeared in the inspected surface |

### 8.1 Candidate route

| Element | Candidate position |
|---|---|
| **Supersession trigger** | A **materially changed baseline** — AD-001 §13 contemplates 0.2, 0.3 … 1.0 rather than in-place editing of an approved one |
| **Authority required** | The **publication / exchange authority** — **UNRESOLVED**. Supersession is a publication act, not an editorial one |
| **New event authorisation** | **A fresh PE-3 authorisation.** A superseding publication is a **new publication event**, never an extension of the earlier one |
| **Relationship to predecessor** | Explicit and recorded **both ways**: the new package cites what it supersedes (metadata field 12); the record of the earlier package cites what superseded it |
| **Status marking** | The superseded package is marked **superseded**, with a date and the superseding identifier |
| **Retention** | **Historical evidence is retained.** Superseded exchanges remain traceable (BEP 7.10, 9.9, 12.10) |
| **Withdrawal circumstances** | Where published information is found unfit for its stated purpose and **no superseding package is issued** — a distinct outcome from supersession |
| **Silent deletion or replacement** | **Prohibited.** No overwrite in place, no deletion, no quiet re-upload under the same identity |
| **Repository record** | The decision and its evidence recorded through a controlled increment |
| **CDE record** | Status marking and, where the platform allows, a visible relationship — **subject to §8.2** |
| **Recipient notification** | Where a delivery has occurred and a recipient exists — **neither applies today** |

### 8.2 The technical route is not proposed

> **PPQ-006 was not observable within the bounded session**, so **no
> successive-version behaviour has been observed at all** in this project.

**The connector exposed no supersession, withdrawal, archive or removal
operation. That is not a governed prohibition**, and it is **not evidence that
Autodesk lacks versioning or supersession capability** (PPER-009).

> **No technical route has been approved, and none is proposed here.**

### 8.3 Unresolved

The route's **authority** is unresolved; its **technical feasibility** is
unconfirmed; and PM-7 **depends on PM-1, PM-2 and PM-4**.

---

## 9. Candidate decision table

| PM | Selected candidate position | Principal rationale | Evidence | Unresolved dependency | Approval / authority required | Status |
|---|---|---|---|---|---|---|
| **PM-1** | Dedicated new child container under `03. Published`, provisionally identified, cross-referenced from the Common Files BEP area | Information state before topic; separation from design deliverables; no reliance on existing content | PPER-004 | **OF-001** intended CDE structure undefined; naming standard absent | Arrangement approval; **implementation authority** to create it | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **PM-2** | Propose a *Training Baseline Publication Owner* **function**; no holder | Authority comes from decision, never from observation or access | **None possible** | Publication / exchange authority **UNRESOLVED** | **A separate authority decision** | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **PM-3** | **Seven `PDF/A-2b` renditions + optional `UTF-8 Markdown` source companions + one authoritative `UTF-8 JSON` manifest + `SHA-256` digests** | A fixed archival record; each controlled resource declares its own status; individually addressable items enable supersession | PPER-005 | **Generation toolchain unselected**; titleblock / template standards absent | Arrangement approval | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **PM-4** | 14-field minimum set, carried primarily **in the document and manifest** | Platform-only metadata is lost when the file leaves the platform | PPER-006 | **Populatability unconfirmed**; naming standard absent | Arrangement approval | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **PM-5** | Nine-stage separated manual procedure; **no mechanism nominated** | Manual controlled publication is the only model contemplated; **no upload route was exposed** | PPER-007 | Implementation route unconfirmed; PM-1 … PM-4 | Arrangement approval; **PE-3 authorisation**; implementation authority | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **PM-6** | Seven-check verification, with source-side **PDF/A-2b validation, JSON manifest parse and `SHA-256` recomputation** as the integrity control | Destination exposed no checksum, size or timestamp | PPER-008 | **Validation toolchain unselected**; retrieval route unconfirmed; PM-1, PM-3, PM-4, PM-5 | Arrangement approval | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |
| **PM-7** | Governance route with retention and a fresh event authorisation; **no technical route** | Supersession is a publication act; history is retained, never deleted | PPER-009 | **PPQ-006 not observable**; technical feasibility unconfirmed; PM-1, PM-2, PM-4 | Publication / exchange authority; fresh **PE-3** | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED** |

---

## 10. Pre-existing live-state treatment

Increment 8D observed conditions that already exist in the project. They are
recorded as **pre-existing observed conditions** and are **not** part of this
candidate.

### 10.1 The existing drawing PDF

One drawing-set PDF was observed in `03. Published / Drawings - PDF`, with **two
approval records, both `IN_REVIEW`**.

**This candidate does not:**

- **retrospectively authorise** that PDF or anything else already in the project;
- **declare it the Training Baseline publication package** — it is unrelated
  design information;
- **infer approval from `IN_REVIEW`** — that is a field value, not an approval
  event;
- **use it as a publication precedent** — **that information sitting in a
  `Published`-named folder establishes no governed publication authority and no
  approved route** (Increment 7C §6A, §9);
- **overwrite, replace, supersede, move or depend on it** in any way.

### 10.2 Naming irregularities

Observed and recorded verbatim: `07.  Reference Infomation` (double space and
spelling as displayed), `2. Structural Consultanrt`, and `3. MEP consultant`
against `2. Structural Consultant` in the same parent.

**These are recorded as observed.** This candidate **does not silently rename or
correct any live folder**, and **does not classify them as non-conformances** —
**no naming standard is established**, so there is nothing for the configuration
to fail against (BEP 12.2, 12.6).

### 10.3 How a later governed publication would be distinguished

| Distinguishing feature | Pre-existing live state | A later governed publication |
|---|---|---|
| **Arrangement** | None recorded | An **approved** arrangement, cited by identifier |
| **Event authorisation** | None recorded | A recorded **PE-3** authorisation, cited by identifier |
| **Authority** | Not established | An identified **function** exercising a recorded authority |
| **Container** | Design-deliverable folder | The **authorised** container (§2), separate from design deliverables |
| **Metadata** | Not governed | The §5 set, carried in document and manifest |
| **Integrity** | No digest available | Per-file digests in the manifest |
| **Verification** | None recorded | The §7 checklist, performed and evidenced |
| **Status** | `IN_REVIEW` field value | A recorded governed status with its decision reference |

> **A governed publication is recognisable by its record, not by its location.**
> Being in a folder named `Published` is not the distinguishing feature — the
> chain of arrangement, authorisation, execution, verification and evidence is.

---

## 11. Authority and event separation

Carried unchanged from the Increment 8A framework §2.1.

| Ref | Event | Current position |
|---|---|---|
| **PE-1** | Planning a publication arrangement | **Candidate prepared — this document** |
| **PE-2** | Approving the arrangement | **Not reached** |
| **PE-3** | Authorising a publication event | **Not reached** |
| **PE-4** | Executing the publication | **Not reached** |
| **PE-5** | Verifying the published result | **Not reached** |
| **PE-6** | Delivering | **Not reached** |
| **PE-7** | Receiving | **Not reached** |
| **PE-8** | Accepting | **Not reached** |
| **PE-S** | Superseding or withdrawing | **Not reached** |

> **No later event follows automatically from candidate preparation.** Preparing
> a candidate is PE-1 and nothing more. **PE-2 requires a decision; PE-3 requires
> an authority that does not exist.**

---

## 12. Authority position — unchanged

| Authority | Status |
|---|---|
| Project publication / exchange authority | **UNRESOLVED** |
| Recipient acceptance authority | **UNRESOLVED** |
| Implementation authority for creating a container | **Not established** |
| Holder nominated by this candidate | **None — for any function** |

**This candidate assigns no authority.** Proposing a function is not creating
one, and naming a role is not filling it.

---

## 13. Standards dependencies

| Standard | Status | What is provisional because it is absent |
|---|---|---|
| **Naming** | **Not established** | The container name (§2.5); filename composition (§5.4); package and rendition file naming |
| **Coordinates** | **Not established** | No direct effect on this document package. Recorded so the gap stays visible, and it would bear on any later model publication |
| **Titleblocks** | **Not established** | Rendition layout, title block and document-control block (§4.5) |
| **Templates / Authoring Resources** | **Not established** | Rendition styling and any standard front matter (§4.5) |

> **This candidate establishes none of these standards**, and must not be read as
> doing so. Where a candidate detail depends on one, it is marked
> **provisional**.

---

## 14. Alternatives considered and not selected

| Matter | Alternative | Why not selected as the current candidate |
|---|---|---|
| **PM-1** | `0. Common Files / 02. BEP (BIM Execution Plan)` | Topically apt and already present, but **Common Files' relationship to the Published / Authorised information state is undefined**, so an authorised baseline placed there would have an **ambiguous information state**. **A strong alternative** — see §15 |
| **PM-1** | Existing `03. Published / Drawings - PDF` | A design-deliverable folder holding unrelated information under review. Using it would **borrow a precedent that does not exist** and risk association with the `IN_REVIEW` records |
| **PM-3** | One merged PDF of all seven documents | Would produce a single artefact carrying **seven conflicting status declarations**, and would defeat per-document supersession |
| **PM-3** | A ZIP archive as the published item | One opaque CDE item; contents not individually addressable, referenceable or supersedable |
| **PM-3** | Publishing Markdown sources as the authoritative form | Maximum traceability, but **weaker as a fixed human-readable record**. Retained as an **optional companion** instead |
| **PM-4** | Rely on ACC platform fields as the primary metadata record | **Populatability is unconfirmed**, and platform-only metadata **does not travel with the file** |
| **PM-5** | Nominate the observed connector as the upload mechanism | **No ACC document-upload route was exposed.** Nominating it would assert a capability not evidenced |
| **PM-7** | Rely on a platform supersession feature | **None was exposed** in the inspected surface |

> **No alternative is characterised as prohibited merely because the connector
> did not expose it.** Non-exposure is a limitation of the inspected surface, not
> a governed prohibition.

**Nor is any format prohibited.** The merged-PDF row above rejects **merging**,
not PDF; **ordinary PDF, and other formats, remain available options for review**
(§15). PDF/A-2b is a **candidate selection**, not an exclusion of alternatives.

---

## 15. Approval-readiness questions for Increment 8G

The following must be reviewed before this candidate could be approved. **This
list is not a request for approval.**

| # | Question |
|---|---|
| 1 | **Internal coherence** — are the PM-1 … PM-7 positions mutually consistent, and are the stated dependencies complete and correct? |
| 2 | **Package completeness** — is §1 the right boundary? Should the source companions be included at all, and is excluding the companion documents and evidence records correct? |
| 3 | **Authority separation** — are the four functions in §3.2 correctly distinguished, and does proposing a publication-owner function pre-empt the unresolved publication / exchange authority decision? |
| 4 | **PM-1 location** — is Option C (a new dedicated container) right, or does Option A (`0. Common Files / 02. BEP`) better fit, given that **OF-001 leaves the intended CDE structure undefined**? Can PM-1 be decided at all before that? |
| 5 | **Technical feasibility** — no upload route was exposed. What confirmation is needed, and under what authority, before PM-5 can name a mechanism? |
| 6 | **Metadata sufficiency** — are the 14 fields sufficient and not excessive, and how should the **unconfirmed populatability** of the ACC-side fields be resolved? |
| 7 | **Verification sufficiency** — is the source-side digest control adequate given the destination exposes no integrity data, and is a retrieval route available to recompute it? |
| 8 | **Pre-existing live state** — is §10's separation adequate, and does anything more need recording about the `IN_REVIEW` PDF sitting in a `Published`-named folder while publication remains unauthorised? |
| 9 | **Standards dependencies** — can an arrangement be approved while naming, titleblock and template standards remain unestablished, or must some be established first? |
| 10 | **Supersession and withdrawal** — is a governance-only route approvable while no technical route is confirmed? |
| 11 | **Progression** — can this candidate proceed to an **arrangement-approval decision (PE-2)**, or must it be revised, deferred, or split? |
| 12 | **Rendition format** — is **`PDF/A-2b`** the appropriate authoritative rendition format for this package, or would ordinary PDF, another PDF/A conformance level, or a different format serve better? |
| 13 | **Generation and validation feasibility** — is a **conforming PDF/A-2b generation and validation route technically feasible** from the Markdown sources, and what would confirming it require? |
| 14 | **Manifest and integrity sufficiency** — are **`UTF-8 JSON`** and **`SHA-256`** sufficient for the manifest and integrity controls, and are the seven required per-file entries (§4.4) the right minimum? |

---

## 16. Candidate statement

> ## **PUBLICATION ARRANGEMENT CANDIDATE 0.1 — PAC-001**
>
> **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED.**
>
> This candidate proposes an arrangement for review. It **approves nothing**,
> **authorises nothing**, **assigns no authority**, **implements nothing**, and
> **resolves no PM matter**. **GCR-005 remains OPEN.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** Framework — `docs/Publication-Planning-Control-Framework.md`.
Register — `docs/Publication-Planning-Evidence-and-Observation-Control-Register.md`.
Observation — `docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`.
Authorisation — `docs/Publication-Planning-Read-Only-Observation-Authorisation.md`.
Approval relied upon — `docs/Training-Baseline-0.1-Approval-Decision.md`.
