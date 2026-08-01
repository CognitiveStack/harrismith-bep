# Information Management Responsibility Matrix

## Document purpose and status

**Purpose.** Allocates information-management **functions** to **roles** across
the process steps defined by the BEP.

This matrix answers one question: **who performs which information-management
function?**

It does **not** answer:

- which organisation authors each specific model or information container —
  that is the Model / Information Responsibility Matrix;
- what is delivered at each milestone — that is the Information Delivery
  Schedule;
- which individual person currently holds each role — no role holder is
  established.

Referenced by BEP section 5.12.

| Field | Value |
|---|---|
| Document status | **APPROVED WITH CONDITIONS — Training Baseline 0.1** |
| Authority | Supporting management resource under the Harrismith BEP framework |
| Approval | **Approved with conditions** through **AD-001**, 2026-08-01. Conditions remain active; **publication remains NOT AUTHORISED** |
| Supports | BEP section 5 — Information Management Roles and Responsibilities |

**Population rule.** This matrix allocates functions to **functional roles**, not
to companies or people. No organisation is appointed and no individual is named.
Allocations are **functional governance proposals** unless the BEP already
expressly establishes the allocation. Where the BEP records an authority as
unresolved, this matrix records it as unresolved rather than filling it with a
plausible role.

**Meaning is defined once, allocation is recorded once.** BEP Section 5 defines
what each function *means*. This matrix records *how those functions are
allocated*. Definitions are not duplicated here (BEP 5.12).

---

## 1. Responsibility grammar

The approved grammar, and the only terms used in this matrix (BEP 5.12):

| Code | Term | Meaning |
|---|---|---|
| **P** | Perform | Carries out the activity |
| **Ck** | Check | Verifies against a defined requirement |
| **Au** | Authorise | Permits progression, for a defined purpose |
| **Co** | Coordinate | Organises across parties or task teams |
| **Ac** | Accept | Receives for an identified purpose |
| **Cs** | Consult | Is asked before the act |
| **In** | Inform | Is told after the act |

Additional cell values:

| Value | Meaning |
|---|---|
| **TBD** | Allocation unresolved. The BEP records this authority as not established. |
| **—** | The role holds no function in this activity. |

**RACI is not adopted.** This grammar is used instead, because it distinguishes
checking from authorising and coordinating from performing — distinctions this
BEP depends on and RACI collapses. RACI is not to be introduced unless
explicitly approved later (BEP 5.12).

**Verification is recorded as Check.** Where the BEP requires verification —
coordination resolution, implementation after change — the grammar term is
**Ck**, since verification is checking against a defined requirement.

## 2. Roles

Functional roles only. No holder is established for any of them.

| Column | Role | Holder |
|---|---|---|
| **AP** | Owner / Appointing Party | **Not established — TBD** (BEP 2.3, 5.3) |
| **LDP** | Lead Delivery Party | **Not established — TBD** (BEP 5.4) |
| **BM** | BIM Manager | **TBD** (BEP 5.5) |
| **BC** | BIM Coordinator | **TBD** (BEP 5.6) |
| **TTL** | Task-Team Lead | **TBD** for every task team (BEP 5.7) |
| **Aut** | Author | **TBD** (BEP 5.8) |
| **Chk** | Checker | **TBD** (BEP 5.8) |
| **CDE** | CDE Administration | **TBD** (BEP 5.9) |
| **Rcp** | Receiving / recipient function | Depends on the exchange; **not established** (BEP 9.8, 10.11) |

`Rcp` is a generic function, not an organisation. It represents whoever receives
a given exchange under the approved delivery arrangement, which does not yet
exist.

---

## 3. Responsibility matrix

Legend: **P** Perform · **Ck** Check · **Au** Authorise · **Co** Coordinate ·
**Ac** Accept · **Cs** Consult · **In** Inform · **TBD** unresolved · **—** none.

### 3.1 Governance

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| G1 | Maintain the BEP governance framework | Cs | Cs | P | Cs | Cs | — | — | — | — |
| G2 | Manage governance decisions and the change process | Cs | Cs | P Co | Cs | Cs | — | — | In | — |
| G3 | Maintain the IM responsibility architecture | Cs | Cs | P | Cs | Cs | In | In | In | — |
| G4 | Maintain and coordinate project information standards | Cs | Cs | Co | Cs | P Cs | Cs | Cs | In | — |
| G5 | Provide BIM onboarding and capability support | In | In | P | Cs | Cs | In | In | Cs | — |

