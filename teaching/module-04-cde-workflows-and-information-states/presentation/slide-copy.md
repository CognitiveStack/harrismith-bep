# Module 4 — Slide Copy

**Status:** Working on-slide wording. **Not the speaker script.**

Everything below is intended to be **visible on the slide**. What the presenter
*says* is in [`presenter-cues.md`](presenter-cues.md).

---

## 1. How to read this file

| Element | Meaning |
|---|---|
| **Title** | The slide title, exactly |
| **Subtitle** | Second line, where used |
| **Main statement** | The one sentence the slide argues |
| **Supporting items** | Labels or single-line bullets |
| **Visual labels** | Text inside the visual |
| **Call-out** | A boxed or emphasised line |
| **Source / status labels** | Small, retained — **content, not styling** |
| **Mandatory warning** | A required on-slide label |

### Density limits

**One principal message per slide** · **no more than five supporting items**
unless the controlled visual requires a larger question or register set · no
paragraph blocks · no full source tables · no dense disclaimer wall · no raw
controlled-source extract · **no unsupported code example** · **no populated
Triviron answer**.

**Slides 9, 11 and 14 exceed the general guide deliberately.** Each carries a
controlled distinction that cannot be compressed without losing it — the
eight-step classification, the one-versus-five contrast, and the five question
groups.

## 2. Mandatory visible wording

**These appear verbatim. They are content, not styling.** **Where a slide-source
file specifies a more exact literal string, that source file governs.**

| # | Wording | Slide |
|---|---|---|
| 1 | `CONTROLLED GOVERNANCE` | 1, 3, 4, 5, 8, 10, 12, 13 |
| 2 | `PROPOSED GOVERNANCE` | 1 |
| 3 | `IMPLEMENTATION UNVERIFIED` | 1, 3, 4, 5, 9, 10, 13 |
| 4 | `A new platform version creates none of the others` | 2 |
| 5 | `Conceptual state model — not proof of live platform implementation` | 3 |
| 6 | `T4 BLOCKED` | 3, 6, 9, 11 |
| 7 | `Publication-authorising function: TBD` | 3, 6, 11 |
| 8 | `Information remains Shared` | 3, 6, 11 |
| 9 | `Areas and information states do not map one to one` | 3, 7 |
| 10 | `Visibility is not permission` | 4 |
| 11 | `Permission to read is not authorisation to rely` | 4 |
| 12 | `Shared means authorised for a defined use` | 5 |
| 13 | `It does not mean approved for every use` | 5 |
| 14 | `Record / Retained is not a folder` | 3, 7 |
| 15 | `Retention method: TBD` | 7 |
| 16 | `File movement ≠ authorised information-state transition` | 8 |
| 17 | `Only T1 and T4 change information state` | 9 |
| 18 | `Planned or controlled governance is not proof of live implementation` | 9, 10 |
| 19 | `Naming standard: not established` | 12 |
| 20 | `Revision convention: not established` | 12 |
| 21 | `Suitability code set: not established` | 12 |
| 22 | `Metadata schema: not established` | 12 |
| 23 | `Configuration implements governance. It does not create it` | 13 |
| 24 | `Who holds publication authority?` | 14 |
| 25 | `Who holds acceptance authority?` | 14 |
| 26 | `CDE configuration basis — not yet established` | 14 |

**None of these may be paraphrased, abbreviated, moved to the notes, or reduced
below 14 pt.**

## 3. Slide copy

### Slide 1 — A CDE is a governed process, not a folder tree

**Subtitle.** *Governance decides · the workflow defines · the platform implements*

**Main statement.**

> The CDE is the governed process; the platform and folders are tools used to implement it.

**Supporting items.**

- **Governance and authority** — who decides, what must be checked, what must be authorised, what must be retained
- **CDE workflow and information states** — the four states, who may rely on each, the transitions and their evidence
- **Platform, folders, permissions and metadata** — root areas, roles, settings, fields

**Visual labels.** `decides and authorises` (band 1 → band 2) · `implemented through` (band 2 → band 3)

**Call-out.**

> The CDE is the governed process; the platform and folders are tools used to implement it.

**Source / status labels.** `CONTROLLED GOVERNANCE · S1 §6.1, §6.9` · `PROPOSED GOVERNANCE · S2 §1, §3` · `IMPLEMENTATION UNVERIFIED · S3 §2 · CGD-C07`

