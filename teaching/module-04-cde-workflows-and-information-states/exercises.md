# Module 4 — Exercises

**Status:** Exercise set for the complete **Slides 1–14** baseline. Teaching
material; **not governance.**

Rehearsal exercises for the presenter, not assessments for an audience. Do them
aloud, alone, before delivering to anyone. **Exercise 13 is done after each of
the others.**

**Seventy-one exercises in four sets.** Exercises 1–14 cover Slides 1–3 and the
questions that arrive as soon as a state diagram appears; **15–29 cover Section B
— the four states**; **30–46 cover Section C — the transition workflow**;
**47–71 cover Sections D and E — properties, the direction of authority, and the
questions Triviron must answer.**

**Exercise 64 is the module's only full-length run.** No timing in this
repository has been measured, and every allocation stays an allocation until it
has been.

**Four of the foundation exercises rehearse questions rather than slides.**
Exercises 7, 10, 11 and 12 cover material whose slides came later — they are kept
where they are, because the questions arrive early.

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

# Section B — Slides 4–7: the four states

**Fifteen further exercises.** Exercise 29 is the timed run, and is done last.
Exercise 13 still applies after each one.

---

## Exercise 15 — Explain WIP without referring to a folder

**Task.** Explain what WIP is, in forty-five seconds, **without mentioning a
folder, an area or a location**.

**Why this exercise.** WIP is the state most tightly bound to a folder in
people's minds, and the binding is exactly what `CGD-C01` refuses.

**What good looks like.** WIP is the task team's **working state** — drafting,
modelling, internal iterations, local coordination inside the team, correction,
getting ready to be checked. It stays under the originating task team's
responsibility. It may hold many versions, and those versions are working steps,
not project exchanges.

**Success criteria**

- [ ] No folder, area, path or location word.
- [ ] I called it a **state**, and described it as the team's **working
      context**.
- [ ] I said responsibility stays with the **originating task team**.
- [ ] I said WIP versions are **not project exchanges**.
- [ ] Forty-five seconds.

**Common failure.** "WIP is where you keep your work in progress." A location
answer to a governance question.

---

## Exercise 16 — Visibility versus permitted reliance

**Task.** Explain the difference in thirty seconds, **using the project's own
words**.

**Why this exercise.** It is Slide 4's central line, and it is quotable, so there
is no need to improvise.

**What good looks like.** Our BEP: **visibility is not permission.** Being able
to see or open another team's WIP — through folder access, a platform
permission, or any other means — **does not constitute authority to use it.
Permission to read is not authorisation to rely.** And other parties do not rely
on WIP unless there is an explicitly governed exception.

**Success criteria**

- [ ] I used the *visibility is not permission* formulation.
- [ ] I distinguished **can see** from **may use**.
- [ ] I mentioned the governed-exception route without describing it.
- [ ] I attributed it to **our BEP**.
- [ ] Thirty seconds.

**Common failure.** "You shouldn't really use it." *Shouldn't* is etiquette.
**Not authorised** is governance.

---

## Exercise 17 — The WIP responsibility chain

**Task.** Name who does what inside WIP. Twenty seconds. **Four lines maximum.**

**Why this exercise.** Module 2 taught the full role model; this is the
compressed version, and compressing it without re-teaching it is the skill.

**What good looks like.** Author authors. Checker checks. Task-Team Lead may
authorise the controlled transition out of WIP **where the approved governance
establishes it**. Everyone else must not treat WIP as coordinated or approved.

**Success criteria**

- [ ] Four lines, no more.
- [ ] I said *where governance establishes it* on the Task-Team Lead line.
- [ ] I included the everyone-else line — it is the one that protects the state.
- [ ] I did not re-teach Module 2.
- [ ] I named no person.

**Common failure.** Expanding into the authority chain. That is Module 2's, and
it costs Slide 5 its time.

---

## Exercise 18 — Shared in one sentence, without *approved*

**Task.** Define Shared in **one sentence**. **The word *approved* is banned** —
along with *signed off*, *cleared* and *authorised for use*.

**Why this exercise.** It is the module's single most common misreading, and the
banned words are the ones a presenter reaches for under pressure.

**What good looks like.** *"Shared means information made available beyond the
originating task team for an identified purpose, after required checking and
authorisation to share."*

**Success criteria**

- [ ] One sentence.
- [ ] **None of the banned words.**
- [ ] I said **for an identified purpose**.
- [ ] I said **after required checking and authorisation**.
- [ ] I did not imply wider reliance than the purpose supports.

**Common failure.** "Shared means it's ready for other people to use." *Ready*
and *use* are both unbounded. The purpose is the boundary.

---

## Exercise 19 — Two valid purposes, one invalid inference

**Task.** Give **two** legitimate uses of Shared information and **one** thing it
does not license. Thirty seconds.

**Why this exercise.** Purpose-bounded reliance is abstract until it has
examples on both sides.

**What good looks like.** Valid: coordination — *"coordination inputs come from
appropriate Shared information, not from uncontrolled WIP"*; and reference by
another task team for the stated working purpose. Invalid: treating it as
approved for construction, procurement, or any purpose it was not shared for —
**suitability is bounded by the purpose**.

**Success criteria**

- [ ] Two valid purposes, both traceable to a source.
- [ ] One invalid inference, stated as invalid.
- [ ] I used the word **purpose** in all three.
- [ ] I did not describe how the coordination cycle runs — that is Module 6.
- [ ] Thirty seconds.

**Common failure.** Offering *"for information"* as a purpose. It is a
disclaimer, not a purpose, and it bounds nothing.

---

## Exercise 20 — Why responsibility stays with the originator

**Task.** Explain in thirty seconds why a receiving team consuming a model does
not become responsible for it.

**Why this exercise.** It protects the originator and the receiver at once, and
audiences get it wrong in both directions.

**What good looks like.** Our BEP: **consumption does not transfer technical
ownership.** A receiving team that consumes a model **does not acquire
responsibility for its content — the originator remains responsible for what it
produced.** And the mirror: **availability is not consumption** — nobody consumes
information by accident, so nothing is imposed on a receiver either.

**Success criteria**

- [ ] I said responsibility **stays with the originator**.
- [ ] I said consumption is a **deliberate act**.
- [ ] I covered **both** directions — nothing transfers, nothing is imposed.
- [ ] I attributed the wording to **our BEP**.
- [ ] Thirty seconds.

**Common failure.** "Once you use it, it's on you." That transfers
responsibility the source explicitly retains with the originator.

---

## Exercise 21 — Why Shared is not Published

**Task.** Explain the difference in thirty seconds. **Name what is required to
cross.**

**Why this exercise.** It is the hinge between Slides 5 and 6, and the audience's
instinct — *Published is Shared with more people* — is wrong in kind, not degree.

**What good looks like.** Shared means available beyond the originating team for
an identified purpose, after check and authorisation **to share**. Published
means **authorised for a defined delivery or use purpose** — a separate decision
by a function holding **publication** authority. Crossing needs a delivery
readiness review and a publication authorisation. Our CDE strategy: **Shared does
not mean published, accepted, or suitable for every purpose.**

**Success criteria**

