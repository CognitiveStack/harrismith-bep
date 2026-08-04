# Module 4 — Visual Demonstration Plan

**Status:** Candidate visuals for the whole Module 4 presentation. **No visual
source file and no rendered image asset exists.** Nothing here is a final asset,
and creating assets is a later increment.

**`W4`–`W7` — the Section B state visuals — are now specified in full** (T4-B).
The remaining ten are candidates at the level established in T4-A.

Source identifiers `S1`–`S14` are defined in
[`source-inventory.md`](source-inventory.md). Classification follows
[`source-map.md`](source-map.md) §1.

---

## 1. Two rules that govern every entry

### 1.1 Governance status and implementation status are both shown

**Every visual that depicts a control must make clear whether it is governed,
proposed, blocked or unverified.** `S2` classifies its own workflow as
**`PROPOSED GOVERNANCE`** and states it **does not describe the live platform**.

A visual that shows a workflow without its status **asserts an operating system
that has not been verified**.

### 1.2 Nothing that is blocked, empty or unresolved is completed

Five things stay visibly incomplete throughout the module:

| | Stays | Because |
|---|---|---|
| **`Shared → Published`** | **Broken** | `T4` has **no available authorising function**; information **remains Shared** |
| **`TRN-E03`** | **Blocked** | **PROPOSED — BLOCKED**, on five matters |
| **Record / Retained** | **Not a folder** | **No `04 Archive` root is approved or required** |
| **Publication and acceptance authority** | **Unheld** | `S4` §9 — **no evidence established** |
| **Code sets and metadata schema** | **Absent** | All four `standards/` directories are empty |

**A producer who completes any of these introduces the module's most misleading
claims.**

## 2. Mermaid caution

**Mermaid is used only where it cannot misrepresent the model.** It is
**avoided** where it would:

| Risk | Affected visuals |
|---|---|
| **Auto-complete a blocked route** | `W3`, `W9`, `W11` |
| Imply hierarchy where none exists | `W1`, `W13` |
| Imply that states progress automatically | `W3`, `W9` |
| **Hide evidence fields** | `W10` |
| Convert a conceptual model into an operating workflow | `W3`, `W9`, `W11` |
| Arrange non-sequential properties as a sequence | `W2` |

**A native-layout specification is preferable wherever deliberate incompleteness
matters** — and in this module it matters on more visuals than not.

## 3. How to read this plan

| Field | Meaning |
|---|---|
| **Slide** | Where it is used |
| **Teaching purpose** | The one thing the audience should take from it |
| **Source basis** | The `S`-identifiers behind it |
| **Classification** | Per [`source-map.md`](source-map.md) §1 |
| **Governance status** | Controlled · proposed · planned · blocked · unresolved |
| **Implementation status** | Verified · unverified · not reached |
| **Simplify** | What must be compressed |
| **Omit** | What must not reach the slide |
| **Overclaim risk** | The risk of asserting more than the sources support |
| **Blocked element visible?** | Whether something must stay incomplete |
| **Live evidence required?** | Whether a platform observation would be needed |
| **External imagery** | Whether an external image would add value |

**On live evidence.** The answer is **no** for every visual. `S4` is an
**existing controlled record**, read as evidence. **No new observation is
requested, and none is authorised** — root [`README.md`](../../README.md) §2.1
applies unmodified.

**On external imagery.** **No** for every visual. A platform screenshot would
assert implementation this module cannot evidence.

---

## 4. Candidate visuals

### W1 — Governance → workflow → platform

| Field | Value |
|---|---|
| **Slide** | 1 |
| **Teaching purpose** | Show three ordered layers, with **governance above configuration** |
| **Source basis** | `S1` §6.1, §12.1; `S2` §17; **`CGD-C07`** |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Governance status** | **Controlled** (`S1` §6.1) · the workflow layer is **proposed** |
| **Implementation status** | Platform layer **unverified** |
| **Simplify** | **Three stacked bands**, top to bottom. Four items maximum per band |
| **Omit** | **Any platform logo or screenshot. Any equals sign between CDE and platform.** Any suggestion that purchasing software creates the process. Any claim of live implementation |
| **Overclaim risk** | **HIGH** — three tidy bands read as *this is how it runs* |
| **Blocked element visible?** | No — but the **proposed** and **unverified** labels are mandatory |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
GOVERNANCE AND AUTHORITY          ← controlled (S1)
        ↓  decides
