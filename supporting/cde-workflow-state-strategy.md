# CDE Workflow & State Strategy

## Document purpose and status

**Purpose.** Defines **how information moves between controlled states** in the
Harrismith CDE — the states, the transitions between them, the checks and
decisions that govern each transition, the evidence each produces, and the
exceptions.

It provides the detailed implementation logic beneath BEP Sections 6 and 7.

| Field | Value |
|---|---|
| Document status | **Controlled Draft** |
| Authority | Supporting management resource to the Harrismith BEP controlled draft |
| Approval | **Not approved** as part of BEP Training Baseline 0.1 |
| Supports | BEP sections 6 and 7 |

**Classification.** The workflow defined here is **PROPOSED GOVERNANCE** for the
training implementation. As-found platform observations are recorded separately
and explicitly as **OBSERVED FACT** (section 5). The two are never merged.

**This strategy does not describe the live platform.** It defines proposed
governed CDE behaviour. It is **not** evidence that the current Autodesk
configuration matches it. Where the two differ, the difference is recorded, not
reconciled by assumption (section 6).

**Safety boundary.** Developing this document does **not** authorise any read
from or write to the Autodesk Desktop Connector / ACCDocs tree, and does not
authorise any change to CDE configuration. See `README.md` section 2.1.

**Six things kept distinct** throughout, because collapsing any of them is how a
CDE stops governing anything:

| | |
|---|---|
| **Conceptual state** | What the information *is*, in governance terms |
| **Platform implementation** | How a state is realised in software |
| **Responsibility** | Who holds the function |
| **Transition decision** | The act that permits movement |
| **Evidence** | What demonstrates the transition happened |
| **Exception** | A recorded departure from the normal route |

**The CDE is a process, not a folder tree.** A folder structure implements part
of the process. Reorganising folders does not change how information is
governed, and the presence or absence of a folder proves nothing about state
(BEP 6.1, 6.3).

---

## 1. Core CDE model

| State | Definition |
|---|---|
| **WIP** | Information under originator / task-team control. Not authorised for general project reliance. |
| **Shared** | Information deliberately made available beyond the originating task team for an identified purpose, after required check and authorisation. |
| **Published / Authorised** | Information authorised for an identified formal or project-facing delivery or use purpose. |
| **Record / Retained** | Historical information and evidence retained for traceability. |

**WIP** is used for authoring, iteration, internal checking, correction and
readiness preparation. It may hold many versions; WIP versions are not project
exchanges, and visibility of WIP is not permission to rely on it (BEP 7.5).

**Shared does not mean** published, accepted, or suitable for every purpose.

**Published does not mean** universally suitable, forever final, or
automatically accepted by recipients. Authorisation is purpose-specific (BEP
6.7).

**Record / Retained is a conceptual state and a retention requirement — not
necessarily a folder.** **No mandatory CDE root named `04 Archive` is required
or approved**, and none is created here. No such project-root requirement has
been approved, and the project's retention approach is **TBD** (BEP 6.3).

---

## 2. State transition model

**Normal production and sharing route:**

```
REQUIREMENT
    ↓
AUTHOR
    ↓
WIP
    ↓
CHECK
    ↓
AUTHORISE SHARE
    ↓
SHARED
    ↓
REVIEW / CONSUME
    ↓
COORDINATE / USE FOR STATED PURPOSE
```

**Where a defined delivery requires it:**

```
SHARED
    ↓
DELIVERY REVIEW
    ↓
AUTHORISE PUBLICATION / EXCHANGE
    ↓
PUBLISHED / AUTHORISED
    ↓
CONTROLLED DELIVERY
    ↓
RECEIPT
    ↓
ACCEPTANCE FOR STATED PURPOSE
```

**Where correction is required:**

```
finding / rejection / issue
    ↓
originating task-team WIP
    ↓
correct
    ↓
check
    ↓
reauthorise
    ↓
reshare / republish as applicable
```

**Every arrow is a controlled transition.** Each has its own trigger, its own
criteria and its own responsible function.

