# Encoded Mandate

> The machine-enforced statement of what an agent is permitted to act on and on whose authority, held in the architecture that mediates the agent's every action rather than in the instructions the agent reads, so the boundary holds whether or not the agent interprets it correctly.

## Extended Definition

An agent's permitted reach is either enforced by the system or held by the agent's own reading of its instructions. There is no third option. Every Transition Is Either Encoded or Human stated that principle for process steps — a transition the architecture does not encode is one a human has to make — and the Encoded Mandate is the same principle applied to scope. A prompt that says "only touch these systems" is not a boundary. It is a description of a boundary, delivered to the one party in the architecture that is supposed to execute rather than judge, and the September 2026 disclosures showed that party exceeding such descriptions in one case and misreading them in another. An Encoded Mandate is the boundary held where it holds: in the layer that mediates the agent's every call, so that an out-of-scope action is refused by the system rather than declined by the agent.

The term is defined against three neighbours. It is not a Task License, which is a credential of competence for a task domain and says nothing about permitted reach; competence and permission are different objects. It is not an Intervention Threshold or a Physical Intervention Threshold, which govern which actions inside scope escalate to a human; the mandate is a perimeter, not a gate, and inside it the agent acts at agent latency with no approval — which is also why it is not an Authorization Trap. And it is not Exception Architecture, which governs what the system does with a state it cannot resolve; the mandate makes the out-of-scope action unavailable, and the exception path is what remains for states inside scope.

A security engineer will say the enterprise already enforces least privilege at the proxy and the service mesh. The increment is not five new controls; each can be built from pieces that exist. The increment is the unit of governance. Identity and network policy are organised around credentials and hosts. An Encoded Mandate is organised around one agent's permitted reach, on whose authority, as a single policy object the existing controls are unified under — and it covers what those controls usually do not: the counterparties an agent may transact with, the resources it may commit, credentials it discovers rather than is given, channels it opens that were never in its tool list, and the identity behind a name.

The mandate is the inbound twin of the Machine-Readable Interface. The MRI declares what outside agents may do to a business; the mandate declares what the business's own agents may do to everything else. Both are machine-readable statements of permitted reach, enforced by the system rather than trusted to the party being bounded. Because each model release extends what agents can reach, a mandate written against one model's footprint has holes the next model can walk through without violating an instruction; the mandate is a recurring obligation on the release cycle, not a design-time deliverable. Arco has not built the enforcement layer this describes; the term is a design requirement derived from public incidents and the corpus's existing principles.

### Application

For every deployed agent, name the systems, actions, counterparties and resources it may reach and on whose authority, then ask where that list lives: if it lives in a prompt, a tool description or a task instruction, the mandate is a sentence; if it lives in the layer every call passes through and binds resolved identities and action classes rather than hostnames, it is encoded.

### Context

The principle that every transition is either encoded or human, applied to scope: an agent's permitted reach is either enforced by the system or held by the agent's own reading of its instructions, which is a Judgment Layer act performed by the Execution Layer. The Encoded Mandate is the inbound twin of the Machine-Readable Interface — the MRI declares what outside agents may do to a business, the mandate declares what the business's own agents may do to everything else — and it ages on the model release cycle, because each release extends what agents can reach.

## Related Terms

- [Judgment Layer / Execution Layer](https://arcoventure.studio/lexicon/judgment-layer-execution-layer) — An agent holding its own scope by reading instructions is a Judgment Layer act performed by the Execution Layer; the Encoded Mandate moves that boundary into the architecture.
- [Machine-Readable Interface (MRI)](https://arcoventure.studio/lexicon/machine-readable-interface) — The Encoded Mandate is the inbound twin of the Machine-Readable Interface: the MRI declares what outside agents may do to a business, the mandate what its own agents may do to everything else.
- [Task License](https://arcoventure.studio/lexicon/task-license) — A Task License certifies competence for a task domain and says nothing about permitted reach, which is what the Encoded Mandate defines.
- [Authorization Trap](https://arcoventure.studio/lexicon/authorization-trap) — The mandate is a perimeter rather than a gate, so inside it the agent acts without approval and no Authorization Trap arises.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — Exception Architecture governs states the system cannot resolve inside scope, while the Encoded Mandate makes out-of-scope actions unavailable.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — Intervention Thresholds govern which in-scope actions escalate to a human; the Encoded Mandate bounds the scope itself.
- [Governance Tempo Gap](https://arcoventure.studio/lexicon/governance-tempo-gap) — Each model release extends what agents can reach, so the mandate must be renewed on the release cycle, which is the tempo gap governance has to close.

## Articles

- [The Mandate Was a Sentence](https://arcoventure.studio/blog/the-mandate-was-a-sentence)
- [The Boundary Cannot Live in the Model](https://arcoventure.studio/blog/the-boundary-cannot-live-in-the-model)
- [Every Transition Is Either Encoded or Human](https://arcoventure.studio/blog/every-transition-is-either-encoded-or-human)

## References

- [Lexicon](https://arcoventure.studio/lexicon/encoded-mandate) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/encoded-mandate) — extended entry

## Metadata

**First used:** 2026-09-22  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
