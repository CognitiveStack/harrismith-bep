# Module 1 — Visual Demonstration Plan

**Status:** Candidate visuals for the complete Module 1 presentation. **Nothing
here is prepared, and no asset exists.** Every entry is a proposal.

**No live Autodesk work is performed in this increment.** Where an entry notes
that a live observation "may be useful", that is an observation of a possible
future need — it is **not** an authorisation. Any live observation is a
separately authorised, bounded, read-only activity under the safety boundary in
root [`README.md`](../../README.md) section 2.1.

---

## 1. How to read this plan

Each candidate visual records:

| Field | Meaning |
|---|---|
| **Teaching purpose** | The one thing the audience should take from it |
| **Likely source** | Where the visual would come from |
| **Derivable from repository?** | Whether it can be built from committed material alone |
| **Live observation useful?** | Whether a later bounded read-only observation would add something — not an authorisation |
| **Over-detail risk** | The risk of putting more on a slide than the audience can absorb, or than should be shown at all |

**A standing rule from [`../shared/presentation-principles.md`](../shared/presentation-principles.md):**
a dense screenshot of a controlled document is not a visual. It is a wall of text
the audience will read instead of listening. Extracts are cropped to the few rows
that carry the message.

---

## 2. Candidate visuals

### V1 — Harrismith Fire Station project or model image

| Field | Value |
|---|---|
| Teaching purpose | Anchor the whole talk in a real building. Establishes that this is a project, not a methodology lecture |
| Likely source | Revit or federated model view; project imagery |
| Derivable from repository? | **No** — the repository holds no image assets |
| Live observation useful? | **Yes, potentially** — a single representative view would be the highest-value asset in the module |
| Over-detail risk | **Low.** Risk is the opposite: a cluttered view with visible view tabs, browser trees and toolbars. A clean 3D view, no UI chrome |
| Slide | 1 |

### V2 — Extract from the principal BEP

| Field | Value |
|---|---|
| Teaching purpose | Show the shape and seriousness of the document without asking anyone to read it |
| Likely source | [`bep/Harrismith-Fire-Station-BEP.md`](../../bep/Harrismith-Fire-Station-BEP.md) — §1.4 "Relationship to Supporting Resources", or the four-document-types table |
| Derivable from repository? | **Yes** |
| Live observation useful? | No |
| Over-detail risk | **High.** A screenshot of the full section is unreadable at projection size. Use the §1.4 four-row document-type table only — BEP / Delivery Guide / Working Process / Standards, with its Authority column. That table alone carries the section |
| Slide | Harrismith BEP structure |

### V3 — Information-management responsibility matrix

| Field | Value |
|---|---|
| Teaching purpose | Show that "who does what" is written down once, in one place, with a precise grammar |
| Likely source | [`supporting/information-management-responsibility-matrix.md`](../../supporting/information-management-responsibility-matrix.md) §3.3 |
| Derivable from repository? | **Yes** |
| Live observation useful? | No |
| Over-detail risk | **Very high.** The full matrix is a nine-column grid across several sub-tables; projected whole, it is noise. Use the four **P1–P4** rows with the P1/P4 note — an Author does not self-authorise. That is one message, and it is the strongest four rows in the document |
| Slide | Responsibilities and delivery planning |

### V4 — Model / information responsibility matrix

| Field | Value |
|---|---|
| Teaching purpose | Show that each container has exactly one accountable originating task team — and that discipline, task team and party are not the same thing |
| Likely source | [`supporting/model-information-responsibility-matrix.md`](../../supporting/model-information-responsibility-matrix.md) §3.1 |
| Derivable from repository? | **Yes** |
| Live observation useful? | No |
| Over-detail risk | **Medium.** Six rows is close to the limit. Consider showing the three MEP rows plus the Fire row, which makes the party-versus-task-team point on its own: MEC, ELE and PLM from one MEP Consultant, FIR from a separate Fire Consultant |
| Caution | Every allocation is **PROPOSED GOVERNANCE under TA-03**. The slide must not imply appointed organisations |
| Slide | Responsibilities and delivery planning |

