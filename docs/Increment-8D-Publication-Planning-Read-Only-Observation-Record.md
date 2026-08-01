# Increment 8D — Publication Planning Read-Only Observation Record

| Field | Value |
|---|---|
| Document status | **CONTROLLED LIVE-SYSTEM OBSERVATION RECORD** |
| Authority | **ROA-001** — [`docs/Publication-Planning-Read-Only-Observation-Authorisation.md`](Publication-Planning-Read-Only-Observation-Authorisation.md) |
| Observation date | **2026-08-01** |
| Increment observed | 8D — the single observation session authorised by ROA-001 |
| Increment recording | 8E — Record and Assess Read-Only Observation Evidence |
| Evidence class | **EC-3** — live-system observational evidence only |
| Approval | **Not approved** — this record decides nothing |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**This record carries no governance authority.** It records what was observed
during one authorised read-only session. It creates no rule, resolves no matter,
assigns no authority, and approves nothing.

---

## 1. Authorisation and its expiry

| Statement | Position |
|---|---|
| **ROA-001 was exercised once** | Yes — one session |
| Session identity | **The one session authorised by ROA-001**; no other session was run |
| **Authorisation expired** | **Yes — automatically, when the completion report was produced** (ROA-001 §5) |
| **Repeat observation** | **Not authorised.** ROA-001 does not renew; any further observation requires a **new** authorisation record with its own identifier |
| Mutation | **None reported** — see §11 |

The session reported reaching **stop condition 7** of the observation brief —
*"You have completed step 10 of the execution order — the authorisation expires
there"* — and confirmed that nothing further was run under ROA-001.

## 2. What this record is, and is not

| | |
|---|---|
| **It contains EC-3 observational evidence only** | What was visibly present or absent, and what the tooling returned or refused |
| **Observation is not a governance decision** | The session proposed statuses; it set none, and it took no decision |
| **No PM matter is resolved** | PM-1 to PM-7 remain **UNRESOLVED** |
| **No authority is assigned** | Publication / exchange and recipient acceptance authority remain **UNRESOLVED** |
| **No publication arrangement is selected** | None is prepared, chosen, preferred or recommended |
| **Publication remains NOT AUTHORISED** | The publication hold remains **ACTIVE** |

## 3. Project, hub and account boundary

| Entity | Identifier as returned |
|---|---|
| Hub | `b.9a766a0e-cd65-4c62-90db-e196e33d3a36` — **"CogStack "** (trailing space as returned), region **EMEA** |
| Project | `b.cf156e09-a2bf-4335-a0c8-5f03bfe873db` — **"Harrismith Fire Station"**, type ACC |
| Root folder | `urn:adsk.wipemea:fs.folder:co.vVzl0nfeQ-uv1u2wxU44YQ` |

**Connector and account boundary.** Observation was performed through the
read-only Autodesk connector surface available to the session's account. Three
other projects were visible in the hub; **the session recorded acting on none of
them**. Visibility is bounded by what that account could see at that moment.

## 4. Exact read-only operations invoked

In the order reported:

| Operation | Calls |
|---|---|
| `list_autodesk_hubs` | 1 |
| `list_projects` | 1 |
| `list_top_folders` | 1 |
| `list_folder_contents` | **9** |
| `list_item_versions` | 2 |
| `get_item_details` | 2 |
| `get_derivative_manifest` | 2 |
| `get_file_version_approval_statuses` | 2 |

**Disclosure carried from the source report.** Of the nine `list_folder_contents`
calls, **four served the PPQ-001 depth-3 enumeration**; the remaining five — the
two empty published-model folders, `Drawings - PDF`, `01. WIP (Work in
Progress) / 1. Architecture`, and `Consumed` — **served sample establishment**
under the brief §3 and are disclosed as such rather than folded into the PPQ-001
answer.

### 4.1 No state-changing operation was invoked

The session reported that **no state-changing operation was invoked, tested or
prepared**; that `create_forma_proposal` was never called and `confirm_write`
was never set; and that `prepare_native_floor_stack_preview` was not invoked.

**Loading a tool definition is not invoking it** — the session recorded loading
the full connector surface in order to classify it for PPQ-004 without calling
anything.

## 5. Controlled sample

**Two items — within the maximum of three.**

| # | Item | Identifiers as returned |
|---|---|---|
| 1 | `HFS-A-DR-A101-A102-Building-Overview-Set.pdf` | lineage `urn:adsk.wipemea:dm.lineage:-LrYWJzxTaWT406lCVkmkA`; tip `urn:adsk.wipemea:fs.file:vf.-LrYWJzxTaWT406lCVkmkA?version=1` |
| 2 | `harrismith_firestation.rvt` | lineage `urn:adsk.wipemea:dm.lineage:onmjknk6Qmq1hPEFVkdzqw`; tip `urn:adsk.wipemea:fs.file:vf.onmjknk6Qmq1hPEFVkdzqw?version=1` |

