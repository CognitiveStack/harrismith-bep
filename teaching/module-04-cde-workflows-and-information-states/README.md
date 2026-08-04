# Module 4 — CDE Workflows and Information States

**Status:** Active module. Structure, source inventory and **Slides 1–11**
baseline. **Not governance, and not a complete module.**

---

## 1. Objective

Enable a multidisciplinary audience to understand what a Common Data Environment
actually controls — and why **being able to move a file is not the same as being
authorised to change its state**.

| # | The audience should understand |
|---|---|
| 1 | What a Common Data Environment is |
| 2 | Why a CDE is a **governed process supported by technology** |
| 3 | **Why a folder tree is not, by itself, a CDE** |
| 4 | Why information states represent permitted purpose and use |
| 5 | The difference between **state, version, revision, status and suitability** |
| 6 | How information moves between states |
| 7 | **Why movement is not automatically an authorised transition** |
| 8 | Who performs, checks and authorises transitions |
| 9 | What evidence is required before and after a transition |
| 10 | Why WIP, Shared, Published / Authorised and Record / Retained are distinct |
| 11 | **Why Shared is not Published** |
| 12 | **Why Published is not Delivered** |
| 13 | **Why Delivered is not Received** |
| 14 | **Why Received is not Accepted** |
| 15 | How naming, revision, suitability and metadata support state control |
| 16 | **Why access permissions implement governance rather than create it** |
| 17 | **Why blocked or unresolved transitions must remain visible** |
| 18 | How the planned model differs from verified live implementation |
| 19 | What a future Triviron project must define before configuring a platform |

Items 3, 7, 16 and 17 are the four the audience is most likely to get wrong, and
the module is structured around defeating them.

## 2. Central teaching statement

> A CDE is a governed process in which information moves between defined states
> only when the required purpose, authority, checks and evidence have been
> established.

**Teaching synthesis.** No controlled source contains this sentence. It is
consistent with `S1` §6.1 and §6.3 and with `S2`'s purpose statement — see
[`source-map.md`](source-map.md) §4.

## 3. The core conceptual distinction

```text
File movement
  ≠
authorised information-state transition
```

A user may be technically able to **upload, move, copy, rename, download,
publish or change permissions**. That technical ability establishes **none** of:

| Not established by technical ability |
|---|
| Professional authority |
| Transition authority |
| Suitability |
| Approval |
| Publication authority |
| Acceptance authority |

**Three controlled sources say this independently**, which is why it is the
module's spine:

> *"**Movement or placement between platform areas must not be treated as
> sufficient evidence of a WIP-to-Shared, Shared-to-Published or other
> information-state transition.**"* — `CGD-C03`

> *"**Being able to perform an action in the software says nothing about who was
> authorised to decide it.**"* — `S4` §9

> *"**Permission ≠ authority.**"* — `S2` §14

## 4. Primary deliverable

A **20-minute presentation**, using Harrismith as the worked example.

| Field | Value |
|---|---|
| Length | 20 minutes |
| Slide count | 14 |
| Worked example | Harrismith Fire Station |
| Transfer context | A future Triviron multidisciplinary project |
| Current state | **Structure, source inventory and Slides 1–11 baseline.** Module not complete |

**This presentation does not exist yet.** What exists after T4-A, T4-B and T4-C:

| Established | Outstanding |
|---|---|
| Module structure (T4-A) | **Slides 12–14** |
| **Source inventory** — exact paths, precedence, registers (T4-A) | Visual source set |
| Terminology register, with variance recorded (T4-A) | Assembly package |
| **Transition register** — all eight steps verified (T4-A) | PowerPoint |
| Implementation-status register (T4-A) | Review |
| 20-minute, fourteen-slide architecture (T4-A) | Rehearsal and measured timing |
| **Slides 1–3** (T4-A) | |
| **Slides 4–7 — Section B, the four states** (T4-B) | |
| **State register** — every state's wording, boundaries and status (T4-B) | |
| Visual specifications `W4`–`W7` (T4-B) | |
| **Slides 8–11 — Section C, the transition workflow** (T4-C) | |
| **Expanded transition register** — seventeen fields, `T1`–`T8` (T4-C) | |
| Visual specifications `W8`–`W11` (T4-C) | |