### V5 — Information-delivery schedule

| Field | Value |
|---|---|
| Teaching purpose | Show that delivery is planned by **event, recipient and purpose** — not by date |
| Likely source | [`supporting/information-delivery-schedule.md`](../../supporting/information-delivery-schedule.md) §2 event-concept table; §3.2 conditions table |
| Derivable from repository? | **Yes** |
| Live observation useful? | No |
| Over-detail risk | **Medium.** The three-row event table is well-sized for a slide. The §3.2 conditions table is denser but carries the "suitability is coordination only" point |
| Caution | **No dates exist.** TRN-E03 is **BLOCKED**. An audience used to programmes will read this as an incomplete schedule unless told plainly that event-triggered is the deliberate position |
| Slide | Responsibilities and delivery planning |

### V6 — CDE workflow-state strategy

| Field | Value |
|---|---|
| Teaching purpose | Show information moving between states **by decision, not by drift** |
| Likely source | [`supporting/cde-workflow-state-strategy.md`](../../supporting/cde-workflow-state-strategy.md) §2 transition sequences; §1 four-state table |
| Derivable from repository? | **Yes** — the §2 sequences are already diagram-shaped and would redraw cleanly |
| Live observation useful? | Not for this visual |
| Over-detail risk | **Medium.** Three sequences on one slide is too many. Use the production-and-sharing route alone; mention the correction route in speech |
| Note | This is the single best redraw candidate in the module — the source is text, but its structure is a diagram |
| Slide | CDE workflow |

### V7 — Coordination-review strategy

| Field | Value |
|---|---|
| Teaching purpose | Show coordination as a **cycle with verification and closure**, not as a clash report |
| Likely source | [`supporting/coordination-review-strategy.md`](../../supporting/coordination-review-strategy.md) §17 coordination cycle |
| Derivable from repository? | **Yes** |
| Live observation useful? | Optionally, paired with V10 |
| Over-detail risk | **High.** The full cycle is sixteen steps. Redraw as a loop with five or six labelled stages; the sixteen steps belong in speaker notes, not on the slide |
| Slide | Coordination and review |

### V8 — Governance-decision register

| Field | Value |
|---|---|
| Teaching purpose | Show that decisions, assumptions and open questions are **recorded and traceable** — including the ones that are still open |
| Likely source | [`supporting/governance-decision-register.md`](../../supporting/governance-decision-register.md) §1 register summary; the **UD-001** entry in §4 |
| Derivable from repository? | **Yes** |
| Live observation useful? | No |
| Over-detail risk | **High for the summary table** — it runs to more than twenty rows with long status strings, several of which name publication-planning decisions that are irrelevant to Module 1 and will pull questions off-topic. **Low for UD-001 alone**, which is three rows of observed team-space bindings and makes its point instantly |
| Recommendation | Use the **UD-001 evidence table**, not the register summary. It is the sharpest thing in the repository for the approval-versus-implementation slide |
| Slide | Approval versus implementation |

### V9 — Representative ACC CDE folder or workflow view

| Field | Value |
|---|---|
| Teaching purpose | Connect the four conceptual states to something the audience recognises on screen — and then immediately undercut the connection, because **states are not folders** |
| Likely source | Live ACC / Forma Data Management interface |
| Derivable from repository? | **No** — no screenshots are committed |
| Live observation useful? | **Yes, potentially.** A single bounded read-only view of the project root would serve. Would require separate authorisation |
| Over-detail risk | **High, and of a different kind.** A platform view can expose folder contents, filenames, user names, dates and activity that are not needed for the teaching point and should not be projected. Any such asset would need review and cropping before use |
| Caution | The adopted root topology (`0. Common Files`, `01. WIP (Work in Progress)`, `02. Shared`, `03. Published`) is approved **with conditions**, with **verification pending** and **no child structures approved** (CGD-001). A folder view is evidence of configuration, never of governance |
| Slide | CDE workflow |

