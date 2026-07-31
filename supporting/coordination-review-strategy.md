# Coordination & Review Strategy

## Document purpose and status

**Purpose.** Defines **how multidisciplinary coordination is performed using
controlled Shared information** — scope, participants, input readiness,
environments, federation, interface checks, findings and Issues, assignment,
resolution, verification, meetings, completion, escalation and evidence.

Expands BEP Section 8.

| Field | Value |
|---|---|
| Document status | **FOR REVIEW — Training Baseline 0.1 Candidate** |
| Authority | Supporting management resource under the Harrismith BEP framework |
| Approval | **Not approved.** Candidate review does not confer approval |
| Supports | BEP sections 8 and 9 |

**Classification.** The coordination arrangements defined here are **PROPOSED
GOVERNANCE** for the training implementation unless explicitly classified
otherwise. As-found observations are recorded separately and explicitly as
**OBSERVED FACT** (section 7).

**This strategy does not describe the live platform.** It does **not** prove that
the corresponding Autodesk configuration currently exists. Where the two differ,
the difference is recorded, not reconciled by assumption.

**Coordination is not technical or design approval.** Nothing in this document
confers design approval, professional certification, publication authority or
recipient acceptance.

---

## 1. Coordination principles

| Principle | |
|---|---|
| **Interfaces, not geometry alone** | Coordination manages multidisciplinary interfaces. |
| **Controlled inputs** | Inputs are controlled information suitable for the coordination purpose. |
| **Authorship stays put** | Originators retain authorship and technical responsibility throughout. |
| **Federation does not merge ownership** | Aggregation creates a coordination artefact, not a jointly-authored model. |
| **Clash detection is one technique** | It is not the whole coordination process. |
| **Finding ≠ managed Issue** | Creating an Issue is a deliberate decision. |
| **Process, not solution** | The BIM Coordinator manages the process, not the technical solution. |
| **Verification ≠ design approval** | Verifying a disposition endorses nothing technically. |
| **Completion ≠ zero clashes** | Completion rests on required checks and dispositions. |
| **Traceability** | Decisions and actions remain recoverable afterwards. |

## 2. Coordination scope

Intended training design-coordination scope covers the discipline domains:

| ARC | STR | MEC | ELE | PLM | FIR |
|---|---|---|---|---|---|

**These are discipline domains.** They are **not** six organisations, **not** six
Autodesk teams, and **not** six professional appointments (BEP 4.4).

Organisation remains as allocated in BEP 4.3 and the Model / Information
Responsibility Matrix:

| Party | Disciplines |
|---|---|
| Architectural Consultant | ARC |
| Structural Consultant | STR |
| **MEP Consultant** — one party | MEC, ELE, PLM |
| **Fire Consultant** — separate party | FIR |

**Construction and trade coordination is a future extension**, introduced when
relevant trade information enters the training delivery workflow. **No trade
coordination deliverable is defined here.**

## 3. Participants and functions

Coordination-specific functions only. The full allocation is in
`information-management-responsibility-matrix.md` and is not duplicated.

**BIM Coordinator** — organise the coordination cycle; identify required inputs;
manage federation; manage and coordinate checks; triage findings; create and
coordinate managed Issues where required; monitor assigned actions; coordinate
re-review; verify coordination disposition; escalate blockers; retain and report
coordination evidence.

The BIM Coordinator does **not**: own discipline design solutions; become
technical approver; or acquire publication authority through coordination.

**Task-Team Lead** — ensure appropriate team input; ensure technical and content
checking; own the team's response to relevant coordination matters; determine and
lead technical resolution within the team; authorise revised information for
controlled reshare where that function is allocated.

**Author** — performs the technical and model correction in WIP.

**Checker** — checks revised information according to the team process.

**BIM Manager** — governs the coordination framework; resolves or escalates
governance-level questions; supports assurance. Does **not** automatically
approve technical design.

**CDE Administration** — implements approved coordination-related platform
configuration. Does **not** invent coordination governance; permission is not
authority.

**Lead Delivery Party** — may coordinate project-level dependencies and
escalation where applicable. **Holder remains TBD.**