### 5.1 Neutral sample rationale

| Rule | How it was satisfied |
|---|---|
| 1 | Item 1 is the existing drawing-set PDF in `03. Published / Drawings - PDF`, **still visible and identifiable** |
| 2 | Item 2 added **once**, to observe a materially different declared file type (`.rvt` against `.pdf`) and a different metadata surface |
| 3 | **Not satisfied — no eligible multi-version item was visible.** See §6, PPQ-006 |
| 4 | One item was preferred over adding more |
| 5 | Both identifiers were **recorded before detailed inspection** |
| 7 | The sample was **not expanded** to chase completeness |
| 8 | **No version was created.** PPQ-006 recorded as not observable |

> **The sample is an observation-control mechanism, not a publication
> selection.** No item is approved, governed, suitable, preferred or recommended
> by having been selected.

## 6. Factual answers

### 6.1 PPQ-001 — visible areas and folders to depth 3

**Names are recorded exactly as displayed.** Apparent spelling and spacing
irregularities are part of the evidence and are **not corrected here**.

| Level | Name as displayed | URN |
|---|---|---|
| 1 | `Project Files` | `co.QM_hV2RGTX6yJ_iLGo5iqw` (objectCount 6, isRoot) |
| 2 | `0. Common Files` | `co._uscktCiS4i8I-PAgyh7gw` |
| 2 | `01. WIP (Work in Progress)` | `co.i7LjQs5tSKuw9YK6JsA-5A` |
| 2 | `02. Shared` | `co.vtFTY_c4SZGjUokM2KrG6Q` |
| 2 | `03. Published` | `co.k_AsWerCQ7G3Fet1CkmuhA` |

| Level 3, under | Folders as displayed |
|---|---|
| `0. Common Files` | `01. Project Docs` · `02. BEP (BIM Execution Plan)` · `03. Naming Standards` · `04. Coordinates` · `05. Titleblocks` · `06. Templates` · **`07.  Reference Infomation`** — 7 folders |
| `01. WIP (Work in Progress)` | `1. Architecture` · **`2. Structural Consultanrt`** · `3. MEP Consultant` · `4. Contractors` — 4 folders |
| `02. Shared` | `0. Coordination` · `1. Architecture` · `2. Structural Consultant` · **`3. MEP consultant`** · `4. Contractor - Mechanical` · `5. Contractor - Electrical` · `6. Contractor - Plumbing & Hydraulic` — 7 folders |
| `03. Published` | `Construction Documents - PDF` · `Drawings - PDF` · `Models - IFC` · `Models - RVT` · `Specifications` — 5 folders |

**Recorded verbatim, deliberately:** `07.  Reference Infomation` (double space
and spelling as displayed); `2. Structural Consultanrt`; and the lower-case
`consultant` in `3. MEP consultant` against `2. Structural Consultant` in the
same folder.

> **These are recorded as observed, not corrected and not characterised as
> approved or governed naming.** The project naming standard remains **Not
> established**. Recording an inconsistency is not raising a non-conformance —
> there is no approved naming standard for the configuration to fail against.

**Standing inference limit.** An area named after an information state —
`01. WIP (Work in Progress)`, `02. Shared`, `03. Published` — is **evidence of
naming only**. None of this structure is thereby the governed publication
location, and none is selected, preferred or recommended by being listed.

### 6.2 PPQ-002 — declared formats and existing derivatives

| Item | Extension | Source type | Derivative outputs, from the **existing** manifest |
|---|---|---|---|
| 1 (PDF) | `.pdf` | PDF | `outputType: svf`, `status: success`; two 2D viewables — `A101 - Building Overview`, `A102 - 3D Building Overview`; resources in `application/autodesk-f2d`, `image/png`, `leaflet/png`, `application/zip`, **`application/octec-stream`** (MIME string spelled as returned) |
| 2 (RVT) | `.rvt` | Revit, `RVTVersion: 2027` | `outputType: svf`, `overrideOutputType: svf2`, `status: success`; two 3D viewables — `{3D}`, `New Construction` (`isMasterView: true`); `application/autodesk-svf` graphics, `application/autodesk-db` property database, `Autodesk.AEC.ModelData` JSON, `image/png` thumbnails |

**No translation was triggered.** Both manifests were pre-existing and were read,
not created. No file content was downloaded, exported or retrieved.

### 6.3 PPQ-003 — metadata surface returned

**Item-version inspection returned a minimal set:**