- [ ] Two **different authorities**, named as such.
- [ ] I did not describe it as an audience-size difference.
- [ ] I named the gate — **delivery readiness review**.
- [ ] I quoted or paraphrased the *Shared does not mean* line.
- [ ] Thirty seconds.

**Common failure.** "Published is the formal version." *Formal* is a feeling.
**A separate authority** is the fact.

---

## Exercise 22 — Why `T4` is blocked

**Task.** Explain in thirty seconds, **without describing it as broken**.

**Why this exercise.** The block is governance working, and the framing decides
whether the audience hears a feature or a fault.

**What good looks like.** Publication and exchange authority is **unresolved** —
it depends on the approved delivery arrangement, which does not yet exist. So the
transition **has no available authorising function, and information remains
Shared**. That is the system declining to complete a route it cannot authorise —
the alternative would be completing it by borrowing an authority nobody granted.

**Success criteria**

- [ ] I said **unresolved**, not *missing* or *broken*.
- [ ] I said **information remains Shared**.
- [ ] I framed the halt as **correct behaviour**.
- [ ] I did not suggest a workaround.
- [ ] Thirty seconds.

**Common failure.** "We just haven't set it up yet." It reframes a recorded
governance position as an admin backlog, and invites someone helpful to finish
it.

---

## Exercise 23 — The missing authority, without inventing it

**Task.** Someone asks who holds publication authority. Answer in thirty seconds
**and refuse three offered candidates**.

**Why this exercise.** The question always comes with a suggestion attached, and
the BEP has already ruled out four names.

**What good looks like.** Nobody currently holds it — the role is **unresolved**,
pending an approved delivery arrangement that does not exist. And our BEP names
four roles that do **not** hold it automatically: the BIM Manager, the BIM
Coordinator, the CDE Administrator and the Architect. The BEP says so
deliberately — it keeps the authority TBD **rather than defaulting it to
whichever role is nearest**.

**Success criteria**

- [ ] I said **unresolved**, and did not name a holder.
- [ ] I named at least three of the four excluded roles.
- [ ] I used the *rather than defaulting it to whichever role is nearest*
      framing.
- [ ] I did not accept a candidate offered from the floor.
- [ ] Thirty seconds.

**Common failure.** "Probably the BIM Manager, in practice." The BEP names the
BIM Manager first among those who do **not** hold it.

---

## Exercise 24 — Why publication is not delivery

**Task.** Explain in thirty seconds. Name all four things kept apart.

**Why this exercise.** Four concepts collapse into one in ordinary speech, and
the collapse is where responsibility moves without anyone deciding it should.

**What good looks like.** **Published** — authorised for a defined purpose.
**Delivered** — an exchange event, sent to an identified recipient. **Received**
— a recipient event, arrived and registered. **Accepted** — a recipient decision
and status against a stated purpose. Only the first is an information state; the
others are events, an event and a status recorded **against** information whose
state is unchanged. Something can be Published and never sent to anyone.

**Success criteria**

- [ ] All four named, each with its own kind.
- [ ] I said only **Published** is an information state.
- [ ] I gave the *published but never sent* case, or an equivalent.
- [ ] I did not describe the delivery-event logic — that is Slides 8–11.
- [ ] Thirty seconds.

**Common failure.** Treating them as four stages of one process. They are four
different kinds of object.

---

## Exercise 25 — Record / Retained, without saying *Archive*

**Task.** Explain the fourth state in forty-five seconds. **The word *Archive* is
banned**, and so is any folder name.

**Why this exercise.** The expectation is near-universal; naming the folder
creates a requirement three controlled documents decline to create.

**What good looks like.** It is about preserving what must be preserved,
maintaining traceability, and retaining evidence — superseded information is
**marked superseded, not deleted**; prior versions and rejected submissions are
**preserved**; history is not overwritten. It is a **conceptual state and a
retention requirement — not necessarily a folder**.

**Success criteria**

- [ ] The banned word never appeared.
- [ ] I named it as a **state or obligation**, not a location.
- [ ] I gave at least two preservation behaviours from the sources.
- [ ] I said **not necessarily a folder**.
- [ ] Forty-five seconds.

**Common failure.** "It's where old stuff goes." Location, and dismissive of
material the sources treat as the most instructive part of the record.

---

## Exercise 26 — Why the retention method is unresolved

**Task.** Explain in thirty seconds why the project has not created a retention
location — **and why creating one now would be wrong**.

**Why this exercise.** The obvious fix is the failure the governance model exists
to prevent.

**What good looks like.** The retention approach is **not yet defined**. No
mandatory `04 Archive` root is approved or required, and a later approved
retention and technical implementation route is **still required**. Creating a
folder now would be **configuration without a decision behind it** — and it might
not turn out to be a folder at all.

**Success criteria**

- [ ] I said the approach is **not yet defined**.
- [ ] I said no root is **approved or required**.
- [ ] I named the failure — **configuration without a decision**.
- [ ] I allowed that the answer may not be a folder.
- [ ] Thirty seconds.

**Common failure.** "We'll add it later." *Later* implies the decision is made
and only the timing is open. **The decision is open.**

---

## Exercise 27 — The state-versus-area mismatch

**Task.** Explain why four states and four areas do not line up. Thirty seconds.

**Why this exercise.** The mismatch is a controlled finding, and tidying it would
invent a mapping nobody approved.

**What good looks like.** Four root areas were adopted, and **three** map to
states. **`0. Common Files` is an area mapped to no state** — nothing becomes
approved, controlled or relied upon by being placed in it. And **Record /
Retained is a state mapped to no approved area**. So it is three-of-four one way
and three-of-four the other — which is what happens when concepts and folders are
kept as separate things.

**Success criteria**

- [ ] I named **both** mismatches, in both directions.
- [ ] I quoted or paraphrased the *area, not a state* line.
- [ ] I framed the mismatch as **correct**, not untidy.
- [ ] I did not propose an alignment.
- [ ] Thirty seconds.

**Common failure.** "It's a bit inconsistent." It is deliberately consistent —
with the rule that states are not folders.

---

## Exercise 28 — Classify all four states

**Task.** For each state, give its **governance status** and its **implementation
status**. Forty-five seconds.

**Why this exercise.** It is Exercise 13 applied to Section B's whole content,
and it is the check that stops the four states sounding equally available.

**What good looks like.**

| State | Governance | Implementation |
|---|---|---|
| **WIP** | Controlled | **Unverified** — one qualified container observation |
| **Shared** | Controlled | **Unverified** — only Architecture demonstrable |
| **Published / Authorised** | **Blocked** | **Not reached** |
| **Record / Retained** | **Unresolved** | **Not addressed** |

**Success criteria**

- [ ] All four, with **both** statuses each.
- [ ] I did not present any as operating.
- [ ] I did not present any as failing.
- [ ] I said *absence of observation is not observation of absence* where
      relevant.
- [ ] Forty-five seconds.

**Common failure.** Giving governance status only. **Two states are governed and
still unverified** — that is the module's whole hazard in one row.

---

## Exercise 29 — Deliver Slides 4–7 to time

**Task.** Deliver the four state slides end to end. **Target: 5.0 minutes.
Measure it.**

