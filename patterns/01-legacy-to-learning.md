# Pattern: From Legacy Control to Learning Systems

### Intent

Prevent legacy understanding from being mistaken for certainty, and ensure learning governs risk reduction even when replacing well-understood systems.

### Context

This pattern applies when organisations are:

* replacing or replatforming existing systems
* migrating functionality from legacy platforms
* “modernising” known capabilities in new technical or organisational contexts

In these situations, feature requirements often appear well understood.

### System Problem

When legacy knowledge is treated as certainty, organisations assume that:

* scope is known
* effort is predictable
* risk is minimal

This leads to deterministic planning, early commitments, and compressed learning.

However, while **what** a system does may be known, **how it will behave in a new context rarely is**.

The result is:

* late discovery of integration risk
* fragile timelines
* defensive scope protection
* delayed or opaque failure

### Forces at Play

* “We’ve built this before”
* Pressure to justify investment with firm plans
* Migration framed as execution, not discovery
* Confidence borrowed from historical delivery

These forces reward certainty signalling over evidence generation.

### EOM Position

This pattern protects the EOM invariants of:

* **Learning Over Certainty**
* **Incremental and Reversible Commitment**
* **Evidence Over Opinion**

It reinforces the principle that **learning must precede high-integrity commitment**, regardless of prior experience.

### The Pattern

The system treats legacy knowledge as **input to hypotheses**, not as proof.

Known functionality informs:

* what must be explored first
* where failure would be costly
* which assumptions deserve early testing

Investment is staged to:

* surface unknowns early
* collapse integration and migration risk
* validate operational, performance, and behavioural assumptions

Legacy systems are sources of questions, not answers.

### Example

Instead of:

> “Rebuild the billing platform with equivalent functionality by Q4”

The system frames:

> “Learn which billing behaviours, integrations, and data flows are most likely to fail or degrade in the new architecture — and reduce those risks before committing to full migration.”

Early work focuses on:

* boundary interactions
* data migration paths
* operational characteristics

Not feature parity.

### Signals This Pattern Is Holding

* Migration plans change early and cheaply
* Teams are rewarded for discovering incompatibilities
* Commitments increase only after risky assumptions are tested
* “Equivalent functionality” is not treated as evidence of readiness

### Anti-Patterns

* “Lift and shift” treated as low risk
* Feature parity used as a success metric
* Migration milestones framed as delivery guarantees
* Learning postponed until late integration testing

### Trade-offs

* Progress appears slower initially
* Requires reframing stakeholder expectations
* Less comforting than deterministic migration plans

### Related EOM Material

* Essay: _Why Feature Roadmaps Feel Safer Than They Are_
* Pattern: Outcome Over Output
* Pattern: Who Does What By How Much
* Diagnostic: Incremental & Reversible Commitment