| Source | Field | Item 1 | Item 2 |
|---|---|---|---|
| `get_item_details` | `id` | `…dm.lineage:-LrYWJzxTaWT406lCVkmkA` | `…dm.lineage:onmjknk6Qmq1hPEFVkdzqw` |
| `get_item_details` | `tip_version_id` | `…vf.-LrYWJzxTaWT406lCVkmkA?version=1` | `…vf.onmjknk6Qmq1hPEFVkdzqw?version=1` |
| `list_item_versions` | `versionNumber` | 1 | 1 |

**Item 2's derivative manifest additionally exposed an embedded authoring-property
block**, values as returned:

| Property | Value as returned |
|---|---|
| `RVTVersion` | `2027` |
| `Project Name` | `"Project Name"` |
| `Project Number` | `"Project Number"` |
| `Author` | `""` (empty) |
| `Project Address` | `"Enter address here"` |
| `Project Issue Date` | `"Issue Date"` |
| `Project Status` | `"Project Status"` |
| `Building Name` | `""` (empty) |
| `Client Name` | `"Owner"` |
| `Organization Name` | `""` (empty) |
| `Organization Description` | `""` (empty) |
| `documentId` | `7be09f8c-…` |
| `instanceId` | `53d21070-…` |
| `revitNumberOfSaves` | `14` |

**Several of these are Revit default or placeholder strings**, recorded as
returned. **Item 1's manifest carried no such property block.**

### 6.4 PPQ-004 — exposed operation surface

**41 operations exposed — 40 non-mutating, 1 state-changing.**

| API area | Read-only operations reported |
|---|---|
| Data Management | `list_autodesk_hubs`, `list_projects`, `list_top_folders`, `list_folder_contents`, `get_item_details`, `list_item_versions` |
| Model Derivative | `get_derivative_manifest`, `list_model_views`, `get_model_properties` |
| Model Coordination | `list_model_sets`, `get_model_set`, `list_model_set_versions`, `get_model_set_version`, `get_latest_model_set_version` |
| Issues | `list_issues`, `get_issue_details`, `list_issue_types`, `list_issue_relationships` |
| RFIs | `search_rfis`, `get_rfi`, `get_rfi_user_context` |
| Submittals | `list_submittals`, `get_submittal`, `get_submittal_user_context` |
| Reviews / Approvals | `list_reviews`, `get_review_details`, `get_review_workflow`, `get_review_progress`, `list_review_workflows`, `list_review_file_versions`, `get_file_version_approval_statuses` |
| Transmittals | `list_transmittals`, `get_transmittal`, `get_transmittal_documents`, `get_transmittal_folders`, `get_transmittal_recipients` |
| Forma | `get_forma_project`, `list_forma_proposals`, `list_forma_proposal_elements` |

`prepare_native_floor_stack_preview` is exposed but documented as making no
Autodesk / APS HTTP request and no Forma SDK call, and as always emitting
`mode='preview'` with `confirmWrite=false`, never able to emit an execute
package. Recorded as **local and non-mutating**. **Not invoked.**

**The single state-changing operation is `create_forma_proposal`** — a guarded
write concerning **Forma proposal creation**. Documented constraints as reported:
it performs no write unless `confirm_write` is exactly `true`, otherwise
returning a structured preview; a confirmed write requires an explicit valid
`source_proposal_urn`; it rejects invalid input and duplicate names; and it never
creates buildings, site limits, roads or geometry, and never modifies or deletes
existing proposals.

> **It was not invoked, and `confirm_write` was never set.**

### 6.5 PPQ-005 — version and integrity-related attributes

| Attribute | Item 1 | Item 2 |
|---|---|---|
| Version number | **1** (`count: 1`, `has_more: false`) | **1** (`count: 1`, `has_more: false`) |
| Creation timestamp | **Not returned** | **Not returned** |
| File size | **Not returned** | **Not returned** |
| Checksum / hash | **Not returned** | **Not returned** |
| Approval-status field | **2 records**, both `review_status: OPEN`, `approval_label: "In review"`, `approval_value: IN_REVIEW`; review ids `a01f3229-7db5-4e66-a8a6-9624ed3aa82d`, `df0d6645-3bbf-478b-8dd0-d8b80c18644a` | `results: []`, `count: 0` |

**No upload was performed to create any observation.**

> **`IN_REVIEW` is not evidence that approval occurred.** It is a field value.
> **An empty approval result is not evidence that no relationship exists** — only
> that none was returned by the inspected route.

### 6.6 PPQ-006 — not observable

**Both sampled items have exactly one version**, and no multi-version item was
visible in the locations checked — `03. Published / Models - RVT` (empty),
`03. Published / Models - IFC` (empty), and `Consumed` under
`01. WIP (Work in Progress) / 1. Architecture` (empty).

**Successive-version relationships and version-history retrievability could not
be observed.** Under the brief's rule 8, **no version was created** to make the
question answerable, and the sample was not expanded.

**Incidental connector-surface fact, recorded neutrally.** Across the 41 exposed
operations, none replaces, supersedes, archives, withdraws or removes a document
version or item.