CDE WORKFLOW AND INFORMATION STATES   ← PROPOSED GOVERNANCE (S2)
        ↓  is implemented by
PLATFORM, FOLDERS, PERMISSIONS, METADATA   ← IMPLEMENTATION UNVERIFIED
```

**Four mandatory design requirements.**

1. **Governance appears above configuration.** The vertical order is the content.
2. **Arrows point downward only.** A return arrow asserts that configuration
   changes governance — the exact failure `S2` §17 rule 1 exists to prevent.
3. **Each band carries its status label** — controlled · proposed · unverified.
4. **No hierarchy of people.** These are layers of decision, not an org chart.

### W2 — The five-property comparison

| Field | Value |
|---|---|
| **Slide** | 2 |
| **Teaching purpose** | Show five properties answering five different governance questions |
| **Source basis** | `S1` §6.8; `S2` §13 |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Governance status** | **Controlled** — definitions. **Unresolved** — every code set |
| **Implementation status** | — |
| **Simplify** | **Five equal cards or columns**, one question each |
| **Omit** | **Any arrow between the cards. Any maturity ordering. Any revision, status or suitability code** |
| **Overclaim risk** | **MEDIUM-HIGH** — five cards in a row read as five stages |
| **Blocked element visible?** | The **absent code sets** must be visible |
| **Live evidence required?** | No |
| **External imagery** | No |

**The five questions — fixed, one per card:**

| Card | Question |
|---|---|
| **State** | Where may it be used? |
| **Version** | Which stored occurrence is this? |
| **Revision** | Which managed issue is this? |
| **Status** | What condition is declared? |
| **Suitability** | For what use is it suitable? |

**Four mandatory design requirements.**

1. **Cards are equal in size and carry no ordering.** A container has all five at
   once — **not a sequence**.
2. **No arrows between them.** `S1` §6.8: *a new platform version creates none
   of the others*.
3. **A visible note on the revision and suitability cards** — *no project
   convention or code set is established*.
4. **No example codes.** One invented code teaches a standard this project does
   not have.

### W3 — The four-state model

| Field | Value |
|---|---|
| **Slide** | 3 |
| **Teaching purpose** | Show four states, four permitted purposes — **and one route that cannot proceed** |
| **Source basis** | `S1` §6.3; `S2` §1, §3; `S3` §3; `S4` |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Controlled** — the four states. **Blocked** — `Shared → Published` |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** throughout |
| **Simplify** | **Four state panels**, each with a purpose label and a *who may rely* line |
| **Omit** | **Any complete green lifecycle. Any completion tick. `04 Archive`. Any implication that Record / Retained is reached automatically. Delivery, receipt or acceptance shown as states** |
| **Overclaim risk** | **HIGHEST IN THE MODULE** — a four-state chain reads as an operating system |
| **Blocked element visible?** | **YES — mandatory** |
| **Live evidence required?** | No |
| **External imagery** | No |

**Format decision: a native layout, not Mermaid.** Mermaid renders a chain, and
a chain implies traversal. **The deliberate break must be a drawn decision, not a
line style a renderer may normalise.**

**The fixed connectors — verified from `S2` §3:**

```text
WIP
  →   Shared                     T1 · authorising function ESTABLISHED
                                      (Task-Team Lead, S1 §9.4)
  ⇢   Published / Authorised     T4 · BLOCKED
                                      no available authorising function
                                      information REMAINS SHARED
  ⇢   Record / Retained          conceptual state · retention approach TBD
                                      NOT A FOLDER