### 3.2 Common Data Environment

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| C1 | Define the CDE governance strategy | Cs | Cs | P | Cs | Cs | — | — | Cs | — |
| C2 | Implement approved CDE configuration | — | In | Cs | Cs | In | In | — | P | — |
| C3 | Administer access and permissions | — | In | Cs | Cs | Cs | In | In | P | — |
| C4 | Verify platform configuration after approved change | — | In | Ck | Cs | In | — | — | P Ck | — |

**C2/C3 note.** CDE Administration **implements** approved governance; it does
not create governance by changing the software. Platform permission is not
authority to share, publish or accept (BEP 5.9, 6.9).

### 3.3 Information production

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| P1 | Author information in WIP | — | — | — | — | Co | **P** | — | — | — |
| P2 | Perform task-team technical / content check | — | — | — | — | Co Ck | Cs | **Ck** | — | — |
| P3 | Perform information-quality / readiness check | — | — | Cs | Cs | Co | Cs | **Ck** | — | — |
| P4 | Authorise WIP information for controlled sharing | — | — | — | In | **Au** | — | Cs | — | — |

**P1/P4 note.** An Author does **not** self-authorise merely because they
authored the information. Authorisation to share is a separate decision held by
the Task-Team Lead, or another role expressly allocated it by approved governance
(BEP 5.8, 9.4).

**P2/P3 note.** **Check is not Authorise.** Checking confirms readiness for the
next controlled decision; it does not permit progression (BEP 9.3).

### 3.4 Sharing and consumption

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| S1 | Execute controlled share | — | In | — | In | Co | P | — | — | In |
| S2 | Review received Shared information | — | — | — | Cs | Co | P | Ck | — | — |
| S3 | Consume / reference Shared information for a stated purpose | — | — | — | In | **Au** | P | — | — | — |

**S3 note.** Availability is not consumption, and consumption does not transfer
technical ownership. The receiving team decides to adopt; the originating team
remains responsible for the content it produced (BEP 6.5, 7.9).

### 3.5 Coordination

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| X1 | Organise coordination inputs | — | In | — | **P Co** | Co | Cs | — | — | — |
| X2 | Perform / manage the multidisciplinary coordination process | — | In | Cs | **P Co** | Cs | Cs | — | — | — |
| X3 | Resolve technical coordination issue | — | — | — | Co | **P** | **P** | Ck | — | — |
| X4 | Verify coordination resolution / process disposition | — | In | Cs | **Ck** | Cs | — | — | — | — |
| X5 | Escalate unresolved multidisciplinary interfaces | Cs | Cs | Co | **P** | Cs | — | — | — | — |

**X3/X4 note.** The BIM Coordinator does **not** own the technical design
solution and does **not** hold design-approval authority. Resolution is performed
by the originating task team. Coordinator verification confirms the coordination
process reached a disposition — it is **not** discipline design approval,
professional certification, or acceptance of technical responsibility (BEP 5.6,
8.10, 9.5).

### 3.6 Delivery and exchange

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| D1 | Coordinate task-team delivery commitments | — | Co | Cs | Cs | **P** | Cs | — | — | — |
| D2 | Coordinate project-level delivery planning | Cs | **P Co** | Cs | Cs | Cs | — | — | — | Cs |
| D3 | Perform delivery readiness review | — | Co | Cs | Cs | **P Ck** | Cs | Ck | — | — |
| D4 | Authorise publication / exchange | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** | — | — | — | — |
| D5 | Execute controlled transmission | — | Co | — | — | P | Cs | — | Cs | In |
| D6 | Receive exchange | — | In | — | In | In | — | — | — | **P** |
| D7 | Accept exchange for a stated purpose | **TBD** | — | — | — | — | — | — | — | **TBD Ac** |

**D4 — publication / exchange authorisation is UNRESOLVED.** The BEP records
that the role holding this authority depends on the approved delivery
arrangement, which does not yet exist. It is **not** automatically held by the
BIM Manager, the BIM Coordinator, the CDE Administrator, the Architect or the
Lead Delivery Party. No allocation is made here (BEP 9.7).

**D7 — acceptance authority is UNRESOLVED.** Acceptance is exercised by the
recipient function for the identified purpose, under the approved delivery
arrangement. No appointing party is established, and no accepting authority is
invented. Acceptance does **not** transfer technical responsibility from the
originator (BEP 9.8, 10.11).

