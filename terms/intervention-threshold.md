# Intervention Threshold

> The architectural parameter that defines the conditions under which an agentic system must halt execution and escalate to a human Steward — set during system design, not discovered through operational failure.

## Extended Definition

The Intervention Threshold is a design decision, not an observed measurement. It is the set of conditions encoded into an autonomous system's logic that determine when an agent must stop executing and surface the task to a human Steward for judgment. The threshold is defined before the system runs. The proportion of tasks that actually trigger it — the escalation rate — is the operational measurement that confirms whether the threshold was set correctly.

The distinction between the two concepts is architecturally important. A system without an explicitly set Intervention Threshold will either over-escalate — surfacing tasks the agent could have handled autonomously, consuming Steward time on work that does not require judgment — or under-escalate, executing tasks that required human assessment and producing errors that compound silently until they produce a structural failure. The Intervention Threshold is what prevents both failure modes. It is the boundary between the Execution Layer and the Judgment Layer, made explicit in code.

At T1 — routine, scripted, high-volume tasks with binary outcomes and low risk — Arco targets an Intervention Threshold of 1:100: one human intervention per hundred autonomous executions. Customer care simulation data validates this target, with T1 ticket types achieving escalation rates of 1–2% across password resets, FAQ resolution, and order tracking. At T2, where tasks require moderate contextual judgment, the threshold rises to approximately 1:10 to 1:5. At T3, where regulatory compliance, relationship management, or high-stakes outcomes are involved, the threshold reflects mandatory human involvement at the majority of execution points.

## Related Terms

- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — The Intervention Threshold is calibrated by task tier: 1:100 at T1, 1:10 to 1:5 at T2, and mandatory human involvement at T3 based on the specific risk profile of the task type.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Intervention Threshold is the code-level implementation of the Stewardship Model's core principle: the Steward handles exceptions, not execution.
- [Judgment Layer / Execution Layer](https://arcoventure.studio/lexicon/judgment-layer-execution-layer) — The Intervention Threshold is the explicit architectural boundary between the Execution Layer — tasks the agent handles autonomously — and the Judgment Layer — decisions the Steward owns.
- [Operational Arbitrage](https://arcoventure.studio/lexicon/operational-arbitrage) — The Intervention Threshold determines how much Operational Arbitrage a system captures: a correctly calibrated threshold maximises autonomous execution without producing silent errors that require costly remediation.
- [Deterministic Outcome](https://arcoventure.studio/lexicon/deterministic-outcome) — Tasks with Deterministic Outcomes can be assigned lower Intervention Thresholds because the system can self-evaluate success; tasks with non-deterministic outcomes require a higher human involvement threshold.
- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — The Escalation Rate is the operational measurement that confirms whether the Intervention Threshold was set correctly: a rate within the target range validates the threshold design.

## Articles

- [The Stewardship Model: The Human Role in an Autonomous Business](https://arcoventure.studio/blog/stewardship-model)
- [What We Mean When We Say Agentic](https://arcoventure.studio/blog/what-we-mean-agentic)
- [What Makes a Market Certain Enough to Build Into](https://arcoventure.studio/blog/what-makes-a-market-certain-enough)

## References

- [Lexicon](https://arcoventure.studio/lexicon/intervention-threshold) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/docs/intervention-threshold) — extended entry

## Metadata

first_used: 2026-04-07
pillar: How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