**Separate transitions do not require separate people.** In a project of this
size one participant may perform several. The requirement is that each decision
is *made*, against its own criteria, and is traceable (BEP 5.11, 7.1).

**Five acts that are never collapsed into one another:**

| Check | Authorisation | Review | Coordination | Acceptance |
|---|---|---|---|---|
| Verifies against a defined requirement | Permits progression for a defined purpose | Considers information for a stated purpose | Multidisciplinary interface process | Recipient acknowledges suitability for the stated purpose |

Checking does not authorise. Coordination does not approve design. Publication
does not constitute acceptance (BEP 9.1, 9.2).

---

## 3. Transition control table

Eight controlled transitions. Presented as two aligned tables keyed by
transition reference.

### 3.1 Transition, trigger and decision

| Ref | From state | Trigger | Required check | Decision / authorisation | Performing function | To state |
|---|---|---|---|---|---|---|
| **T1** | WIP | Information ready for controlled sharing | Task-team technical / content check **and** information-quality / readiness check | **Authorise share** | Authoring team performs; **Task-Team Lead** (or other explicitly allocated function) authorises | Shared |
| **T2** | Shared | Receiver chooses to use shared information for a stated purpose | Receiver review of suitability for that purpose | Receiver **consume** decision | Receiving task team | Consumed / referenced in receiver's working context |
| **T3** | Shared | Container included in a defined coordination cycle | Input readiness appropriate to the coordination purpose | Coordination **input inclusion** decision | **BIM Coordinator** (process function) | Coordination input |
| **T4** | Shared | A defined delivery or exchange requirement | **Delivery readiness review** | **Authorise publication / exchange** | **UNRESOLVED — TBD** (BEP 9.7) | Published / Authorised |
| **T5** | Published / Authorised | Approved exchange route executed | Transmission prepared per the delivery requirement | Execute controlled transmission | Originating task team; CDE Administration may execute platform functions | Delivered |
| **T6** | Delivered | Recipient receives the exchange | Registration of receipt | Receipt | Receiving / recipient function | Received |
| **T7** | Received | Recipient decision for the stated purpose | Assessment against the applicable requirement | **Accept** (or reject) | **UNRESOLVED — TBD / recipient-function dependent** (BEP 9.8, 10.11) | Accepted |
| **T8** | Shared or Published | Coordination finding, rejection, or issue requiring correction | Task-team check of the revised information | **Reauthorise share** (or republish, as applicable) | **Originating** task team; Task-Team Lead authorises | Back to WIP, then Shared / Published |

### 3.2 Evidence and failure route

| Ref | Evidence | Failure / return route |
|---|---|---|
| **T1** | Version history; checking record; share / exchange record as appropriate | Information remains in, or returns to, WIP. No partial progression |
| **T2** | Consume state or history; receiver's record of the working purpose | Receiver declines to consume; may request clarification or raise a coordination issue |
| **T3** | Coordination input record; federation record | Input rejected as unready; container returns to the originating task team, which decides whether rework is required |
| **T4** | Delivery review record; publication authorisation record | **Currently blocked** — no authorisation can be given while the authority is unresolved. Information remains Shared |
| **T5** | Transmission record — what, when, by which role, to whom, for what purpose | Transmission fails or is withdrawn; recorded and re-executed |
| **T6** | Receipt record | No receipt recorded; sender follows up. Non-receipt is not deemed acceptance |
| **T7** | Acceptance or rejection record, with the stated purpose | **Rejection** → reason recorded → T8 rework route |
| **T8** | Issue history; revised version history; re-check and re-authorisation records; superseded marking of the previous exchange | Correction found inadequate at re-coordination; issue remains open and the container returns to WIP |

**Notes carried from the BEP:**

- **T2 — availability is not consumption.** Information being visible or present
  in a shared location does not mean any team adopted it. Consumption is a
  deliberate act, and it does **not** transfer technical ownership from the
  originator (BEP 6.5, 7.9).
- **T3 — coordination input is not design approval.** Including a container in a
  coordination cycle carries no technical endorsement (BEP 8.1, 9.5).