```

**Six mandatory design requirements.**

1. **`WIP → Shared` may be solid** — and only because the authorising function is
   established. Drawing every connector broken reads as *non-functional* rather
   than *deliberately halted*.
2. **`Shared → Published` is broken or visibly halted.** Never solid, never a
   faded arrow that reads as *in progress*.
3. **`Published → Record / Retained` is unreachable**, and drawn so.
4. **Record / Retained is not drawn as a folder, and `04 Archive` appears
   nowhere.**
5. **The mandatory on-slide label:** **`Conceptual state model — not proof of
   live platform implementation`**.
6. **Publication authority is shown unresolved**, on the diagram.

**Design note.** The four adopted **areas** may appear alongside — but **three
areas map to states, one (`0. Common Files`) maps to none, and one state has no
area at all.** **The mismatch is the teaching**, and a tidy four-to-four
alignment destroys it.

### W4 — The WIP task-team boundary · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 4 |
| **Teaching purpose** | Show WIP as bounded by the task team, and that **visibility is not permission to rely** |
| **Source basis** | `S1` §6.4, §7.5; `S2` §1; `S3` §3.2; `S4` §7 |
| **Classification** | `CONTROLLED` + `DECISION-RECORD` |
| **Governance status** | **Controlled** |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — one qualified container observation |
| **Simplify** | One boundary, three functions inside, several versions inside, one observer outside |
| **Omit** | **Any named person. Any team-space screenshot. Any automatic arrow to Shared.** Any suggestion the boundary is a permission setting. Any green approval tick |
| **Overclaim risk** | **MEDIUM-HIGH** — a boundary with a gate on it invites the eye to follow the route out |
| **Blocked element visible?** | No — but **no route out is drawn** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
┌─ TASK-TEAM WIP ──────────────────────────────────┐
│                                                  │
│   Author  →  Checker  →  [ Task-Team Lead gate ] │
│                                                  │
│   v1  v2  v3  v4 …   working steps,              │
│                      NOT project exchanges       │
│                                                  │
│   originating responsibility — retained          │
└──────────────────────────────────────────────────┘

        ●  another team — CAN SEE
           ✗ MAY NOT RELY

   "Visibility is not permission.
    Permission to read is not authorisation to rely."  (BEP §7.5)
```

**Six mandatory design requirements.**

1. **No automatic arrow to Shared.** The Task-Team Lead gate may be **visible on
   the boundary**, but **no connector leaves it** — transition mechanics are
   Slides 8–11.
2. **The observer outside can see and may not rely.** Both halves are drawn — a
   sight line in, and a refusal marker on reliance.
3. **Originating responsibility is visible inside the boundary**, and stays
   there.
4. **Multiple versions are shown inside**, annotated as **working steps, not
   project exchanges**.
5. **No green approval tick, anywhere.**
6. **No claim that every task team has a verified live area.** If implementation
   is annotated at all: *"`ARC-01` — one qualified observation; five containers
   not observed at the inspected level"*.

**Design note.** Draw the boundary as a **responsibility boundary, not a
permission boundary**. `S1` §6.4: *"A team space is a platform construct…
**Membership confers no authority**."* A boundary drawn as a padlock teaches the
opposite.

### W5 — Shared: permitted use for a defined purpose · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 5 |
| **Teaching purpose** | Show that Shared carries a **stated purpose**, that reliance is bounded by it, and that **responsibility stays with the originator** |
| **Source basis** | `S1` §6.3, §6.5, §6.6, §7.7; `S2` §1, §3; `S3` §3.3; `S4` §7 |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Controlled** — `T1`'s authorising function is established |
| **Implementation status** | **`IMPLEMENTATION UNVERIFIED`** — *"only Architecture currently demonstrable as a Shared input"* |
| **Simplify** | One central container, **two or three purpose call-outs**, one retained-responsibility line |
| **Omit** | **Any approval stamp. Any publication symbol. Any client-acceptance symbol. Any green compliance treatment.** Any platform screenshot |
| **Overclaim risk** | **HIGH** — Shared is the state most often read as *signed off* |
| **Blocked element visible?** | No |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
                    ┌──────────────────────┐
   originating      │   SHARED CONTAINER   │      purpose call-outs:
   task team  ══════│                      │────  · coordination
   RESPONSIBILITY   │  stated purpose:     │────  · controlled review
   RETAINED         │  ……………………            │────  · reference by another
                    └──────────────────────┘         task team

   ── ON-SLIDE WARNING:
      Shared means authorised for A DEFINED USE.
      It does not mean approved for EVERY use.
