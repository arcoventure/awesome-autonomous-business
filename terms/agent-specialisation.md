# Agent Specialisation

> The architectural practice of designing agents with a narrowly defined task domain, a constrained and explicit capability set, and a formal cooperation interface that enables handoff to other specialised agents when the task exceeds the agent’s domain — producing agents that outperform general-purpose agents within their domain while remaining composable in multi-agent systems that exceed any single domain.

## Extended Definition

The principle that makes specialised autonomous businesses structurally superior to diversified incumbents — that a company engineered for one task class at high volume produces a structural cost and quality advantage that a general-purpose competitor cannot replicate — applies at the agent design level. A general-purpose agent asked to execute sales qualification, generate marketing content, resolve customer support tickets, and run financial analysis is optimised for none of them. Its system prompt is a compromise. Its tool set is a superset that adds cost without adding capability at any specific task. Its output on each task class is the intersection of what a generalist can produce rather than what a specialist can produce.

An Agent Specialisation is defined by three properties. First, a Task Domain Boundary: the explicit specification of which tasks fall within the agent’s operational scope and which require handoff. The boundary is not vague but precise: the agent handles inbound support tickets of a defined classification range, as specified in the Exception Architecture — any ticket outside that classification is escalated. Second, a constrained capability set: the agent has access only to the tools, data sources, and model capabilities required for its defined domain. Tool sprawl — giving an agent access to every available API because it might need them — produces ambiguity at tool selection time and increases the surface area for Handoff Friction when the agent calls the wrong tool. Third, a cooperation interface: the agent exposes a defined protocol by which other agents can invoke it with a structured request and receive a structured response. This is what makes Agent Specialisation composable: a sales intelligence agent can invoke a data retrieval specialist, which invokes a web search specialist, which returns structured output the sales agent can use without understanding the mechanics of how it was produced.

**Sub-concept: Task Domain Boundary** — The explicit specification of which tasks fall within an agent’s operational scope and which require handoff to another specialised agent — the design input that determines the agent’s tool set, cooperation interface, and Intervention Threshold.

## Related Terms

- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — Task Tiers define the complexity and judgment requirements of each task class that Agent Specialisation partitions into distinct domain boundaries.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — Exception Architecture specifies the escalation protocol at the Task Domain Boundary: when a task exceeds an agent's scope, Exception Architecture governs how and to whom it is handed off.
- [Handoff Friction](https://arcoventure.studio/lexicon/handoff-friction) — Handoff Friction is the failure mode that poorly designed cooperation interfaces produce: Agent Specialisation prevents it by making the structured request-response protocol explicit before deployment.
- [Context Collision](https://arcoventure.studio/lexicon/context-collision) — Context Collision occurs when agents operating on different context sets reach contradictory conclusions; Agent Specialisation reduces it by ensuring each agent operates within a precisely defined and non-overlapping domain.
- [Operational Ontology](https://arcoventure.studio/lexicon/operational-ontology) — The Operational Ontology provides the shared vocabulary that makes cooperation interfaces between specialised agents unambiguous at execution time.
- [Judgment Layer / Execution Layer](https://arcoventure.studio/lexicon/judgment-layer-execution-layer) — Agent Specialisation operationalises the Judgment Layer / Execution Layer separation: specialised Execution Layer agents handle deterministic tasks while Judgment Layer decisions are escalated to the Steward.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Stewardship Model governs the Judgment Layer exceptions that specialised agents escalate when a task exceeds their Task Domain Boundary.
- [Breakable Market](https://arcoventure.studio/lexicon/breakable-market) — Agent Specialisation compounds the Operational Arbitrage available in a Breakable Market by producing per-domain cost and quality advantages that general-purpose agents cannot replicate.

## Articles

- [The Knowledge Handoff Problem](https://arcoventure.studio/blog/the-knowledge-handoff-problem)
- [The Steward’s True Asset](https://arcoventure.studio/blog/the-stewards-true-asset)

## References

- [Lexicon](https://arcoventure.studio/lexicon/agent-specialisation) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/agent-specialisation) — extended entry

## Metadata

**First used:** 2026-05-15  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*