**D5/D6 note.** A transmission record is not the information, and a transmittal
is not technical approval. Published, Delivered, Received and Accepted are four
distinct states (BEP 10.10, 10.11).

### 3.7 Change and assurance

| # | Information-management function | AP | LDP | BM | BC | TTL | Aut | Chk | CDE | Rcp |
|---|---|---|---|---|---|---|---|---|---|---|
| A1 | Assess governance change | Cs | Cs | **P Co** | Cs | Cs | — | — | Cs | — |
| A2 | Authorise governance change | **TBD** | **TBD** | **TBD** | — | **TBD** | — | — | — | — |
| A3 | Implement approved change | — | In | Co | In | Co | In | — | **P** | — |
| A4 | Verify implementation | — | In | **Ck** | Cs | Cs | — | Ck | Ck | — |
| A5 | Retain decision and change evidence | — | In | **P** | Cs | Cs | — | — | Cs | — |

**A2 — authority depends on the class of change.** The BEP defines three
conceptual levels — minor operational change, governance change, and major
delivery / governance change — and requires that the authority correspond to the
nature of the decision. **No single universal approver exists**, and unlimited
authority is not assigned to the BIM Manager. The authority for each class
remains TBD (BEP 12.7).

**A4 note.** No single universal verifier is defined; the verifying role varies
by change type. A change is not complete because a document was edited or a
setting was clicked (BEP 12.9).

---

## 4. Role principles preserved

| Role | Holds | Does not hold |
|---|---|---|
| **BIM Manager** | Governance framework, BEP and CDE strategy, standards architecture, responsibility architecture, governance change, onboarding, assurance | Design approval; publication authority; contractual decisions; Appointing Party or Lead Delivery Party function |
| **BIM Coordinator** | Coordination process, input organisation, finding and issue triage, resolution monitoring, coordination verification, escalation | Ownership of the technical design solution; design-approval authority |
| **Task-Team Lead** | Team production and readiness, required checking, authorisation to share where allocated, technical and interface responsibility for the team | Project-level delivery authority; publication authority |
| **Author** | Produces and modifies information | Self-authorisation of own work |
| **Checker** | Performs the defined check | Authorisation — checking is not authorising |
| **CDE Administration** | Implements approved platform governance | Creation of governance; permission is not authority |
| **Lead Delivery Party** | Project-level delivery coordination across task teams | Automatic combination with the BIM Manager function; holder **TBD** |
| **Owner / Appointing Party** | High-level information needs and outcomes; receipt and acceptance functions where established | Any established identity — **TBD** |

## 5. Role combination and independence

**One participant may hold more than one role** in this training implementation
(BEP 5.11, 9.12).

This matrix allocates **functions to roles**. It does **not** demonstrate that
separate people perform them, and it must not be read as evidence of
independence.

Where Author and Checker are combined:

- the functional distinction remains — a self-check is still a checking act
  against a defined requirement;
- the combination is **recorded**, so the independence limitation is visible in
  the evidence;
- independence is **never claimed where it does not exist**. Fictional
  independence is worse than an acknowledged limitation, because it removes the
  reader's ability to weigh the information.

## 6. Unresolved allocations

| Ref | Unresolved matter | BEP reference |
|---|---|---|
| D4 | Publication / exchange authorisation authority | 9.7 |
| D7 | Recipient acceptance authority | 9.8, 10.11 |
| A2 | Governance change approval authority, by change class | 12.7 |
| — | Owner / Appointing Party identity | 2.3, 5.3 |
| — | Lead Delivery Party holder | 5.4, 10.6 |
| — | BIM Manager, BIM Coordinator, CDE Administration holders | 5.5, 5.6, 5.9 |
| — | Task-Team Lead holders, every task team | 5.7 |

These are recorded as unresolved in the Governance & Decision Register and are
resolved only by explicit recorded decision. None is resolved here.

## 7. Relationship to other resources

| Resource | Answers |
|---|---|
| **This matrix** | Who performs, checks, authorises, coordinates and accepts information-management process functions |
| `model-information-responsibility-matrix.md` | Who produces which information containers |
| `information-delivery-schedule.md` | What is delivered, when, to whom, why and in what form |

The Model / Information Responsibility Matrix and the Information Delivery
Schedule are **separately controlled supporting resources**. Each declares its
own current status, version and authority. Reference from this matrix does not
by itself constitute approval of either resource or of its content.

Their content is not duplicated or anticipated here.
