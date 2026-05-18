# Quality Threshold

> The minimum acceptable output standard for a given task class — defined before routing decisions are made and used to bound Intelligence Arbitrage such that cost optimisation never routes a task to a model incapable of meeting the standard the revenue loop requires, ensuring that routing reduces cost without degrading the outputs agents and Stewards depend on.

## Extended Definition

Intelligence Arbitrage is the practice of routing each task class to the cheapest model capable of executing it at the required quality level. The phrase "required quality level" is doing structural work that most implementations leave undefined. Without a Quality Threshold — a precise, per-task-class specification of what constitutes acceptable output — routing becomes a cost tool that also, sometimes, accidentally, degrades output. The agent produces a result. The result is cheaper. It may or may not meet the standard the business depends on for that task class. The degradation is often invisible until the Escalation Rate for that class rises and the Steward cannot identify why.

The Quality Threshold resolves this by making the bound explicit before routing decisions are made. For T1 task classes — fully deterministic, high-volume, schema-driven — the Quality Threshold is typically a structured output specification: the agent must produce a result in a defined format, within defined field constraints, with no hallucinated values. This threshold can be met by small, cheap, fast models; the Inference Floor has already reached most T1 tasks. For T2 task classes, the Quality Threshold must also specify the accuracy rate for the judgment calls the agent is permitted to make autonomously before an escalation is required. For T3 tasks, the Quality Threshold governs the agent's supporting work — data preparation, context assembly, output formatting — not the judgment itself, which is the Steward's.

Structured output and model routing compose directly: routing to a cheaper model for structured extraction tasks is safe when the Quality Threshold is a schema, because schema compliance is evaluable by logic. It is unsafe when the Quality Threshold is undefined, because the model may return plausible-looking values that violate business constraints.

## Related Terms

- [Intelligence Arbitrage](https://arcoventure.studio/lexicon/intelligence-arbitrage) — The Quality Threshold is the bounding constraint on Intelligence Arbitrage: it ensures that routing to the cheapest capable model never routes to a model that cannot meet the output standard the task class requires.
- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — Task Tiers determine the form of the Quality Threshold for each class: T1 thresholds are structured output schemas, T2 thresholds include accuracy rate specifications, and T3 thresholds govern supporting work rather than the judgment itself.
- [Inference Floor](https://arcoventure.studio/lexicon/inference-floor) — The Inference Floor determines which models can meet a given Quality Threshold: once all frontier models perform equivalently on a task class, the threshold can be met by the cheapest model available.
- [Execution Divergence](https://arcoventure.studio/lexicon/execution-divergence) — Execution Divergence is the operational signal that a Quality Threshold has been violated: when a workflow deviates more than 15% from its predicted path, the output quality assumption embedded in the routing decision has likely failed.
- [Escalation Rate](https://arcoventure.studio/lexicon/escalation-rate) — A rising Escalation Rate for a specific task class is the lagging indicator of a Quality Threshold violation: when routing to a cheaper model produces outputs the Steward must correct, the Escalation Rate rises before the cause is identified.
- [Architectural Decoupling](https://arcoventure.studio/lexicon/architectural-decoupling) — Architectural Decoupling is the prerequisite for Quality Threshold-based routing: a knowledge layer entangled with a specific model cannot apply a per-task-class threshold because switching providers requires rebuilding the operational substrate.
- [Context Architecture](https://arcoventure.studio/lexicon/context-architecture) — Context Architecture determines whether a given model can meet the Quality Threshold for a task: the same model operating on rich, structured operational context produces higher-quality outputs than the same model operating on sparse context.

## Articles

- [BYOK as Architectural Decoupling](https://arcoventure.studio/blog/byok-as-architectural-decoupling)
- [The Inference Floor](https://arcoventure.studio/blog/the-inference-floor)

## References

- [Lexicon](https://arcoventure.studio/lexicon/quality-threshold) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/quality-threshold) — extended entry

## Metadata

**First used:** 2026-05-15  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