**Why this exercise.** Section B is 6.5 minutes across five slides; Slide 3 takes
1.5, leaving 5.0 for these four. If they run long, Section C teaches transitions
between things the audience is still absorbing.

**What good looks like.** Slide 4 lands *visibility is not permission*. Slide 5
lands *authorised for a defined use, not approved for every use*. Slide 6 lands
the empty authority field and *information remains Shared*. Slide 7 lands
*obligation established, method TBD*.

**Success criteria**

- [ ] **5.0 minutes ± 20 seconds**, measured.
- [ ] The word *approved* never described the Shared state.
- [ ] The publication-authority field was **shown empty**, not skipped.
- [ ] *Archive* was said only to refuse it.
- [ ] The retention-method panel was **shown empty**, not skipped.
- [ ] No holder, period, folder or route was invented.
- [ ] I did not teach the transition mechanics.

**Common failure.** Slide 6 running to 2.5 minutes because the unresolved
authority invites discussion. **Name it, show the empty field, move.** The
discussion belongs after the session.

---

# Section C — Slides 8–11: the transition workflow

**Seventeen further exercises.** Exercise 46 is the timed run, and is done last.
Exercise 13 still applies after each one.

---

## Exercise 30 — File movement versus authorised transition

**Task.** Explain the difference in thirty seconds, **using the project's own
words**.

**Why this exercise.** It is Section C's opening claim, and `CGD-C03` states it
so cleanly that improvising is a waste.

**What good looks like.** `CGD-C03`: **movement or placement between platform
areas must not be treated as sufficient evidence of a WIP-to-Shared,
Shared-to-Published or other information-state transition.** Each transition
requires the applicable governed **checks, authorisation and evidence**. Moving a
file changes where a file is. A transition changes what the information may be
used for.

**Success criteria**

- [ ] I used `CGD-C03`, or a close paraphrase.
- [ ] I named the three requirements — **checks, authorisation, evidence**.
- [ ] I distinguished **where a file is** from **what it may be used for**.
- [ ] I did not describe it as a rule someone imposed — three sources say it.
- [ ] Thirty seconds.

**Common failure.** "You have to follow the process." True and empty. **Name the
three things the process requires.**

---

## Exercise 31 — Four actions that establish nothing

**Task.** Name **four** things a user can technically do that do **not** establish
an information state. Twenty seconds.

**Why this exercise.** The abstraction lands only when the audience recognises
actions they perform daily.

**What good looks like.** Any four of: upload, move, copy, rename, change a
permission, create a new platform version. And the point that follows — **none
establishes** the required checks, the required evidence, transition authority, a
changed permitted use, a changed suitability, publication, delivery, receipt or
acceptance.

**Success criteria**

- [ ] Four concrete platform actions.
- [ ] I said what none of them establishes.
- [ ] I included **create a new version** — the one people forget.
- [ ] I did not name a product.
- [ ] Twenty seconds.

**Common failure.** Listing only file operations. **A permission change is the
most consequential of the four**, and the one nearest to authority.

---

## Exercise 32 — Build the transition anatomy

**Task.** Say the six-step anatomy from memory and **label it correctly**. Thirty
seconds.

**Why this exercise.** The order carries the teaching — and the labelling stops
it being mistaken for controlled wording.

**What good looks like.** Required input → checks → gate conditions → authorised
decision → recorded evidence → changed permitted use. And: *"that's my
arrangement of what our CDE strategy establishes — every arrow is a controlled
transition, with its own trigger, its own criteria and its own responsible
function."*

**Success criteria**

- [ ] All six, in order.
- [ ] **Evidence before permitted use** — the order is the point.
- [ ] I labelled it **teaching structure**, not controlled wording.
- [ ] I did not populate the fields — that is Slide 10.
- [ ] Thirty seconds.

**Common failure.** Putting evidence last, after the permitted use. **Evidence is
part of the transition, not a report about it.**

---

## Exercise 33 — Classify `T1`–`T8`

**Task.** Give the **kind** of each of the eight. **Forty-five seconds.** No
notes.

**Why this exercise.** It is Slide 9's whole content, and hesitating here means
hesitating in front of an audience holding the table.

**What good looks like.** `T1` state transition · `T2` action · `T3` use or
context · `T4` state transition · `T5` event · `T6` event · `T7` decision or
status · `T8` rework route.

**Success criteria**

- [ ] All eight, correctly classified.
- [ ] I used the controlled words — *action*, *use or context*, *event*,
      *decision or status*, *rework*.
- [ ] I did not call any of the six a transition.
- [ ] Under forty-five seconds, without notes.

**Common failure.** Calling `T5` and `T6` transitions because something moves.
**Delivery and receipt are events; the state is unchanged.**

---

## Exercise 34 — Which two change state

**Task.** Name them, and say what happens to the state in the other six. Twenty
seconds.

**Why this exercise.** The headline of Slide 9, and the correction the module
exists to make.

**What good looks like.** **`T1` and `T4`.** In `T2` and `T3` the information
stays **Shared**. In `T5`, `T6` and `T7` it stays **Published**. `T8` returns it
to **WIP** and then reuses `T1` or `T4`.

**Success criteria**

- [ ] `T1` and `T4`, named without hesitation.
- [ ] I said the state is **unchanged** in `T2`, `T3`, `T5`, `T6` and `T7`.
- [ ] I described `T8` as a **return and reuse**, not a new transition.
- [ ] Twenty seconds.

**Common failure.** Naming `T1` and `T8`, because both involve WIP. **`T8`
returns; it does not introduce a new kind of state change.**

---

## Exercise 35 — Why a linear flowchart misleads

**Task.** A designer proposes drawing `T1 → T2 → … → T8`. Explain why not.
Thirty seconds.

**Why this exercise.** This will be proposed, it looks helpful, and refusing it
quickly matters.

**What good looks like.** A chain asserts four things that are not true: **one
mandatory order**, **eight sequential transitions**, **automatic progression**,
and **a complete operating route**. Six of the eight are not transitions; most
information goes through `T1` and stops; `T5`–`T7` cannot arise at all while
`T4` is blocked. **A grouped table is the honest form.**

**Success criteria**

- [ ] I named at least three of the four false assertions.
- [ ] I said most information stops at `T1`.
- [ ] I offered the **alternative** — a table grouped by kind.
- [ ] I was brief and not precious about it.
- [ ] Thirty seconds.

**Common failure.** Accepting a compromise — *"a chain with some dashed lines"*.
Anything that runs left to right through eight boxes asserts the sequence.

---

## Exercise 36 — `T8` without calling it a state transition

**Task.** Explain `T8` in thirty seconds. **The word *transition* is banned.**

**Why this exercise.** `T8` is the step most often miscounted as a third
transition, and the ban forces the right framing.

**What good looks like.** `T8` is the **rework route**. Something is rejected,
found unsuitable, or raises an issue; the originating task team corrects it **in
its own WIP**, checks it, and reauthorises. Coming back out it uses `T1` or `T4`
again. Previous exchanges are **marked superseded, not deleted**.

**Success criteria**