### V10 — Representative Revit or federated-model view

| Field | Value |
|---|---|
| Teaching purpose | Show what "federation does not merge ownership" actually looks like — several disciplines visible together, each still owned by its originator |
| Likely source | Revit view, or a federated coordination view |
| Derivable from repository? | **No** |
| Live observation useful? | **Yes, potentially** |
| Over-detail risk | **Medium.** A full federated model at projection size reads as coloured noise. A partial view — two or three disciplines at one interface — teaches better than the whole building |
| Caution | Only Architecture was observed as a populated direct production stream at the level inspected (OF-002). A view must not be captioned in a way that implies all six disciplines are modelled and active |
| Slide | Coordination and review |

---

## 2A. Slide-specific visual plan — Slides 4–8

The entries above are candidate *evidence sources* for the module as a whole.
This section plans the actual visual for each developed slide.

**All five are producible from Markdown alone.** None requires an image asset,
none requires a screenshot, and **live Autodesk observation is unnecessary for
every one of them** — the content is already committed text that needs redrawing
or extracting, not observing.

**No image assets are created in this increment.**

### Slide 4 — Who prepares, reviews and approves the BEP?

| Field | Value |
|---|---|
| **Proposed form** | **Role-flow diagram** — five functions left to right: prepare / maintain → contribute → review → approve → implement, with the consulted roles shown as inputs feeding the first box |
| **Repository source** | IM Responsibility Matrix §3.1 (row G1) and §3.7 (rows A2–A4); BEP §5.5, §5.9, §9.10 |
| **Enlarge / simplify** | Enlarge the five function names — they are the slide. Simplify G1 to a single caption: *BIM Manager performs; AP, LDP, BC and TTL are consulted*. Show the BEP §9.10 route as a thin arrow beneath, six words maximum per step |
| **Must not appear** | Any person's name; any organisation name; the full G-row table; the AG-001 to AG-005 governance identifiers (correct but off-topic here, and they invite publication-planning questions the module does not cover) |
| **Producible from Markdown alone?** | **Yes** — a redraw of committed text |
| **Live Autodesk observation** | **Unnecessary** |

**Design note.** The temptation is a hierarchy diagram. Resist it — a hierarchy
implies reporting lines, and BEP §5.2 is explicit that its role model is a
conceptual functional model, **not an appointment or organisation chart**. A
left-to-right flow of *acts* avoids the implication entirely.

### Slide 5 — Template versus project-specific BEP

| Field | Value |
|---|---|
| **Proposed form** | **Two-column comparison**, with a third element beneath: a short honest list of what Harrismith has *not* decided |
| **Repository source** | Left column: teaching synthesis, no source. Right column and the unresolved list: IM Responsibility Matrix §6; Model / Information Responsibility Matrix §6; Information Delivery Schedule §7; BEP §9.7 |
| **Enlarge / simplify** | Enlarge the required message. Cut the comparison to five rows per column — the outline holds nine, which is a reading exercise, not a slide. Show four unresolved items, not nine |
| **Must not appear** | Any suggestion that the comparison comes from the Harrismith documents; any real company's template; the full unresolved-matters tables from three separate sources |
| **Producible from Markdown alone?** | **Yes** |
| **Live Autodesk observation** | **Unnecessary** |

**Labelling requirement.** If the comparison is shown as a slide, the
teaching-synthesis status belongs in the speaker's mouth, not necessarily on the
slide — but it must be said. See [`source-map.md`](source-map.md) section 5.

### Slide 6 — The Harrismith BEP structure

| Field | Value |
|---|---|
| **Proposed form** | **Document-relationship diagram** — the BEP central; the five supporting resources arranged around it; the governance-decision register alongside all of them rather than beneath |
| **Repository source** | BEP §1.4 and §13.2 (the six supporting resources and what each holds); BEP §13.1 (the non-duplication reason) |
| **Enlarge / simplify** | Enlarge the seven document names. Give each supporting resource a **three-to-five word** caption, not the full purpose sentence. Consider one call-out: *detail lives in one place only* |
| **Must not appear** | File paths in full (`supporting/information-management-responsibility-matrix.md` is unreadable projected — use "Information Management Responsibility Matrix"); any arrow implying contractual authority or legal hierarchy; any completion indicator, tick or progress bar |
| **Producible from Markdown alone?** | **Yes** |
| **Live Autodesk observation** | **Unnecessary** |

