# Module 6 — Speaker Notes

**Status:** Presenter notes for teaching material. **Not governance.**

**Notes exist for all fourteen slides**, together with the **normal and emergency
module closings** and a one-sentence **Module 7 bridge**. **No slide lacks
presenter notes.**

**No rehearsal has been performed.** Timing throughout remains **allocated, not
measured**.

**The per-slide times are pacing allocations.** **No automatic slide-transition
timing exists; advance each slide manually when ready.**

Statement IDs refer to [`source-map.md`](source-map.md) §3. Source identifiers
`S1`–`S14` are defined in [`source-inventory.md`](source-inventory.md).

**Timing: `20.0 minutes allocated — not measured`. Do not describe the
per-slide times as measured.**

---

## Slide 1 — Module 6: from who is responsible to what actually happened · 1.0 min

### What you are doing here

Three things, in one minute: **close Module 5**, **open Module 6's question**,
and **set the evidence boundary before anyone forms an implementation belief**.

The third one is the reason this slide exists. If the audience leaves Slide 1
thinking Harrismith runs a coordination cycle, everything after it is heard
wrongly.

### Opening sentence

> *"Module 5 finished with three resources that say who is responsible for
> producing which information. It also finished with a warning: a matrix records
> responsibility, it never records occurrence. Module 6 is the module about
> occurrence."*

### Delivery

Take the BEP §8.1 definition slowly. The **second half** is the part worth the
pause:

> *"Its purpose is not to generate clash counts. A clash count measures how much
> software found; it says nothing about whether anything was understood, decided
> or fixed."*

That sentence is doing the work of a whole slide. It is the BEP telling you, in
its own words, that the number everybody asks for is the number that means
least.

Then §9.1 — *"the decision-control layer between production and use."* Two
sections, two jobs: **§8 governs a process, §9 governs decisions.** Module 6 has
to hold both.

### The status strip is not a footnote

Deliver it as the slide's second message, not as small print:

- four principal resources — **approved with conditions**, publication **not
  authorised**;
- the Coordination & Review Strategy's arrangements — **`PROPOSED GOVERNANCE`**;
- its own sentence — *"This strategy does not describe the live platform"*;
- **`GCR-006` — one complete governed coordination cycle to be exercised and
  evidenced — OPEN.**

> *"So everything I am about to describe is governed, and none of it has been
> shown to run. Both of those are true, and I am going to keep saying both."*

### The trap on this slide

**The audience hears "coordination" and pictures a clash meeting they have been
in.** They then map everything you say onto that memory, and the governance
distinctions slide off.

Name it early:

> *"If you have sat in a clash-detection review, park it for ten minutes.
> Harrismith is not describing a meeting; it is describing a controlled route,
> most of which has not been exercised."*

### If asked

**"Has any of this actually been done?"**

> *"Fragments. A Model Coordination model set exists with zero coordinated
> versions, two Client Reviews are open, one Coordination-type Issue is open. The
> validation record's own conclusion is 'partially traceable, not yet
> demonstrated as a complete cycle.' `GCR-006` is the open condition that says
> exactly that. Slide 3 has the detail."*

**"Who signs off coordination?"**

> *"Nobody yet, and the BEP says so rather than defaulting it. Publication and
> exchange authority is unresolved at §9.7 — expressly not automatically the BIM
> Manager, the BIM Coordinator, the CDE Administrator or the Architect. Recipient
> acceptance has no defined workflow at §9.8."*

**"Is `GCR-006` just paperwork?"**

> *"It is a carried condition of the baseline approval. It says one complete
> governed coordination cycle has to be exercised and evidenced. Until that
> happens, nobody can point at this project and say the process works — only
> that it is defined."*

### Do not say

- That coordination "is running" or "is in place".
- That the resources are "approved" without "with conditions".
- Any role holder, company or person.
- That Module 6 will resolve the publication or acceptance authority.
- That `GCR-006` is close to closure, or a formality.

### Transition to Slide 2

> *"Before any of that route makes sense, we have to stop nine different things
> from turning into one word. The BEP is unusually direct about this."*

### Recovery line if time is short

> *"Module 5 said who is responsible. Module 6 asks what happened, who decided
> and what was verified. Harrismith governs that route in detail — and a complete
> cycle has not yet been demonstrated."*

### Delivery warning

**Do not deliver the definition without the status strip.** They are one unit.
Splitting them is how a governance module becomes an implementation claim.

---

## Slide 2 — Nine objects, and the words that collapse them · 1.5 min

### What you are doing here

Fixing the vocabulary **before** the process. Nine distinct things: six
decisions from BEP §9.2, three coordination objects from the strategy §12.

This is the module's most heavily controlled slide — **ten of eighteen
statements are `CONTROLLED`**. Most of what you say here is quotation.

### Opening sentence

> *"English gives us one word — 'approval' — for about six different decisions.
> The BEP refuses to. Section 9.2 is worth reading almost verbatim."*

### Delivery

Walk the six terms. Keep each to a sentence. The pairs that matter most:

- **Check versus Authorise.** *"Checking verifies against a requirement. It
  approves nothing, and it does not authorise sharing — that is a separate
  decision at §9.4."*
- **Authorise versus Accept.** *"Authorise is the sender permitting progression
  for a purpose. Accept is the **recipient**, afterwards, and its authority is
  unresolved."*
- **Coordinate versus everything.** *"Coordinate is the interface process — the
  BEP adds three words: 'not design approval.'"*

Then the §9.1 line, delivered as the rule it is:

> *"'Approval' is not used as a catch-all for different decision functions."*

Then the three coordination objects, and the inequality:

> **`Clash / finding ≠ Issue`**

Land §8.7 hard:

> *"Not every clash becomes an Issue. Many findings are tolerable, duplicated,
> out of scope, already known, or artefacts of the test setup. Creating an issue
> is a decision."*

### The dangerous word

**`Accepted condition`.** Spend fifteen seconds on it:

> *"At triage, 'Accepted condition' means the finding needs no further action for
> that check and that purpose. It is not recipient acceptance. It is not design
> approval. The strategy says so in terms — 'a coordination disposition and
> nothing more.' Two documents, one word, two entirely different objects."*

### Two scopes, recorded not merged

> *"One honest wrinkle: the BEP defines 'Issue' slightly more narrowly than the
> strategy does. The strategy adds ownership, escalation and a residual
> 'otherwise needs a controlled project record' limb. We teach the strategy's,
> because the BEP hands it the detail — and we record that the BEP's is
> narrower. Neither gets rewritten to match."*

### The trap on this slide

**Someone will try to map these onto a platform's status list** — or onto RACI.
Refuse both:

> *"These are governance decisions. A platform status is a rendering of a
> decision, not the decision. And RACI was refused on the record back in Module
> 5 — for exactly this reason: it collapses checking from authorising."*

### If asked

**"Isn't 'review' just a softer word for 'check'?"**

> *"No. Check is verification against a defined requirement before progression.
> Review is consideration for a stated purpose. Different criteria, different
> function, different moment. The BEP also names two different reviews —
> coordination review at §9.5 and delivery review at §9.6."*

**"Our platform calls everything an Issue. Does that matter?"**

> *"It matters if the label starts doing the governing. The strategy's Issue
> types are proposed governance concepts and are expressly not Autodesk
> system-native labels. Mapping platform fields onto them is an implementation
> decision, and it has not been made."*

