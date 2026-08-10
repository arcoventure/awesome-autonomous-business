# Delegation Trace

> The extension of the Accountability Trace across a multi-agent delegation chain, recording which agent acted under which authority at each step — including the specific point where authority was handed from one provider's system to another's — so that a cascading failure remains attributable to a specific link in the chain rather than dissolving into a gap no single Accountability Trace was built to close.

## Extended Definition

Every governance framework and liability statute this body of work has examined was written assuming an agentic failure has one author — one agent, operating under one business's authority, making one decision. A correctly specified Accountability Trace is built precisely for that case, and it remains sufficient for the overwhelming majority of what an autonomous business actually does. It was never built to answer a harder question: when several specialized agents, operated by entirely different companies, compose into one delegation chain and the final output causes harm, whose Trace is the one that matters, and does any single Trace even capture what happened across the full chain.

The Delegation Trace closes that specific gap without replacing what already exists. Each agent's own Accountability Trace remains the record of what that agent did and why. The Delegation Trace is the connective record layered on top: which agent initiated a delegation, what authority and constraints were passed along with it, which agent accepted the task, and under what disclosed terms — captured at every point authority crosses from one provider's system into another's.

The genuinely hard part of this problem is not logging. It is identity. A record showing that a handoff occurred is not the same as a verifiable identity for each agent in the chain, checkable across provider boundaries rather than only within one business's own system. This infrastructure does not yet exist as a mature, adopted standard, and the Delegation Trace should not be mistaken for a complete solution to multi-agent liability allocation — it is the record a business can build today, honestly bounded by what it cannot yet fully resolve alone.

### Application

The Delegation Trace is layered on top of, not instead of, each agent's own Accountability Trace. It is a verified log of every handoff in a chain: which agent initiated the delegation, what authority and constraints were passed along with it, which agent accepted the task, and under what disclosed terms. A business relying on a third-party specialist agent through the Orchestrator-Specialist market structure should treat every cross-provider handoff as a point requiring its own disclosed terms and its own verifiable record, the same discipline already applied to an internal Intervention Threshold before a decision class is promoted.

### Context

Every governance framework and liability statute Arco has examined — Singapore's Model AI Governance Framework, the EU AI Act, California's AB 316, and the EU Product Liability Directive — was written with a single agent, or a single operator's agentic stack, in mind, and each independently flagged multi-agent composition as an unresolved edge case. A single Accountability Trace answers whether one agent's decision was correct; it does not answer who had the authority to make a cross-provider delegation chain possible, or whether that authority was exercised within its disclosed bounds. The harder unresolved problem beneath the Delegation Trace is agent identity: a verifiable identity for each agent that persists and is checkable across provider boundaries, not merely a log that a handoff occurred. That identity infrastructure does not yet exist as a mature, adopted standard — NIST's AI Agent Standards Initiative, announced February 2026, has identified it as a core research priority, but the Delegation Trace as currently specified can show that a handoff occurred without yet being able to prove, to a standard a court or regulator would accept, which specific entity was accountable for the authority granted at that handoff.

## Related Terms

- [Accountability Trace](https://arcoventure.studio/lexicon/accountability-trace) — The per-agent record of what each individual agent did and why; the Delegation Trace is the connective record layered on top to capture cross-provider authority handoffs.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The Delegation Trace applies the same evidentiary discipline as the Intervention Threshold to every cross-provider handoff point in a multi-agent chain.
- [Disclosure Threshold](https://arcoventure.studio/lexicon/disclosure-threshold) — The Delegation Trace records whether authority was exercised within its disclosed bounds at each handoff point, connecting to the Disclosure Threshold framework.
- [Moat Perimeter](https://arcoventure.studio/lexicon/moat-perimeter) — The Orchestrator-Specialist market structure that creates the multi-provider delegation chains the Delegation Trace is built to make attributable.

## Articles

- [Who's Liable When Nobody Decided?](https://arcoventure.studio/blog/whos-liable-when-nobody-decided)
- [How to Compete Against a Moat You Didn't Build](https://arcoventure.studio/blog/how-to-compete-against-a-moat-you-didnt-build)

## References

- [Lexicon](https://arcoventure.studio/lexicon/delegation-trace) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/delegation-trace) — extended entry

## Metadata

**First used:** 2026-08-09  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