All holders remain TBD (BEP 5.3–5.9).

## 4. Coordination input register

The input register records what enters a coordination cycle, and on what basis.

**Fields:**

| Field | Meaning |
|---|---|
| Coordination Cycle / Event | The cycle the input belongs to |
| Container Ref | From the Model / Information Responsibility Matrix |
| Discipline | Information domain |
| Originating Party | Party producing the container |
| Task Team | Task team producing it |
| Information State | Must be **Shared** for normal coordination |
| Version / Revision reference | Where applicable |
| Coordination Purpose | Why it is included |
| Readiness Status | Per section 5 |
| Known Limitations / Exclusions | Declared by the originator |
| Included / Excluded | The inclusion decision |
| Notes | Context |

**Governed information classes** — the proposed container refs:

| ARC-01 | STR-01 | MEC-01 | ELE-01 | PLM-01 | FIR-01 |
|---|---|---|---|---|---|

For **TRN-E01**, all six are **potential and applicable** coordination inputs.

**No live version or revision values are recorded.** None were observed or
validated, and none is invented. **This is not a claim that all six currently
exist as live coordination models** — only Architecture was observed as a
populated direct production stream at the inspected level (OF-002). Absence of
observation is not observation of absence.

## 5. Input readiness

Before inclusion, confirm as applicable:

- correct container identity;
- correct originator and task team;
- **Shared** state;
- intended coordination purpose;
- required task-team checks completed;
- share authorised;
- coordinate and reference context known well enough for the check;
- known omissions and limitations visible;
- dependencies identified;
- version or revision identifiable where required.

**Readiness for coordination does not mean** complete design, construction-ready,
published, accepted, or technically approved. Information can be ready to
coordinate while remaining incomplete and subject to change (BEP 8.3).

**If an input is not ready, exclude or defer it and record the reason.**
Coordinating uncontrolled WIP is not the normal method (BEP 6.6). An exclusion
with a recorded reason is a governed outcome; coordinating an unready input
quietly is not.

## 6. Coordination environments

**Autodesk Model Coordination** — intended project-facing cloud environment for
aggregation of suitable Shared model information, multidisciplinary visual
review, clash and interface coordination, and coordination issue context, **where
configured and appropriate**.

**No Coordination Space is claimed to be configured.** Discovery established that
no Design Collaboration Coordination Space was observed configured (section 7,
OF-005).

**Navisworks** — specialist desktop coordination environment for federation,
detailed visual analysis, specialist clash analysis, and review workflows where
desktop capability is beneficial.

**Navisworks is not a separate governance system.** A Navisworks result enters
the same governed finding and Issue workflow as any other; the tool used to find
something does not determine how it is managed.

**Forma / project Issues** — where used, governed project Issues provide the
operational record for actionable coordination matters requiring ownership,
tracking, resolution, verification and history. **Not every clash creates an
Issue** (section 12).

**Meetings** — coordination meetings support the process. They do **not** replace
controlled information, Issues, decision records or governance records (section
20).

## 7. As-found coordination context

**OBSERVED FACT** — sanitised context from Gate A discovery, at the level
inspected, at that time.

| Observation | |
|---|---|
| A coordination area existed under Shared | OBSERVED FACT |
| A Navisworks area was observed with limited content | OBSERVED FACT |
| No Design Collaboration Coordination Space was observed configured | OBSERVED FACT |
| Direct production content at the inspected level was primarily Architecture | OBSERVED FACT |
| MEP / Structural Design Collaboration mapping discrepancy | **UD-001 — UNRESOLVED** |

**No platform maturity is claimed.** Presence of an area is not evidence that a
governed coordination process is operating.

**Limited observed content does not mean coordination is absent.** It means
limited content was observed, at one level, at one time.

**UD-001 is not resolved, corrected or classified as a non-conformance here**, and
no replacement mapping is proposed. **The live project was not accessed.**

## 8. Federation model

**COORD-01**, from the Model / Information Responsibility Matrix — a **temporary
controlled multidisciplinary coordination aggregation**.

