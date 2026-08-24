---
description: Do you understand why your teams behave the way they do?
---

# Why Won't Your Teams Behave?

You've successfully rolled out your Agile/Product-Led/a.n.other change transformation (delete as appropriate). The programme of workshops and training was well attended and, more importantly, well received. You have identified and mapped your value stream(s), and found the one big impediment to flow. Your team of champions is in place, providing mentoring and guidance to the various product engineering teams, now organised into Stream-aligned, Enabling, and Complex Subsystem teams; communication has improved and there are clear signs of better alignment. OKRs have been rolled out across the teams too; the signs are that most will score highly this quarter. The new language is being spoken in corridors and in emails; the terminology wasn't too confusing after all and, at last, people seem to be on the same page. Things are looking up and the feedback from the teams is positive; the expected dissent didn't materialise, and people are genuinely enthusiastic about the changes.

But, annoyingly, certain old behaviours stubbornly persist. Work in progress is still too high, despite the new Kanban boards and WIP limits, which are frequently breached. Deployment frequency is up, since it was set as a bonusable KPI, but strangely the expected improvement in end-to-end delivery performance hasn't materialised. There is still friction between teams, and hand-offs remain annoyingly common. Teams assure you they're building CI/CD pipelines, yet weeks of manual regression testing remain embedded in every delivery plan. And, most disconcertingly, this year's major initiative isn't tracking to plan, despite the percentage of completed against committed having risen for the last two quarters. What is wrong with the teams' ability to estimate accurately?

What's going on? The transformation should be reaping rewards, but there are signs something is amiss.

The underlying system is still shaping behaviour, but you're not yet sure how.

**Behaviour to Constraint Mapping** is a simple technique that might help you understand where the system is exerting itself invisibly.

Before I explain the technique, let's first make one assertion:

> People behave rationally within the operating system they inhabit.

The behaviour you're observing - whether that is too much WIP, long lead times, or something else - isn't malfeasance. It isn't ignorance of expectations either. Start from the assumption that the behaviour is rational in its local context, even if it is considered undesirable more broadly; there will be a reasonable explanation. An explanation that doesn't demand more training, stricter conformance, or more effort. The behaviour is unlikely to be the problem itself. It is more likely to be an adaptation to the conditions in which the team operates.

So, instead of asking, "How do we stop teams \[insert observed behaviour here]?", ask:

> "What is making this behaviour make sense in this context?"

If we treat observed behaviour as a signal, and we understand that signals contain information, we can follow that information to uncover what, in the surrounding system, makes the behaviour sensible.

Behaviour to Constraint Mapping is a way of following that information.

The technique starts with the behaviour you can observe and works outwards. Rather than searching for a defect in the team, or drilling down towards a single "root cause", you progressively ask what conditions make the behaviour rational: what prevents the alternative, what risks are being avoided, what is rewarded, where decisions are being made, what happens when uncertainty is exposed, and what lies beyond the team's control.

Importantly, the inquiry doesn't stop when it reaches another part of the organisation. "Leadership wants it", "Finance requires it", "Risk won't approve it", or "the Product Owner keeps adding work" aren't root causes. They are invitations to keep going. You need to understand what conditions make their behaviour rational too.

Eventually, what looked like a behavioural problem starts to look rather different. You begin to see a network of incentives, governance expectations, decision rights, dependencies, risk structures, and legitimacy signals within which the behaviour emerged.

At that point, you can reframe the original observation:

Given these conditions, this behaviour is a rational response.

Now you have something useful to work with.

The [Behaviour to Constraint Mapping](https://app.gitbook.com/s/yYdXGH2DtxmsDRcRRrNr/16-bahaviour-constraint-mapping) pattern describes the diagnostic logic in detail. The accompanying [facilitation guide](https://app.gitbook.com/s/wVqEs2cuXgPu222Kt8eP/facilitation-guides/behaviour-constraint-mapping-in-practice) provides a lightweight way of exploring it with a group. Neither is intended to prescribe a solution. The map itself is only a hypothesis about how the system behaves.

If you choose to change a constraint, that change becomes an experiment: if the constraint really is contributing materially to the behaviour, changing it should change what you observe. If it doesn't, you've learned something too.

The process is recursive:

**Observe → Map → Hypothesise → Intervene → Observe → Update.**

\[[Behaviour to Constraint Mapping pattern](https://app.gitbook.com/s/yYdXGH2DtxmsDRcRRrNr/16-bahaviour-constraint-mapping)]

\[[Facilitation guide](https://app.gitbook.com/s/wVqEs2cuXgPu222Kt8eP/facilitation-guides/behaviour-constraint-mapping-in-practice)]