- [ ] The banned word never appeared.
- [ ] I called it a **route** or a **return**.
- [ ] I said correction happens **in the originator's WIP**.
- [ ] I said it **reuses** `T1` or `T4`.
- [ ] I mentioned superseded, not deleted.

**Common failure.** "It's the transition back to WIP." One word, and the count
goes to three.

---

## Exercise 37 — Describe `T1` by purpose, checks, authority and evidence

**Task.** Take `T1` apart in sixty seconds. Four headings.

**Why this exercise.** It is Slide 10's content, and it is the only transition
that can be taken apart with an established authority behind it.

**What good looks like.** **Purpose** — make information available beyond the
originating task team for the stated purpose. **Checks** — task-team technical
and content, **and** information-quality and readiness. **Authority** — the
Task-Team Lead, or another role explicitly allocated the function. **Evidence** —
version history, checking record, share record.

**Success criteria**

- [ ] All four headings, in order.
- [ ] **Both** checks named.
- [ ] The *or another role explicitly allocated* qualifier included.
- [ ] All three evidence items named.
- [ ] Sixty seconds.

**Common failure.** Naming one check. **There are two, and both are required.**

---

## Exercise 38 — Why the evidence field cannot be omitted

**Task.** Explain in thirty seconds why a transition diagram without evidence is
wrong.

**Why this exercise.** Evidence is the field cut first for space, and it is the
one that distinguishes a governed transition from a file move.

**What good looks like.** Evidence is what makes the transition demonstrable
afterwards. It must show that the **required checks occurred**, that the
**authorised function decided**, that a **new permitted use was established**,
and that the **originator and container remain traceable**. Without it you have a
claim that something was authorised, and nothing to support it. Our BEP: evidence
must be **sufficient and traceable**, and needn't come from any particular
software function.

**Success criteria**

- [ ] I named at least three of the four things evidence must show.
- [ ] I used **sufficient and traceable**.
- [ ] I said evidence needn't come from a particular software feature.
- [ ] I did not list specific platform features as required.
- [ ] Thirty seconds.

**Common failure.** "The system records it automatically." Some of it. **The
checking record and the authorisation record are not automatic.**

---

## Exercise 39 — Governance definition versus live evidence

**Task.** Explain the difference for `T1`. Thirty seconds.

**Why this exercise.** It is the module's central hazard, applied to its best
example.

**What good looks like.** `T1` is **controlled governance** — its purpose,
checks, authority and evidence are all defined, and the authority is established.
It is also **implementation unverified** — no complete traceable cycle has been
observed. **Both are true at once.** Defining a transition well is not evidence
that it has run.

**Success criteria**

- [ ] I gave **both** statuses for `T1`.
- [ ] I said they are **simultaneously true**.
- [ ] I did not present the gap as a failure.
- [ ] I distinguished *defined* from *demonstrated*.
- [ ] Thirty seconds.

**Common failure.** Choosing one. **The whole point is that they are different
questions.**

---

## Exercise 40 — Why `ARC-01` does not prove a `T1` cycle

**Task.** Explain in thirty seconds.

**Why this exercise.** One qualified observation is the most over-read piece of
evidence in the module.

**What good looks like.** `ARC-01` is recorded as *"live equivalent observed"* —
a **container** observation. It says a container exists in a comparable form. It
does not show that a check occurred, that the Task-Team Lead authorised anything,
that evidence was recorded, or that a permitted use was established. And our
validation record is explicit that **no complete traceable cycle** was observed.

**Success criteria**

- [ ] I called it a **container observation**.
- [ ] I named at least two things it does not show.
- [ ] I cited the no-complete-cycle finding.
- [ ] I did not turn it into a failure claim — *absence of observation is not
      observation of absence*.
- [ ] Thirty seconds.

**Common failure.** "So Architecture is working." A container was seen. **A cycle
was not.**

---

## Exercise 41 — Why `T4` is blocked

**Task.** Explain in thirty seconds. **Do not describe it as broken.**

**Why this exercise.** Repeated from Exercise 22 deliberately, now with the
transition anatomy behind it — the answer should be **more precise**, not longer.

**What good looks like.** `T4` needs a delivery readiness review and then a
publication or exchange authorisation. That authorisation needs an authority our
BEP records as **unresolved** — it depends on an approved delivery arrangement
that does not yet exist. So `T4` has **no available authorising function**, and
**information remains Shared**. The evidence it would produce cannot be produced,
because the decision cannot be made.

**Success criteria**

- [ ] I named the gate — **delivery readiness review**.
- [ ] I said the authority is **unresolved**, not missing.
- [ ] I said **information remains Shared**.
- [ ] I noted that the evidence cannot be produced.
- [ ] The answer was **sharper** than my Exercise 22 answer, not longer.

**Common failure.** Repeating Exercise 22 verbatim. Section C should have added
the gate and the evidence.

---

## Exercise 42 — Distinguish `T4` from `TRN-E03`

**Task.** Explain the difference in thirty seconds. **Name both kinds.**

**Why this exercise.** They are merged constantly, and the merge hides four
unresolved matters.

**What good looks like.** **`T4` is an information-state transition** — Shared to
Published. **`TRN-E03` is a delivery event** — a controlled design review or
project-facing exchange. `TRN-E03` **exercises** `T4`; it is not `T4`. And they
are blocked differently: `T4` by **one** matter, `TRN-E03` by **five**.

**Success criteria**

- [ ] Both **kinds** named — transition and event.
- [ ] I used **exercises**, or an equivalent, for the relationship.
- [ ] I gave the **one versus five** contrast.
- [ ] I did not use the identifiers interchangeably at any point.
- [ ] Thirty seconds.

**Common failure.** "They're basically the same block." They are two blocks, and
one is four matters larger.

---

## Exercise 43 — The five `TRN-E03` dependencies

**Task.** Name all five. Twenty seconds. **No notes.**

**Why this exercise.** The count is the argument — and four of the five are
invisible if you only think about publication authority.

**What good looks like.** Publication / exchange authorisation authority ·
recipient acceptance authority · recipient identity · required formats ·
deliverable set.

**Success criteria**

- [ ] All five.
- [ ] I did not invent a sixth.
- [ ] I did not offer a candidate for any of them.
- [ ] Twenty seconds, without notes.

**Common failure.** Naming four and adding *"and probably a date"*. **No date is
among them**, and inventing one adds a matter the sources do not record.

---

## Exercise 44 — Why information remains Shared

**Task.** Explain what actually happens to information while `T4` is blocked.
Thirty seconds. **Make it sound workable, because it is.**

**Why this exercise.** An audience hearing *blocked* assumes *stuck*. Most of the
project's work is unaffected.

**What good looks like.** It **remains Shared** — a perfectly usable state. Teams
can coordinate against it, review it, consume it, reference it for the stated
purpose. What cannot happen is a project-facing exchange that depends on
publication. So work continues; only the route needing an unheld authority stops.
And **no partial progression** — nothing sits half-transitioned.

**Success criteria**

- [ ] I said **remains Shared**, and that Shared is usable.
- [ ] I named at least two things that still work.
- [ ] I named what does not.
- [ ] I said there is **no partial progression**.
- [ ] Thirty seconds.

**Common failure.** Describing the project as stalled. **One route is stopped.
The rest of the workflow is unaffected.**