**"Who decides whether a finding becomes an Issue?"**

> *"It is decided at triage — that is Slide 8. The responsibility matrix
> allocates the coordination-process functions to the BIM Coordinator; it names
> no holder, and no holder is established."*

### Do not say

- Any two of the six terms as synonyms.
- "Approval" as a general word for a decision.
- That *Accepted condition* is acceptance.
- That the platform's statuses are the governed set.
- The triage outcomes, the Issue taxonomy or the status model — **Slides 7, 8
  and 10**.

### Transition to Slide 3

> *"Those are the pieces. Now the route they sit in — and the part most decks
> would leave out, which is how much of it has actually been done."*

### Recovery line if time is short

> *"Six decisions in the BEP — check, review, authorise, accept, reject,
> coordinate — and the BEP refuses to collapse them into 'approval.' Three
> coordination objects — finding, clash, Issue — and a clash is not an Issue
> until somebody decides it is."*

### Delivery warning

**Do not paraphrase the §9.2 definitions.** They are controlled wording, and the
precision is the teaching point. If you are short of time, cut the commentary,
not the definitions.

---

## Slide 3 — The governed coordination cycle — and the evidence gap · 1.5 min

### What you are doing here

Two jobs held together: **show the governed route**, and **show what has
actually been demonstrated**. Neither alone is honest.

### Opening sentence

> *"Here is the route Harrismith governs, end to end. Fifteen steps. Then I am
> going to show you how much of it anyone has been able to observe, which is
> considerably less."*

### Delivery — the route

Do not read all fifteen steps. Group them:

> *"Controlled Shared inputs, checked for readiness. Federate. Run the
> coordination checks. You get findings. Triage them — and only some become
> Issues. The originating team corrects in its own WIP, checks, authorises a
> controlled reshare back to Shared. Re-coordinate. Verify. Close or disposition.
> Retain the evidence."*

Then the two rules inside it, both quoted:

> *"The originating task team makes the technical change."*
> *"The BIM Coordinator manages the process, not the solution."*

And the boundary, which is where Module 4 is protected:

> *"Coordination creates no new information state. Rework returns information to
> WIP; controlled reshare returns it to Shared. Those are the only two state
> transitions in the whole cycle."*

Mention the variance briefly:

> *"The BEP words 'findings' and 'triage' as a single step; the strategy splits
> them. Same route. We record both rather than picking a winner."*

### Delivery — the evidence

**Change register here.** Slow down. This is the honest part of the module.

> *"One Model Coordination model set exists. Seven folders. **Zero coordinated
> versions.** No Design Collaboration Coordination Space configured. Two Client
> Reviews open, one Coordination-type Issue open — and the register's own words:
> 'No completed review, authorisation, verification or closure was
> established.'"*

Then the line that carries the slide:

> *"'Environment configured does not equal coordination process executed.' That
> is the register, not me."*

Then the recorded result, verbatim:

> **"Partially traceable. Not yet demonstrated as a complete cycle."**

> *"And `GCR-006` — one complete governed coordination cycle to be exercised and
> evidenced — remains open."*

### The counterweight — say it every time

> *"One thing this is not: an accusation. Absence of observation is not
> observation of absence. Nobody looked at everything, and nothing here says the
> other disciplines are absent from the project or behind on anything."*

### The trap on this slide

**Two opposite failures, and you have to avoid both.**

- **Overclaim** — describing the cycle as though it runs. The fragments make
  this tempting because they look like a cycle in progress.
- **Underclaim** — presenting the project as broken or immature. It is not.
  **A defined route with an open implementation condition is a normal, honest
  position for a project at this stage.**

> *"The route is governed and the cycle has not been exercised. That is not a
> failure — it is an accurate record, and it is the reason `GCR-006` exists as a
> condition rather than a footnote."*

### If asked

**"Doesn't the model set prove coordination is happening?"**

> *"It proves a capability is provisioned. Zero coordinated versions. The
> register makes the distinction explicitly — environment configured is not
> process executed — and it also keeps the two Autodesk services apart:
> provisioning Model Coordination does not configure the Design Collaboration
> Coordination Space, which remains unconfigured."*

**"There's an open Issue. Isn't that the cycle working?"**

> *"It is the cycle's first step being visible. An open item is an open item —
> the register's phrase. No completed review, authorisation, verification or
> closure was established against it."*

**"So the other five disciplines aren't participating?"**

> *"That is exactly the inference the sources forbid. Only Architecture was
> observed as a populated direct production stream, at one level, at one time.
> Absence of observation is not observation of absence."*

**"What would close `GCR-006`?"**

> *"One complete governed coordination cycle, exercised and evidenced. I am not
> going to speculate on when or by whom — no decision owner is established, and
> inventing one would be exactly the failure this module is about."*

### Do not say

- That the cycle is operating, running, or partially running.
- That the fragments are "a start" in a way that implies progress toward
  closure.
- That any discipline is absent, inactive, behind or non-compliant.
- Any date, frequency or tolerance.
- That `GCR-006` is nearly closed.
- Federation detail, readiness conditions, the interface matrix or triage
  outcomes — **Slides 4–8**.

### Transition to Slide 4

> *"Step three of that route is federation, and it is the step most likely to be
> misunderstood — because assembling the models looks like merging them."*

**Slide 4 is architecture only after T6-A.** If you are presenting this material
before Slide 4 is developed, **stop here and say so** rather than improvising
the next slide.

### Recovery line if time is short

> *"Fifteen governed steps from Shared inputs to retained evidence, with only two
> state transitions in the whole cycle. Observed: a provisioned environment with
> zero coordinated versions, two open reviews, one open issue, nothing completed.
> Partially traceable, not yet demonstrated."*

### Delivery warning

**Never deliver the cycle without the evidence, or the evidence without the
counterweight.** The cycle alone is an implementation claim; the evidence alone
is an accusation. **All three parts, every time.**

---

## Slide 4 — Federation: a lens, not an author · 1.5 min

### What you are doing here

Stopping a transfer that nobody intends and no source authorises. **Assembling
models looks like merging them**, and the visual similarity does the damage.

### Opening line

> *"We are about to put six disciplines' information into one view. Before we
> do, I want to be precise about what that view is — because it is the single
> place on this project where responsibility most easily goes missing."*

### The load-bearing explanation

BEP §8.5 is a list of four negatives. Deliver them as a list, not as prose:

> *"Federation does not merge authorship. It does not transfer technical
> ownership. It does not create a new design author. It does not turn discipline
> models into one jointly-owned authoring model."*

Then the sentence that does the most work:

> *"Nobody becomes responsible for another team's content by appearing alongside
> it."*

Say it twice if you have to. It is the whole slide.

Then the six separations. Do not rush them — **source container, federated view,
originator, technical ownership, coordination-process responsibility, deliverable
status.** The BIM Coordinator holds **exactly one** of those six: the process.

### Source boundary

`S1` §8.5 governs. `S2` §8 repeats it for `COORD-01` and adds the five
exclusions. **`S4` §3.4 allocates `COORD-01`; Module 5 taught it. Do not
re-teach the container allocation here.**

### Governance-status warning

