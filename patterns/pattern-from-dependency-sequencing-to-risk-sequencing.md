# Pattern: From Dependency Sequencing to Risk Sequencing

#### Context

In complex product environments, teams are expected to identify cross-team dependencies and sequence work accordingly. This can result in Gantt charts and similar documents that imply certainty about ordering, duration, and readiness.

***

#### Problem

Dependencies in complex systems are rarely stable or fully knowable upfront. Sequencing work against speculative dependencies:

* creates false certainty
* delays learning
* back-loads integration risk
* incentivises narrative management over truth
* increases coordination cost without reducing failure

***

#### Forces at Play

* Leaders need predictability
* Teams fear being the blocker
* PMs are expected to “have a plan”
* Governance expects dependency management
* Risk is easier to _schedule_ than to _surface_

***

#### Solution

Replace dependency-driven plans with **risk-ordered learning**, where work is prioritised based on its ability to reduce uncertainty, expose dependencies, or collapse risk.

Rather than sequencing features across teams, teams:

* identify assumptions that create dependencies
* prioritise work that validates or invalidates those assumptions
* front-load integration and feasibility learning
* use evidence thresholds to unlock subsequent commitments

***

#### Resulting System Behaviour

* Dependencies surface earlier
* Integration risk declines faster
* Plans remain adaptive rather than brittle
* Teams collaborate around learning, not deadlines

***

#### Consequences

✅ Faster learning\
✅ Fewer late surprises\
✅ Reduced coordination overhead\
⚠️ Requires tolerance for ambiguity\
⚠️ Requires governance that can operate without fixed plans