---

## Exercise 45 — Published, Delivered, Received, Accepted

**Task.** Explain all four as separate concepts. Forty-five seconds. **Say which
is a state.**

**Why this exercise.** Repeated from Exercise 24 with the transition
classification behind it — the answer should now name the *kinds*.

**What good looks like.** **Published** — an information **state**, authorised
for a defined purpose. **Delivered** — an **event**, sent to an identified
recipient. **Received** — an **event**, arrived and registered. **Accepted** — a
**decision and status** against a stated purpose. Only the first is a state; the
other three are recorded **against** information whose state is unchanged. And
acceptance authority is **unresolved** on this project.

**Success criteria**

- [ ] All four, each with its **kind**.
- [ ] I said **only Published is a state**.
- [ ] I said the other three leave the state unchanged.
- [ ] I noted that acceptance authority is unresolved.
- [ ] Forty-five seconds.

**Common failure.** Treating them as four stages. **They are four different kinds
of object**, and three of them never change the state.

---

## Exercise 46 — Deliver Slides 8–11 to time

**Task.** Deliver Section C end to end. **Target: 6.0 minutes. Measure it.**

**Why this exercise.** Section C is the module's technical heart, and Slides 9
and 11 both invite discussion that belongs after the session.

**What good looks like.** Slide 8 lands *movement is not transition*. Slide 9
lands *only `T1` and `T4`*. Slide 10 takes `T1` apart with its evidence field
intact. Slide 11 shows two panels, an empty authority position, and the one-versus
-five contrast.

**Success criteria**

- [ ] **6.0 minutes ± 20 seconds**, measured.
- [ ] *Only `T1` and `T4` change information state* was said explicitly.
- [ ] The `T1` **evidence field** was named, not skipped.
- [ ] The publication-authority position was **shown empty**.
- [ ] `T4` and `TRN-E03` were never used interchangeably.
- [ ] I did not draw or describe a `T1`–`T8` sequence.
- [ ] No authority, recipient, format or deliverable was invented.

**Common failure.** Slide 9 running to 2.5 minutes because eight rows invite
eight explanations. **Group them, name the two, and move.**

---

# Section D and E — Slides 12–14: properties, governance direction and the questions

**Fifteen practice exercises and five delivery exercises.** The closing five
include the module's only full-length timed run.

**One rule runs through all twenty.** These slides are where the temptation to be
helpful is strongest — to supply a naming convention, to name an authority, to
answer a Triviron question. **Every exercise below is partly a test of not doing
that.**

---

## Exercise 47 — Six properties, six questions

**Task.** Name the six container properties and the **control question** each one
answers. Sixty seconds, from memory.

**Why this exercise.** A property list is inert. The questions are what make them
controls, and they are what Slide 12 has to land.

**What good looks like.** **Name** — which container is this? **Version** — which
stored platform occurrence? **Revision** — which managed issue, *where project
convention requires one*? **Status** — what condition is declared? **Suitability**
— for what purpose may it be relied upon? **Metadata** — which structured
attributes support control?

**Success criteria**

- [ ] All six, each with **its own** question.
- [ ] I used the **Harrismith** wording, not an ISO definition.
- [ ] I included the *"where project convention requires one"* qualification on
      revision.
- [ ] Sixty seconds.

**Common failure.** Merging status and suitability into "the status of the file".
**They answer different questions** — one is a condition, one is a permitted use.

---

## Exercise 48 — A version is not a revision

**Task.** Explain why saving a new version in the platform does not create a
revision. Thirty seconds.

**Why this exercise.** This is the single most common property confusion, and the
BEP has a sentence for it.

**What good looks like.** A **version** is a platform or file history instance —
the software creates it. A **revision** is a **controlled issue identifier**,
applied where project convention requires one — a person applies it as part of a
managed issue. The BEP's line: *"a new platform version creates none of the
others."* Saving is not issuing.

**Success criteria**

- [ ] I distinguished **automatic** from **managed**.
- [ ] I quoted or paraphrased *a new platform version creates none of the others*.
- [ ] I did **not** invent a revision code to illustrate it.

**Common failure.** "Version 3 is revision C." **You have just invented a
revision convention** — and this project has none.

---

## Exercise 49 — Status, suitability, acceptance

**Task.** Explain the difference between **status**, **suitability** and
**acceptance**. Forty-five seconds.

**Why this exercise.** Three words used interchangeably in most project
conversations, and the gap between the second and third is where reliance goes
wrong.

**What good looks like.** **Status** is a workflow or decision **condition**.
**Suitability** states **what the information may be used for**. **Acceptance** is
a **recipient's decision and status** against a stated purpose — and on this
project, acceptance authority is **unresolved**. Status does not equal
suitability; suitability does not equal acceptance.

**Success criteria**

- [ ] Three distinct definitions.
- [ ] I said **suitability is not acceptance**.
- [ ] I noted acceptance authority is unresolved.
- [ ] I did not use a code to explain any of them.

**Common failure.** Explaining suitability by reciting a code set. **There is no
approved code set on this project**, and reciting one from elsewhere adopts it.

---

## Exercise 50 — "What naming convention should we use?"

**Task.** Answer the question **without inventing a convention**. Sixty seconds.

**Why this exercise.** It will be asked, it will be asked sincerely, and the
helpful answer is the wrong one.

**What good looks like.** The project **Naming Standard does not yet exist** —
`standards/naming/` is empty. The BEP creates **no field order, no separator set
and no permitted-value list**, and **imposes no ISO 19650 filename pattern**. What
it does state is what naming must achieve: **unambiguous identity**; origin,
discipline and task-team context; information type; consistency for retrieval and
traceability; and identity that survives the container being **moved, copied or
exchanged** — because **platform folder placement alone is not identification**.
Adopting a syntax is a governance decision.

**Success criteria**

- [ ] I gave the **principles** and withheld the **syntax**.
- [ ] I said the Naming Standard does not yet exist.
- [ ] I said folder placement is not identification.
- [ ] **I offered no example filename of any kind.**

**Common failure.** "Well, something like Project-Discipline-Type-Number." **You
have just written the project's naming standard from the front of a room**, and
somebody in the audience wrote it down.

---

## Exercise 51 — Why no ISO 19650 filename pattern is imposed

**Task.** Explain why the BEP declines to impose an ISO 19650 filename pattern,
**without implying the project rejects ISO 19650**. Forty-five seconds.

**Why this exercise.** Declining to impose is not the same as declining to adopt,
and the distinction is easy to fumble into a conformity claim in either direction.

**What good looks like.** The BEP states that **no ISO 19650 filename pattern is
imposed** — it creates no syntax at all, from any source. Adopting one is
available to the project; it simply has to be **adopted by whoever holds that
decision, and recorded**. Not assumed because it is the familiar pattern, and not
excluded either. The document is silent by design, not opposed.

**Success criteria**

- [ ] I said no pattern is **imposed**.
- [ ] I did **not** say ISO 19650 is rejected, unsuitable or inapplicable.
- [ ] I did **not** say Harrismith conforms to, or fails to conform to, ISO 19650.
- [ ] I said adoption is a governance decision.