**`S1` §8.5 is `CONTROLLED GOVERNANCE`; `COORD-01` and its exclusions are
`PROPOSED GOVERNANCE`** from `S4` §3.4 via `TA-03`. **Say which is which if
asked.**

### Implementation-status warning

**A Model Coordination model set exists with zero coordinated versions.** **No
completed federation or coordination run has been demonstrated.** If you show a
federated view on this slide, **it is a diagram of a concept, not a screenshot
of a project.**

### Words that must remain separate

**Aggregation** and **merging**. **Coordination view** and **authoring model**.
**Process responsibility** and **technical ownership**. **A federated view** and
**a deliverable**.

### What not to imply

- That ownership or authorship **flows into** the federated model.
- That the BIM Coordinator acquires authorship, technical approval or
  publication authority by chairing coordination.
- That the federation is a **"single source of truth"** — **no controlled source
  uses that phrase, and it implies exactly the merge the BEP denies.**
- That a model set with included folders **is** a completed federation.
- That `COORD-01` is scheduled, contracted or deliverable.

### Likely audience question

**"So who owns the federated model?"**

> *"The coordination process is led by the BIM Coordinator. The content is owned,
> discipline by discipline, by the task teams that authored it — before and after
> federation. Nobody owns the federation as a design artefact, because nobody
> authored it as one."*

**"Isn't the federated model the coordinated model we issue?"**

> *"Not automatically. `COORD-01` does not become a formal deliverable unless it
> is explicitly scheduled as one, and no such schedule entry exists. It is a
> lens, and lenses are not deliverables."*

**"Our models sit in the same folder — doesn't that make them one model?"**

> *"No. Folder location, platform environment and federation membership do not
> determine authorship. Tools do not define responsibility — that is BEP 8.4."*

### Transition

> *"So the federation is a lens. The next question is what is allowed to be in
> it — because 'the file is there' is not the same as 'the information is a
> governed input.'"*

### Delivery warning

**Never draw an arrow pointing into the federated view.** If your visual shows
containers feeding a central model, the audience reads ownership flowing inward,
and no amount of narration will remove it.

---

## Slide 5 — Inputs and readiness: what may enter a cycle · 1.5 min

### What you are doing here

Making **readiness an entry condition**, and separating eight things that look
identical in a file browser.

### Opening line

> *"Everyone has been in the meeting where somebody says 'the model's in there.'
> That sentence answers none of the questions Harrismith actually asks."*

### The load-bearing explanation

Walk the twelve register fields quickly — they are a list, not a lecture. Pause
on **`Information State`**:

> *"It must be Shared. Coordinating uncontrolled WIP is not the normal method —
> that is BEP 6.6 and 8.3."*

Then the ten readiness conditions. Group them rather than reading them out:

> *"Identity and originator. State and purpose. Checks completed and share
> authorised. Context, limitations, dependencies, version. Ten conditions,
> confirmed as applicable."*

Then the eight separations — the heart of the slide:

> *"Visible is not selected. Selected is not suitable. Suitable is not ready.
> Permission to read is not authorisation to rely. Observed content is not a
> governed input set."*

### Source boundary

`S2` §4 and §5 hold the register and conditions. `S1` §8.3 governs readiness and
supplies the completeness distinction. **`S6` governs the `Shared` state — do
not re-teach Module 4's state model.**

### Governance-status warning

**The register and the ten conditions are `PROPOSED GOVERNANCE`.** The
readiness-versus-completeness distinction is **`CONTROLLED`** — BEP §8.3.

### Implementation-status warning

**Only Architecture was observed as a populated direct production stream, at the
inspected level.** **No live version or revision values are recorded** — *"none
were observed or validated, and none is invented."* And **the intended
coordination environment remains unresolved** — no Coordination Space was
observed configured, and no configuration is approved.

### Words that must remain separate

**Uploaded** and **input**. **Readiness** and **completeness**. **Permission**
and **authorisation**. **Excluded** and **absent**.

### What not to imply

- That an uploaded or visible file **is** a controlled coordination input.
- That exclusion from a cycle says anything about the project.
- That limited observed content proves other containers do not exist.
- That any observed platform configuration **is** the approved coordination
  environment.
- **Any invented number** — deadline, completeness percentage, model-health
  score, required format, frequency, named approver, suitability code or
  platform workflow. **None exists.**

### Likely audience question

**"What percentage complete does a model need to be?"**

> *"There is no threshold, and inventing one would be the failure this slide
> exists to prevent. Readiness is not completeness — BEP 8.3 says information can
> be ready to coordinate while remaining incomplete, unapproved and subject to
> change. What matters is that the ten conditions are confirmed for the defined
> purpose."*

**"What if a discipline isn't ready?"**

> *"Exclude or defer it, and record the reason. An exclusion with a recorded
> reason is a governed outcome; coordinating an unready input quietly is not."*

**"Only Architecture is there — are the others behind?"**

> *"That inference is not available. Architecture was observed as a populated
> stream at one level at one time. Absence of observation is not observation of
> absence."*

### Transition

> *"Once you have a governed input set, you have to decide what to test — and
> Harrismith is explicit that you do not test everything."*

### Delivery warning

**Do not shorten the twelve fields or the ten conditions into a tidy five.**
They are controlled lists, and compressing them changes what readiness means. If
time is short, **group them aloud but leave them complete on the slide.**

---

## Slide 6 — Checks are chosen, not exhaustive · 1.5 min

### What you are doing here

Two jobs: **check selection is a governed choice**, and **neither a vendor
default nor a clash count carries authority**.

### Opening line

> *"The instinct is to test everything against everything. Harrismith declines,
> and gives a reason worth remembering."*

### The load-bearing explanation

> *"Testing everything against everything produces volume, not insight, and
> buries the findings that matter."*

Then the principle:

> *"A check exists because a meaningful interface exists."*

Walk the six check types briefly, and land the one people forget:

> *"Two of these — Information / Readiness, and Design / Interface Question —
> are not geometry at all. Not every category depends on automated detection, and
> they are no less governed for that."*

Then the twelve checks: **name the pattern, not all twelve.**

> *"Twelve proposed checks, built around structure and architecture as the two
> hubs, plus mechanical against the other services. Not all possible pairs are
> built — the matrix stops at meaningful interfaces rather than completing the
> combinatorial set."*

Then the two authority statements. **Slow down for both.**

> *"Every one of the twelve tolerances is TBD. And a software default tolerance
> is not a project requirement — a value shipped with a tool has no governance
> authority, and adopting it silently would convert a vendor default into a
> project rule."*

> *"Where no tolerance is approved, a check must not present a numeric threshold
> as though it carried governance authority. The check may still run. Its output
> is a finding for triage, not a compliance judgement."*

### Source boundary

`S2` §9, §10 and §11 hold the checks, types and tolerance position. `S1` §8.6
governs the selection principle and §8.1 the clash-count warning. **Detailed
combinations, tolerances and exclusions belong to `S2` — BEP §8.6 says so.**

### Governance-status warning

**All twelve checks are `PROPOSED`.** **Every tolerance is `TBD`.** They are
**proposed training coordination checks** — *"not evidence of real client
requirements, and they do not become project requirements by appearing here."*

### Implementation-status warning

**No check is recorded as executed.** Do not mark, colour or annotate any check
as run, passed or failed.

### Words that must remain separate