**Mandatory warning.** **`PROPOSED GOVERNANCE` is the warning.** It stays on the band.

**Must not appear.** Platform logo, screenshot or product name · any upward arrow · any org-chart shape

---

### Slide 2 — State, version, revision, status and suitability are different

**Subtitle.** *One container. Five properties. Five different questions.*

**Main statement.**

> Five properties may describe the same container, but each answers a different governance question.

**Supporting items.**

- **State** — Where may it be used?
- **Version** — Which stored occurrence is this?
- **Revision** — Which managed issue is this?
- **Status** — What condition is declared?
- **Suitability** — For what use is it suitable?

**Visual labels.** `ONE INFORMATION CONTAINER — ALL FIVE AT ONCE` · card footers: `governed concept` · `platform-native; no project convention` · `no convention established` · `no code set established` · `no code set established`

**Call-out.**

> A new platform version creates none of the others.

**Source / status labels.** `— S1 §6.8`

**Mandatory warning.** **Three cards carry `not established`.** State and Version do not, and must not be made to.

**Must not appear.** Any connector · any example code or filename · **metadata as a sixth card**

---

### Slide 3 — The Harrismith information-state model

**Subtitle.** *Four states · four permitted purposes · one route that cannot proceed*

**Main statement.**

> Each state defines a different permitted purpose; movement between them requires more than technical file movement.

**Supporting items.**

- **WIP** — the originating task team only
- **Shared** — receiving teams, for the stated purpose
- **Published / Authorised** — whoever the authorised purpose names
- **Record / Retained** — anyone needing traceability

**Visual labels.** `T1` · `Task-Team Lead authority established` · `T4 BLOCKED` · `Publication-authorising function: TBD` · `Information remains Shared` · `Retention approach: unresolved` · `Not reachable while T4 is blocked`

**Call-out.**

> Areas and information states do not map one to one.
> `0. Common Files` — an area mapped to no state.
> `Record / Retained` — a state with no approved area.

**Source / status labels.** `CONTROLLED GOVERNANCE` ×2 · `BLOCKED` · `UNRESOLVED` — and `IMPLEMENTATION UNVERIFIED` ×2 · `Not reached` · `Not addressed`

**Mandatory warning.** **`Conceptual state model — not proof of live platform implementation`** — on the visual, at body size.

**Must not appear.** **`04 Archive`** · folder icons as states · a four-area row beneath the panels · Delivered, Received or Accepted

---

### Slide 4 — Work in Progress: authoring inside the task team

**Subtitle.** *Authoring inside the task team*

**Main statement.**

> WIP is where a task team develops its information — not where the wider project is entitled to rely on it.

**Supporting items.**

- Author → Checker → Task-Team Lead gate — **all inside the boundary**
- `v1 v2 v3 v4 …` — **working steps, not project exchanges**
- **originating responsibility — retained**
- Another team: **CAN SEE** · **MAY NOT RELY**

**Visual labels.** `TASK-TEAM WIP` · `CAN SEE` · `MAY NOT RELY`

**Call-out.**

> Visibility is not permission. Permission to read is not authorisation to rely.

**Source / status labels.** `CONTROLLED GOVERNANCE` · `IMPLEMENTATION UNVERIFIED` — `ARC-01`, one qualified observation; five containers not observed at the inspected level

**Mandatory warning.** **No route out of WIP is drawn.** Transitions are Slides 8–11.

**Must not appear.** Any arrow leaving the boundary · a padlock or permission shield · a named person · a green tick

---

### Slide 5 — Shared: controlled use for a defined purpose

**Subtitle.** *Controlled use for a defined purpose*

**Main statement.**

> Shared information may be relied upon only for the purpose for which it was shared.

**Supporting items.**

- **stated purpose:** ______ — stated per exchange, not fixed here
- Permitted uses: **coordination** · **controlled review** · **reference by another task team**
- **RESPONSIBILITY RETAINED** by the originating task team
- *Shared does not mean published, accepted, or suitable for every purpose*

**Visual labels.** `SHARED CONTAINER` · `originating task team` · `RESPONSIBILITY RETAINED`

**Call-out.**

> Shared means authorised for **a defined use**. It does not mean approved for **every** use.

**Source / status labels.** `CONTROLLED GOVERNANCE` · `IMPLEMENTATION UNVERIFIED` — only Architecture currently demonstrable as a Shared input