**Potential inputs:** ARC-01, STR-01, MEC-01, ELE-01, PLM-01, FIR-01, as
applicable.

COORD-01 does **not**:

- merge authorship;
- transfer technical responsibility;
- become a jointly-authored design model;
- replace the discipline containers;
- automatically become a formal deliverable.

**The BIM Coordinator leads the federation *process*.** Originating task teams
remain responsible for their source information, before and after federation
(BEP 8.5).

## 9. Interface / check strategy

**Blind all-versus-all testing is not adopted.** Testing everything against
everything produces volume rather than insight and buries the findings that
matter (BEP 8.6). **A check exists because a meaningful interface exists.**

**PROPOSED training interface matrix — 12 checks.**

| Check Ref | Discipline A | Discipline B / context | Coordination purpose | Typical interface | Check type | Tolerance / rule | Status |
|---|---|---|---|---|---|---|---|
| **CI-01** | ARC | STR | Architectural / structural interface review | Structural elements vs architectural space and openings; major penetrations and interfaces; alignment affecting usable space | Hard Clash; Spatial Interface; Alignment / Reference | **TBD** | PROPOSED |
| **CI-02** | STR | MEC | Mechanical routes vs structural system | Duct and service routes; major structural penetrations; clearance around structural elements | Hard Clash; Clearance / Access | **TBD** | PROPOSED |
| **CI-03** | STR | ELE | Electrical distribution vs structural system | Major tray, conduit and service routes; penetrations; space conflicts | Hard Clash; Spatial Interface | **TBD** | PROPOSED |
| **CI-04** | STR | PLM | Plumbing routes vs structural system | Pipe routes; falls where spatially relevant; penetrations; structural conflicts | Hard Clash; Clearance / Access | **TBD** | PROPOSED |
| **CI-05** | STR | FIR | Fire-service routes and equipment vs structural system | Service routes; penetrations; access and clearance interfaces | Hard Clash; Clearance / Access | **TBD** | PROPOSED |
| **CI-06** | ARC | MEC | Mechanical services vs architectural space | Ceiling zones; plant and access space; diffuser and service placement; shafts and openings | Spatial Interface; Clearance / Access | **TBD** | PROPOSED |
| **CI-07** | ARC | ELE | Electrical systems vs architectural space | Fixtures and devices; ceiling interfaces; access and space requirements | Spatial Interface; Clearance / Access | **TBD** | PROPOSED |
| **CI-08** | ARC | PLM | Plumbing systems vs architectural layout | Fixtures; shafts; service routes; access and space | Spatial Interface; Clearance / Access | **TBD** | PROPOSED |
| **CI-09** | ARC | FIR | Fire-system interfaces with architectural layout | Equipment and device locations; service routes; access; architectural interface requirements | Spatial Interface; Design / Interface Question | **TBD** | PROPOSED |
| **CI-10** | MEC | ELE | Services congestion between mechanical and electrical distribution | Shared service zones; route congestion; access for maintenance | Hard Clash; Clearance / Access | **TBD** | PROPOSED |
| **CI-11** | MEC | PLM | Services congestion between mechanical and plumbing distribution | Shared service zones; route congestion; access for maintenance | Hard Clash; Clearance / Access | **TBD** | PROPOSED |
| **CI-12** | MEC | FIR | Mechanical distribution vs fire services | Shared service zones; route congestion; clearance around fire equipment | Hard Clash; Clearance / Access | **TBD** | PROPOSED |

**Not all possible pairs are built.** The matrix stops at meaningful interfaces
rather than completing the combinatorial set.

**These are PROPOSED TRAINING COORDINATION CHECKS.** They are **not** evidence of
real client requirements, and they do not become project requirements by
appearing here.

## 10. Check types

| Type | Meaning |
|---|---|
| **Hard Clash** | A physical geometric intersection |
| **Clearance / Access** | Required operating, installation, maintenance or access space |
| **Alignment / Reference** | Inconsistent alignment, coordinates, levels, reference basis or positioning |
| **Spatial Interface** | Elements competing for required usable or service space without necessarily intersecting |
| **Information / Readiness** | Missing, incomplete, incorrectly identified or unsuitable coordination input |
| **Design / Interface Question** | A multidisciplinary interface requiring a technical decision, not necessarily a geometric clash |