- **T4 — the authority is not assigned here.** See sections 11 and 19.
- **T7 — acceptance does not transfer technical responsibility** from the
  originating task team (BEP 9.8).
- **T8 — superseded exchanges remain traceable.** Previous exchanges are marked
  superseded, not deleted (BEP 7.10, 9.9).

---

## 4. Design Collaboration workflow

Where Design Collaboration is configured, the proposed design-team workflow is:

```
Task-team WIP
  → check
  → authorise
  → package / share
  → Shared
  → receiver review
  → consume where appropriate
```

**Share and consume are different acts by different parties.**

| Act | Who | Meaning |
|---|---|---|
| **Share** | Originating task team | Makes information available through a controlled exchange |
| **Consume** | Receiving task team | Deliberately adopts it into its own working context |

**Availability of a package does not mean the recipient has consumed it.** A
package sitting available is not a package in use, and nothing is consumed by
accident.

**Consumption does not transfer technical ownership.** The originator remains
responsible for what it produced, before and after consumption.

**Design Collaboration is not required for every exchange or every container.**
It is the preferred project-facing mechanism for design-team exchange *where
appropriate*; the route must fit the information type and the approved workflow
(BEP 7.8). **No additional platform team is created or proposed by this
strategy.**

---

## 5. As-found platform mapping

**OBSERVED FACT** — sanitised context recorded at Discovery Gate A, at the level
inspected, at that time. Recorded as evidence, not endorsed as intended
governance.

**Observed project root areas:**

| Common Files | WIP | Shared | Published |
|---|---|---|---|

**Observed Design Collaboration teams:**

- Architecture
- MEP Consultant
- Structural

**Observed team-space mapping:**

| Observed team | Observed bound WIP space |
|---|---|
| Architecture | Architecture-labelled WIP |
| **MEP Consultant** | **Structural-labelled WIP** |
| **Structural** | **MEP-labelled WIP** |

The second and third constitute the observed mapping discrepancy recorded as
**UD-001**.

| UD-001 | |
|---|---|
| Classification | **OBSERVED discrepancy + UNRESOLVED DECISION** |
| Status | **Unresolved** |
| Intended state | **Not decided, not approved** |
| Decision owner | Not established — TBD |

**This strategy does not:** correct the discrepancy; propose replacement
bindings; classify it as a non-conformance; or change any Autodesk
configuration. A non-conformance requires approved governance to fail against,
and no intended mapping has been approved (BEP 12.6).

**Further observations:**

| Observation | Classification |
|---|---|
| A Contractors WIP area exists | OBSERVED FACT |
| No corresponding Contractors Design Collaboration team was established in the discovery evidence | OBSERVED FACT |
| No Design Collaboration Coordination Space was observed configured | OBSERVED FACT |
| Standards and governance Common Files areas were observed empty | OBSERVED FACT |

All are observations of a point in time. **None is a permanent requirement**,
and none should be read as one. Absence of an observed team or space is not
evidence that one is required, or that one is not.

---

## 6. Intended vs implemented mapping

Four layers, each distinct:

| Layer | Is |
|---|---|
| **AS-FOUND** | Observed evidence of current behaviour |
| **INTENDED GOVERNANCE** | The approved target configuration |
| **IMPLEMENTED CONFIGURATION** | The platform result after an authorised change |
| **VERIFIED CONFIGURATION** | The implemented state checked against intended governance |

**Lifecycle:**

```
observe
  → record
  → decide intended state
  → authorise change
  → CDE Administration implements
  → verify
  → close / update register
```

**Where UD-001 currently sits:**

```
observe        ✓ done
  → record     ✓ done (UD-001, section 5)
  → decide intended state    ← STOPS HERE. Decision unresolved.
  → authorise change         — not reached
  → CDE Administration implements — not reached
  → verify                   — not reached
  → close / update register  — not reached
```

**UD-001 stops before "decide intended state".** Every downstream step is
therefore unavailable. Implementing a change now would be configuration without
a decision behind it — the exact failure this model exists to prevent.

**Observed state does not prove correctness. Intended state does not prove
implementation. Implementation does not prove success until verified** (BEP
12.3, 12.9).