**Selected** and **exhaustive**. **Default** and **approved**. **Clash count**
and **coordination quality**. **A finding** and **a compliance judgement**.

### What not to imply

- That any numeric tolerance exists, or that a default is a reasonable
  placeholder.
- That every cycle runs every check.
- That the twelve cover every technical, regulatory or constructability concern.
- That **zero clashes** means coordinated — *"a zero-clash report can be produced
  by testing nothing, excluding everything, or resolving symptoms."*
- That a detected clash is a **design error**.
- That **no detected clash** proves coordination.

### Likely audience question

**"What tolerance should we use — 25 mm?"**

> *"There is no approved value, and I am not going to supply one. Every tolerance
> in the strategy is TBD, to be set by approved coordination requirement,
> technical standard, system requirement or documented decision. Different
> interfaces may need different rules — a single project-wide threshold is not
> assumed."*

**"Why not just run all-versus-all and filter afterwards?"**

> *"Because the filtering never happens, and the findings that matter get buried.
> The BEP declines blind all-versus-all for that reason."*

**"We got zero clashes — are we coordinated?"**

> *"You know what the software found under the settings it was given. Completion
> rests on required checks and dispositions, not on an absolute zero-clash
> state — that is Slide 12."*

### Transition

> *"A check produces output. Output is not yet a finding anybody has accepted,
> and a finding is not yet an Issue. That gap is where the governance lives."*

### Delivery warning

**Never write a number on this slide.** Not as an example, not as an
illustration, not with a caveat. **A number on a projected slide becomes the
project's tolerance by Monday.**

---

## Slide 7 — Finding, clash, Issue: and the decision between them · 1.5 min

### What you are doing here

**Slide 2 named the three objects. This slide develops the decision between
them.** Do not repeat the vocabulary walk — the audience has it.

### Opening line

> *"You have a check result on screen. Nothing has been decided yet. What turns
> that output into a governed record is a decision somebody takes, and it has
> criteria."*

### The load-bearing explanation

Lead with the boundary, then the criteria:

> *"Creating an Issue is a decision — taken at triage, not as an automatic
> consequence of detection."*

Then the strategy's criteria, in its own words:

> *"An Issue is created when a matter requires ownership, action, decision,
> tracking, verification or escalation — or otherwise needs a controlled project
> record."*

Then the five reasons a finding may not need one:

> *"Tolerable. Duplicated. Out of scope. Already known. An artefact of the test
> setup. Those are the BEP's own words, and they are five good reasons not to
> create a record."*

Then the point people miss:

> *"And it runs the other way too. A missing input, or an unresolved interface
> decision, may need a governed record and never be a clash at all."*

Finally, what creation does **not** establish:

> *"Creating an Issue records a matter for action. It does not prove it was
> correctly classified, correctly assigned, resolved or verified."*

### The recorded variance — say it plainly

> *"One honest wrinkle. The BEP's list is assignment, tracking, decision,
> verification. The strategy's is broader — it adds ownership, escalation, and a
> residual limb for anything otherwise needing a controlled record. We teach the
> strategy's, because the BEP hands it the detail. We record that the BEP's is
> narrower. Neither is rewritten."*

### Source boundary

`S1` §8.7 governs; `S2` §12 and §14 hold the detail. **The BEP expressly defines
no issue numbering or status codes.** **The status model is Slide 10 — do not
preview it.**

### Governance-status warning

**The seven Issue types are `PROPOSED` governance concepts.** *"These are not
Autodesk system-native labels, and no claim is made that the platform provides
them."* Any later mapping is *"an implementation decision, not yet made."*

### Implementation-status warning

**One open Coordination-type Issue was observed.** **No completed review,
authorisation, verification or closure was established.**

### Words that must remain separate

**Detection** and **decision**. **Finding** and **Issue**. **A clash** and **an
error**. **A governance concept** and **a platform object type**.

### What not to imply

- That every clash or finding **must** become an Issue.
- That detection alone creates a governed record.
- That creating an Issue proves valid triage.
- That the two Issue scopes should be reconciled.
- That a platform's object type **overrides** a controlled definition.
- Any Issue identifier, numbering scheme or status code. **None exists.**

### Likely audience question

**"Shouldn't we log everything, to be safe?"**

> *"Logging everything is how a register stops being read. The BEP lists five
> reasons a finding may not warrant an Issue, and creating one is a decision with
> criteria. A record nobody triages is not safety, it is noise."*

**"Our platform calls them Issues — so aren't they the same thing?"**

> *"The label may be the same; the definition is the project's. The strategy's
> seven types are proposed governance concepts and expressly not
> system-native labels. Mapping the platform's fields onto them has not been
> decided."*

**"Which definition wins, the BEP's or the strategy's?"**

> *"For teaching, the strategy's — because BEP 8.13 defers the detail to it. But
> we record that the BEP's is narrower, and neither is rewritten to match. That
> is a recorded variance, not a mistake."*

### Transition

> *"That decision has seven recorded outcomes — and one of them uses a word that
> means something completely different three sections later."*

### Delivery warning

**Do not re-run Slide 2 here.** If you find yourself defining *finding*, *clash*
and *Issue* again, you have lost the slide. **The subject is the decision, not
the nouns.**

---

## Slide 8 — Triage: seven dispositions, one dangerous word · 1.0 min

### What you are doing here

**One minute. Seven dispositions, and one warning.** Do not narrate the table —
put it up, name the seven, and spend the remaining time on `Accepted condition`.

### Opening line

> *"Triage has seven recorded outcomes. Six are unremarkable. One is the most
> misread word in the module."*

### The load-bearing explanation

Name the seven at pace — the slide carries the definitions:

> *"No action or false positive. Accepted condition. Action required, one task
> team. Action required, multiple task teams. Decision required. Deferred.
> Escalated. Seven. Not six, not eight."*

Then the traceability line:

> *"Material dispositions remain traceable. A finding closed without record is a
> finding that will be rediscovered."*

Then **spend half the slide here**:

> *"'Accepted condition' does not mean recipient acceptance or design approval.
> It means the finding requires no further action for the defined check and the
> defined coordination purpose. It is a coordination disposition and nothing
> more — that is the strategy's own wording."*

And the consequences, as a list:

> *"It is not recipient Accept. Not publication authorisation. Not technical
> approval. Not regulatory acceptance. Not acceptance of the container for every
> use. It does not release T4. It does not resolve acceptance authority. It does
> not unblock TRN-E03."*

### Source boundary

`S2` §13 holds all seven. `S1` §9.2 and §9.8 govern *Accept* as a recipient
function. **The Issue status model is `S2` §15 — Slide 10 owns it.**

### Governance-status warning

**The dispositions are `PROPOSED GOVERNANCE`.** **Recipient acceptance authority
is `UNRESOLVED` — no Appointing Party acceptance workflow is defined.**

### Implementation-status warning

**No completed triage decision has been established.** *"No completed review,
authorisation, verification or closure was established."*

### Words that must remain separate

**`Accepted condition`** and **`Accept`**. **Disposition** and **status**.
**Disposition** and **information state**. **Disposition** and **suitability
code** — and **no suitability code set exists on this project at all**.

### What not to imply

- That there are six dispositions, or eight.
- That two may be merged for simplicity.
- That a disposition is an Issue status, an information state, a suitability
  code or recipient acceptance.