**Design note.** Draw the register **alongside** the whole set, not below the
BEP. It records decisions about every document including the BEP itself, and
placing it in a subordinate position misrepresents what it does.

**Second design note.** Avoid arrowheads that read as "flows into" or "authorises".
Plain connecting lines are safer — the relationship being shown is *holds the
detail for*, not *derives authority from*.

### Slide 7 — Two responsibility matrices, two different questions

| Field | Value |
|---|---|
| **Proposed form** | **Two-column comparison** with one **simplified matrix extract** under each column |
| **Repository source** | IM Responsibility Matrix §3.3 (rows P1 and P4) and its purpose statement; Model / Information Responsibility Matrix §3.1 (the MEC / ELE / PLM / FIR rows) and its purpose statement |
| **Enlarge / simplify** | Enlarge the two questions — they are the slide's message. Cut the IM extract to **two rows and four columns** (P1, P4 × Aut, Chk, TTL, BC). Cut the model extract to **four rows and three columns** (container, originating party, task team) |
| **Must not appear** | The full nine-column IM grid; all seven IM sub-tables; any RACI letters; any role holder name; the model matrix's format, state, interface or dependency columns |
| **Producible from Markdown alone?** | **Yes** |
| **Live Autodesk observation** | **Unnecessary** |

**This is the highest over-detail risk in Slides 4–8.** Both source documents are
wide tables, and both are unreadable when projected whole. The two extracts
above are six rows in total, and each makes exactly one point: *an Author does not
self-authorise*, and *one party can hold three task teams*.

### Slide 8 — Information-delivery planning

| Field | Value |
|---|---|
| **Proposed form** | **Simplified schedule extract** — one TRN-E01 row shown vertically as field/value pairs — plus a small three-row event table |
| **Repository source** | Information Delivery Schedule §1 (the sixteen fields), §2 (event concepts), §3.1–3.2 (TRN-E01 rows and conditions), §5.1 (why TRN-E03 is blocked) |
| **Enlarge / simplify** | Show **one** container's row, turned on its side — container, originator, recipient, purpose, state/suitability, checking, authorisation, timing. Eight lines. Enlarge the timing value: **event-triggered / TBD**. Show the three events as three lines with their statuses |
| **Must not appear** | All sixteen fields as a horizontal table; all six TRN-E01 rows; the TRN-E02 conditional template rows; any invented date, month, stage name or programme bar; the full five-row blocking table (state the count in speech, show at most two) |
| **Producible from Markdown alone?** | **Yes** |
| **Live Autodesk observation** | **Unnecessary** |

**The one thing this slide must show visually:** a field labelled *Timing* whose
value is **event-triggered / TBD**. Saying "there are no dates" is weaker than
letting the audience see the field and read the value. It converts an apparent
omission into a visible, deliberate position.

**Prohibition specific to this slide.** No calendar, no Gantt fragment, no stage
sequence, no month labels — not even as illustrative decoration. Anything that
looks like a programme will be read as one.

---

## 2B. Slide-specific visual plan — Slides 9–14

Same discipline as §2A. **No image assets are created in this increment.**

An additional field appears here — **overclaim risk** — because Slides 9–13 all
describe governed processes that are **not evidenced as running**. A visual that
looks like a live system implies implementation the sources expressly deny.

### Slide 9 — Information moves through controlled CDE states