**Mandatory warning.** `S3` §3.3 — *placement alone does not evidence that checking or authorisation occurred*.

**Must not appear.** Any approval, publication or acceptance symbol · **any green** · a handover arrow · an invented example purpose

---

### Slide 6 — Published / Authorised: a separate decision and authority

**Subtitle.** *A separate decision, by a separate authority*

**Main statement.**

> Publication is not the next folder; it is a separate authorised decision that this project cannot currently make.

**Supporting items.**

- **required check:** delivery readiness review
- **required evidence:** review + authorisation record
- **Publication-authorising function:** ⟶ **empty, not omitted**
- *Putting a file in `03. Published` does not publish it*

**Visual labels.** `PUBLICATION GATE` · `TBD / UNRESOLVED` · `T4 BLOCKED` · `No available authorising function` · `INFORMATION REMAINS SHARED` · `PUBLISHED / AUTHORISED  (not reached)`

**Call-out.**

> Publication is not the next folder. It is a separate authorised decision this project cannot currently make.

**Source / status labels.** `BLOCKED` · `Not reached`

**Mandatory warning.** **The authority position appears and stays empty.** Filled invents an authority; removed implies none is needed; shaded reads as failure.

**Must not appear.** Any named or implied holder · any solid `Shared → Published` arrow · any checkmark · **any red failure styling**

---

### Slide 7 — Record / Retained: preservation without an Archive folder

**Subtitle.** *Preservation without an Archive folder*

**Main statement.**

> Retention is a governed obligation; the project has not yet decided the folder, system or method by which it will be implemented.

**Supporting items.**

- **Obligation — established:** preserve · protect against uncontrolled change or loss · maintain traceability · retain required evidence
- **superseded ≠ deleted**
- **Method — unresolved:** `location: TBD` · `retention period: TBD` · `responsible holder: TBD` · `implementation evidence: unavailable`
- `0. Common Files` — an area mapped to **no state**. `Record / Retained` — a state mapped to **no approved area**

**Visual labels.** `OBLIGATION — ESTABLISHED` · `METHOD — UNRESOLVED` · `← stays empty →`

**Call-out.**

> Record / Retained is a state or obligation. It is **NOT** automatically a folder.

**Source / status labels.** `CONTROLLED GOVERNANCE` (obligation) · `UNRESOLVED` (method) · **Not addressed in any validation record**

**Mandatory warning.** **No `04 Archive` root is approved or required** — `CGD-C06`.

**Must not appear.** **`04 Archive` in any form** · folder or storage icons · an invented retention period or holder · a destination arrow

---

### Slide 8 — A transition is more than moving a file

**Subtitle.** *Technical action against governed transition*

**Main statement.**

> The transition occurs when the project authorises a new permitted use and records the required evidence — not when a file changes location.

**Supporting items.**

- **Technical action:** upload · move · copy · rename · change permissions · create a new version
- **establishes NONE of:** checks · evidence · authority · permitted use · suitability · publication · delivery · receipt · acceptance
- **Governed transition:** required input → checks → gate conditions → authorised decision → recorded evidence → changed permitted use
- *Each transition requires the applicable governed checks, authorisation and evidence* — `CGD-C03`

**Visual labels.** `TECHNICAL ACTION` · `GOVERNED TRANSITION` · `Teaching structure`

**Call-out.**

> File movement ≠ authorised information-state transition.
> **NO CONNECTOR. The left does not produce the right.**

**Source / status labels.** `CONTROLLED GOVERNANCE` — `CGD-C03`, an active condition · Implementation: **not applicable**

**Mandatory warning.** **The gutter stays empty.** Any graphic in it will be read as a relationship.

**Must not appear.** **Any connector between the panels** · any equals sign · anything at all in the gutter

---

### Slide 9 — The eight controlled steps, and the two that change state

**Subtitle.** *Eight controlled steps, grouped by kind*

**Main statement.**

> The identifiers describe different controlled acts. Only two change the information state.

**Supporting items.**

- **Information-state transitions** — `T1` WIP → Shared, authority Task-Team Lead, **ESTABLISHED** · `T4` Shared → Published, authority **TBD**, **BLOCKED**
- **Actions and uses — state unchanged** — `T2` consume decision · `T3` coordination input · both Shared → Shared
- **Events — state unchanged** — `T5` delivery executed · `T6` receipt registered · both Published → Published
- **Decision or status — state unchanged** — `T7` accept or reject, Published → Published, authority **TBD**
- **Rework route** — `T8` return to the originator's WIP, then reuse `T1` or `T4`