- That **`Accepted condition`** is acceptance, approval, authorisation or
  regulatory clearance.
- That it releases `T4`, resolves acceptance authority or unblocks `TRN-E03`.
- That any triage decision **has been taken** on this project.

### Likely audience question

**"So 'Accepted condition' means the client accepted it?"**

> *"No — and that is exactly why the slide exists. It means the coordination
> finding needs no further action for that check and that purpose. Recipient
> acceptance is a different function, at a different time, held by a role that is
> unresolved on this project."*

**"Can we just merge 'one task team' and 'multiple task teams'?"**

> *"They record different things — how many teams must respond changes who owns
> the response and how it is coordinated. The register lists seven, and I am not
> going to hand you six."*

**"Is 'Deferred' just a polite 'ignored'?"**

> *"Not if it is done properly. Deferred is carried forward with a recorded
> reason. A finding closed without record is a finding that will be
> rediscovered — that is the strategy's line, and it is the difference between
> deferring and losing."*

### Transition

> *"Four of those seven send work somewhere. Which raises the question Slide 9
> answers: who owns the fix — and what does an assignment actually prove?"*

**Slide 9 is architecture only after T6-B.** If you are presenting before it is
developed, **stop here and say so** rather than improvising.

### Delivery warning

**This slide is one minute and it is a table.** Do not read the definitions
aloud — the audience can read faster than you can speak. **Your minute is best
spent on the one word that will otherwise be misused for the rest of the
project.**

---

## Slide 9 — Assignment and technical response: who owns the fix · 1.5 min

### What you are doing here

Keeping two functions apart that share a room: **coordinating an assignment** and
**owning a technical solution**. The BIM Coordinator does the first. The
originating task team does the second. Nothing about chairing the meeting changes
that.

### Opening line

> *"An Issue has been created and it has to go somewhere. Who it goes to, and
> what that assignment does and does not make them responsible for, is more
> precise in Harrismith than most projects manage."*

### The load-bearing explanation

Walk the seven assignment fields quickly — the slide carries them. **Land on the
two qualifiers**, because they are the honest part:

> *"Priority or impact — where established. A target trigger — only where
> genuinely established. And the strategy is explicit: no dates are invented.
> Where no target exists, the field records that rather than a plausible value."*

Then the division, quoted:

> *"The BIM Coordinator coordinates assignment. The originating or affected
> Task-Team Lead owns the technical response of its team."*

> *"An Issue assigned to a task team does not make the BIM Coordinator
> responsible for designing the fix. Coordinating an assignment and owning a
> solution are different things."*

Then where the work happens:

> *"Technical resolution occurs in the originating task team's WIP. A mechanical
> conflict means the Mechanical team evaluates and modifies MEC-01 if required.
> The coordinator may facilitate agreement — they do not author a discipline
> solution because they chair the meeting."*

And the multi-team case, which is the one people get wrong:

> *"Where several teams must change, each remains responsible for its own
> information. A jointly-agreed resolution is still a set of separate changes
> under separate responsibility."*

### Source boundary

`S2` §16 holds the assignment fields; §18 holds technical resolution. `S1` §8.8
and §8.10 govern. **`S3` §3.5 `X3` allocates the function — Module 5 taught the
matrix grammar; do not re-teach it.**

### Governance-status warning

**`PROPOSED GOVERNANCE`** for the assignment structure and `X3`.
**`CONTROLLED GOVERNANCE`** for *"the originating task team makes the technical
change"* and *"the BIM Coordinator manages the process, not the solution."*

### Implementation-status warning

**No assignment, technical response or WIP correction has been demonstrated.**
*"No actual Issue identifiers are created here."*

### Distinctions that must remain separate

**Issue assignment** · **process coordination** · **technical authorship** ·
**technical response** · **WIP correction** · **task-team check** ·
**controlled reshare**. Seven things, and a fluent speaker will merge at least
two of them without noticing.

### What not to imply

- That assignment **proves work started**.
- That a response **proves resolution**.
- That a **verbal agreement** modifies controlled information.
- That the **federated view is edited** to implement the fix — it is a lens, and
  Slide 4 established that.
- Any **named person**, organisation, due date, priority or Issue number.
- That the BIM Coordinator owns, designs or approves the solution.

### Likely audience question

**"Who do we assign it to if the role holder isn't appointed?"**

> *"To the function, not the person. The strategy assigns to the responsible task
> team or function, and all holders remain TBD. That is not a gap in the
> assignment — it is the assignment being honest about what exists."*

**"What if two teams both have to change something?"**

> *"Then both change their own information, and each remains responsible for it.
> A jointly-agreed resolution is still separate changes under separate
> responsibility — one agreement does not create one author."*

**"Can the coordinator just fix it in the federated model?"**

> *"No, on two counts. The federated view is a lens — Slide 4. And the
> coordinator does not author a discipline solution. The fix happens in the
> originating team's WIP, through their own checking route."*

### Transition

> *"That assignment carries a status. And a status is the single most
> over-interpreted object in coordination — so it is worth a slide of its own."*

### Delivery warning

**Do not supply an example date or priority, even hypothetically.** The strategy
says no dates are invented; a spoken example becomes a project convention faster
than a written one.

---

## Slide 10 — The Issue status model is not an information state · 1.5 min

### What you are doing here

Showing a six-status model, keeping two alternate dispositions **off the main
line**, and stopping five different misreadings of what a status means.

### Opening line

> *"Every coordination tool has statuses, and everyone reads more into them than
> they carry. Harrismith's model is six steps — and two things that are
> deliberately not steps."*

### The load-bearing explanation

Name the six in order:

> *"New. Triaged. Assigned. In Progress. Ready for Verification. Closed."*

Then the two, and **be explicit about the geometry**:

> *"Deferred and Escalated are controlled alternate dispositions. They are not a
> seventh and eighth stage — a matter does not pass through them on the way to
> Closed. It goes to one of them instead."*

Then the label point:

> *"Platform implementation may use different native labels. The governed
> meaning is what matters; a native label is a rendering of it, not a
> replacement for it. And the model is not claimed to be configured in Forma —
> configuring it would follow a governance decision that has not been taken."*

Then the five separations, briskly — the slide carries them.

Then **the two statuses that promise less than they look**, which is where the
minute is best spent:

> *"'Ready for Verification' means verification has not happened. It is a queue
> position, not an outcome."*

> *"And 'Closed' as a label does not by itself prove the closure conditions were
> met. A status change does not demonstrate that the technical condition
> changed."*

### Source boundary

`S2` §15 holds the model. `S1` §8.7 expressly defines **no** issue numbering or
status codes and defers the taxonomy to `S2`. **Slide 11 owns verification —
name it and move on.**

### Governance-status warning

**`PROPOSED GOVERNANCE`.** **The model is not claimed to be configured
anywhere.** Publication authorisation and recipient acceptance are separate
decisions and both remain **UNRESOLVED**.

### Implementation-status warning

**Two Client Reviews and one Coordination-type Issue were observed open.** *"An
open item is an open item."* **No completed review, authorisation, verification
or closure was established.**

### Distinctions that must remain separate

**Issue status** and **information state**. **Issue status** and **suitability
code** — and none exists on this project. **Issue status** and **recipient
acceptance**. **Issue status** and **publication authorisation**. **A label** and
**a technical fact**.

