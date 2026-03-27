# Context Leakage

**Canonical definition (Arco Lexicon)**
> The failure mode in which an agent loses the intent of the original task as it progresses through a multi-step process — completing each step correctly in isolation while producing a result that is logically irrelevant to the goal.

## Extended Definition

Context Leakage is the most common failure mode in long-running agentic workflows. It does not announce itself the way a discrete error does. The agent continues executing — fetching data, reconciling records, updating systems — and at each individual step the output is technically correct. The problem is cumulative. Small deviations in interpretation compound across a long process until the agent is following the instructions precisely and producing a result the original task never intended. The system has not broken. It has drifted.

## Related Terms

- [Execution Divergence](../execution-divergence.md) — [Execution Divergence on Arco Lexicon](https://arcoventure.studio/lexicon/execution-divergence)
- [Deterministic Failure](../deterministic-failure.md) — [Deterministic Failure on Arco Lexicon](https://arcoventure.studio/lexicon/deterministic-failure)
- [Architectural Certainty](../architectural-certainty.md) — [Architectural Certainty on Arco Lexicon](https://arcoventure.studio/lexicon/architectural-certainty)
- [MTTI (Mean Time to Intervention)](../mtti.md) — [MTTI (Mean Time to Intervention) on Arco Lexicon](https://arcoventure.studio/lexicon/mtti)
- [Stewardship Model](../stewardship-model.md) — [Stewardship Model on Arco Lexicon](https://arcoventure.studio/lexicon/stewardship-model)

## In the Log

- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## Links

- [Concise entry on Arco Lexicon](https://arcoventure.studio/lexicon/context-leakage)
- [Autonomous Business Wiki](https://wiki.arcoventure.studio/lexicon/context-leakage)

---

*First used: 2026-03-20*

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*