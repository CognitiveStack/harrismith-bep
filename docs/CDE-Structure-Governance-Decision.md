# CGD-001 — CDE Structure Governance Decision

| Field | Value |
|---|---|
| Document status | **Controlled Governance Decision** |
| Decision classification | **APPROVED GOVERNANCE** |
| Governance reference | **CGD-001** |
| Decision outcome | **APPROVE WITH CONDITIONS** |
| Structural determination | **AS-FOUND FOUR-AREA ROOT TOPOLOGY ADOPTED AS INTENDED TRAINING CDE GOVERNANCE** |
| Decision status | **OF-001 RESOLVED — IMPLEMENTATION AND VERIFICATION NOT YET PERFORMED** |
| Decision date | **2026-08-01** |
| Deciding function | **Training CDE Governance Approver under AG-002** |
| Functional holder exercising the function | **Training Implementation Owner** |
| Training basis | **TA-02** — simulated role participation |
| Source | **Orchestrator decision — Increment 8G-B** |
| Scope | **Harrismith BIM-management training / reference implementation only** |

> **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

> **This is a simulated training-governance decision under TA-02.** It creates
> **no real project appointment and no professional authority**. It **authorises
> no publication**, **authorises no Autodesk configuration change**, **assigns no
> publication / exchange or recipient acceptance authority**, **does not approve
> PAC-001**, and **does not establish the missing project naming, coordinate,
> titleblock or template standards**.

---

## 1. Decision identification

### 1.1 Arising from

| Source | Contribution |
|---|---|
| **OF-001** | The observed fact recording the as-found CDE root areas, with intended state **"Not defined"** and a decision required on whether the as-found structure is **adopted, amended or replaced** |
| **AG-002** | Established the **Training CDE Governance Approver** — the function exercised here |
| **PRA-B01** | The sole principal blocker preventing PAC-001 from reaching PE-2, being the unresolved OF-001 / PM-1 dependency |
| **PRA-001** | The readiness assessment recording that blocker |
| **PAC-001 PM-1** | The candidate publication-location position dependent on this decision |
| **Increment 8G-R scope review** | Established that OF-001 must be decided as a full CDE-structure matter, and that a PM-1-only determination would not close it |

### 1.2 Function exercised

**The Training CDE Governance Approver is exercised here**, under **AG-002 §3**,
by the **Training Implementation Owner** as functional holder. **No personal
holder is recorded.**

**This decision states which function is being exercised**, as AG-001 §9 and
AG-002 §5.1 require where one holder performs more than one training function
(BEP 5.11, 9.12).

## 2. Decision

> ## **APPROVE WITH CONDITIONS**
>
> **The as-found four-area root topology is ADOPTED as the intended training CDE
> topology.**

| # | Adopted root area |
|---|---|
| 1 | **`0. Common Files`** |
| 2 | **`01. WIP (Work in Progress)`** |
| 3 | **`02. Shared`** |
| 4 | **`03. Published`** |

### 2.1 What this decision adopts

- the **four-area functional topology**;
- the **intended relationship between those areas and the CDE information
  states** (§3);
- the role of **`0. Common Files`** as a **controlled reference /
  governance-support area** (§3.1).

### 2.2 What this decision does not adopt

> **The decision adopts the functional root topology and its intended governance
> mapping. It does not approve every existing child folder, item, spelling or
> current operational practice.**

Not adopted:

- **every child folder**;
- **every observed discipline mapping**;
- **every existing filename**;
- **every spelling or capitalisation**;
- **every existing item or version**;
- **every current operational practice**.

## 3. Intended governance mapping

### 3.1 `0. Common Files`

**Intended role:**

- **controlled project-wide reference and governance-support information**;
- **may contain approved or controlled resources whose individual status is
  declared through their own documents and records** (README §7; BEP §13.6);
- **is not itself one of the WIP, Shared, Published / Authorised or Record /
  Retained information states**;
- **placement there does not grant general reliance, approval or authority.**

> **`0. Common Files` is an area, not a state.** Nothing becomes approved,
> controlled or relied upon by being placed in it.

### 3.2 `01. WIP (Work in Progress)`

**Intended mapping:**

- **corresponds to the WIP information state** (BEP 6.3; CDE Workflow & State
  Strategy §1);
- information remains **under originator or task-team control**;
- information is **not authorised for general project reliance**;
- **progression from WIP requires the governed transition applicable to the
  intended next state** (CDE Workflow & State Strategy §3, T1).

### 3.3 `02. Shared`

**Intended mapping:**

- **corresponds to the Shared information state**;
- information is **made available beyond its originating task team for an
  identified purpose**;
- **required checking and authorisation must occur before the information is
  treated as Shared**;
- **placement alone does not evidence that checking or authorisation
  occurred.**

### 3.4 `03. Published`

**Intended mapping:**

- **corresponds to Published / Authorised information**;
- information **must be authorised for a defined delivery or use purpose**;
- **placement alone does not publish, approve, authorise, deliver, issue or
  accept information**;