```

**Six mandatory design requirements.**

1. **Purpose labels are visible**, and each permitted use is attached to one.
2. **The responsibility line stays attached to the originator** — drawn as a
   persistent connection, not a handover arrow.
3. **A visible warning that Shared is not Published.**
4. **No approval stamp, publication symbol, acceptance symbol or tick.**
5. **No green.** Green reads as *cleared*, which is the misreading the slide
   exists to refuse.
6. **`02. Shared` may be referenced, with `S3` §3.3 attached** — *"placement
   alone does not evidence that checking or authorisation occurred"*.

**Design note.** The purpose call-outs must look like **conditions**, not
**benefits**. A fan of arrows radiating outward reads as distribution; the same
arrows terminating in labelled purposes read as bounded permission.

### W6 — The publication-authority gate · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 6 |
| **Teaching purpose** | Show publication as a **separate decision by a separate authority** — and that the authority is **required and unassigned** |
| **Source basis** | `S1` §6.7, §9.7; `S2` §1, §3.1, §3.2, §11; `S3` §3.4; `S4` §9; `S6` `D4` |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **`BLOCKED`** — the authority is **UNRESOLVED** |
| **Implementation status** | **Not reached** |
| **Simplify** | One Shared input, one gate, **one empty authority position**, one blocked output |
| **Omit** | **Any named or implied authority holder. Any solid `Shared → Published` arrow. Any checkmark.** Any suggestion an administrator may substitute. Any red failure styling |
| **Overclaim risk** | **HIGH in both directions** — an empty gate invites the audience to fill it; a red gate reads as a defect |
| **Blocked element visible?** | **YES — the authority position is drawn empty, and the output is broken** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
   SHARED
     │
     ▼
  ┌─────────────────────────────────────────────┐
  │  PUBLICATION GATE                           │
  │                                             │
  │  required check:  delivery readiness review │
  │  required evidence: review + authorisation  │
  │                       record                │
  │                                             │
  │  Publication-authorising function:          │
  │  ┌───────────────────────────────────┐      │
  │  │        TBD / UNRESOLVED           │      │   ← EMPTY, not omitted
  │  └───────────────────────────────────┘      │
  └─────────────────────────────────────────────┘
     ⇢     T4 BLOCKED
           No available authorising function
           INFORMATION REMAINS SHARED
     ⇢
   PUBLISHED / AUTHORISED        (not reached)
```

**Seven mandatory design requirements.**

1. **No solid `Shared → Published` connector.** Broken or visibly halted —
   never solid, never a faded arrow reading as *in progress*.
2. **The authority position appears and is empty.** **Omitting it would imply no
   authority is required**, which is the opposite of true.
3. **Three labels, all present:** **`T4 blocked`** · **`No available authorising
   function`** · **`Information remains Shared`**.
4. **No name in the authority position** — and **no substitution**. `S1` §9.7
   names the BIM Manager, BIM Coordinator, CDE Administrator and Architect as
   **not** holding it automatically.
5. **No checkmark, and no red failure styling.** The block is **deliberate
   governance**, not a technical fault.
6. **`TRN-E03` is not drawn as the transition.** It may be named in a single
   annotation as *a later delivery event that depends on `T4`* — **the event
   logic is Slides 8–11**.
7. **`S3` §3.4 appears on the slide** — *"Putting a file in `03. Published` does
   not publish it."*

**Design note — the hardest instruction on this visual.** An empty box looks
unfinished, and a designer will want to fill it, shade it, or remove it. **All
three are wrong.** Filled invents an authority; removed implies none is needed;
shaded reads as failure. **A plain, labelled, empty position is the only accurate
rendering.**

### W7 — Retention obligation versus method · **specified (T4-B)**

| Field | Value |
|---|---|
| **Slide** | 7 |
| **Teaching purpose** | Show retention as an **established obligation** with an **undecided method** |
| **Source basis** | `S1` §6.3, §7.10, §9.9, §12.10; `S2` §1, §19; **`S3` §3.1, §3.5, `CGD-C06`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Controlled** — the obligation. **`UNRESOLVED`** — the method |
| **Implementation status** | **Not addressed in any validation record** |
| **Simplify** | **Two panels, side by side** — obligation established, method unresolved |
| **Omit** | **`04 Archive` in any form. Any folder icon. Any placeholder folder name. Any destination arrow. Any completed storage icon. Any green check. Any invented retention period. Any invented named holder** |
| **Overclaim risk** | **MEDIUM-HIGH** — the audience expects a folder and will read one in |
| **Blocked element visible?** | **YES — the method panel is visibly empty** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form:**