**Not every category depends on automated clash detection.** Alignment,
readiness, spatial-interface and design-question matters are frequently
identified by review rather than by a detection run, and are no less governed for
that.

## 11. Tolerances and rules

**No numeric tolerance is defined.** For every check in section 9 the tolerance
or rule remains:

> **TBD** by approved coordination requirement, technical standard, system
> requirement, or documented coordination decision.

**A software default tolerance is not a project requirement.** A value shipped
with a tool has no governance authority, and adopting it silently would convert a
vendor default into a project rule.

**Different interfaces may require different rules.** A single project-wide
threshold is not assumed.

**Where no tolerance is approved, a check must not present a numeric threshold as
though it carried governance authority.** The check may still run; its output is
a finding for triage, not a compliance judgement.

## 12. Findings, clashes and Issues

| Term | Meaning |
|---|---|
| **Finding** | An observed coordination matter requiring triage |
| **Clash** | A geometric or spatial coordination finding generated or identified through review |
| **Issue** | A governed action record created when a matter requires ownership, action, decision, tracking, verification or escalation, or otherwise needs a controlled project record |

**Clash / finding ≠ Issue.**

**Not every clash becomes an Issue.** Many findings are tolerable, duplicated, out
of scope, already known, or artefacts of the test setup. Creating an Issue is a
decision taken at triage, not an automatic consequence of detection (BEP 8.7).

## 13. Finding triage

A finding may be dispositioned as:

| Outcome | Meaning |
|---|---|
| **No action / false positive** | Not a real coordination matter for the defined check |
| **Accepted condition** | Requires no further action **for the defined check and coordination purpose** |
| **Action required — one task team** | A single team must respond |
| **Action required — multiple task teams** | More than one team must respond |
| **Decision required** | A technical or governance decision is needed before action |
| **Deferred** | Carried forward, with a recorded reason |
| **Escalated** | Raised beyond the normal cycle (section 23) |

**"Accepted condition" does not mean recipient acceptance or design approval.**
It means only that the coordination finding requires no further action for the
defined check and purpose. It is a coordination disposition and nothing more
(BEP 9.2, 9.8).

**Material dispositions remain traceable.** A finding closed without record is a
finding that will be rediscovered.

## 14. Issue taxonomy

**PROPOSED governance concepts:**

| Type |
|---|
| Clash / Physical Conflict |
| Clearance / Access |
| Spatial Interface |
| Alignment / Reference |
| Missing / Incomplete Information |
| Multidisciplinary Design Decision |
| Coordination Configuration / Process |

**These are not Autodesk system-native labels**, and no claim is made that the
platform provides them. The platform may later map its available fields and
statuses to these governance concepts — that mapping is an implementation
decision, not yet made.

## 15. Issue status model

**Governance status model:**

```
New
  → Triaged
  → Assigned
  → In Progress
  → Ready for Verification
  → Closed
```

**Controlled alternate dispositions:** **Deferred** and **Escalated**.

**Platform implementation may use different native labels.** The governed meaning
is what matters; a native label is a rendering of it, not a replacement for it.

**This status model is not claimed to be configured in Forma.** Configuring it
would follow a governance decision, which has not been taken (BEP 12.1).

## 16. Issue assignment

An assignment identifies:

- the affected interface;
- the responsible task team or function;
- the required action or outcome;
- context and evidence;
- priority or impact **where established**;
- status;
- a target trigger **only where genuinely established**.

**No dates are invented.** Where no target is established, the field records that
rather than a plausible value.

**The BIM Coordinator coordinates assignment. The originating or affected
Task-Team Lead owns the technical response of its team.**

**An Issue assigned to a task team does not make the BIM Coordinator responsible
for designing the fix.** Coordinating an assignment and owning a solution are
different things.

**No actual Issue identifiers are created here.**