**Common failure.** Sliding into either "we don't use ISO here" or "we follow ISO
naming anyway". **Both are conformity claims**, and neither is supported.

---

## Exercise 52 — Software-native metadata is not the project standard

**Task.** Respond to *"the software already has all these fields — isn't that our
metadata?"* Forty-five seconds.

**Why this exercise.** The tool's field list is concrete and present; the
governance requirement is abstract and absent. The concrete one wins unless you
say otherwise.

**What good looks like.** The BEP's position is direct: **software-native
metadata is not the project standard**, and the project's metadata requirements
are **defined by governance, not inherited from whatever fields a tool happens to
provide**. Those fields may well end up carrying the metadata — they do not get to
define it. And **no classification system is adopted**: Uniclass, OmniClass,
MasterFormat all remain unadopted.

**Success criteria**

- [ ] I quoted or paraphrased **defined by governance, not inherited**.
- [ ] I allowed that the tool may **carry** it.
- [ ] I said **no classification system is adopted**.
- [ ] I named no field and specified no schema.

**Common failure.** Listing the software's fields approvingly. **That adopts a
schema by demonstration.**

---

## Exercise 53 — A correct name proves nothing about state

**Task.** Explain why a correctly named file in the correct folder still tells you
nothing about its information state. Thirty seconds.

**Why this exercise.** It closes the loop between Slide 12 and Slide 1, and it is
the property-level version of the module's central error.

**What good looks like.** A filename **identifies** a container; it does not
declare its state and does not authorise anything. Folder placement does not
determine state either. A correct name and a correct location can both be true of
information that **nobody authorised anyone to rely on**. A code does not prove
that the process behind it occurred.

**Success criteria**

- [ ] I said naming **identifies** and does not **authorise**.
- [ ] I linked it back to folder placement.
- [ ] I said a code does not prove the process ran.

**Common failure.** Answering only about naming. **The point is that both
mechanisms fail in the same way**, and saying both is what makes it land.

---

## Exercise 54 — The four empty boxes, in thirty seconds

**Task.** Explain the four `not established` boxes on Slide 12 — **what they are,
and why they are shown rather than omitted**. Thirty seconds.

**Why this exercise.** A presenter who apologises for the empty boxes has
misunderstood them; a presenter who skips them has removed the slide's point.

**What good looks like.** Naming standard, revision convention, suitability code
set and metadata schema — **all four not established**, all four `standards/`
directories empty. They are **shown** because omitting them would imply no
decision is needed, and **empty** because filling them would invent four
standards at once. This is a decision still to be made, stated as a decision still
to be made.

**Success criteria**

- [ ] All four named.
- [ ] I gave the reason for **showing** them.
- [ ] I gave the reason for leaving them **empty**.
- [ ] I did not apologise for them or promise a date.

**Common failure.** "We're still working on those." **You do not know that**, and
it converts an unmade decision into work in progress.

---

## Exercise 55 — The direction of authority, in one sentence

**Task.** State the direction — decision to evidence — in **one sentence**, then
state what does **not** flow backwards. Thirty seconds total.

**Why this exercise.** Slide 13 has one minute. A presenter who cannot say this in
one sentence will take three.

**What good looks like.** *Governance decides, the process records the decision,
configuration implements it, and evidence shows the two agree.* And backwards: **a
platform setting creates no governance authority.**

**Success criteria**

- [ ] Four stages, one sentence.
- [ ] The reverse stated explicitly as **refused**.
- [ ] Under thirty seconds.

**Common failure.** Giving only the forward chain. **A one-directional statement
is one somebody can read in either direction**, which is why the visual shows the
refusal.

---

## Exercise 56 — Deviation versus non-conformance

**Task.** Define both, using the BEP's distinguishing criterion. Thirty seconds.

**Why this exercise.** These are defined terms in this project, not synonyms for
"mistake", and using them loosely undoes their usefulness.

**What good looks like.** A **deviation** is a **knowingly permitted** departure.
A **non-conformance** is an **unintended** one. *"The difference is intent and
authorisation, not severity."* A deviation can be serious; a non-conformance can
be trivial. The distinction is not about how bad it is.

**Success criteria**

- [ ] Both defined.
- [ ] I said the criterion is **intent and authorisation**.
- [ ] I said explicitly that it is **not severity**.

**Common failure.** Presenting deviation as the mild one and non-conformance as
the serious one. **That is precisely the reading the BEP rules out.**

---

## Exercise 57 — "We configured it before the document existed"

**Task.** Respond, without either excusing it or treating it as a scandal. Sixty
seconds.

**Why this exercise.** It is the most common real situation in the room, and both
easy answers are wrong.

**What good looks like.** That is a **deviation** — a defined term, not an insult.
The BEP's sentence is **a configuration that was never approved is a deviation,
however competently it was applied**: competence is not the test, authorisation
is. What the BEP does not allow is the third option, pretending the sequence
happened correctly. **Record it**, then decide whether to approve it or correct
it. And keep document, process and configuration aligned afterwards — a change
applied to one and not the others produces **a governance system that describes
something the project is not doing**.

**Success criteria**

- [ ] I named it a **deviation**, using the defined sense.
- [ ] I quoted or paraphrased **however competently it was applied**.
- [ ] I gave the action: **record, then approve or correct**.
- [ ] I did not moralise, and I did not wave it through.

**Common failure.** "That's fine, everyone does that." **It may well be common,
and it is still a departure that has to be recorded** — that is the entire point
of having the word.

---

## Exercise 58 — What CDE Administration may and may not do

**Task.** Give both columns. Forty-five seconds.

**Why this exercise.** The role is the one most often mistaken for an authority,
and the BEP addresses it explicitly.

**What good looks like.** **May**: configure folders, spaces, roles, permissions
and platform workflow **where authorised**; implement approved changes; check
configuration after an approved change. **Does not**: determine the
information-state model; assign publication authority; assign acceptance
authority; approve technical design. The governing sentences: **CDE
Administration implements governance; it does not create it**, and administrative
rights confer **the technical ability to change it and nothing more**. **Platform
permission is not BEP authority.** And the **holder is TBD**.

**Success criteria**

- [ ] Both columns, roughly equal weight.
- [ ] I said **implements, does not create**.
- [ ] I said **technical ability and nothing more**.
- [ ] I said the holder is **TBD** and named nobody.

**Common failure.** Delivering the *may* column at length and the *does not*
column as an afterthought. **The exclusions are the teaching.**

---

## Exercise 59 — Refuse an offered name

**Task.** Someone in the room says *"surely the BIM Manager holds publication
authority."* Respond in thirty seconds.

**Why this exercise.** Repeated in spirit from Exercise 23, now with Slide 13's
configuration boundary behind it. **The second answer should be faster and
firmer.**

**What good looks like.** No — and the BEP names four roles that do **not** hold
it by default: the **BIM Manager**, the **BIM Coordinator**, the **CDE
Administrator** and the **Architect**. It is recorded as **unresolved**, pending
an approved delivery arrangement that does not yet exist. Being able to perform
the action is not holding the authority. It stays TBD rather than being defaulted
to whichever role is nearest.

**Success criteria**