- **a governed publication requires its arrangement, event authorisation,
  execution, verification and evidence** (Increment 8A framework §2.1,
  PE-2 … PE-5).

> **Putting a file in `03. Published` does not publish it.** Publication is a
> chain of governed events, not a location.

### 3.5 Record / Retained

**Intended position:**

- **Record / Retained remains a conceptual information state and retention
  requirement**;
- **it need not be represented by a literal root folder**;
- **no mandatory `04 Archive` root is approved or required by CGD-001**;
- **historical versions, decisions, exchanges and evidence must remain traceable
  through an approved retention method** (BEP 7.10, 9.9, 12.10);
- **the technical retention method remains subject to later governance and
  implementation.**

## 4. Conditions

All eight conditions are **active** on and after this decision.

### CGD-C01 — States are not folders

**The existence or name of an area does not by itself establish an information
state.** The governed status of information arises from the applicable
**process, decision, authorisation and record** — never from where it sits
(BEP 6.3, 6.11; Increment 7C §4).

### CGD-C02 — No retrospective effect

**This decision does not retrospectively classify, approve, authorise, share,
publish, issue, deliver, receive or accept any information already present in
the CDE.**

**The existing drawing PDF and its `IN_REVIEW` records remain pre-existing
observed conditions only** (Increment 8D record §6.1, §6.5; PPER-008).

### CGD-C03 — Controlled transitions

**Movement or placement between platform areas must not be treated as sufficient
evidence of a WIP-to-Shared, Shared-to-Published or other information-state
transition.**

**Each transition requires the applicable governed checks, authorisation and
evidence** (CDE Workflow & State Strategy §3).

### CGD-C04 — Child structures excluded

**This decision approves only the root-area topology and intended state
mapping.**

**Existing child folders, discipline structures and team-space mappings are not
approved by implication.**

> **UD-001 remains unresolved.**

### CGD-C05 — Naming remains provisional

**The current root labels may continue to identify the adopted areas for the
training implementation.**

**Their adoption does not establish a project naming standard.**

**No observed spelling, numbering or capitalisation below the root is approved
or corrected by this decision** — including `07.  Reference Infomation`,
`2. Structural Consultanrt` and `3. MEP consultant`, which remain recorded as
observed and **are not classified as non-conformances**, no naming standard
existing to fail against (BEP 12.2, 12.6).

### CGD-C06 — Retention without mandatory Archive root

**Record / Retained is approved as a conceptual requirement, not as a mandatory
`04 Archive` root.**

**A later approved retention and technical implementation route is still
required** where operational retention controls are needed.

### CGD-C07 — Decision is not implementation

**CGD-001 authorises no folder creation, renaming, movement, deletion,
permission change or other Autodesk configuration act.**

**Because the observed root topology corresponds to the approved intended
topology, no root-level configuration change is directed by this decision.**

> **A later controlled verification must confirm the live topology before the
> mapping is relied on operationally.**

### CGD-C08 — Authority separation

The Training CDE Governance Approver obtains **no**:

- **publication / exchange authority**;
- **publication-event authority**;
- **recipient acceptance authority**;
- **CDE administration authority**;
- **implementation authority**;
- **design or professional approval authority**.

> **Holding the Training CDE Governance Approver function confers none of those
> authorities.**

## 5. Explicit non-effects

CGD-001 does **not**:

- authorise publication, or lift or vary the **publication hold**;
- approve **PAC-001**, or approve its **PM-1** position;
- reach or authorise **PE-2**, or any later PE event;
- establish **publication / exchange authority** — **UNRESOLVED**;
- establish **recipient acceptance authority** — **UNRESOLVED**;
- confer **CDE administration or implementation authority**;
- authorise any **Autodesk configuration change**;
- create, rename, move or delete any folder, or change any membership or
  permission;
- approve any **child folder, discipline structure or team-space mapping**;
- resolve **UD-001**;
- close **GCR-005** or **GCR-006**;
- establish the **naming, coordinate, titleblock or template** standards;
- retrospectively authorise, approve or classify any existing information;
- create a **real project appointment**, professional or contractual authority;
- create a tag, release or publication package.

## 6. Relationship to PAC-001 and PM-1

| Statement | |
|---|---|
| **PM-1 is a consequence of this full CDE-structure decision, not a substitute for it** | OF-001 asked what the intended structure **is**; PM-1 asks which destination holds one package |
| **The higher-order OF-001 dependency recorded by PRA-B01 is resolved by CGD-001** | The dependency is removed at the governance level (§7) |
| **The adopted topology supports retaining PAC-001's candidate position** — a dedicated governance / management-baseline child container under **`03. Published`** | The mapping in §3.4 is consistent with that position |
| **PAC-001's PM-1 position is not approved by CGD-001** | Support is not approval |
| **PAC-001 remains prepared and NOT APPROVED** | Unchanged |
| **No child container is created** | CGD-C07 |
| **Its naming remains provisional** | CGD-C05 |
| **Separate arrangement approval and implementation authority remain necessary** | PE-2 and a later implementation authorisation |
| **No substantive PAC-001 revision is required solely because of CGD-001** | The candidate's PM-1 position stands as written |
| **A later readiness reassessment must confirm the consequence** | Not performed here |