## 17. Coordination cycle

```
controlled Shared inputs
  → readiness check
  → federation
  → coordination checks
  → findings
  → triage
  → create / assign Issues where required
  → originating task-team WIP correction
  → task-team check
  → authorise controlled reshare
  → Shared
  → re-coordinate
  → verify
  → close / disposition
  → retain evidence
```

**Mapping to the Information Delivery Schedule events:**

| Event | Role in this cycle |
|---|---|
| **TRN-E01** | The initial / proposed coordination share — establishes the coordination input set |
| **TRN-E02** | **Conditional** reshare, activating **only for affected containers** |
| **TRN-E03** | A **separate** project-facing delivery / review event — **not** part of the normal coordination reshare cycle, and currently **blocked** pending unresolved publication and acceptance authorities |

**A coordination cycle may activate one TRN-E02 template row, several, or none.**
Nothing here implies all six disciplines reshare every cycle.

## 18. Technical resolution

**Technical resolution occurs in the originating task team's WIP.**

| Example | Response |
|---|---|
| Mechanical conflict | The Mechanical task team evaluates and modifies **MEC-01** if required |
| Structural response | The Structural task team modifies **STR-01** if required |

**The BIM Coordinator may facilitate agreement between teams but does not author
a discipline solution merely because they chair coordination.**

**Where multiple task teams must change, each remains responsible for its own
information.** A jointly-agreed resolution is still a set of separate changes
under separate responsibility.

## 19. Verification

Verification occurs **after** the corrected information has been:

- checked;
- authorised for reshare;
- returned to **Shared**;
- included in re-coordination.

Verify that the defined coordination matter:

- no longer exists; **or**
- meets the agreed coordination rule; **or**
- has an explicitly approved and recorded disposition.

**Verification does not equal** design approval, professional certification,
publication authority, or recipient acceptance (BEP 8.10, 9.5).

**A material Issue is not closed solely because someone says it was fixed in
WIP.** Closure follows re-coordination against reshared, controlled information —
a change nobody can see in Shared information has not been demonstrated.

## 20. Meetings and communication

**No meeting frequency is prescribed.**

A coordination meeting may review current input readiness; unresolved
interfaces; high-impact findings; assigned Issues; blockers; pending
verification; required decisions; and escalations.

Meeting output may include decisions; actions; owners or functions; Issue
references; and required next-cycle inputs.

**Operational and model actions remain linked to the governed Issue record** where
appropriate. **Governance decisions belong in the Governance & Decision
Register.**

**A meeting is not an authoritative Issue or governance database**, and reliance
on undocumented verbal decisions is not acceptable — a decision nobody can
produce afterwards did not happen (BEP 8.9).

## 21. Coordination completion

**Completion is not "zero clashes."** A zero-clash report can be produced by
testing nothing, excluding everything, or resolving symptoms rather than
interfaces.

For a defined coordination cycle, completion means, as applicable:

- required inputs were identified;
- required readiness checks were performed;
- required coordination checks were performed;
- material findings were triaged;
- required Issues were created and assigned;
- required resolutions or dispositions were recorded;
- required verification was completed;
- unresolved matters were explicitly carried forward or escalated;
- coordination evidence was retained.

**Completion is cycle-specific and purpose-specific.** It does **not** mean the
entire design is complete, technically approved, construction-ready, or accepted
by the project.

## 22. Coordination outputs and evidence

| Output |
|---|
| Coordination input register |
| COORD-01 federation / reference |
| Check execution record |
| Clash / finding record |
| Issue records and history |
| Meeting decisions and actions |
| Verification record |
| Unresolved / escalated matter list |
| Cycle summary and status |

**No duplicate record is required where an existing controlled platform record
already provides adequate evidence.**

**A coordination report summarises governed evidence; it does not become a second
Issue database.** Two records of the same Issue eventually become two different
records of the same Issue.

## 23. Exceptions and escalation

**Escalation triggers may include:** an unresolved multidisciplinary interface;
conflicting technical decisions; missing information blocking coordination; a
repeatedly unresolved Issue; a coordinate or reference problem affecting multiple
teams; a configuration or platform blocker; unclear decision authority; an issue
affecting delivery readiness.

