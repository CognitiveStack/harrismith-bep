# Module 4 — Exercises

**Status:** Initial exercise set for the Slides 1–3 baseline. Teaching material;
**not governance.**

Rehearsal exercises for the presenter, not assessments for an audience. Do them
aloud, alone, before delivering to anyone. **Exercise 13 is done after each of
the others.**

**Four exercises rehearse questions rather than slides.** Exercises 7, 10, 11 and
12 cover material whose slides are not yet developed — but the questions arrive
the moment you show a state diagram. Rehearse the answers before the slides
exist, not after.

---

## Exercise 1 — Explain a CDE without mentioning software

**Task.** Explain what a common data environment is, in under a minute,
**without naming any software** — no ACC, no BIM 360, no SharePoint, no "the
platform", no "the system".

**Why this exercise.** The audience's mental image is a product they were sold.
If the product word comes from you, everything after it is heard as a feature
list — and Slide 1's whole argument is that the CDE is not the product.

**What good looks like.** A CDE is a process for controlling how information is
developed, checked, shared, authorised, delivered and retained. Our BEP's line
does the rest: an information-management process supported by technology — **not
a folder tree**.

**Success criteria**

- [ ] No product or platform word, in any form.
- [ ] I described **control**, not storage.
- [ ] I named at least four of the six things it controls.
- [ ] I attributed *"not a folder tree"* to **our BEP**, not to a standard.
- [ ] Under sixty seconds.

**Common failure.** Describing a folder structure with better rules. That is
still a folder structure, and it teaches the opposite of the slide.

---

## Exercise 2 — Governance, workflow and platform

**Task.** Explain the relationship between governance, workflow and platform in
forty-five seconds. Say which one comes first, and why.

**Why this exercise.** It is the three-layer model behind the whole module, and
the order is load-bearing.

**What good looks like.** Governance decides what must happen and who may decide
it. The workflow is how information moves under that governance — the states,
the transitions, the checks. The platform implements the workflow: folders,
permissions, metadata. And the order runs **one way** — our CDE strategy's first
platform rule is *governance decision precedes configuration change*, and CDE
Administration *implements governance; it does not define it*.

**Success criteria**

- [ ] Three layers, named in order.
- [ ] I said **governance first**, explicitly.
- [ ] I said configuration follows a decision, not the reverse.
- [ ] I did not describe a product feature.
- [ ] Forty-five seconds.

**Common failure.** Describing the layers as equal partners. They are ordered,
and reversing them is the failure the model exists to prevent.

---

## Exercise 3 — Why a folder tree is insufficient

**Task.** Someone says: *"We've got WIP, Shared and Published folders — so we've
got a CDE."* Answer in thirty seconds.

**Why this exercise.** It is the most reasonable-sounding wrong answer in the
module, and on this project it is nearly true — the four areas **are** adopted
and **are** mapped to states.

**What good looks like.** The folders are a correct partial implementation, and
the mapping is a real governance decision — CGD-001 adopted it. But the decision
itself says: **the existence or name of an area does not by itself establish an
information state**, and **placement alone does not evidence that checking or
authorisation occurred**. The folders are where things sit. The CDE is what had
to be true before they got there.

**Success criteria**

- [ ] I acknowledged that the folders and the mapping are **real**.
- [ ] I quoted or paraphrased `CGD-C01`.
- [ ] I distinguished **where a thing sits** from **what had to be true**.
- [ ] I did not sound like I was correcting whoever built the folders.
- [ ] Thirty seconds.

**Common failure.** Dismissing the folder structure. It was adopted by a
governance decision; the point is narrower — it proves nothing on its own.

---

## Exercise 4 — State versus version

**Task.** Explain the difference. Thirty seconds. One concrete example.

**Why this exercise.** These two are collapsed more often than any other pair,
and the collapse makes every transition look automatic.

**What good looks like.** A version is a platform fact — an occurrence in the
file history, created by someone saving. A state is a governed context — where
the information may be relied on, and by whom. Our BEP: **a new platform version
creates none of the others.** You can save forty versions inside WIP and the
information never leaves WIP.

**Success criteria**

- [ ] I called the version a **platform fact** and the state a **governed
      context**.
- [ ] I used the *new version creates none of the others* rule.
- [ ] I gave one concrete example.
- [ ] I attributed the wording to **our BEP**.
- [ ] Thirty seconds.

**Common failure.** "A version is a small change and a state is a big one." Size
has nothing to do with it. One is automatic; the other is decided.

---

## Exercise 5 — Version versus revision

**Task.** Explain the difference. Thirty seconds. **Then say what our project
does not have.**

**Why this exercise.** The second half is the part presenters skip, and it is
what stops the audience asking for a code that does not exist.

**What good looks like.** A version happens because someone saved. A revision is
a **controlled issue identifier** — it exists because someone decided to issue
something and recorded which issue it was. And our BEP's definition carries a
qualifier: a revision applies *where project convention requires one*. **We have
not established a convention.** The concept is defined; the code set is not.

**Success criteria**