> **Stated narrowly.** This establishes only what was not visible in the checked
> locations and what the inspected surface did not expose. It is **not** evidence
> that no multi-version item exists elsewhere, **not** evidence that Autodesk
> lacks versioning or supersession capability, and **not** a governed
> prohibition.

### 6.7 PPQ-007 — limitations encountered

**No connector error, refusal or "unauthorised" result arose on PPQ-002,
PPQ-004 or PPQ-006.** The version-listing calls underlying PPQ-006 **succeeded**,
returning `count: 1`; the non-observability is an absence of eligible subject
matter, not a tooling failure.

## 7. Exact errors, empty results and access warnings

| Source | Exact return |
|---|---|
| `list_autodesk_hubs` | The `CogStack` hub **plus seven `meta.warnings`**, each `HttpStatusCode: "403"`, `ErrorCode: "BIM360DM_ERROR"`, `Detail: "You don't have permission to access this API"`, for regions **US, AUS, IND, GBR, CAN, DEU, JPN** |
| `Models - RVT` | `counts: {items:0, folders:0, total:0}`, `has_more: false` |
| `Models - IFC` | `counts: {items:0, folders:0, total:0}`, `has_more: false` |
| `Consumed` | `counts: {items:0, folders:0, total:0}`, `has_more: false` |
| `get_file_version_approval_statuses` (Item 2) | `results: []`, `count: 0` |

**The seven 403 warnings are per-region platform-access facts.** They concern
other regions, establish nothing about this project, and — under the standing
rule — **establish nothing about governance authority**.

## 8. Limitations

- `get_item_details` and `list_item_versions` **do not return** creation
  timestamp, file size, or checksum / hash — bearing directly on PPQ-005;
- **no multi-version item was visible** in the checked locations, blocking
  PPQ-006;
- the sample was **two items**, bounded and **not exhaustive** of the project;
- enumeration was to **depth 3** and to **what the session's account could see**;
- the observation is a **single point in time**, 2026-08-01;
- **absence of observation is not observation of absence**, throughout.

## 9. Final PPQ statuses

Proposed by the session; **decided by the orchestrator** and recorded here.

| PPQ | Final status |
|---|---|
| **PPQ-001** | **ANSWERED** |
| **PPQ-002** | **ANSWERED** |
| **PPQ-003** | **ANSWERED** |
| **PPQ-004** | **ANSWERED** |
| **PPQ-005** | **PARTIALLY ANSWERED** |
| **PPQ-006** | **NOT OBSERVABLE WITH AVAILABLE TOOLING** |
| **PPQ-007** | **ANSWERED** |

**The session proposed these statuses; it did not set them** (brief §8).

## 10. Evidence recorded from this observation

Six entries were created in the register from this record:

| Entry | Subject |
|---|---|
| **PPER-004** | Visible folder and area structure |
| **PPER-005** | Sampled formats and existing derivatives |
| **PPER-006** | Metadata surface returned by the authorised routes |
| **PPER-007** | Exposed connector operation surface and technical boundary |
| **PPER-008** | Sampled version and approval-related attributes |
| **PPER-009** | Non-observability of successive-version and supersession relationships |

Each is recorded in
[`docs/Publication-Planning-Evidence-and-Observation-Control-Register.md`](Publication-Planning-Evidence-and-Observation-Control-Register.md)
§9.4, with what it supports and what it does **not** support.

## 11. Confirmation that no mutation occurred

Reported by the session and recorded here:

- **only read-only / non-mutating operations were invoked**;
- `create_forma_proposal` **was never called**; `confirm_write` **was never set**;
- `prepare_native_floor_stack_preview` **was not invoked**;
- **no item, version, folder, area, permission, membership, issue, review,
  transmittal, model set or approval status was created or changed**;
- **no file content was uploaded, downloaded, translated or exported**.

## 12. Explicit non-effects

This record does **not**:

- authorise publication, or lift or vary the publication hold;
- resolve **PM-1** to **PM-7** — all remain **UNRESOLVED**;
- resolve **PM-2**, which remains **GOVERNANCE DECISION REQUIRED** and was
  excluded from the observation entirely;
- select, prepare, prefer or recommend a publication arrangement;
- treat any visible `Published` folder as the governed publication location;
- treat `IN_REVIEW` as evidence that approval occurred;
- treat an unreturned checksum as evidence that integrity data does not exist;
- treat PPQ-006 non-observability as evidence that multi-version information
  does not exist;
- establish publication / exchange or recipient acceptance authority;
- establish any project standard, including naming;
- close **GCR-005** or **GCR-006**;
- resolve **UD-001**;
- renew or reopen **ROA-001**;
- authorise any further observation;
- create a tag, release or publication package.

> **Observation informs; decisions resolve.** Nothing here is a decision.
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**