```text
  ┌── OBLIGATION — ESTABLISHED ──┐   ┌── METHOD — UNRESOLVED ──────┐
  │                              │   │                             │
  │  · preserve required         │   │  location:            TBD   │
  │    project information       │   │  retention period:    TBD   │
  │  · protect against           │   │  responsible holder:  TBD   │
  │    uncontrolled change       │   │  implementation                │
  │    or loss                   │   │    evidence:     unavailable   │
  │  · maintain traceability     │   │                             │
  │  · retain required evidence  │   │                             │
  │                              │   │                             │
  │  superseded ≠ deleted        │   │      ← stays empty →        │
  └──────────────────────────────┘   └─────────────────────────────┘

  ── ON-SLIDE STATEMENT:
     Record / Retained is a state or obligation.
     It is NOT automatically a folder.

  ── STATE-VERSUS-AREA MISMATCH:
     0. Common Files   — an area mapped to NO state
     Record / Retained — a state mapped to NO approved area
```

**Seven mandatory design requirements.**

1. **`04 Archive` appears nowhere** — not as a label, an example, a grey
   placeholder, a future suggestion or a visual destination.
2. **The method panel appears and stays empty.** **An omitted method panel reads
   as complete**; an empty one shows the open decision.
3. **No destination arrow** from the obligation panel to anywhere. There is
   nowhere to point.
4. **No completed storage icon, no green check, no archive imagery.**
5. **No invented retention period** — none exists in any controlled source.
6. **No invented named holder** — **no records manager or archive administrator
   exists in the Harrismith set**.
7. **The state-versus-area mismatch is shown**, both directions. **Do not force a
   four-state-to-four-area alignment.**

**Design note.** The two panels are the **same size**. A large obligation panel
beside a small method panel implies the method is a detail. It is an undecided
governance matter, and the panels should look equally consequential.

### W8 — File movement versus authorised transition

| Field | Value |
|---|---|
| **Slide** | 8 |
| **Teaching purpose** | Show the two side by side, and that **one does not produce the other** |
| **Source basis** | **`CGD-C03`**; `S2` §3; `S4` §9 |
| **Classification** | `DECISION-RECORD` + `SUPPORTING` |
| **Governance status** | **Controlled** — active condition |
| **Implementation status** | — |
| **Simplify** | **Two panels.** Left: what a user can technically do. Right: what a transition requires |
| **Omit** | **Any connector between the panels. Any equals sign.** Any permission screenshot |
| **Overclaim risk** | **HIGH** — a two-panel layout invites the eye to pair them |
| **Blocked element visible?** | No |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed content:**

| **Technically able to** | **A transition requires** |
|---|---|
| upload · move · copy · rename · download · publish · change permissions | purpose · authority · check · authorisation · evidence |

**Requirement.** The panels are **not** joined. `CGD-C03` on the slide:
*"movement or placement between platform areas must not be treated as sufficient
evidence of… an information-state transition."*

### W9 — The eight controlled steps

| Field | Value |
|---|---|
| **Slide** | 9 |
| **Teaching purpose** | Show all eight steps — **and that only `T1` and `T4` change state** |
| **Source basis** | **`S2` §3.1** |
| **Classification** | `SUPPORTING` |
| **Governance status** | **Mixed** — `T1` controlled · `T4` **blocked** · `T7` **unresolved** · the rest proposed |
| **Implementation status** | **Unverified** — no complete cycle demonstrated (`S4` §8) |
| **Simplify** | **A table, not a flow.** Eight rows, four columns: ref · kind · state before → after · status |
| **Omit** | **Any eight-step flowchart.** Any implication that the eight run in sequence. Any completion marker |
| **Overclaim risk** | **HIGHEST, jointly with `W3`** — eight identifiers in a row read as an eight-step state machine |
| **Blocked element visible?** | **YES** — `T4` and `T7` marked |
| **Live evidence required?** | No |
| **External imagery** | No |

**Format decision: a table, deliberately not Mermaid.** A flowchart of `T1`–`T8`
would render eight sequential transitions. **Six of the eight are not state
transitions at all** — they are actions, uses, events, a status and a rework
route. **The table's *kind* column is the slide's whole teaching.**

**Requirement.** The two state transitions are **visually distinguished** from
the other six, and `S2` §3's sentence appears on the slide: *"only `T1` and `T4`
are information-state transitions."*

### W10 — Gate, authority and evidence