**And one worth naming aloud:** `Deferred` and `Escalated` appear on Slide 8 as
**triage dispositions** and here as **alternate status dispositions**. **Related
structures, not the same one, and neither is merged into the other.**

### What not to imply

- That `Deferred` or `Escalated` are **sequential stages**.
- That the model **is configured**, or that a platform mapping exists.
- That a **native label overrides** the governed meaning.
- That **`Ready for Verification`** means verified.
- That **`Closed`** proves anything was fixed or verified.
- That a status is a **state**, a **code**, an **approval** or **acceptance**.
- That the observed open items are **completed decisions**.

### Likely audience question

**"Our platform has different statuses — is that a problem?"**

> *"Not automatically. The governed meaning is what matters; a native label
> renders it. What would be a problem is the label quietly becoming the
> governance — and the mapping between them is an implementation decision that
> has not been taken."*

**"If it's Closed, it's done — surely?"**

> *"Closed is a label. Whether the closure conditions were met is a separate
> question, and Slide 11 is about exactly that. Closure follows re-coordination
> against reshared controlled information, not somebody changing a dropdown."*

**"Is 'Escalated' a failure state?"**

> *"No. It is a controlled disposition — a governed route for a matter that
> cannot be settled in the normal cycle. Recording it is the system working, not
> the system failing."*

### Transition

> *"`Ready for Verification` is a queue, not an outcome. So what does
> verification actually require? The strategy is precise, and it is stricter than
> most projects expect."*

### Delivery warning

**Never draw `Deferred` and `Escalated` in line with the six.** If your visual
puts them in the sequence, the audience counts eight steps and the distinction is
gone before you speak.

---

## Slide 11 — Verification: after reshare, against controlled information · 1.5 min

### What you are doing here

Three jobs: **when** verification may occur, **what** it tests, and **what it is
not** — plus one honest admission about what the sources do not settle.

### Opening line

> *"Somebody says 'it's fixed.' That sentence is not verification, and Harrismith
> is unusually blunt about why."*

### The load-bearing explanation

Lead with the sentence that carries the slide:

> *"A material Issue is not closed solely because someone says it was fixed in
> WIP. Closure follows re-coordination against reshared, controlled information —
> a change nobody can see in Shared information has not been demonstrated."*

Then the four prerequisites, **as conditions that must all hold**:

> *"Checked. Authorised for reshare. Returned to Shared. Included in
> re-coordination. All four, before verification is even possible."*

Then the three findings:

> *"And then you verify one of three things: the matter no longer exists, or it
> meets the agreed coordination rule, or it has an explicitly approved and
> recorded disposition. That third one matters — a matter can be verified as
> dispositioned rather than eliminated."*

Then the exclusions, quoted:

> *"Verification does not equal design approval, professional certification,
> publication authority, or recipient acceptance."*

And the four near-misses:

> *"Checking is not verification — it confirms readiness for the next decision.
> A technical response is not verification — it is the change, not the check on
> it. 'Ready for Verification' is not verification. And an Issue status alone is
> not verification evidence."*

### The honest admission

> *"One thing the sources do not settle. The BEP says the coordinator **may**
> verify. The strategy and the responsibility matrix treat verification as a
> defined act. And the completion conditions say 'required verification was
> completed' — conditioned on 'required.' Whether every cycle requires it is not
> established, and I am not going to decide it for them."*

### Source boundary

`S2` §19 holds the prerequisites, findings and exclusions. `S1` §8.10 and §9.5
govern; §9.3 supplies the checking distinction. **`S3` `X4` allocates it `Ck`.**
**Do not reteach Module 4's transition system** — WIP, controlled reshare and
`Shared` are all this slide needs.

### Governance-status warning

**`PROPOSED GOVERNANCE`** for §19. **`CONTROLLED GOVERNANCE`** for the
exclusions and the responsibility position. **`NOT ESTABLISHED`** for whether
verification is mandatory — **`H18`, and it stays that way.**

### Implementation-status warning

**No completed verification has been established.** Nothing on this project has
been verified.

### Distinctions that must remain separate

**Checking** and **verification**. **Technical response** and **verification**.
**`Ready for Verification`** and **verification**. **Verification** and
**approval, certification, publication authority, acceptance**. **Verification**
and **transfer of responsibility** — it transfers none.

### What not to imply

- That **every cycle requires** verification.
- That the BIM Coordinator is a **named holder**.
- That verification **authorises publication** or **accepts a deliverable**.
- That verification **certifies** professional or regulatory compliance.
- That a **screenshot or status label** proves verification.
- That verification **moves responsibility** off the originator.

### Likely audience question

**"The team says they fixed it — isn't that enough to close?"**

> *"Not for a material Issue. The strategy's words: it is not closed solely
> because someone says it was fixed in WIP. Closure follows re-coordination
> against reshared, controlled information. If nobody can see the change in
> Shared, it has not been demonstrated."*

**"Does verification mean the design is approved?"**

> *"No — and the matrix says so in the same breath as allocating it. Coordinator
> verification confirms the coordination process reached a disposition. It is not
> discipline design approval, professional certification, or acceptance of
> technical responsibility."*

**"Do we have to verify everything?"**

> *"The sources genuinely disagree in emphasis, and I am not going to paper over
> it. The BEP says may verify; the strategy treats it as a defined act; the
> completion conditions say required verification. Whether it is mandatory in
> every cycle is recorded as not established."*

### Transition

> *"Verification settles one matter. Completion is a claim about a whole cycle —
> and it is the claim most often made on the thinnest evidence."*

### Delivery warning

**Do not resolve the `may`/defined question, even if pressed.** Picking a side
would decide a matter the sources leave open, and `H18` exists precisely to stop
that.

---

## Slide 12 — Completion is not zero clashes · 1.5 min

### What you are doing here

Refusing the number everyone wants, and replacing it with nine conditions —
**with their qualifiers intact**, because the qualifiers are the governance.

### Opening line

> *"Somebody will ask for the clash count. Harrismith's answer is that a
> zero-clash report can be produced by testing nothing."*

### The load-bearing explanation

Quote the refusal in full:

> *"Completion is not 'zero clashes.' A zero-clash report can be produced by
> testing nothing, excluding everything, or resolving symptoms rather than
> interfaces."*

Then the nine conditions. **Do not read them one by one** — group them and
**stress the qualifiers**:

> *"For a defined coordination cycle, and as applicable: required inputs
> identified, required readiness checks and coordination checks performed,
> material findings triaged, required Issues created and assigned, required
> resolutions or dispositions recorded, required verification completed,
> unresolved matters explicitly carried forward or escalated, and coordination
> evidence retained."*

Then stop and point at the qualifiers:

> *"'For a defined cycle.' 'As applicable.' 'Required.' 'Material.' Those words
> are doing the governance. This is not an unconditional checklist you tick to
> declare victory."*

Then the point most audiences find surprising:

> *"Condition eight means a cycle can complete with an unresolved matter carried
> forward. Carrying something forward, explicitly and on the record, is a
> governed outcome — not concealment, and not failure."*

Then the boundary:

> *"Completion is cycle-specific and purpose-specific. It does not mean the
> entire design is complete, technically approved, construction-ready, or
> accepted by the project. And it does not publish anything, resolve acceptance
> authority, release T4, or unblock TRN-E03."*