## 5. What makes this module different

**Module 4 returns to repository-only evidence.** Module 3's subject was a
copyrighted standard the programme does not hold; **Module 4's subject is
entirely controlled Harrismith material**, and every statement traces to a
document in this repository.

**But it introduces a new hazard.** Module 4 teaches a workflow that is
**proposed, not operating**. `S2` says so on its own first page:

> *"The workflow defined here is **PROPOSED GOVERNANCE**… **This strategy does
> not describe the live platform.** It is **not** evidence that the current
> Autodesk configuration matches it."*

**Three consequences shape every file in this module:**

1. **Governance status and implementation status are separate, and both are
   stated.** A concept can be approved governance and still unimplemented.
2. **Blocked routes stay blocked.** Publication authority is unresolved;
   `T4` has no available authorising function; `TRN-E03` is blocked on five
   matters. **None of these is completed to tidy a diagram.**
3. **A missing verification is not a failure claim.** `S4`: *"Absence of
   observation is not observation of absence."*

## 6. Source precedence

| Level | Source class |
|---|---|
| **1** | Approved Harrismith governance documents — `S1` |
| **2** | Approved supporting schedules, matrices and strategies — `S2`, `S5`–`S9` |
| **3** | Controlled decision or validation records — `S3`, `S4` |
| **4** | Completed teaching-source interpretation from Modules 1–3 |
| **5** | Teaching synthesis |

**A teaching statement never silently overrides a controlled project source.**
Where controlled documents differ, the difference is **recorded**; where one
explicitly governs, that is stated; otherwise the matter is **unresolved**.
**Nothing is harmonised by invention** — see
[`source-inventory.md`](source-inventory.md) §6.

## 7. Governance and implementation status classes

Every major workflow concept carries one:

| Class | Meaning |
|---|---|
| **`CONTROLLED GOVERNANCE`** | Approved and governing |
| **`PROPOSED GOVERNANCE`** | Developed and classified as proposed — the status of `S2`'s workflow |
| **`PLANNED`** | Recorded as intended |
| **`CONDITIONALLY AVAILABLE`** | Available where a stated condition is met |
| **`BLOCKED`** | Cannot proceed; a required authority or input is unresolved |
| **`UNRESOLVED`** | Open matter, recorded as open |
| **`IMPLEMENTATION UNVERIFIED`** | Not checked against intended governance |
| **`LIVE IMPLEMENTATION VERIFIED`** | **Only where controlled evidence explicitly supports it** |

**`LIVE IMPLEMENTATION VERIFIED` is used sparingly and only from `S4`.**

## 8. Scope

**In scope:**

- what a CDE controls, and why it is not a folder tree;
- the four Harrismith information states and their permitted reliance;
- the eight controlled steps `T1`–`T8`, and **which two are state transitions**;
- gates, authority and evidence at a transition;
- why `Shared → Published` is blocked, and why the block is correct;
- state, version, revision, status, suitability and metadata **as distinct
  properties**;
- why governance precedes permissions and configuration;
- what Triviron must define before configuring a platform.

**Out of scope for Module 4:**

| Out of scope | Belongs to |
|---|---|
| Responsibility-matrix construction; matrix-cell grammar | **Module 5** |
| Information-delivery-schedule construction; appointment-level delivery planning | **Module 5** |
| Coordination cycles, clash triage, issue escalation, technical review | **Module 6** |
| Assurance sampling, design approval | **Module 6** |
| Triviron BEP development | Module 7 |
| Workshop facilitation | Module 8 |
| **Any coding standard** | **No module** — **none exists** (`S12`) |

