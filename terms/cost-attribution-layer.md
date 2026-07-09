# Cost Attribution Layer

> The architectural component that traces the operational cost of every agentic step, task class, and job-to-be-done against the business’s v0 baseline — enabling the Steward to evaluate the economic impact of each architectural optimisation decision with precision, rather than measuring compounding effect by impression or total spend.

## Extended Definition

Total token spend is not a governance instrument. A Steward who knows that the business spent $12,000 on tokens last month knows nothing about whether that spend was optimally allocated, whether specific task classes are generating disproportionate cost, or whether the architectural changes made in month three reduced the per-unit cost or merely shifted it to a different line item. Cost visibility at the aggregate level is accounting. Cost visibility at the step level is architecture.

The Cost Attribution Layer connects every model call, every tool invocation, and every data retrieval to the task class it serves, the step in the Revenue Loop it occupies, and the job-to-be-done it contributes to. This structure serves two distinct functions. First, it makes Architecture Cost Drift visible: the cumulative deviation between the current system’s cost profile and the v0 baseline, measured continuously as the Steward makes architectural refinements. If a month-four optimisation reduced the Escalation Rate by 30% but increased per-execution cost by 15%, the Cost Attribution Layer shows both effects at the step level. Second, it enables intelligent routing: when the Cost Attribution Layer confirms that a specific task class consistently consumes disproportionate compute relative to its contribution to output quality, that is the data signal that triggers an Intelligence Arbitrage routing review for that class.

The connection to the Operational Ledger is structural: cost records are a layer of the Ledger, not a separate system. Every execution cycle that the Ledger records includes the cost attribution for that cycle, indexed against the step and task class that generated it. The Ledger compounds operational intelligence. The Cost Attribution Layer compounds economic intelligence. Both must be designed from the same underlying trace data or they diverge and lose their comparability over time.

**Sub-concept: Architecture Cost Drift** — The cumulative economic delta between the current architecture’s cost profile and the v0 baseline, measured continuously by the Cost Attribution Layer to validate whether Steward optimisation decisions are compounding correctly or producing cost drift that offsets operational gains.

## Related Terms

- [Operational Ledger](https://arcoventure.studio/lexicon/operational-ledger) — The Operational Ledger is the knowledge asset the Cost Attribution Layer extends: cost records are a layer of the Ledger, not a separate system, ensuring economic and operational intelligence derive from the same underlying trace data.
- [Deterministic Logging](https://arcoventure.studio/lexicon/deterministic-logging) — Deterministic Logging is the technical foundation of the Cost Attribution Layer: causation-level records of every decision are what allow cost to be attributed to the specific step and task class that generated it.
- [Intelligence Arbitrage](https://arcoventure.studio/lexicon/intelligence-arbitrage) — The Cost Attribution Layer is the data input that triggers Intelligence Arbitrage routing reviews: when a task class consistently consumes disproportionate compute, the attribution data signals that cheaper model routing is warranted.
- [Proof of Action](https://arcoventure.studio/lexicon/proof-of-action) — The Proof of Action trail and the Cost Attribution Layer share the same underlying trace data: every agentic decision recorded for governance is also the record from which cost is attributed.
- [Audit Surface](https://arcoventure.studio/lexicon/audit-surface) — The Audit Surface digests Cost Attribution Layer data into the Steward's daily governance view: Architecture Cost Drift alerts are the economic component of the governance digest alongside Escalation Rate summaries.
- [Quality Threshold](https://arcoventure.studio/lexicon/quality-threshold) — The Quality Threshold bounds what the Cost Attribution Layer can route: cost optimisation decisions must be evaluated against the minimum output standard required for each task class before routing to a cheaper model.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Cost Attribution Layer is the primary economic governance tool of the Stewardship Model: it gives the Steward the step-level visibility needed to evaluate optimisation decisions with precision rather than impression.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — Intervention Threshold calibration decisions are among the optimisation choices the Cost Attribution Layer must evaluate: a threshold adjustment that reduces the Escalation Rate is only beneficial if the per-execution cost impact is also measured.

## Articles

- [The Operational Ledger](https://arcoventure.studio/blog/the-operational-ledger)
- [The Audit Surface Problem](https://arcoventure.studio/blog/the-audit-surface-problem)

## References

- [Lexicon](https://arcoventure.studio/lexicon/cost-attribution-layer) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/cost-attribution-layer) — extended entry

## Metadata

**First used:** 2026-05-15  
**Pillar:** What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*