**Each escalation records:**

| Field |
|---|
| The matter |
| Affected teams |
| Impact |
| Decision required |
| Decision function / owner **where established** |
| Next step / status |

**No owner is invented where none is established.** "Decision owner: not
established" is a valid and useful entry.

**Governance-level escalations link to the Governance & Decision Register.**

## 24. Relationship to the CDE Workflow & State Strategy

| Resource | Governs |
|---|---|
| **CDE Workflow & State Strategy** | Information states and transitions |
| **This strategy** | What happens when suitable Shared information is used for multidisciplinary coordination |

**Coordination does not create a new CDE information state.**

Shared information can be consumed, become coordination input, and be reviewed —
**while remaining in the Shared state**. Coordination input is a *use and
context*, not a state (CDE strategy section 3).

**Rework returns affected information to the originating task team's WIP.
Controlled reshare returns revised information to Shared.** Those are the only
state transitions in the coordination cycle.

## 25. Relationship to other supporting resources

| Resource | Holds |
|---|---|
| `information-management-responsibility-matrix.md` | Who performs coordination-related process functions |
| `model-information-responsibility-matrix.md` | Which task team owns and originates each information class |
| `information-delivery-schedule.md` | TRN-E01 / E02 / E03 exchange logic |
| `cde-workflow-state-strategy.md` | State transitions surrounding coordination |
| `governance-decision-register.md` | Unresolved decisions, changes, exceptions and governance history |

Content of these resources is referenced, not duplicated. Each is separately
controlled and declares its own status; reference here does not constitute
approval of it.

## 26. Current unresolved coordination matters

Existing matters, referenced rather than renumbered. **No new decision ID is
created.**

| Matter | Status |
|---|---|
| **UD-001** — MEP / Structural team-space mapping | **UNRESOLVED** |
| Coordination Space — no Design Collaboration Coordination Space observed configured (OF-005) | **Intended configuration not yet approved** |
| Numeric clash and clearance tolerances | **TBD** |
| Issue taxonomy and status platform mapping | **Not yet implemented** |
| Coordination-cycle frequency | **Not established** |
| Coordination completion evidence format | **PROPOSED — to be validated** |
| Coordinate reference basis for coordinated model use (BEP 11.5) | **Candidate context only, not approved** |

**None of these is resolved by this strategy.**

## 27. Worked training example

An **educational workflow example only**. It illustrates the governed sequence.
It does **not** describe an actual condition on the project.

**Scenario.** A mechanical service route conflicts with structural information —
**STR-01** versus **MEC-01**.

| Step | What happens |
|---|---|
| 1 | **TRN-E01** — STR-01 and MEC-01 are shared by their own task teams and used as **Shared** coordination inputs |
| 2 | Readiness confirmed; both included in the input register; COORD-01 federated |
| 3 | Check **CI-02** (STR ↔ MEC) executed; a **finding** is identified |
| 4 | **Triage** determines action is required — the finding becomes a managed **Issue** |
| 5 | Issue assigned to the relevant task team or teams by the BIM Coordinator |
| 6 | **MEC and/or STR technical response occurs in their own WIP** — each team owns its own change |
| 7 | Task-team **check** of the revised information |
| 8 | The affected **TRN-E02 template row or rows activate** — only for containers that actually changed |
| 9 | Task-Team Lead authorises **controlled reshare**; revised information returns to **Shared** |
| 10 | **Re-coordinate** |
| 11 | BIM Coordinator **verifies** the coordination disposition |
| 12 | Issue **closes** if the criteria are met; otherwise it remains open |

**Nothing invented.** This example contains no actual project geometry, no clash
coordinates, no Issue identifier, no tolerance value, and no named person. If
only MEC-01 changes, **TRN-E02-MEC activates and TRN-E02-STR does not.**

**Verification at step 11 is not design approval.** It confirms the coordination
process reached a disposition against reshared controlled information — nothing
about the technical adequacy of the design solution.