> **PAC-001 is not approved, and PE-2 is not moved forward, by this decision.**

## 7. Relationship to PRA-B01

**PRA-B01's stated blocking dependency — the unresolved OF-001 / PM-1
CDE-structure matter — is resolved at the governance level by CGD-001.**

**PRA-001's original outcome remains historically valid** as the assessment made
on its date, against the position then obtaining. **It is not rewritten, and its
BLOCKER finding is not deleted or reclassified.**

**PAC-001 has not automatically become approved or ready.** **A fresh controlled
readiness reassessment is required**, and **implementation verification of
CGD-001 remains pending** (CGD-C07).

## 8. Relationship to the pre-existing live state

CGD-001 does **not**:

- **retrospectively authorise the existing PDF in `03. Published`**;
- **treat its `IN_REVIEW` values as approval** — they are field values, not
  approval events;
- **approve the existing child-folder structure**;
- **adopt the observed naming irregularities**;
- **treat current platform use as proof that the newly approved governance was
  previously implemented.**

> **The intended governance applies prospectively from CGD-001.**

**Observed state is not intended governance**, and a decision taken today does
not reach backwards over information placed before it.

## 9. Decision, implementation and verification

```text
AG-002
established who may decide OF-001.

CGD-001
defines the approved intended CDE root topology and mapping.

A later implementation authorisation
would permit any required technical change.

A later verification
must confirm that the live configuration corresponds with CGD-001.
```

> **No implementation or verification occurs in Increment 8G-B.**

**Deciding is not implementing** (BEP 5.9 — *"CDE Administration implements
governance; it does not create it"*). Under **CGD-C07**, no root-level
configuration change is directed — the observed topology already corresponds to
the approved one — but **correspondence is asserted from a single bounded
observation and has not been verified for this purpose**.

## 10. Status after this decision

| Item | Status |
|---|---|
| **OF-001** | **RESOLVED at governance level by CGD-001.** Intended state now **defined**. Historical record of its previously undefined state **preserved** |
| **PRA-B01** | Blocking dependency **resolved**; PRA-001's historical outcome **unchanged** |
| **PRA-001** | Original outcome **NOT READY FOR APPROVAL** remains historically valid; **fresh reassessment required** |
| **PAC-001** | **PROPOSED GOVERNANCE — NOT APPROVED — unchanged** |
| PM-1 … PM-7 | **CANDIDATE ARRANGEMENT PREPARED — NOT APPROVED — unchanged** |
| PM-2 | **GOVERNANCE DECISION REQUIRED — unchanged** |
| **UD-001** | **Unresolved — unchanged** (CGD-C04) |
| **GCR-005**, **GCR-006** | **OPEN — unchanged** |
| Publication / exchange authority | **UNRESOLVED — unchanged** |
| Recipient acceptance authority | **UNRESOLVED — unchanged** |
| CDE administration / implementation authority | **Not conferred** (CGD-C08) |
| Project standards | **Not established — unchanged** |
| **PE-2 … PE-S** | **Not reached — unchanged** |
| **Publication** | **NOT AUTHORISED — unchanged** |
| **Publication hold** | **ACTIVE — unchanged** |
| Implementation | **None — not authorised** |
| Verification | **Pending** |

## 11. Decision statement

> ## **CGD-001 — APPROVE WITH CONDITIONS**
>
> **The as-found four-area root topology — `0. Common Files`, `01. WIP (Work in
> Progress)`, `02. Shared`, `03. Published` — is ADOPTED as the intended
> training CDE governance topology**, with the intended state mapping in §3 and
> the eight conditions in §4.
>
> **OF-001 is resolved at the governance level. Implementation and verification
> have not been performed.**
>
> **PAC-001 is not approved. No Autodesk change is authorised. No other
> authority is conferred.**
>
> ## **PUBLICATION REMAINS NOT AUTHORISED — PUBLICATION HOLD ACTIVE.**

**Related records.** OF-001 — `supporting/governance-decision-register.md` §3.
AG-002 — [`docs/Training-CDE-Governance-Approver-Function-Decision.md`](Training-CDE-Governance-Approver-Function-Decision.md).
Readiness assessment — [`docs/Publication-Arrangement-Readiness-Assessment.md`](Publication-Arrangement-Readiness-Assessment.md).
Candidate — [`docs/Publication-Arrangement-Candidate-0.1.md`](Publication-Arrangement-Candidate-0.1.md).
Observation — [`docs/Increment-8D-Publication-Planning-Read-Only-Observation-Record.md`](Increment-8D-Publication-Planning-Read-Only-Observation-Record.md).
