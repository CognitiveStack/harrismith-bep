# Module 4 — Exercises

**Status:** Exercise set for the **Slides 1–7** baseline. Teaching material;
**not governance.**

Rehearsal exercises for the presenter, not assessments for an audience. Do them
aloud, alone, before delivering to anyone. **Exercise 13 is done after each of
the others.**

**Twenty-nine exercises in two sets.** Exercises 1–14 cover Slides 1–3 and the
questions that arrive as soon as a state diagram appears; **Exercises 15–29 cover
Section B — the four states.**

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

## Scope note

**Twenty-nine exercises, covering the Slides 1–7 baseline.**

| Set | Exercises | Covers |
|---|---|---|
| Foundation | 1–14 | Slides 1–3, and the questions that arrive with a state diagram |
| Section B | 15–29 | Slides 4–7 — the four states |

**Exercise 13 is done after every one of the other twenty-eight.** If you cannot
say whether a statement is controlled, proposed or unresolved, do not say it.

Exercises for Slides 8–14 are a later increment.