**Visual labels.** Five group headings, eight rows, and a **state-effect column on every row**

**Call-out.**

> Only `T1` and `T4` change information state.

**Source / status labels.** Mixed — `T1` controlled · `T4` **BLOCKED** · `T7` **UNRESOLVED** · the rest proposed · `IMPLEMENTATION UNVERIFIED` — *no complete traceable cycle demonstrated*

**Mandatory warning.** **Planned or controlled governance is not proof of live implementation.**

**Must not appear.** **Any flowchart, arrow chain or Mermaid** · group numbering · green-for-`T1` or red-for-`T4`

---

### Slide 10 — Gates, authority and evidence

**Subtitle.** *One transition, unpacked*

**Main statement.**

> `T1` works as a governed transition because its purpose, checks, authority and evidence are defined — even though complete live operation is not yet verified.

**Supporting items.**

- **required checks** — technical / content · information-quality / readiness
- **gate conditions** — information present · checking complete · purpose of sharing known
- **AUTHORITY** — Task-Team Lead (or another allocated role)
- **EVIDENCE** — version history · checking record · share / exchange record
- **CDE Administration** — implements the permission arrangement; **does not decide**

**Visual labels.** `WIP` · `SHARED` · `for the defined purpose` · `Author` · `Checker` · `Task-Team Lead` · `receiving user`

**Call-out.**

> Failure route: information remains in, or returns to, WIP. **NO PARTIAL PROGRESSION.**

**Source / status labels.** `CONTROLLED GOVERNANCE` · `IMPLEMENTATION UNVERIFIED`

**Mandatory warning.** **Governance definition ≠ live implementation evidence.**

**Must not appear.** Any publication path · any green tick or completion marker · the full eight-item readiness list · a folder icon for evidence

---

### Slide 11 — Why `Shared → Published` remains blocked

**Subtitle.** *Two blocked objects, not one*

**Main statement.**

> `T4` cannot proceed because publication authority is unassigned; `TRN-E03` remains blocked because a delivery event requires several additional decisions.

**Supporting items.**

- **`T4` — information-state transition.** Shared ⇢ Published / Authorised. Publication-authorising function: **TBD**
- **Status: BLOCKED.** **Information remains Shared**
- **`TRN-E03` — delivery event.** It **exercises** `T4`
- **Blocked on five:** publication authority · acceptance authority · recipient identity · required formats · deliverable set
- **Status: PROPOSED — BLOCKED.** Blocked by **five** matters; `T4` is blocked by **one**

**Visual labels.** `PANEL 1 · T4` · `PANEL 2 · TRN-E03` · `exercises T4` · `▲ empty, not omitted`

**Call-out.**

> Satisfying `T4` alone would not automatically complete delivery.
> **Published ≠ Delivered ≠ Received ≠ Accepted.**

**Source / status labels.** `BLOCKED` and `PROPOSED — BLOCKED` · **Not reached**, both panels

**Mandatory warning.** **The panels stay separate.** No connector crosses the gutter.

**Must not appear.** Any merged object · any connector between the panels · any invented recipient, format or deliverable · red styling

---

### Slide 12 — Naming, revision, suitability and metadata support control

**Subtitle.** *What the properties control — and what has not been decided*

**Main statement.**

> Naming and metadata support control by identifying information and its permitted use — but the code never replaces the governance decision.

**Supporting items.**

- **Name / identifier** — Which container is this?
- **Version** — Which stored platform occurrence? · **Revision** — Which managed issue applies?
- **Status** — What condition is declared? · **Suitability** — For what purpose may it be relied upon?
- **Metadata** — Which structured attributes support control?
- **ON THIS PROJECT:** `Naming standard: not established` · `Revision convention: not established` · `Suitability code set: not established` · `Metadata schema: not established`

**Visual labels.** `PROPERTY` / `CONTROL QUESTION` · four bordered, empty boxes · `▲ four positions, shown and empty — not omitted`

**Call-out.**

> A code identifies. It does not authorise, and it does not prove the process behind it occurred.

**Source / status labels.** `CONTROLLED GOVERNANCE` (what each property must support) · `UNRESOLVED` (every code set and the schema) · **No standard established**