- [ ] Automatic versus decided.
- [ ] I quoted the *where project convention requires one* qualifier.
- [ ] I said plainly that **no convention is established**.
- [ ] I did not invent an example code.
- [ ] Thirty seconds.

**Common failure.** "So this would be revision P01." One invented code and the
audience leaves believing the project has a revision standard.

---

## Exercise 6 — Status versus suitability

**Task.** Explain the difference. Thirty seconds. Give one example where a
container has a status and is still not suitable.

**Why this exercise.** These two look like synonyms and are not, and confusing
them is how information gets relied on for a purpose nobody authorised.

**What good looks like.** Status is a **workflow or decision condition** — what
has happened to it. Suitability is **what the information may be used for**.
Something can be marked *reviewed* — a status — and still be unsuitable for a
use it was never prepared for. Status looks backwards at what occurred;
suitability looks forwards at what may be done.

**Success criteria**

- [ ] I used both controlled definitions.
- [ ] I gave one example where the two diverge.
- [ ] I framed status as backwards-looking and suitability as forwards-looking,
      or an equivalent.
- [ ] I did not invent a status or suitability code.
- [ ] Thirty seconds.

**Common failure.** Treating suitability as a stronger status. It is a different
property, not a higher grade of the same one.

---

## Exercise 7 — Why suitability does not prove acceptance

**Task.** Explain it in thirty seconds. Say who decides each.

**Why this exercise.** It is the last link in the chain the audience most wants
to shortcut, and the two decisions belong to different parties.

**What good looks like.** Suitability is a designation carried with the
information — what it may be used for. Acceptance is a **recipient's decision and
status against a stated purpose** — someone else's call, made later. A container
can carry a suitability designation and be rejected, and the rejection does not
change the designation; it records a decision against a purpose. And on our
project, **acceptance authority is unresolved** — nobody holds it.

**Success criteria**

- [ ] I named two different parties.
- [ ] I said acceptance is a **decision and status**, not a state.
- [ ] I said rejection does not change the suitability designation.
- [ ] I said acceptance authority is **unresolved** on this project.
- [ ] Thirty seconds.

**Common failure.** "Once it's suitable, they accept it." That is the assumption
the distinction exists to break.

---

## Exercise 8 — Why moving a file is not a transition

**Task.** Explain it in thirty seconds, **using the project's own words**.

**Why this exercise.** It is the module's spine, and three controlled sources say
it independently — so there is no need to improvise.

**What good looks like.** Our structure decision, `CGD-C03`: **movement or
placement between platform areas must not be treated as sufficient evidence of a
WIP-to-Shared, Shared-to-Published or other information-state transition.** Each
transition requires the applicable governed checks, authorisation and evidence.
Our validation record adds the other half: **being able to perform an action in
the software says nothing about who was authorised to decide it.**

**Success criteria**

- [ ] I used at least one of the two quotations.
- [ ] I named the three things a transition requires — **checks, authorisation,
      evidence**.
- [ ] I separated **capability** from **authority**.
- [ ] I did not name a person or a permission level.
- [ ] Thirty seconds.

**Common failure.** Explaining it as a rule someone imposed. It is recorded in
three controlled documents; say so, and it stops being your opinion.

---

## Exercise 9 — The four states, in sixty seconds

**Task.** Describe all four Harrismith information states. **Exactly sixty
seconds.** Time it.

**Why this exercise.** It is Slide 3's core, and the four definitions must be
fluent before Section C teaches movement between them.

**What good looks like.** WIP — under originator or task-team control, **not
authorised for general project reliance**. Shared — available beyond the
originating task team for an identified purpose, **after required checking and
authorisation**. Published / Authorised — **authorised for a defined delivery or
use purpose**, by a separate decision. Record / Retained — historical evidence
retained for traceability, **and not a folder**.

**Success criteria**

- [ ] All four, in order, with their controlled definitions.
- [ ] I said *after required checking and authorisation* for Shared.
- [ ] I said Published requires a **separate** decision.
- [ ] I said Record / Retained is **not a folder**.
- [ ] Sixty seconds or under, measured.

**Common failure.** Describing them as a progression that everything travels.
Most information never leaves WIP, and on this project nothing can pass Shared.

---

## Exercise 10 — Why Shared is not Published

**Task.** Explain it in thirty seconds. **Then say what is required to cross
between them.**

**Why this exercise.** The audience's instinct is that Published is Shared with
more people, and it is not — it is a different authority.

**What good looks like.** Shared means available beyond the originating team for
an identified purpose, after check and authorisation to share. Published means
**authorised for a defined delivery or use purpose** — a separate decision, by a
function holding publication authority. Our CDE strategy is explicit: **Shared
does not mean published, accepted, or suitable for every purpose.** Crossing
requires a delivery readiness review and a publication authorisation — and on
this project **nobody holds that authority**.

**Success criteria**

- [ ] Two different authorities, named as such.
- [ ] I quoted the *Shared does not mean* line.
- [ ] I named the gate — **delivery readiness review**.
- [ ] I said the authority is **unresolved**, without inventing a holder.
- [ ] Thirty seconds.