---

## 7. Team space model

An Autodesk collaboration team is a **platform construct**:

```
Autodesk collaboration team
   ≠ organisation
   ≠ task team
   ≠ discipline
   ≠ appointment
```

Membership of a team confers **no authority of any kind** (BEP 4.5, 6.4).

**A team-space mapping is an implementation decision serving governance.** It
follows from a decision about responsibility; it does not create one.

**Six discipline codes do not produce six platform teams.** ARC, STR, MEC, ELE,
PLM and FIR are information domains. This strategy does **not** create, propose
or imply a platform team per discipline code. In particular, MEC, ELE and PLM
sit within a single MEP Consultant party, and FIR sits with the separate Fire
Consultant (BEP 4.3) — an organisational fact that a naive one-team-per-code
mapping would misrepresent.

**The intended future team-space model is unresolved** wherever it has not been
explicitly approved, including the matter recorded as UD-001 and the open
question of whether platform teams should map one-to-one to task teams at all.

---

## 8. Production flow

The design containers allocated in `model-information-responsibility-matrix.md`:

| Container | Originating party | Task team | Discipline |
|---|---|---|---|
| ARC-01 | Architectural Consultant | Architectural task team | ARC |
| STR-01 | Structural Consultant | Structural task team | STR |
| MEC-01 | **MEP Consultant** | Mechanical task team | MEC |
| ELE-01 | **MEP Consultant** | Electrical task team | ELE |
| PLM-01 | **MEP Consultant** | Plumbing task team | PLM |
| FIR-01 | **Fire Consultant** | Fire task team | FIR |

Each follows the same state logic:

```
container
  → WIP
  → internal check
  → authorise share
  → Shared
```

**The same logic applies to all six. That is not a claim that all six currently
exist in the live platform.** Only Architecture was observed as a populated
direct production stream at the inspected level (OF-002). The allocations above
are **PROPOSED GOVERNANCE** under TA-03; they are not converted into OBSERVED
FACT by appearing in this strategy, and absence of observation is not
observation of absence.

---

## 9. TRN-E01 mapping — design coordination share

Maps `information-delivery-schedule.md` event **TRN-E01**.

**Applicable containers:** ARC-01, STR-01, MEC-01, ELE-01, PLM-01, FIR-01, as
applicable.

```
WIP
  → check (technical/content + information-quality/readiness)
  → Task-Team Lead authorises share
  → Shared
  → coordination input
```

| Field | Value |
|---|---|
| Transitions used | **T1** (WIP → Shared), then **T3** (Shared → coordination input) |
| State reached | **Shared** |
| Suitability | **Coordination use only** |
| Authorisation | Task-Team Lead authorisation to share |

**Entering a coordination cycle does not promote a container to Published.**
Coordination consumes Shared information; it is not a publication route, and no
container becomes Published by being coordinated.

**Receiver consumption is not design approval.** A decision to consume or
reference shared information for coordination is a consumption decision only
(BEP 6.5, 9.5).

**Shared coordination information is not** construction-ready, formally accepted
design, or record information.

---

## 10. TRN-E02 mapping — conditional coordination reshare

Maps event **TRN-E02**, which is **repeatable and conditional**.

```
coordination finding / Issue
  → originating task-team WIP
  → correction
  → check
  → authorise share
  → Shared
  → re-coordinate
  → verify
```

| Field | Value |
|---|---|
| Transitions used | **T8** (rework), then **T1** and **T3** again |
| Activation | **Per affected container only** |
| Frequency | None. Repeatable, event-triggered |

**Only affected containers activate.** The Information Delivery Schedule holds
six conditional template rows; a row becomes an active exchange only when its own
container requires controlled rework and reshare.

| Example | Result |
|---|---|
| MEC-01 requires correction | **TRN-E02-MEC activates** |
| FIR-01 does not require correction | **TRN-E02-FIR does not activate** |

**A coordination cycle may activate one container, several, or none.** Nothing
here implies that all six disciplines reshare every cycle.

