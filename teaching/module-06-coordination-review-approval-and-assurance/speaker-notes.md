# Module 6 — Speaker Notes

**Status:** Presenter notes for teaching material. **Not governance.**

**Notes exist for Slides 1–3 only.** Slides 4–14 are **architecture only** and
have **no presenter notes**. **No module closing has been written** — the
closing belongs to the increment that develops Slide 14.

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

## Status

| Field | Value |
|---|---|
| Increment | **T6-A** |
| Notes developed | **Slides 1–3 only** |
| Slides without notes | **4–14 — architecture only** |
| Module closing | **Not written.** Belongs to the increment that develops Slide 14 |
| Timing | **`20.0 minutes allocated — not measured`** |
| Slide progression | **No automatic slide-transition timing.** Advance manually when ready |
| Rehearsal | **None performed** |
| Exercises | **None exist** |
| Visual specifications / sources / assets | **None exist** |
| Assembly package / PowerPoint | **None exist** |
| Outstanding | **T6-B** — the next Module 6 increment. **Not started** |