### Source boundary

`S2` §21 holds the nine conditions; `S1` §8.11 governs the refusal and the
purpose-specific limit. **Slide 13 owns evidence outputs, escalation detail and
assurance — name them and stop.**

### Governance-status warning

**`CONTROLLED GOVERNANCE`** for the refusal and the purpose-specific limit;
**`PROPOSED GOVERNANCE`** for the nine conditions. Publication and acceptance
authority remain **UNRESOLVED**; `T4` and `TRN-E03` remain **BLOCKED**.

### Implementation-status warning

**No coordination cycle has been completed.** **None of the nine conditions is
recorded as performed.** **`GCR-006` remains OPEN**, and **Module 6 teaching
cannot close it** — only evidence of a complete governed cycle could.

### Distinctions that must remain separate

**Completion** and **zero clashes**. **Completion** and **absence of open
matters**. **Cycle completion** and **project completion**. **Carried forward**
and **concealed**. **What completion would require** and **what has been done**.

### What not to imply

- That **zero clashes** is completion or coordination.
- That the nine are an **unconditional universal checklist**.
- That any of the nine **has been performed**.
- That completion means **complete, approved, construction-ready or accepted**.
- That completion **publishes**, **resolves acceptance authority**, **releases
  `T4`** or **unblocks `TRN-E03`**.
- That an unresolved matter carried forward is a **failure**.
- That **teaching this closes `GCR-006`**.

### Likely audience question

**"So what do we report to the client at the end of a cycle?"**

> *"What was in scope, what was checked, what was found, what was dispositioned,
> what was verified, and what is being carried forward — with the evidence
> retained. Not a number. The number is the one thing that can be manufactured
> by doing less work."*

**"Can a cycle be complete if something's still open?"**

> *"Yes — condition eight says so directly, provided the unresolved matter is
> explicitly carried forward or escalated. What is not acceptable is the matter
> quietly disappearing."*

**"Does completing cycles close `GCR-006`?"**

> *"One complete governed cycle, exercised and evidenced, would be what
> `GCR-006` asks for. Teaching the conditions does not do it, and nothing in this
> module changes its status. It is open."*

### Transition

> *"Which leaves the evidence itself — what a coordination cycle actually leaves
> behind, and what a closed Issue still does not prove."*

**Slide 13 is architecture only after T6-C.** If you are presenting before it is
developed, **stop here and say so** rather than improvising.

### Delivery warning

**Never put a tick, a percentage or a green marker against any of the nine.**
The slide's whole argument is that these are conditions that would have to be
met, and none of them is recorded as met.

---

## Slide 13 — Evidence, escalation, and what a closed Issue does not prove · 1.0 min

### What you are doing here

Three connected things in sixty seconds: **what the cycle leaves behind**, **how
a matter leaves the cycle unresolved**, and **what none of it proves**.

**This is also the slide to shorten if you are running long** — see the delivery
warning.

### Opening line

> *"A cycle produces records. The question worth a minute is which of those
> records prove something, and which just show that somebody clicked."*

### The load-bearing explanation

**Do not read the nine outputs aloud.** Point at them and move:

> *"Nine outputs — the input register, the federation reference, check and
> finding records, Issue history, meeting decisions, the verification record, the
> unresolved list, and the cycle summary."*

Then the two lines that matter more than the list:

> *"No duplicate record is required where a controlled platform record already
> does the job. And a coordination report summarises governed evidence — it does
> not become a second Issue database. Two records of the same Issue eventually
> become two different records of the same Issue."*

Then escalation, briskly, landing on one field:

> *"An escalation records the matter, the affected teams, the impact, the
> decision required, the decision function or owner **where established**, and
> the next step. And the strategy is explicit: no owner is invented where none is
> established. 'Decision owner: not established' is a valid and useful entry."*

Then the closure limit — **the heart of the slide**:

> *"A properly evidenced closure concerns the defined coordination matter, for
> the defined purpose. By itself it does not prove every container was updated,
> every interface was coordinated, the whole model was checked, the design is
> complete, or that anything was approved, published, accepted or certified. A
> Closed label alone proves none of them."*

### The absence, delivered as the takeaway

> *"And one honest gap. The responsibility matrix allocates change and assurance
> functions. The strategy says the BIM Manager supports assurance. That is the
> whole of it. No source defines a sampling population, a sample size, a
> frequency, a selection method, a pass/fail threshold or a report form.
> Assurance-sampling method: not established. I am not going to invent one for
> you, and neither should anybody else."*

### Source boundary

`S2` §22 holds the outputs, §23 the escalation. `S1` §8.12 governs escalation
without invented authorities. `S3` §3.5 `X5` allocates escalation; §3.7 holds
`A1`–`A5`. **`H9`, `H10`, `H12` and `U14` carry the recorded limits — do not
re-derive them.**

### Governance-status warning

**`PROPOSED GOVERNANCE`** for the outputs and escalation structure.
**`CONTROLLED GOVERNANCE`** for *"no owner is invented"*. **`A2` remains `TBD`
by change class; `A4` has no universal verifier.** **Assurance-sampling method:
`NOT ESTABLISHED`.**

### Implementation-status warning

**No evidence output is recorded as produced.** The cycle is **partially
traceable**; a complete governed cycle is **not demonstrated**; **`GCR-006`
remains OPEN**.

### Distinctions that must remain separate

**Evidence** and **a status label**. **Activity** and **a governed decision**.
**A summary report** and **the Issue record**. **Escalating** and **resolving**.
**Change-assurance functions** and **an assurance-sampling method**.
**Assurance** and **certification**.

### What not to imply

- That **all nine outputs have been produced** — none is recorded as produced.
- That a report **should duplicate** the Issue database, or that duplicates are
  harmless.
- That **escalation resolves** anything, or **creates authority**.
- That an unknown decision owner should be **filled with a plausible role**.
- That a **`Closed`** label proves verification, updates, coordination,
  approval, publication, acceptance or compliance.
- That **`A1`–`A5`** constitute a sampling method.
- Any sample size, population, frequency or threshold — **none exists**.
- That **`GCR-006` is closed** or nearly closed.

### Likely audience question

**"What assurance process should we run?"**

> *"On this project, none is defined — and that is the answer, not a dodge. The
> matrix allocates change-assurance functions and the strategy says the BIM
> Manager supports assurance. No sampling population, size, frequency or
> threshold exists in any source. Inventing one here would be exactly the failure
> this module keeps warning about."*

**"If the Issue is closed, isn't the clash gone?"**

> *"For the defined matter and purpose, if closure was properly evidenced — yes.
> But a Closed label on its own proves nothing about the other containers, the
> other interfaces, or the design. Scope, not suspicion."*

**"Isn't escalating just admitting failure?"**

> *"No. It is a governed route for a matter that cannot be settled in the normal
> cycle, and it gets recorded with its decision owner — or with 'not established'
> where none exists. What would be a failure is the matter quietly disappearing."*

### Transition

> *"That is Harrismith's coordination governance, end to end — including the
> parts it declines to invent. Which leaves the only question that matters for
> the project we are actually here for."*

### Delivery warning

**This slide is the pacing-recovery point.** If you are over time, compress the
nine outputs to a gesture and the escalation triggers to one sentence — **but
never cut the closure limit or the assurance absence.** Those two are the slide's
reason for existing.

