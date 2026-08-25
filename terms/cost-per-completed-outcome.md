# Cost per Completed Outcome

> The fully loaded cost of one resolved unit of a business's actual output — compute, Steward intervention time, and residual Coordination Tax — divided by the number of outcomes actually completed, not merely executed, reported by Task Tier rather than as a single blended figure.

## Extended Definition

Cost per Completed Outcome is the fully loaded cost of one resolved unit of a business's actual output — compute, Steward intervention time, and residual Coordination Tax combined — divided by the number of outcomes the system actually completed, not merely executed. It is the metric that determines whether an autonomous operation is economically superior to the human-staffed process it replaced, as distinct from whether it is merely faster or more autonomous by the process-health metrics already in use.

The distinction from existing metrics is deliberate. Tokens measure computation, not value delivered. Benchmark scores measure performance against a fixed evaluation set, not against a business's actual task distribution. Completion claims measure that a task finished, not what finishing it cost relative to what the business earned from it. MTTI and Escalation Rate come closer — both measure whether a system is running autonomously — but neither measures whether it is running economically. A system can post an excellent MTTI and still lose money per completed outcome if its interventions are expensive enough, or if what counts as "completed" has quietly narrowed to exclude the cases that made the number look good.

### Application

Cost per Completed Outcome is calculated per Task Tier, never as a single business-wide average. At T1, where Escalation Rate runs approximately 1:100, the figure sits close to pure compute cost because the fully loaded cost of a Steward intervention is amortised across a hundred outcomes for every one that reaches a human. At T2, where Escalation Rate runs 1:5 to 1:10, the same fixed Steward cost is amortised across far fewer outcomes and the figure rises accordingly — not because execution quality declined, but because the denominator shrank. At T3, where human judgement is mandatory, the figure converges toward the cost structure of the legacy process, correctly reflecting that Operational Arbitrage is not capturable where the task requires human judgement by nature. A completed outcome is the resolved customer request, closed transaction, or delivered result the business exists to produce — not the intermediate step handed to the next stage of a pipeline. A task a T1 agent processes correctly but that later requires rework, reversal, or triggers a complaint was executed, not completed.

### Context

MTTI and Escalation Rate answer whether a system is running autonomously — how long it goes and how often it needs a human. Neither answers whether that autonomous operation is economically superior to the human-staffed process it replaced. A system can post an excellent MTTI and still be uneconomical per completed outcome, if the interventions it does require are expensive enough or if the definition of "completed" has quietly narrowed. Cost per Completed Outcome exists to close that gap: it is the unit-economics metric that process-health metrics were never designed to be, and its absence from every current frontier-lab agent launch is not an oversight — it is evidence that unit economics for agentic systems has not yet been built as a discipline, only assumed.

## Related Terms

- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — MTTI measures how often a system needs a human; Cost per Completed Outcome measures whether the operation that results is economically superior to the process it replaced.
- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — Escalation Rate sets the denominator that Cost per Completed Outcome amortises Steward intervention cost across, so a rising Escalation Rate at a given tier directly raises the figure.
- [Coordination Tax](https://arcoventure.studio/lexicon/coordination-tax) — Residual Coordination Tax is one of the three components — alongside compute and Steward intervention time — that make up the fully loaded cost in Cost per Completed Outcome.
- [Workforce Arbitrage](https://arcoventure.studio/lexicon/workforce-arbitrage) — Cost per Completed Outcome is the metric that verifies whether a claimed Workforce Arbitrage is real, by pricing the agentic operation against the human-staffed process it replaced.
- [Operational Arbitrage](https://arcoventure.studio/lexicon/operational-arbitrage) — Operational Arbitrage is not capturable at T3, and Cost per Completed Outcome reflects that directly: the figure converges toward legacy process cost where human judgement is mandatory.
- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — Cost per Completed Outcome is calculated per Task Tier rather than as a single blended figure, because Escalation Rate — and therefore amortised Steward cost — differs structurally by tier.

## Articles

- [Overhead Is a Design Choice](https://arcoventure.studio/blog/overhead-is-a-design-choice)
- [The Stewardship Model: The Human Role in an Autonomous Business](https://arcoventure.studio/blog/stewardship-model)
- [What We Mean When We Say Agentic](https://arcoventure.studio/blog/what-we-mean-agentic)

## References

- [Lexicon](https://arcoventure.studio/lexicon/cost-per-completed-outcome) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/cost-per-completed-outcome) — extended entry

## Metadata

**First used:** 2026-08-25  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