| Field | Value |
|---|---|
| **Teaching purpose** | Show four controlled states, each defining permitted use rather than location |
| **Proposed form** | Simplified state-flow diagram using Harrismith terminology |
| **Repository source** | CDE Workflow & State Strategy §1 (four-state table), §13 (version/revision/state/status/suitability); BEP §6.3, §6.7 |
| **Simplify** | Four states, four short definitions. One line under each on what it does *not* mean |
| **Omit** | **`Archived` — it is not an adopted Harrismith state.** The fourth is **Record / Retained**. Also omit any folder icon, any folder path, and the full §13 five-term table (state it in speech) |
| **Evidence classification** | **Direct** — the states and their definitions are source wording |
| **Producible from Markdown?** | **Yes** |
| **Later bounded observation?** | Would add little. A platform view would show *folders*, which is the misreading this slide exists to prevent |
| **Overclaim risk** | **Medium.** A clean four-box flow implies the flow is operating. Caption it as the governed model, not as current project behaviour |

**Design note.** Draw *Record / Retained* deliberately detached — no folder, no
box in the same row as the others if that reads as a location. The source is
explicit that it is a conceptual state and a retention requirement, not
necessarily a folder, and that the retention approach is TBD.

### Slide 10 — A folder location is not the same as an information status

| Field | Value |
|---|---|
| **Teaching purpose** | Separate technical file movement from governed status transition; separate permission from authority |
| **Proposed form** | Two-column comparison — *technical action* against *governed decision* — with permission and authority shown as separate, non-touching concepts |
| **Repository source** | CDE Strategy §3 (transition control table T1–T8), §14 (access and permission model), §17 (platform implementation rules); BEP §5.9, §9.7 |
| **Simplify** | Show **four transitions, not eight** — T1, T4, T7, T8. Four columns only: from, to, trigger/check, required function. Enlarge the two **UNRESOLVED — TBD** values |
| **Omit** | All three sub-tables of §3 in full; T2, T3, T5, T6; any arrow suggesting automation; any Autodesk permission-settings screenshot |
| **Evidence classification** | **Direct** for the transitions, triggers, functions and the unresolved authorities; **synthesis** for the required message |
| **Producible from Markdown?** | **Yes** |
| **Later bounded observation?** | **No — and it would be actively counterproductive.** A permissions view invites exactly the permission-equals-authority inference the slide refutes |
| **Overclaim risk** | **Low, if T4 is shown blocked.** High if the sequence is drawn as complete — which would invent an authority the sources leave unresolved |

**Requirement, not preference.** T4 must appear with its authority marked
unresolved and its status blocked. A tidy end-to-end diagram here would
manufacture governance, and the module spends Slide 13 arguing against exactly
that.

### Slide 11 — Coordination is a managed review cycle

| Field | Value |
|---|---|
| **Teaching purpose** | Show coordination as a repeatable cycle, not a clash test |
| **Proposed form** | Circular or staged cycle — six labelled stages |
| **Repository source** | Coordination & Review Strategy §17 (the sixteen-step cycle), §1 (principles), §8 (federation), §12 (finding vs Issue), §21 (completion) |
| **Simplify** | Six stages: prepare → federate → check → triage → resolve → verify and close. The sixteen source steps belong in speaker notes |
| **Omit** | The full sixteen-step list; any Navisworks or Model Coordination screenshot; any clash count; any tolerance value (**TBD** in source); any meeting frequency (**not established**) |
| **Evidence classification** | **Direct** for the cycle and the four distinctions; **interpretation** for the six-stage grouping |
| **Producible from Markdown?** | **Yes** |
| **Later bounded observation?** | **Possibly, later** — a Model Coordination view could illustrate federation. But see the overclaim risk, which is the highest in the module |
| **Overclaim risk** | **High.** The sources record that **no Design Collaboration Coordination Space was observed configured** (OF-005), that the issue status model is **not claimed to be configured**, and that the taxonomy-to-platform mapping is **not yet made**. Any platform imagery here would imply a running coordination process that is not evidenced |

**Caption requirement.** If a federated-model image is ever used, it is captioned
as *the governed coordination model* — never as *Harrismith's coordination
process in operation*.

### Slide 12 — From coordination issue to recorded resolution