---

## Slide 14 — What Triviron must decide about coordination · 2.0 min

### What you are doing here

Transferring the **method**, and answering nothing. Seven groups of questions,
seven answer areas, all of them empty.

### Opening line

> *"Everything so far has been Harrismith. Two minutes on the project we are
> actually here for — and I am going to answer none of it, which is the point."*

### The load-bearing explanation

**Do not read all seven groups.** Name them, and dwell on two:

> *"Coordination governance. Roles and authority. Inputs and federation. Checks
> and tolerances. Findings, Issues and statuses. Verification, evidence and
> completion. And the publication and acceptance boundary."*

Then **group 2**, because it is where projects default fastest:

> *"Who coordinates, who owns each technical response, who verifies, when
> verification is required, who may escalate, who decides escalated technical
> matters, who decides governance matters. Harrismith answers exactly one of
> those with a named holder — none. Every holder is TBD, and it says so rather
> than defaulting."*

Then **group 6**, because it is the module in one question:

> *"And the last one in that group: what evidence would demonstrate one complete
> governed cycle? Harrismith has that question open as `GCR-006`. Triviron gets
> to answer it before it becomes a condition rather than after."*

### The transfer boundary — say it precisely

> *"What transfers is the questions, the distinctions, and the discipline of
> typing an absence instead of leaving a hole. What does not transfer is
> Harrismith's role allocations, its twelve interface checks, its TBD tolerances,
> its Issue taxonomy and status model, and its platform arrangements. Those are
> Harrismith's training decisions, not Triviron's governance."*

Then close the slide:

> *"Module 7 is the Harrismith-to-Triviron translation. This slide answers none
> of its own questions, and neither will I."*

### Source boundary

Every question group is **derived** from cited `S1`, `S2`, `S3` and `S7`
sections — classified `INTERP`, and recorded as such. **`TA-02` and `TA-03`
establish that Harrismith is a training reference.** **`S13` sets the Module 7
boundary.**

### Governance-status warning

**`NOT YET ESTABLISHED` throughout.** Harrismith statuses appear **only** where
labelled as a training reference. **No Triviron governance exists.**

### Implementation-status warning

**Not applicable — nothing exists to implement.** **No Triviron information
exists in this repository.**

### Distinctions that must remain separate

**A question** and **an answer**. **A training reference** and **governance**.
**What transfers** and **what does not**. **Module 6's scope** and **Module 7's**.

### What not to imply

- **Any answer, in any group.**
- That a **Harrismith value** may fill an answer position as an example or a
  default.
- Any Triviron party, task team, role holder, container, check, tolerance, Issue
  type, status, environment, date or authority.
- That any **Harrismith coordination rule automatically applies**.
- That **Module 7's translation has been performed**, or that this begins it.
- That the transfer table is a **recommendation** rather than a boundary.

### Likely audience question

**"Can't we just adopt Harrismith's twelve checks as a starting point?"**

> *"You can adopt the method — decide which interfaces are meaningful and build
> checks for those. The twelve themselves are Harrismith's proposed training
> checks with every tolerance TBD. Copying them across would import an answer to
> a question Triviron has not asked yet."*

**"What would you recommend for Triviron's status model?"**

> *"That is a Triviron decision and I am not going to make it from here. What I
> would say is: whatever you adopt, keep the governed meaning separate from
> whatever the platform calls it — that is the transferable part."*

**"So Module 6 doesn't tell us what to do?"**

> *"It tells you what to decide, and which distinctions to keep while you decide
> it. That is a more useful thing to carry than somebody else's answers."*

### Closing

**Deliver the module closing here**, on the closing marker — **inside this
slide's two minutes.**

### Delivery warning

**Do not fill an answer area, even conversationally.** Saying *"well, Harrismith
uses the BIM Coordinator for that"* while pointing at group 2 **is** answering
it, whatever the slide shows.

---

## Module 6 closing

### Normal closing — approximately 30 seconds

Delivered after Slide 14, on the closing marker. **Inside Slide 14's allocated
2.0 minutes. It adds no time to the module.**

> *"So — Harrismith governs a route. A finding gets triaged; some findings become
> Issues; an Issue gets assigned; the originating team fixes it in its own WIP,
> checks it, reshares it; you re-coordinate, and only then can you verify. Every
> one of those is a different act with a different owner, and the module has been
> about not letting them collapse into each other."*
>
> *"Federation transfers no authorship. Assignment transfers no authorship. A
> status label is not evidence, and 'Closed' is not 'verified'. Completion is not
> zero clashes."*
>
> *"And the honest part: that whole route is governed, and it has not been shown
> to run. A model set with zero coordinated versions, two open reviews, one open
> issue, nothing completed. `GCR-006` — one complete governed coordination cycle,
> exercised and evidenced — is still open. That is not a criticism of the
> project; it is the project being accurate about itself."*
>
> *"Module 7 asks which of these decisions Triviron actually has to establish —
> with Triviron's information, not ours."*

### Emergency closing — ten seconds

For when Slide 14 has overrun, or the session is being cut.

> *"Finding, Issue, status, response, verification, acceptance — six different
> things, and a label proves none of them. Harrismith governs the route; the
> cycle has not been demonstrated, and `GCR-006` is open. Module 7 asks what
> Triviron must decide."*

**Both closings must retain all four elements:** the distinctions · the evidence
boundary · **the unresolved implementation position** · the Module 7 direction.

### Transition toward Module 7

**Do not begin Module 7 content.** One sentence, if a bridge is wanted:

> *"Module 7 is the Harrismith-to-Triviron BEP translation — and it starts where
> Slide 14 stopped, with the questions rather than our answers."*

**Nothing beyond that sentence.** **No Triviron party, role, container, check,
tolerance, status, environment or decision may be named**, and **no Triviron
information exists in this repository.**

---

## Status

| Field | Value |
|---|---|
| Increment | **T6-D — notes COMPLETE.** Slides 1–3 (T6-A) · 4–8 (T6-B) · 9–12 (T6-C) · 13–14 (T6-D) |
| Notes developed | **All fourteen slides** |
| Slides without notes | **None** |
| Module closing | **Normal (≈30 s) and emergency (≈10 s)**, plus a one-sentence Module 7 bridge |
| Timing | **`20.0 minutes allocated — not measured`** |
| Slide progression | **No automatic slide-transition timing.** Advance manually when ready |
| Rehearsal | **None performed** |
| Exercises | [`exercises.md`](exercises.md) — created in **T6-D** |
| Visual specifications | **14 of 14 — `M6V-01`–`M6V-14`**, **ACCEPTED after `T6-E-R`** — [`visual-demonstration-plan.md`](visual-demonstration-plan.md) |
| Visual sources | **14 of 14 — `M06-S01`–`M06-S14`**, **ACCEPTED after `T6-F-R`** — [`../assets/module-06/`](../assets/module-06/) |
| Rendered assets | **None** |
| Assembly package | **COMPLETE (T6-G)** — [`presentation/`](presentation/), seven files; **`PENDING CHATGPT GOVERNANCE REVIEW`** |
| Module 6 PowerPoint | **None exists.** No `.pptx` committed |
| Outstanding | **T6-H** — external PowerPoint production. **`NOT STARTED — BLOCKED PENDING T6-G ACCEPTANCE`** |