| Field | Value |
|---|---|
| **Slide** | 10 |
| **Teaching purpose** | Show what must exist **before** and **after** a transition |
| **Source basis** | `S2` §3.2, §3.3, §16; `S6` |
| **Classification** | `SUPPORTING` |
| **Governance status** | Proposed |
| **Implementation status** | Unverified |
| **Simplify** | **One transition, fully unpacked** — `T1` is the only one with an established authority, so use it |
| **Omit** | **All eight transitions at once.** Matrix-cell grammar — **Module 5**. The review that satisfies the gate — **Module 6** |
| **Overclaim risk** | **MEDIUM-HIGH** — a fully populated example reads as a running procedure |
| **Blocked element visible?** | The **`T4` contrast** is worth one line |
| **Live evidence required?** | No |
| **External imagery** | No |

**The fixed form — five fields, in order:**

```text
trigger  →  required check  →  authorising function  →  the act  →  evidence
```

**Requirement.** **The evidence field is never hidden or abbreviated away.**
`S2` §3.3 lists what each transition produces, and a gate diagram without its
evidence teaches a decision with no record.

**Boundary.** One transition unpacked. **If the visual starts showing who signs
which matrix cell, it is Module 5's.**

### W11 — The blocked `Shared → Published` route

| Field | Value |
|---|---|
| **Slide** | 11 |
| **Teaching purpose** | Show the block, and that **stopping an unauthorised process is correct behaviour** |
| **Source basis** | `S2` §3, §11, §19; `S5` §5.1; `S4` §9 |
| **Classification** | `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **BLOCKED** |
| **Implementation status** | Not reached |
| **Simplify** | One route, one halt, one list of blocking matters |
| **Omit** | **Any completed route. Any invented authorising function. Any red failure styling** |
| **Overclaim risk** | **HIGH in both directions** — reads as a defect if styled as failure; reads as operating if the route completes |
| **Blocked element visible?** | **YES — this visual is the block** |
| **Live evidence required?** | No |
| **External imagery** | No |

**The blocking matters — `S5` §5.1, all five, for `TRN-E03`:**

| Blocking matter | Status |
|---|---|
| Publication / exchange authorisation authority | **UNRESOLVED — TBD** |
| Recipient acceptance authority | **UNRESOLVED — TBD** |
| Recipient identity | Not established |
| Required formats | Not established — no approved standard |
| Deliverable set | Not defined |

**And the `T4` / `TRN-E03` distinction, which belongs on this slide:** `T4` is
blocked by **one** matter; `TRN-E03` is blocked by **five**. **They are not
interchangeable.**

**Requirement.** The block is styled as **deliberate governance, not failure** —
neutral, not red. `S2` §19's position appears: *"Each is recorded so the gap
stays visible rather than being filled with a plausible value."*

### W12 — The metadata and property stack

| Field | Value |
|---|---|
| **Slide** | 12 |
| **Teaching purpose** | Show the five properties plus metadata as **controls that support transition evidence** |
| **Source basis** | `S1` §6.8, §11.3, §11.4; `S2` §13; `S12` |
| **Classification** | `CONTROLLED` + `INTERP` |
| **Governance status** | **Controlled** — the properties. **UNRESOLVED** — every code set and the schema |
| **Implementation status** | **No schema established** |
| **Simplify** | A container with its property fields, and **which fields are empty on this project** |
| **Omit** | **Any coding standard. Any example code. Any metadata schema.** Module 5's suitability-in-delivery-planning |
| **Overclaim risk** | **HIGH** — a populated property stack teaches a standard that does not exist |
| **Blocked element visible?** | **YES** — the unestablished fields stay **visibly empty** |
| **Live evidence required?** | No |
| **External imagery** | No |

**Requirement.** **The empty fields are the slide.** Naming, revision
convention, suitability code set and metadata schema are all **not established**;
drawing them populated would invent four standards at once.

### W13 — Responsibility before permission

| Field | Value |
|---|---|
| **Slide** | 13 |
| **Teaching purpose** | Show the order — **decision, then configuration** — and that reversing it is a deviation |
| **Source basis** | `S2` §14, §17; `S1` §6.9, §12.1; **`CGD-C07`, `CGD-C08`** |
| **Classification** | `CONTROLLED` + `SUPPORTING` + `DECISION-RECORD` |
| **Governance status** | **Controlled** |
| **Implementation status** | **Unverified** |
| **Simplify** | **One arrow, one direction**: approved responsibility → permission. Beneath it, the reverse **struck through** |
| **Omit** | **Any permissions screenshot or table. Any named administrator.** Any org-chart shape |
| **Overclaim risk** | MEDIUM — low content risk, but it reprises Slide 1 |
| **Blocked element visible?** | No |
| **Live evidence required?** | No |
| **External imagery** | **No.** A permissions screenshot would prove the opposite point by making configuration the concrete thing |

**Requirement.** `S2` §14 on the slide: *"Access is configured to follow approved
responsibility; responsibility comes first and permission follows it. Where
access and approved responsibility diverge, the divergence is recorded as a
**deviation**."*

### W14 — Triviron CDE-definition questions

| Field | Value |
|---|---|
| **Slide** | 14 |
| **Teaching purpose** | Convert the module into **questions Triviron must answer before configuring anything** |
| **Source basis** | **None.** No Triviron project information exists |
| **Classification** | `SYNTH` |
| **Governance status** | — |
| **Implementation status** | — |
| **Simplify** | Grouped questions — states · transitions · authorities · properties · evidence |
| **Omit** | **Every Triviron fact.** No answer, no placeholder, no default, no platform name |
| **Overclaim risk** | **HIGH — about Triviron, not about Harrismith** |
| **Blocked element visible?** | The end state stays **open** |
| **Live evidence required?** | No |
| **External imagery** | No |

**Requirement.** Every item ends in a question mark. **The questions that must
appear:** *Which information states will the project use?* · *Who authorises
each transition?* · **_Who holds publication authority?_** · **_Who holds
acceptance authority?_** · *What evidence will each transition produce?* ·
*What is the retention approach?*

---

## 5. Summary

| ID | Slide | Format | Overclaim risk | Blocked element visible |
|---|---|---|---|---|
| `W1` | 1 | Layout | **HIGH** | Status labels |
| `W2` | 2 | Layout / cards | MEDIUM-HIGH | **Absent code sets** |
| `W3` | 3 | **Layout — not Mermaid** | **HIGHEST** | **YES** |
| `W4` | 4 | **Layout — specified** | MEDIUM-HIGH | **No route out drawn** |
| `W5` | 5 | **Layout — specified** | **HIGH** | No |
| `W6` | 6 | **Layout — specified** | **HIGH** | **YES — empty authority position** |
| `W7` | 7 | **Layout — specified** | MEDIUM-HIGH | **YES — empty method panel** |
| `W8` | 8 | Layout — two panels | **HIGH** | No |
| `W9` | 9 | **Table — not Mermaid** | **HIGHEST** | **YES** |
| `W10` | 10 | Mermaid or layout | MEDIUM-HIGH | `T4` contrast |
| `W11` | 11 | **Layout — not Mermaid** | **HIGH** | **YES — the visual is the block** |
| `W12` | 12 | Layout | **HIGH** | **YES — empty fields** |
| `W13` | 13 | Mermaid or layout | MEDIUM | No |
| `W14` | 14 | Layout | **HIGH (Triviron)** | End state open |

**Fourteen candidate visuals. Four specified in full — `W4`–`W7` (T4-B). Six
carry HIGH or HIGHEST overclaim risk, and seven must keep something visibly
incomplete.**

**Two of the Section B visuals carry a mandatory empty field.** `W6`'s
publication-authority position and `W7`'s retention-method panel are **shown and
left blank** — because omission reads as *not needed* and a filled field invents a
decision. **A producer who removes, fills or shades either has changed the
claim.**

**Only three are safely Mermaid** — `W10`, `W13`, and `W1` if drawn without a
return arrow. **`W4` moved to a layout specification in T4-B**: a Mermaid
boundary with a gate on it renders an outbound edge, and the route out of WIP
must not be drawn. **Everything that depicts a state, a transition set or an absent
control is a layout specification**, because a renderer that normalises a broken
line into a solid one commits the module's central error.

**No external imagery is required. No live observation is required, and none is
authorised.**

## 6. What this plan does not do

- It creates **no asset**. No source file, no rendered image.
- It authorises **no live Autodesk observation, read or configuration act.**
  Root [`README.md`](../../README.md) §2.1 applies unmodified.
- It does **not** resolve any unresolved matter.
- It carries **no governance authority.**
