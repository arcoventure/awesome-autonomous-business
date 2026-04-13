# Context Leakage

> The failure mode in which an agent loses the intent of the original task as it progresses through a multi-step process — completing each step correctly in isolation while producing a result that is logically irrelevant to the goal.

## Extended Definition

Context Leakage is the most common failure mode in long-running agentic workflows. It does not announce itself the way a discrete error does. The agent continues executing — fetching data, reconciling records, updating systems — and at each individual step the output is technically correct. The problem is cumulative. Small deviations in interpretation compound across a long process until the agent is following the instructions precisely and producing a result the original task never intended. The system has not broken. It has drifted.

## Related Terms

- [Execution Divergence](https://arcoventure.studio/lexicon/execution-divergence) — Execution Divergence is the measurable signal that Context Leakage is occurring: when a workflow deviates more than 15% from its predicted path, accumulated context drift is the most common cause.
- [Deterministic Failure](https://arcoventure.studio/lexicon/deterministic-failure) — Deterministic Failure is the designed response to Context Leakage: the system halts, logs the full execution context, and escalates rather than continuing on a drifted path.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — Preventing Context Leakage through explicit context anchoring at each workflow step is a prerequisite for achieving Architectural Certainty in long-running agentic processes.
- [MTTI (Mean Time to Intervention)](https://arcoventure.studio/lexicon/mtti) — Context Leakage is a primary driver of unscheduled human interventions, and its detection speed directly affects MTTI.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Steward's role in reviewing escalated Context Leakage incidents is to update the architecture so the same class of drift does not recur.

## Articles

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## References

- [Lexicon](https://arcoventure.studio/lexicon/context-leakage) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/context-leakage) — extended entry

## Metadata

first_used: 2026-03-20
pillar: How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