| Field | Value |
|---|---|
| **Teaching purpose** | Show that detection and recording are not resolution and closure |
| **Proposed form** | Concise issue-lifecycle diagram — the six governed statuses in sequence, with Deferred and Escalated branching off |
| **Repository source** | Coordination Strategy §15 (status model), §13 (triage outcomes), §16 (assignment), §18 (technical resolution), §19 (verification), §27 (worked example) |
| **Simplify** | Six statuses plus two branches. Add one call-out on the verification step — *closure follows re-coordination against reshared information* |
| **Omit** | The seven-type issue taxonomy; the seven triage outcomes; any ACC Issues screenshot; any issue identifier, clash coordinate, tolerance or named person |
| **Evidence classification** | **Direct** for the status model and the closure rule; **interpretation** for the eight-step teaching sequence and the five-function table |
| **Producible from Markdown?** | **Yes** |
| **Later bounded observation?** | **No.** An ACC Issues view would directly contradict the source's own statement that the status model is not claimed to be configured |
| **Overclaim risk** | **High — the highest of any single visual in the module.** A lifecycle diagram styled to resemble an ACC Issues board would assert a verified live workflow that does not exist |

**Do not make this look like a platform.** Plain boxes, governance labels, no
product chrome. If the diagram could be mistaken for a screenshot, redraw it.

### Slide 13 — Approval does not prove implementation

| Field | Value |
|---|---|
| **Teaching purpose** | Separate approval, authorisation, implementation, evidence and verification |
| **Proposed form** | Two-column comparison — *evidence of approval* against *evidence of implementation* |
| **Repository source** | Training Baseline 0.1 Approval Decision §3, §8, §11; BEP §12.3, §12.8, §12.9, §9.11; CDE Strategy §6 (intended vs implemented) and §16 (evidence); Coordination Strategy §22 |
| **Simplify** | Five rows per column at most. Consider the UD-001 lifecycle strip beneath, with the **STOPS HERE** marker enlarged — it teaches faster than the table |
| **Omit** | **The publication-planning history** — conditions C1–C6, prerequisites P1–P8, PAD-001, the publication hold, the naming control. None of it belongs on this slide. Also omit any completion percentage or maturity score |
| **Evidence classification** | **Direct** for "approval is not implementation, and implementation is not verification" and for the outstanding-implementation statements; **interpretation** for the five-state framing; **synthesis** for the required message and for *correctly named information* as an evidence example |
| **Producible from Markdown?** | **Yes** |
| **Later bounded observation?** | **No** — and note the irony worth avoiding: observing the platform to prove implementation would be a separate authorised activity, and the point of the slide is that no such verification has been performed |
| **Overclaim risk** | **Inverted here.** The risk is *underclaiming* — presenting Harrismith as broken rather than as honestly incomplete. Frame the unresolved list as discipline |

**Scope guard.** This slide has one job. If the visual grows a publication
timeline, it has left the increment's boundary and reopened a paused programme.

### Slide 14 — What must Triviron decide for itself?

| Field | Value |
|---|---|
| **Teaching purpose** | Move from worked example to the audience's own project, as questions |
| **Proposed form** | Transfer diagram: `worked example → questions → project-specific decisions → implemented Triviron BEP` |
| **Repository source** | The unresolved-matters sections across all seven sources, plus [`source-map.md`](source-map.md) subject 10. **No Triviron source exists** |
| **Simplify** | Four boxes in the transfer chain. Beneath it, **five or six questions**, not thirteen — the full list belongs in the notes and the handout |
| **Omit** | **Every Triviron fact, name, date, organisation, platform choice and requirement.** Also omit any tick, progress indicator or completion state on the final box — the Triviron BEP does not exist |
| **Evidence classification** | **Synthesis** for the closing message and the three takeaways; **direct** for each question's derivation from a recorded Harrismith gap |
| **Producible from Markdown?** | **Yes** |
| **Later bounded observation?** | **Not applicable.** No Triviron material exists to observe, and Harrismith observation would add nothing here |
| **Overclaim risk** | **High, of a specific kind.** The final box — *implemented Triviron BEP* — must read as a destination, not a plan. Anything resembling a schedule, phase count or scope estimate would assert Triviron decisions that do not exist |

