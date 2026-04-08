# Intervention Threshold

**Canonical definition (Arco Lexicon)**
> The architectural parameter that defines the conditions under which an agentic system must halt execution and escalate to a human Steward — set during system design, not discovered through operational failure.

## Extended Definition

The Intervention Threshold is a design decision, not an observed measurement. It is the set of conditions encoded into an autonomous system's logic that determine when an agent must stop executing and surface the task to a human Steward for judgment. The threshold is defined before the system runs. The proportion of tasks that actually trigger it — the escalation rate — is the operational measurement that confirms whether the threshold was set correctly.

The distinction between the two concepts is architecturally important. A system without an explicitly set Intervention Threshold will either over-escalate — surfacing tasks the agent could have handled autonomously, consuming Steward time on work that does not require judgment — or under-escalate, executing tasks that required human assessment and producing errors that compound silently until they produce a structural failure. The Intervention Threshold is what prevents both failure modes. It is the boundary between the Execution Layer and the Judgment Layer, made explicit in code.

At T1 — routine, scripted, high-volume tasks with binary outcomes and low risk — Arco targets an Intervention Threshold of 1:100: one human intervention per hundred autonomous executions. Customer care simulation data validates this target, with T1 ticket types achieving escalation rates of 1–2% across password resets, FAQ resolution, and order tracking. At T2, where tasks require moderate contextual judgment, the threshold rises to approximately 1:10 to 1:5. At T3, where regulatory compliance, relationship management, or high-stakes outcomes are involved, the threshold reflects mandatory human involvement at the majority of execution points.

## Related Terms

- [Task Tiers (T1 / T2 / T3)](./t1-t2-t3.md) — [Arco Lexicon →](https://arcoventure.studio/lexicon/t1-t2-t3)
- [Stewardship Model](./stewardship-model.md) — [Arco Lexicon →](https://arcoventure.studio/lexicon/stewardship-model)
- [Judgment Layer / Execution Layer](./judgment-layer-execution-layer.md) — [Arco Lexicon →](https://arcoventure.studio/lexicon/judgment-layer-execution-layer)
- [Operational Arbitrage](./operational-arbitrage.md) — [Arco Lexicon →](https://arcoventure.studio/lexicon/operational-arbitrage)
- [Deterministic Outcome](./deterministic-outcome.md) — [Arco Lexicon →](https://arcoventure.studio/lexicon/deterministic-outcome)
- [Escalation Rate](./escalation-rate.md) — [Arco Lexicon →](https://arcoventure.studio/lexicon/escalation-rate)

## In the Log

- [The Stewardship Model: The Human Role in an Autonomous Business](https://arcoventure.studio/blog/stewardship-model)
- [What We Mean When We Say Agentic](https://arcoventure.studio/blog/what-we-mean-agentic)
- [What Makes a Market Certain Enough to Build Into](https://arcoventure.studio/blog/what-makes-a-market-certain-enough)

## Links

- [Concise entry on Arco Lexicon](https://arcoventure.studio/lexicon/intervention-threshold)
- [Autonomous Business Wiki](https://wiki.arcoventure.studio/lexicon/intervention-threshold)
- [Markdown source on GitHub](https://github.com/arcoventure/awesome-autonomous-business/blob/main/terms/intervention-threshold.md)

---

*First used: 2026-04-07*

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
