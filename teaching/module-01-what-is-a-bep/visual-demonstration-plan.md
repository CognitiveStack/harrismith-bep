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