**Design note.** Draw the final box in outline only — unfilled, dashed, or
otherwise visibly not-yet-real. The first three boxes describe what exists; the
fourth describes work nobody has started.

---

## 3. Summary

| Ref | Visual | From repo? | Live obs. may help | Over-detail risk |
|---|---|---|---|---|
| V1 | Project / model image | No | Yes | Low |
| V2 | BEP extract | Yes | No | High |
| V3 | IM responsibility matrix | Yes | No | Very high |
| V4 | Model / information matrix | Yes | No | Medium |
| V5 | Information-delivery schedule | Yes | No | Medium |
| V6 | CDE workflow states | Yes | No | Medium |
| V7 | Coordination cycle | Yes | Optional | High |
| V8 | Governance register / UD-001 | Yes | No | High / Low |
| V9 | ACC CDE folder view | No | Yes | High |
| V10 | Revit / federated view | No | Yes | Medium |

**Six of ten are derivable from the repository today** (V2–V8). Four require
material that does not exist in the repository (V1, V9, V10) — and of those, V1
is the one whose absence would be most felt, because the talk opens with it.

### Slides 4–8 — all five producible without any external material

| Slide | Form | From Markdown alone? | Live observation |
|---|---|---|---|
| 4 | Role-flow diagram | Yes | Unnecessary |
| 5 | Two-column comparison + unresolved list | Yes | Unnecessary |
| 6 | Document-relationship diagram | Yes | Unnecessary |
| 7 | Two-column comparison + two matrix extracts | Yes | Unnecessary |
| 8 | Simplified schedule extract + event table | Yes | Unnecessary |

This is worth stating plainly: **the nine-minute middle of the presentation
needs no screenshots, no model views and no Autodesk access.** It is redrawn and
extracted text.

### Slides 9–14 — all six producible without any external material

| Slide | Form | From Markdown alone? | Live observation | Overclaim risk |
|---|---|---|---|---|
| 9 | State-flow diagram | Yes | Adds little | Medium |
| 10 | Two-column: technical action vs governed decision | Yes | **Counterproductive** | Low if T4 shown blocked |
| 11 | Staged coordination cycle | Yes | Possibly later | **High** |
| 12 | Issue-lifecycle diagram | Yes | **No** | **High** |
| 13 | Two-column: approval vs implementation | Yes | No | Inverted — risk is underclaiming |
| 14 | Transfer diagram | Yes | Not applicable | High, Triviron-specific |

**The whole presentation is producible from committed Markdown.** Of the ten
candidate evidence sources in §2, only V1 (project/model image), V9 (ACC folder
view) and V10 (Revit/federated view) require material that does not exist — and
none of them is required for any of the fourteen slides to be delivered. They
would enrich Slides 1, 9 and 11; they are not prerequisites.

**Live Autodesk observation is unnecessary for every slide in the deck.** For
Slides 10 and 12 it would be worse than unnecessary: a permissions view or an
ACC Issues board would assert precisely the implementation the sources record as
not evidenced.

## 4. Standing cautions

1. **No live Autodesk work is authorised by this plan.** Every "live observation
   useful" note records a possible future need, bounded and read-only, requiring
   separate authorisation.
2. **Screenshots of platform views can carry more than intended** — filenames,
   user names, activity history, folder contents. Any captured asset is reviewed
   and cropped before it reaches a slide.
3. **Configuration is not governance.** A folder view proves what the software is
   doing. It never establishes that anyone is appointed, responsible or
   authorised (BEP §1.5).
4. **Extracts are cropped to the rows that carry the message.** A full-table
   screenshot is a failure of preparation, not a thorough one.
5. **Every extract inherits its source's status.** Sources are approved with
   conditions and **not published**. A slide must not imply otherwise.
6. **No asset is committed to `assets/` without reading
   [`../assets/README.md`](../assets/README.md) first.**
