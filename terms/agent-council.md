# Agent Council

> A function-specific layer of specialized review agents governing execution agent outputs before escalation to the human Steward — the agentic equivalent of the management function, handling quality review, error detection, misinterpretation resolution, and escalation triage between the Execution Layer and the human Judgment Layer.

## Extended Definition

The Agent Council refines the existing Execution Layer / Judgment Layer binary into a three-tier architecture. The existing binary assigns everything the Execution Layer cannot handle to the human Judgment Layer — but not all judgment requires human judgment. The Agent Council governs T2: the quality review, consistency checking, escalation triage, and pattern-learning functions that human-operated businesses assign to management. These are AI-level judgment tasks that require a different kind of agent, not a different kind of person.

The Agent Council performs four specific functions. Quality review: each execution agent output is evaluated against established Quality Threshold standards before delivery, checked against the Operational Ledger and known failure modes for the task class — at compute cost, within the same execution cycle, without a queue. Error detection: outputs are cross-referenced against the Proof of Action trail using a contradiction protocol that does not share the execution agents' failure modes, because an Agent Council that shares the same model and context provides corroborated confirmation, not independent review. Escalation triage: the council resolves what it can and surfaces only conditions exceeding its resolution authority to the Audit Surface. Pattern learning: the council identifies recurring failure patterns across executions and surfaces improvement signals before they compound into Logic Decay.

The independence requirement is the most critical architectural specification. Effective council-layer review requires a different evaluation angle from the execution layer: a structured contradiction protocol, a different model, or a methodology that actively looks for inconsistency rather than confirming correctness. Methodological independence is the source of the council's value as a review layer.

The Agent Council is also the architectural resolution of the Authorization Trap at the quality review checkpoint: once the council demonstrates through a supervised operation window that its error detection meets the promotion criteria, the human approval step above it becomes an undepurated Human Premium component rather than a safety measure. The council must be specified at Full-System Design time — its pattern-learning function compounds from the first execution cycle, and retrofitting it into an operating function means reconstructing baselines from a history not designed to produce them.

### Application

Each execution agent output passes through a council agent that checks it against the Operational Ledger and Quality Threshold before delivery, using a contradiction protocol that does not share the execution agent's model or context — because identical failure modes produce corroborated errors rather than genuine review. The council resolves what it can and escalates only what exceeds its authority to the Steward.

### Context

The Agent Council refines the existing Execution Layer / Judgment Layer binary into a three-tier architecture. The binary previously assigned everything the Execution Layer could not handle to the human Judgment Layer by default — but not all judgment requires human judgment. The Agent Council governs T2: the quality review, consistency checking, and escalation triage that human-operated businesses assign to management, converting the 'best team is no team' principle from an execution-layer claim into one that extends to governance itself.

## Related Terms

- [Judgment Layer / Execution Layer](https://arcoventure.studio/lexicon/judgment-layer-execution-layer) — The Agent Council introduces a third tier between the Execution Layer and the Judgment Layer, governing quality review and escalation triage at compute cost rather than human cost.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Agent Council reduces the volume of escalations that reach the Steward by resolving AI-level judgment tasks within the agentic layer before any human is involved.
- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — The Agent Council governs T2 — the quality review and escalation triage tasks that sit between routine T1 execution and the T3 human judgment reserved for the Steward.
- [Authorization Trap](https://arcoventure.studio/lexicon/authorization-trap) — The Agent Council is the architectural resolution to the Authorization Trap at the quality review checkpoint, earning the removal of human approval by demonstrating verified governance through a supervised operation window.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — The Agent Council integrates with the Exception Architecture to triage which escalations it can resolve at council level and which exceed its authority and must surface to the Audit Surface.
- [Continuous Regression Loop](https://arcoventure.studio/lexicon/continuous-regression-loop) — The Agent Council's pattern-learning function surfaces recurring failure patterns to the Continuous Regression Loop before they compound into Logic Decay.
- [Human Premium](https://arcoventure.studio/lexicon/human-premium) — The Agent Council depurates Human Premium components from the quality review function, converting a human approval step into an AI governance layer at compute cost once it has demonstrated verified performance.

## Articles

- [The Best Team Is No Team](https://arcoventure.studio/blog/the-best-team-is-no-team)
- [The Decision Belongs to the Logic](https://arcoventure.studio/blog/the-decision-belongs-to-the-logic)
- [The Last Approval](https://arcoventure.studio/blog/the-last-approval)
- [The System That Does Not Call](https://arcoventure.studio/blog/the-system-that-does-not-call)
- [The Business That Forgets Nothing](https://arcoventure.studio/blog/the-business-that-forgets-nothing)

## References

- [Lexicon](https://arcoventure.studio/lexicon/agent-council) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/agent-council) — extended entry

## Metadata

**First used:** 2026-07-03  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*