**Common failure.** "Published is just more widely shared." Audience size has
nothing to do with it.

---

## Exercise 11 — Record / Retained is not an Archive folder

**Task.** Someone asks where the Archive folder is. Answer in thirty seconds.

**Why this exercise.** The expectation is near-universal, and inventing the
folder to satisfy it would create a requirement three controlled documents
decline to create.

**What good looks like.** There isn't one, and there doesn't need to be. Record /
Retained is a **conceptual state and a retention requirement**. Our BEP, our CDE
strategy and CGD-001 all say the same thing: **no mandatory `04 Archive` root is
approved or required**, none has been created, and the retention approach is
**TBD**. What matters is that historical versions, decisions, exchanges and
evidence remain traceable — by a method still to be decided.

**Success criteria**

- [ ] I said clearly that no such folder exists **or is required**.
- [ ] I named it as a **conceptual state and a retention requirement**.
- [ ] I said the retention approach is **TBD**.
- [ ] I said what the requirement actually is — **traceability**.
- [ ] I did not apologise for the absence.

**Common failure.** "Not yet." It implies one is coming. **The requirement is
traceability; the method is undecided, and a folder may never be the answer.**

---

## Exercise 12 — "Is the state model live in ACC?"

**Task.** Answer it in forty-five seconds. **Neither claim it works nor claim it
fails.**

**Why this exercise.** It is the module's hardest question, and both confident
answers are wrong.

**What good looks like.** The four root areas were observed and correspond to the
topology we adopted — but CGD-001 says **a later controlled verification must
confirm the live topology before the mapping is relied on operationally**, and
that verification has not happened. Our validation record found only Architecture
demonstrable as a Shared input, no complete coordination cycle, and **no
publication or acceptance authority evidence established**. So: adopted,
partially observed, **not verified**. And the caution that goes with it —
**absence of observation is not observation of absence.** Nothing there says the
project is failing; it says nobody has checked.

**Success criteria**

- [ ] I said **not verified**, rather than *works* or *doesn't work*.
- [ ] I distinguished **adopted**, **observed** and **verified**.
- [ ] I cited at least one specific finding from the validation record.
- [ ] I said *absence of observation is not observation of absence*.
- [ ] I did not turn a gap into a failure claim.

**Common failure.** "It's not really implemented yet." That converts an
unverified state into a deficiency finding nobody made.

---

## Exercise 13 — One controlled, one planned, one unresolved

**Do this after every other exercise, and after every rehearsal of every slide.**

**Task.** Name **one** thing you just said that is controlled governance, **one**
that is planned or proposed, and **one** that is unresolved. Ten seconds each.

**Why this exercise.** Module 4's whole hazard is that all three sound identical
when spoken confidently. This is the check.

| Class | Test |
|---|---|
| **Controlled** | Is it in `S1`, or in an approved supporting resource, as governing wording? |
| **Planned / proposed** | Is it `S2`'s workflow — which **classifies itself** as proposed governance? |
| **Unresolved** | Is it in the unresolved register — publication authority, acceptance authority, retention, naming, metadata, code sets? |

**Success criteria**

- [ ] All three named, without hesitation.
- [ ] I did not classify a proposed workflow as controlled.
- [ ] I did not classify an unresolved matter as merely planned.
- [ ] I could say **which document** each came from.
- [ ] I noticed if I had said *"the process does X"* where the truth is *"the
      process is designed to do X"*.

**Common failure — and the one this module is built to prevent.** Delivering
proposed governance in the present tense. *"When information is ready, the
Task-Team Lead authorises the share"* describes a design. **Whether it happened
last Tuesday is a different question, and mostly an unanswered one.**

---

## Exercise 14 — Deliver Slides 1–3 to time

**Task.** Deliver Section A and the first slide of Section B end to end.
**Target: 4.5 minutes. Measure it.**

**Why this exercise.** Slides 1–3 carry the module's vocabulary. If they run
long, Section C teaches transitions between things the audience cannot name.

**What good looks like.** Slide 1 lands *not a folder tree* and the
proposed-governance framing. Slide 2 gets five properties, five questions, and
the *new version creates none of the others* rule. Slide 3 gets four states,
four definitions, the no-Archive position, and the conceptual-model caption.

**Success criteria**

- [ ] **4.5 minutes ± 20 seconds**, measured.
- [ ] The proposed-governance framing was said on **Slide 1**, not later.
- [ ] *A new version creates none of the others* was said.
- [ ] *Record / Retained is not a folder* was said.
- [ ] No invented code, schema, holder or folder.
- [ ] I did not complete the route through Published.
- [ ] The four-line earlier-module callback stayed at four lines.

**Common failure.** Slide 2 running to 2.5 minutes because five properties invite
five examples. One example, on the pair the audience most confuses — version and
revision.

---

## Scope note

**Fourteen exercises, covering the Slides 1–3 baseline and the questions that
arrive as soon as a state diagram appears.** Exercises for Slides 4–14 are a
later increment.