**Module-boundary rule.** Module 4 explains **what a control is and why it
exists**. References to a matrix cell or a coordination cycle may explain a
transition **gate**; the detailed teaching stays deferred.

## 9. Relationship to Modules 1–3

Three positions carried forward and **not re-derived**:

| Carried forward | From |
|---|---|
| The BEP records the agreed method | Module 1 |
| Author performs · Checker checks · Task-Team Lead authorises controlled sharing · **publication and acceptance authority remain unresolved** | Module 2 |
| Principles become project-specific governance, then configuration, then evidence | Module 3, Slide 12 |

**Module 3 deliberately deferred this module's subject.** Its `source-map.md`
§9.9 records the deferral: CDE state mechanics, transitions and transition
authority, evidence requirements and conditions, naming and suitability coding,
metadata, folder workflows and the complete state diagram. **Module 4 picks up
exactly where Module 3's Slide 10 stopped.**

## 10. Honesty constraints on delivery

Four things must be said, or the module misrepresents its example:

1. **This workflow is proposed, not operating.** `S2` classifies itself
   `PROPOSED GOVERNANCE` and states it does not describe the live platform.
2. **`Shared → Published` cannot proceed.** Publication authority is
   **unresolved**; `T4` has **no available authorising function**; information
   **remains Shared**.
3. **There is no `04 Archive` folder, and none is required.** Record / Retained
   is a **conceptual state and a retention requirement**; the retention approach
   is **TBD**.
4. **No naming standard, coordinates standard, metadata schema or suitability
   code set exists.** All four `standards/` directories are empty.

**And the counterweight, which matters as much:** a framework that records what
it has not resolved, and stops a route it cannot authorise, is **working
correctly**. `S2` §19: *"Each is recorded so the gap stays visible rather than
being filled with a plausible value."*

## 11. Module files

| File | Holds |
|---|---|
| [`source-inventory.md`](source-inventory.md) | **Exact source paths**, precedence, source-authority register, terminology register and variance, folder topology, **transition register**, implementation-status register, unresolved matters |
| [`presentation-outline.md`](presentation-outline.md) | The 20-minute structure and Slides 1–3 |
| [`speaker-notes.md`](speaker-notes.md) | Delivery notes for Slides 1–3 |
| [`visual-demonstration-plan.md`](visual-demonstration-plan.md) | Candidate visuals for all fourteen slides |
| [`exercises.md`](exercises.md) | Practice and self-assessment |
| [`source-map.md`](source-map.md) | Statement classification, the four registers and the **prohibited-claims list** |

[`source-inventory.md`](source-inventory.md) is the load-bearing file in this
increment. It records what each source actually says, where the sources differ,
and what remains unresolved.

## 12. Status

| Field | Value |
|---|---|
| Module 4 | **CURRENT — ACTIVE**, not complete |
| Structure | **Established (T4-A)** |
| Source inventory | **Complete (T4-A)** |
| Statements classified | **189** across Slides 1–11 — [`source-map.md`](source-map.md) §5 |
| Registers | **5** — source authority · **state** · terminology · transition · unresolved |
| Prohibited claims | **75** — [`source-map.md`](source-map.md) §9, §9.1–§9.3 |
| Visual specifications | **`W4`–`W11` complete**; `W1`, `W2`, `W3`, `W12`, `W13`, `W14` remain candidates |
| Slides developed | **1–11** — Sections A (T4-A), B (T4-B) and C (T4-C) |
| Slides outstanding | **12–14** |
| Visual source | **None** |
| Assembly package | **None** |
| PowerPoint | **None** |
| Review and rehearsal | **Outstanding** |
| Modules 1–3 | Content, visual source, assembly package and PowerPoint produced; **review and rehearsal deferred** |
| Module 2 README correction | **Deferred** |
| Publication automation | **PAUSED** |