**Mandatory warning.** **`not established` — not *in progress*, not *to follow*, not a date.**

**Must not appear.** Any code, filename, field name or schema · any classification system · a properties-palette screenshot · a date

---

### Slide 13 — Governance first; permissions and configuration follow

**Subtitle.** *Direction of authority*

**Main statement.**

> Configuration implements governance. It does not create it.

**Supporting items.**

- `Governance decision` → `Process rule` → `Permission / configuration` → `Implementation evidence`
- **`Platform setting ──✕──▶ governance authority`** — shown, and refused
- **CDE Administration MAY** — configure folders, spaces, roles, permissions, workflow *where authorised* · implement approved changes · check configuration after an approved change · **`Holder: TBD`**
- **DOES NOT** — determine the information-state model · assign publication authority · assign acceptance authority · approve technical design

**Visual labels.** `▲ shown and refused — not omitted` · `Holder: TBD`

**Call-out.**

> Configuration implements governance. It does not create it.
> A configuration that was never approved is a deviation, however competently it was applied.

**Source / status labels.** `CONTROLLED GOVERNANCE` · `IMPLEMENTATION UNVERIFIED`

**Mandatory warning.** **Evidence remains the required final stage.** It is not optional and not abbreviated.

**Must not appear.** Any permissions screenshot or matrix · a named administrator · an org chart · a loop back to the start

---

### Slide 14 — What Triviron must define before configuring its CDE

**Subtitle.** *Questions only*

**Main statement.**

> Configure the platform only after the states, purposes, authorities, gates and evidence requirements have been decided.

**Supporting items.**

- **1 · CDE purpose and scope** — What information? Which teams? Which uses? Which phases? What evidence that the process operates?
- **2 · Information states and permitted use** — Which states? What is each for? Who may rely on each? Conceptual, physical or both? Which folder relationship? How will folder location be prevented from meaning state?
- **3 · Transitions, gates and authority** — Which actions change state? Who initiates? Who checks? Who authorises? What if an authority is unassigned? Which transitions must stay blocked?
- **4 · Naming, revision, suitability and metadata** — Which standard? Which convention? Which codes? What schema? Who assigns and checks? How are codes kept distinct from evidence that the process occurred?
- **5 · Platform configuration and implementation evidence** — Which platform? Who may configure? How authorised? How are deviations recorded? How is configuration verified against governance? Who declares the CDE ready for use?

**Visual labels.** Set apart, in their own bordered block: **`Who holds publication authority?`** · **`Who holds acceptance authority?`** · `▲ asked, and not answered`

**Call-out.**

> Configure the platform only after the states, purposes, authorities, gates and evidence requirements have been decided.

**Source / status labels.** **None asserted for Triviron** — the project has no entry in any register

**Mandatory warning.** **`CDE configuration basis — not yet established`** — neutral styling. No warning colour, icon, date or owner.

**Must not appear.** **Every Triviron fact** · every answer, default, placeholder and recommendation · any status colour on the end state

---

## 4. Slide-specific copy controls

| Slide | Control |
|---|---|
| **1** | Three layers with their statuses visible. **Not an organisation chart** |
| **2** | **Five properties only.** No metadata. No arrows, no ordering language |
| **3** | **Exactly four state panels.** All eight governance and implementation labels. Area/state mismatch retained |
| **4** | WIP responsibility and visibility-versus-reliance. **No route out** |
| **5** | Defined permitted uses and retained originating responsibility. **Never "Shared is approved"** |
| **6** | **Publication-authority field empty. Output blocked** |
| **7** | Established obligation separated from unresolved method. **No Archive folder** |
| **8** | **The two panels stay unconnected** |
| **9** | A **classified table, not a journey.** Only `T1` and `T4` change state |
| **10** | Checks, Task-Team Lead authority and **evidence**. The evidence field is not compressed away |
| **11** | `T4` and `TRN-E03` separate. One-versus-five retained. **Published ≠ Delivered ≠ Received ≠ Accepted** |
| **12** | Six properties and **four visibly unestablished controls**. No example code |
| **13** | One supported forward chain, one **refused** reverse route |
| **14** | **Questions only**, every one ending in a question mark. Both compulsory questions. Neutral end state |

## 5. Status

**Fourteen slides of final working copy.** **No measured timing is claimed.**
**No Triviron answer, code example or invented authority appears anywhere in
this file.**