- [ ] I declined, immediately.
- [ ] I named the **four excluded roles**.
- [ ] I did **not** offer a fifth candidate.
- [ ] Thirty seconds — a long answer here sounds like negotiation.

**Common failure.** "Probably, but it's not confirmed." **That confirms it in the
room**, whatever the qualifier says.

---

## Exercise 60 — The five question groups, from memory

**Task.** Name Slide 14's five decision areas **in order**, with one question from
each. Sixty seconds.

**Why this exercise.** The order is the argument — purpose before states, states
before transitions, configuration last. A presenter who reorders them teaches
configuration-first.

**What good looks like.** **1 — CDE purpose and scope.** **2 — Information states
and permitted use.** **3 — Transitions, gates and authority.** **4 — Naming,
revision, suitability and metadata.** **5 — Platform configuration and
implementation evidence.** One question from each, each ending in a question mark.

**Success criteria**

- [ ] Five areas, correct order.
- [ ] One question from each, **phrased as a question**.
- [ ] Configuration last.
- [ ] **No answers offered.**

**Common failure.** Starting with the platform, because that is where real
projects start. **The slide's order is the correction.**

---

## Exercise 61 — The two questions you will not answer

**Task.** Deliver the two compulsory authority questions and **stop**. Twenty
seconds, including the silence.

**Why this exercise.** The instinct to fill the pause after an unanswered question
is very strong, and filling it is how an unassigned authority becomes an assumed
one.

**What good looks like.** *"Who holds publication authority? Who holds acceptance
authority?"* — asked plainly, left open, and followed by moving on to the next
group. If pressed: both are **unresolved** on Harrismith, and they are the two a
new project assumes into existence in week one.

**Success criteria**

- [ ] Both asked **verbatim**.
- [ ] **Neither answered**, hinted at, or paired with a candidate.
- [ ] I did not fill the pause with "which is usually the…".
- [ ] I moved on cleanly.

**Common failure.** Answering the second one because the silence after the first
was uncomfortable. **The silence is the exercise.**

---

## Exercise 62 — Deliver Slide 12 to time

**Task.** Deliver Slide 12 alone. **Target: 1.5 minutes. Measure it.**

**Why this exercise.** Slide 12 carries a whole section on its own and invites a
coding-standards discussion it cannot hold.

**What good looks like.** Six properties with their questions, the key
distinctions, the four empty boxes, and the governance-not-inherited line. **No
example code anywhere.** If a naming question arrives, answer it in one sentence
and move.

**Success criteria**

- [ ] **1.5 minutes ± 10 seconds**, measured.
- [ ] All six properties, each with its control question.
- [ ] All four `not established` fields shown and named.
- [ ] **No filename, revision, suitability, status or metadata example given.**
- [ ] I said a code does not prove the process occurred.

**Common failure.** Running to three minutes because someone asked about naming.
**That question belongs after the session**, and Slide 14 asks it properly.

---

## Exercise 63 — Deliver Slides 13–14 to time

**Task.** Deliver Section E end to end. **Target: 3.0 minutes — 1.0 and 2.0.
Measure both.**

**Why this exercise.** Slide 13 is the only one-minute slide in the module, and it
steals from Slide 14 if allowed to.

**What good looks like.** Slide 13: the chain, the refused reverse, the
never-approved-configuration sentence, three callbacks, stop. Slide 14: five
question groups, the two authority questions in the open, the closing message,
the end state.

**Success criteria**

- [ ] **Slide 13 at 1.0 minute ± 10 seconds.**
- [ ] **Slide 14 at 2.0 minutes ± 15 seconds.**
- [ ] I did not re-argue Slides 1, 8 or 10 on Slide 13.
- [ ] Every Slide 14 item was a **question**.
- [ ] **No Triviron fact was stated.**
- [ ] The end state was delivered as written, with no date and no owner.

**Common failure.** Slide 13 running to two minutes because the callbacks turned
into recaps. **Three lines, named, not re-argued.**

---

## Exercise 64 — Deliver the whole module to time

**Task.** Deliver Slides 1–14 end to end. **Target: 20.0 minutes. Measure it.**

**Why this exercise.** This is the module's only full-length run, and **no timing
in this repository has ever been measured**. Every figure in the outline is an
allocation until this exercise is done.

**What good looks like.** Section A 3.0, Section B 6.5, Section C 6.0, Section D
1.5, Section E 3.0. Where you lose time, you lose it in Section B and Slide 9;
where you recover it, recover from Slide 4 or Slide 13. **Slide 11 and Slide 14
are not recovery slides.**

**Success criteria**

- [ ] **20.0 minutes ± 60 seconds**, measured end to end.
- [ ] Per-section times recorded against the allocation, so the outline can be
      corrected if it is wrong.
- [ ] No state, transition, authority, code or Triviron fact was invented at any
      point.
- [ ] Every blocked, empty or unresolved element was **shown as such**.
- [ ] I said nothing that asserted live implementation.

**Common failure.** Treating the allocation as a measurement. **It is not one, and
it will not become one until this exercise has been run at least twice.**

---

## Exercise 65 — The closing, and stopping

**Task.** Deliver the module's closing, then **stop**. Thirty seconds.

**Why this exercise.** The end of a twenty-minute module invites a summary of the
programme, a preview of Module 5 and a reassurance that Harrismith is nearly
finished. All three are additions, and the third is untrue.

**What good looks like.** Four states, two of them currently unreachable. Eight
controlled steps, two of which change information state. Four coding standards
everyone assumes exist, which do not. **The CDE is the process; the folders are
where it shows up.** Then stop.

**Success criteria**

- [ ] The closing delivered in **one breath's worth of content**.
- [ ] **No Module 5 preview.**
- [ ] **No programme summary.**
- [ ] **No claim that Harrismith is nearly complete, live, issued or conformant.**
- [ ] I stopped talking.

**Common failure.** "And next time we'll look at…" **Module 5's scope is not
yours to announce here**, and the closing loses its edge the moment it becomes an
agenda item.

---

## Exercise 66 — The invention self-audit

**Task.** After any delivery of Slides 12–14, audit yourself against the four
invention classes. Sixty seconds, written.

**Why this exercise.** This is Exercise 13's discipline applied to the two slides
where invention is most tempting and least visible — because an invented naming
convention and an invented Triviron fact both sound like helpfulness.

**What good looks like.** Four questions, answered honestly. **Did I state a
name, code, convention or schema?** **Did I state a Triviron fact — jurisdiction,
platform, structure, role, date?** **Did I answer either authority question, or
hint at an answer?** **Did I claim any control is operating, or that Harrismith
conforms to anything?** Any yes is a correction to make before the next delivery,
not a thing to explain away.

**Success criteria**

- [ ] All four asked, in writing.
- [ ] Any yes recorded with the exact wording used.
- [ ] The correction made in the notes, not just noted mentally.
- [ ] I did not count "I only said it as an example" as a no.

**Common failure.** Auditing the slides instead of the delivery. **The slides are
already controlled; the risk is in what gets said around them.**

---

## Exercise 67 — Write five state-definition questions for a new project

**Task.** Write five questions a new project must answer before it can say what
its information states *are*. **Questions only.** Five minutes, written.