**The originating task team performs the technical correction**, in its own WIP,
through its own checking route. The shared instance is never edited in place as
an uncontrolled workaround (BEP 7.10).

**Verification is not design approval.** BIM Coordinator verification confirms
the coordination process reached a disposition — not that any discipline
approved the design condition behind it (BEP 8.10, 9.5).

---

## 11. TRN-E03 mapping — controlled design review / project-facing exchange

Maps event **TRN-E03**.

**Status: PROPOSED — BLOCKED PENDING GOVERNANCE DECISIONS.**

```
Shared
  → delivery review
  → [ BLOCK: publication / exchange authority UNRESOLVED — TBD ]
  → Published / Authorised
  → [ BLOCK: acceptance authority UNRESOLVED — TBD ]
  → Accepted
```

The transition toward Published / Authorised **cannot become operational** until,
as applicable:

| Blocking matter | Status |
|---|---|
| Deliverable / container set defined | Not defined |
| Recipient identified | Not established |
| Publication / exchange authority established | **UNRESOLVED — TBD** (BEP 9.7) |
| Acceptance authority and criteria established | **UNRESOLVED — TBD** (BEP 9.8, 10.11) |
| Format requirement established | Not established — no approved standard |
| Delivery purpose defined | Not defined |

**None of these is solved here.** The block is represented deliberately and is a
feature of the model, not a gap in it: **governance can intentionally stop a
workflow.** A route that cannot legitimately proceed should visibly halt, rather
than complete itself by borrowing an authority nobody granted.

Transition **T4** therefore has no available authorising function, and
information remains **Shared**.

---

## 12. Desktop Connector and local access

**Desktop Connector is a filesystem access mechanism** to cloud-managed
information.

It is **not**:

- a separate CDE;
- a local authoritative project state;
- the BEP Git repository;
- an approved live-sync publication mechanism.

A file being present locally says nothing about its state, suitability or
authorisation. **Project state is governed by the CDE process** (BEP 6.10).

**Git repository — authoritative authoring source** for the BEP's controlled
source documents:

```
Git source
  → review
  → approved baseline
  → controlled manual publication
  → project-facing CDE artefact
```

**A Git draft is not the issued project baseline.** Git may hold a newer
controlled draft while the CDE holds the last issued baseline; that is
legitimate provided the status of each is clear.

Standing constraints:

- the `harrismith-bep` repository is not configured inside, linked to, or
  live-synchronised with the Desktop Connector CDE location;
- **no symlink, junction, bind-mount or live-sync publication model is approved
  for this workflow**;
- publication is manual and human-performed;
- **no machine-specific paths are recorded in this document.**

---

## 13. Versions, revisions, state, status and suitability

| Term | Meaning |
|---|---|
| **Version** | A platform or file history instance |
| **Revision** | A controlled issue identifier, where project convention requires one |
| **State** | WIP / Shared / Published / retained |
| **Status** | A workflow or decision condition |
| **Suitability** | The permitted intended use |

**These are never used interchangeably.**

| A new version does **not** automatically mean | A Published container does **not** automatically mean |
|---|---|
| a new revision | delivered |
| a new state | received |
| approval | accepted |
| suitability for a new purpose | suitable for a different purpose |

Each is a separate act with its own decision and responsible function (BEP 6.8,
10.11).

---

## 14. Access and permission model

**Permission ≠ authority.**

CDE Administration may implement membership, permissions, folders and spaces,
team mappings and platform workflow configuration — **only in support of approved
governance** (BEP 5.9, 6.9).

Platform access does **not** confer:

- authority to share;
- publication authority;
- technical approval authority;
- acceptance authority.

Access is configured to follow approved responsibility; responsibility comes
first and permission follows it. Where access and approved responsibility
diverge, the divergence is recorded as a deviation rather than treated as a
redefinition of who is responsible.

**CDE Administration implements governance; it does not define it.** Changing
the software does not make a decision.

---

## 15. Exceptions

```
normal workflow unavailable
  → identify exception
  → record reason
  → assess impact / risk
  → define temporary controlled route
  → authorise exception where required
  → execute
  → restore normal workflow
  → verify / close
```

