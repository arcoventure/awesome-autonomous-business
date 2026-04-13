# Escalation Rate

> The proportion of agentic task executions that require escalation to a human Steward — the primary operational metric governing the boundary between autonomous execution and human judgment under the Stewardship Model.

## Extended Definition

The Escalation Rate is distinct from MTTI. MTTI measures the temporal dimension of autonomous operation — how long the system runs between required human interventions. The Escalation Rate measures the transactional dimension — what proportion of individual task executions require a human decision before they can complete. The two metrics together define the operational profile of an autonomous system: MTTI tells you how frequently the system calls for help; Escalation Rate tells you how often, across all the work it handles, a human is in the loop.

The Escalation Rate is not a fixed target across the portfolio. It is tier-dependent, topic-dependent, and risk-dependent. At T1 — routine, scripted, high-volume tasks with binary outcomes and low stakes — Arco targets an Escalation Rate of approximately 1:100: one human intervention per hundred autonomous executions. The customer care simulation data supporting this target shows T1 ticket escalation rates of 1–5% across password resets, FAQ handling, order tracking, and basic billing — with the lowest-complexity tasks achieving 1% escalation, the operational expression of the 1:100 target. At T2, where tasks require moderate judgment and contextual interpretation, the rate rises to approximately 1:5 to 1:10. At T3, where regulatory compliance, relationship management, or high-stakes judgment is required, human involvement is mandatory at a proportion that reflects the specific risk profile of the task type.

## Related Terms

- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — The Escalation Rate target varies by task tier: approximately 1:100 at T1, 1:5 to 1:10 at T2, and mandatory human involvement at T3.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Escalation Rate is the operational metric that validates the Stewardship Model: a rate within target confirms the Steward is handling exceptions, not routine execution.
- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — MTTI and Escalation Rate are complementary operational metrics: MTTI measures how long the system runs between interventions, while Escalation Rate measures the proportion of transactions that trigger one.
- [Operational Arbitrage](https://arcoventure.studio/lexicon/operational-arbitrage) — The Escalation Rate directly determines the operational arbitrage captured: a 1% escalation rate at T1 means 99% of transactions execute at near-zero marginal cost, capturing the full human-to-compute cost differential.
- [Judgment Layer / Execution Layer](https://arcoventure.studio/lexicon/judgment-layer-execution-layer) — The Escalation Rate is the operational measurement of where the boundary between the Execution Layer and Judgment Layer has been set in practice.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The Intervention Threshold is the design parameter that sets the target Escalation Rate; the actual Escalation Rate in operation is the measurement that confirms whether the threshold was set correctly.

## Articles

- [The Stewardship Model: The Human Role in an Autonomous Business](https://arcoventure.studio/blog/stewardship-model)
- [What We Mean When We Say Agentic](https://arcoventure.studio/blog/what-we-mean-agentic)

## References

- [Lexicon](https://arcoventure.studio/lexicon/escalation-rate) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/escalation-rate) — extended entry

## Metadata

**First used:** 2026-04-07  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