**Why this exercise.** Slide 14 gives you a group heading and some examples. The
skill is generating the questions yourself, for a project you know nothing about
— which is exactly the position the slide puts the audience in.

**What good looks like.** Five questions covering **which states the project
adopts**, **what each state is for**, **who may rely on information in each**,
**whether each state is conceptual, physical or both**, and **how folder location
will be stopped from being mistaken for state**. Each ends in a question mark.
None contains a proposed answer, a state name borrowed from Harrismith presented
as the expected set, or a folder path.

**Success criteria**

- [ ] Five questions, **each ending in a question mark**.
- [ ] **No answer smuggled into the phrasing** — no "will the project adopt the
      four states…?"
- [ ] The conceptual-versus-physical question is present.
- [ ] The folder-is-not-state question is present.
- [ ] **No Triviron fact assumed** — not the platform, not the phases, not the
      participants.

**Common failure.** Writing *"Will the project use Work in Progress, Shared,
Published and Archive?"* — a Harrismith answer wearing a question mark.
**Harrismith's four states are one project's decision, not the menu.**

---

## Exercise 68 — Write five transition-authority questions for a new project

**Task.** Write five questions a new project must answer about who moves
information between states. **Questions only.** Five minutes, written.

**Why this exercise.** This is the group Harrismith did not finish, and the
reason a route is blocked. Generating these questions is the transferable part of
the whole module.

**What good looks like.** Five questions covering **which actions actually change
state**, **who initiates**, **who checks**, **who authorises**, and **what
happens when an authority is unassigned**. **Both compulsory questions appear
verbatim** — *"Who holds publication authority?"* and *"Who holds acceptance
authority?"* — if you use fewer than five slots, they are the two that stay.

**Success criteria**

- [ ] Five questions, **each ending in a question mark**.
- [ ] **Both compulsory authority questions present, word for word.**
- [ ] Initiating, checking and authorising treated as **separate** questions.
- [ ] The unassigned-authority question present.
- [ ] **No candidate holder named**, not even as an illustration.

**Common failure.** Collapsing initiate, check and authorise into one question
about "who signs it off". **Three functions, three questions** — Slide 10 spent
its time establishing exactly that.

---

## Exercise 69 — Write five naming, coding and metadata questions

**Task.** Write five questions a new project must answer about identification,
revision, suitability and metadata. **Questions only.** Five minutes, written.

**Why this exercise.** This is the group most likely to be answered by whoever
configures the platform first, using whatever the tool provides — which is the
failure Slide 12 and Slide 13 exist to prevent.

**What good looks like.** Five questions covering **what naming standard
applies**, **what revision convention applies**, **which status and suitability
codes are required**, **what metadata schema is required**, and **who assigns and
checks each property**. A sixth, if you have room: **how will codes be
distinguished from evidence that the process behind them happened?**

**Success criteria**

- [ ] Five questions, **each ending in a question mark**.
- [ ] **No example code, filename, field name or schema anywhere** — not even as
      "something like".
- [ ] Assignment and checking asked as a **governance** question, not a tooling
      one.
- [ ] **No ISO pattern offered as the default answer.**
- [ ] Nothing implies the software's own fields are the schema.

**Common failure.** Writing *"Will we use ISO 19650 naming?"* — which is a
recommendation, not a question, and Harrismith's own BEP declines to impose that
pattern.

---

## Exercise 70 — "Can we just copy Harrismith's CDE?"

**Task.** Answer it. Forty-five seconds. **Do not recommend the structure, and do
not disparage it.**

**Why this exercise.** It is the most reasonable question in the room and the
most dangerous answer to get wrong. Saying yes exports two unresolved authorities
into a project that will never know they were inherited. Saying "no, build your
own" wastes the one worked example the audience has.

**What good looks like.** The shape can be copied; what it stands on cannot. The
structure is the **output** of the five question groups, and it is
**conditionally adopted** on a project whose publication and acceptance
authorities are still open and whose `T4` route is blocked. Copy it and you
inherit those without the record explaining them. **Take the questions, not the
answers.**

**Success criteria**

- [ ] **Neither recommended nor criticised** — the structure's status is
      *conditionally adopted*, and that is what gets said.
- [ ] The two unresolved authorities named as **what would be inherited**.
- [ ] Questions offered instead of the structure.
- [ ] **No Triviron assumption** about what it would need.
- [ ] **No claim that Harrismith's model conforms to anything** it could be
      copied for.

**Common failure.** "It's a good starting point." **It is a governed answer to
another project's questions**, and calling it a starting point is how it becomes
an unexamined default.

---

## Exercise 71 — The ten-second closing

**Task.** Deliver the ten-second closing fallback. **Measure it.** Then run it
back to back with Exercise 65's thirty-second form and hear the difference.

**Why this exercise.** The closing is where an over-running session gets
improvised, and an improvised closing is where the module's carefully unclaimed
things get claimed — that Harrismith is finished, that the states are running,
that the standards are coming.

**What good looks like.** Four states, eight steps, four standards that do not
exist yet, and the process-not-folders line. **Nothing added to compensate for
the lost twenty seconds.** The dropped qualifiers stay dropped rather than being
replaced by a rounder claim.

**Success criteria**

- [ ] **Ten seconds**, measured — not "about ten".
- [ ] The process-not-folders line survives.
- [ ] **No claim added** to fill the gap left by the qualifiers.
- [ ] **No Module 5 preview**, no programme summary.
- [ ] I stopped.

**Common failure.** Compressing to *"four states, eight steps, and the standards
are on their way"* — eight words shorter and one invented fact heavier. **No
source records any standards work in progress.**

---

## Scope note

**Seventy-one exercises, covering the complete Slides 1–14 baseline.**

| Set | Exercises | Covers |
|---|---|---|
| Foundation | 1–14 | Slides 1–3, and the questions that arrive with a state diagram |
| Section B | 15–29 | Slides 4–7 — the four states |
| Section C | 30–46 | Slides 8–11 — the transition workflow |
| Sections D and E | 47–71 | Slides 12–14 — properties, governance direction, the questions |

**Five exercises are deliberate repeats** — 41 revisits 22, 45 revisits 24, 53
revisits the Slide 1 folder error at property level, and 59 revisits 23 with the
configuration boundary behind it. **The second answer should be sharper, not
longer.**

**Five are timed delivery runs** — 14 (Slides 1–3), 29 (Slides 4–7), 46 (Slides
8–11), 62 (Slide 12) and 63 (Slides 13–14) — **and Exercise 64 runs all fourteen
slides end to end.** **Two more time the closing** — 65 at thirty seconds and 71
at ten. Until 64 has been run, **every timing in this module is an allocation,
not a measurement.**

**Three exercises build questions rather than answer them** — 67, 68 and 69 ask
you to generate a new project's state, authority and coding questions from
nothing. **They are the transferable part of the module**, and the failure mode
in all three is the same: writing a Harrismith answer with a question mark on the
end.

**Exercise 13 is done after every one of the other seventy.** If you cannot say
whether a statement is controlled, proposed or unresolved, do not say it.
**Exercise 66 is done after every delivery of Slides 12–14**, for the same reason
in the two places the discipline is hardest to hold.