Each exception records: the reason; the affected information; the temporary
route used; the responsible role; the risk and impact; and the required
follow-up (BEP 7.11).

**An exception does not become precedent through repeated use.** A route used
once under recorded justification carries no standing; repetition without a
decision is how undocumented practice quietly replaces governance.

**Uncontrolled routes are not recommended and are not acceptable as quiet
workarounds** — email exchange, personal cloud storage, local-drive exchange and
messaging attachments are not controlled exchange routes. Where exceptional
circumstances force such a route, it is **governed and recorded** as an exception
above, and the normal workflow is restored afterwards.

Detailed exception governance sits in BEP Section 12 and
`governance-decision-register.md`.

---

## 16. Evidence

Evidence that may demonstrate CDE transitions:

- platform version history;
- Design Collaboration share / package history;
- consume state and history;
- checking record;
- authorisation record;
- coordination input record;
- issue history;
- review record;
- publication / transmission record;
- receipt and acceptance record;
- Governance & Decision Register entry.

**No transition is required to use a specific Autodesk feature.** Evidence
depends on the workflow and the purpose; what matters is that it is sufficient
and traceable (BEP 9.11).

**Git history is source history.** It records what changed in the authoring
source and when. It does not by itself establish CDE issue, project
authorisation, delivery or recipient acceptance.

---

## 17. Platform implementation rules

1. **Governance decision precedes configuration change.**
2. **CDE Administration implements approved configuration** — it does not create
   governance by changing software.
3. **Configuration is verified after change** (section 6).
4. **Evidence of current state is not authority to retain that state.** That
   something has always been configured a certain way is not a reason it should
   remain so.
5. **Folder and team naming is not silently corrected.** An observed naming or
   mapping condition is recorded and decided, not quietly fixed (UD-001).
6. **Unresolved mappings remain unresolved until decided.**
7. **Platform configuration reflects the approved BEP and supporting strategy —
   it does not redefine them.**

---

## 18. Relationship to other resources

| Resource | Holds |
|---|---|
| **BEP Sections 6–7** | Governing CDE principles |
| `information-management-responsibility-matrix.md` | Who performs each transition and process function |
| `model-information-responsibility-matrix.md` | Which task team originates each container |
| `information-delivery-schedule.md` | Which containers exchange at which event, and for what purpose |
| `governance-decision-register.md` | Decisions, deviations and changes affecting this workflow |
| `coordination-review-strategy.md` | The detailed coordination process, after Shared information becomes coordination input |

**This strategy holds the transition logic.** Content of the resources above is
referenced, not duplicated. Each is separately controlled and declares its own
status; reference here does not constitute approval of it.

---

## 19. Status of CDE governance matters

Existing matters, referenced rather than renumbered. **No new decision ID is
created.**

| Matter | Reference | Status |
|---|---|---|
| MEP / Structural team-space mapping | **UD-001** | **UNRESOLVED** — observed discrepancy; intended state not decided |
| TRN-E03 publication / exchange authority | BEP 9.7; IM matrix D4 | **UNRESOLVED / TBD** |
| TRN-E03 recipient acceptance authority | BEP 9.8, 10.11; IM matrix D7 | **UNRESOLVED / TBD** |
| Coordinates standard | BEP 11.5; OF-003 | **Not approved** — Hartebeesthoek94 / Lo29 exists as candidate context requiring confirmation |
| Naming standard | BEP 11.3; OF-003 | **Not established** |
| Retention / record approach | BEP 6.3 | **TBD** — no `04 Archive` root requirement approved |
| Design Collaboration Coordination Space | OF-005 | **Not observed configured** — intended state not decided |
| Contractors Design Collaboration team | OF-004; BEP 4.5 | **Not established in discovery evidence** — intended state not decided |
| Whether platform teams map one-to-one to task teams | BEP 4.5 | **Open question** |
| Governance change approval authority, by change class | BEP 12.7; IM matrix A2 | **UNRESOLVED / TBD** |

None of these is resolved by this strategy. Each is recorded so the gap stays
visible rather than being filled with a plausible value.
