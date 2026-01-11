# Anti-Pattern: Outcome-Wrapped Feature Plans

### Also known as

* Feature Roadmaps in Outcome Clothing
* OKR Theatre
* Hypothesis-in-Name-Only
* Learning-Flavoured Determinism

***

### Summary

Outcome-Wrapped Feature Plans are delivery plans that **appear** outcome-led but **behave** exactly like traditional feature roadmaps.

Outcomes are used as labels.\
Features remain the unit of commitment.

This anti-pattern preserves the _language_ of learning while retaining the _behaviour_ of prediction.

***

### Context

This anti-pattern commonly appears when organisations:

* adopt outcome language (OKRs, hypotheses) without changing funding or governance
* want the perceived modernity of outcome-led planning without surrendering certainty
* are replacing legacy systems where “the requirements are known”
* experience executive discomfort with unbounded delivery horizons
* attempt to satisfy EOM principles without altering decision constraints

It is particularly prevalent during “transformation” efforts.

***

### What It Looks Like

#### Superficial signals

* Outcomes written, but…
* Features fully specified upfront
* Delivery dates inferred from feature scope
* Learning treated as optional
* Discovery constrained to validation of predetermined solutions

#### Typical artefacts

* OKRs where Key Results are features
* Roadmaps with outcome-themed epics
* Hypotheses that already assume the solution
* Migration plans where “unknowns” are acknowledged but scheduled anyway

***

### Example

#### Claimed framing (outcome-led)

**Objective**\
“Enable customers to complete payments reliably in the new platform”

**Key Results**

* Implement payment gateway integration
* Build reconciliation service
* Migrate legacy transaction data

#### Actual behaviour

* Scope is fixed
* Dates are expected
* Risk is deferred
* Learning is constrained to implementation

The “outcome” does not constrain decisions.\
It decorates them.

***

### Why This Happens

Outcome-Wrapped Feature Plans persist because they satisfy _multiple competing needs_:

* Leaders retain delivery predictability
* PMs appear aligned with modern thinking
* Funding mechanisms remain unchanged
* Governance remains approval-based
* Nobody has to say “we don’t know yet”

The organisation gains **defensibility**, not learning.

***

### Why It Fails

This anti-pattern reliably produces:

* delayed discovery of architectural risk
* late integration surprises
* defensive delivery behaviour
* erosion of psychological safety
* performative alignment
* slow adaptation despite outcome language

When learning contradicts the plan, the plan usually wins.

***

### How It Violates EOM Invariants

Outcome-Wrapped Feature Plans subtly break several EOM conditions of compatibility:

* **Learning no longer precedes commitment**\
  Commitment is implicit in feature selection.
* **Metrics stop acting as signals**\
  Progress reporting dominates sense-making.
* **Commitments become irreversible too early**\
  Even when risk remains high.
* **Flow optimises around delivery, not learning**\
  Uncertainty accumulates silently.

The system _claims_ EOM while behaving incompatibly with it.

***

### How to Detect This Anti-Pattern

Ask these questions:

* Would stopping this initiative early still be considered success?
* Can funding be withdrawn without reputational harm?
* Are delivery dates expectations or hypotheses?
* Can assumptions be invalidated without escalation?
* Is learning rewarded independently of scope completion?

If most answers are “no”, outcomes are cosmetic.

***

### Contrast With: Hypothesis Backlog

| Dimension     | Outcome-Wrapped Feature Plan | Hypothesis Backlog        |
| ------------- | ---------------------------- | ------------------------- |
| Planning unit | Features                     | Problems / outcomes       |
| Commitment    | Implicit & early             | Incremental & conditional |
| Learning      | Secondary                    | Primary                   |
| Risk          | Back-loaded                  | Front-loaded              |
| Flow          | Delivery-optimised           | Learning-optimised        |

Both may deliver the same product.\
Only one reduces uncertainty before commitment.

***

### When This Anti-Pattern Is Especially Dangerous

* Platform rebuilds
* Legacy system replacements
* Data migrations
* New architectures
* Regulatory integrations
* Cross-team dependency programmes

These domains **feel** knowable — but aren’t.

***

### How Organisations Get Stuck Here

Most organisations do not choose this anti-pattern deliberately.

They arrive here because:

* governance requires commitments
* funding requires predictability
* leaders are rewarded for certainty
* stopping work looks like failure

Without system-level change, outcome language collapses into theatre.

***

### In EOM Terms

Outcome-Wrapped Feature Plans are:

> **A compromise between learning language and control incentives**

They are not malicious.\
They are rational — within the wrong constraints.

***

### In Summary

Outcome-Wrapped Feature Plans allow organisations to _talk about learning_ while still behaving as if certainty exists.

They delay the moment where reality asserts itself — usually into delivery, integration, or operations.

EOM does not oppose features.\
It opposes **pretending certainty has been earned when it has not**.

When outcomes are merely wrappers, learning loses.
