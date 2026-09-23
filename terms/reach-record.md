# Reach Record

> The component of the decision trail that records what an agent reached during execution, every system, credential, channel, counterparty and resource it touched, permitted or not, so scope drift is visible when it occurs; the record against which an Encoded Mandate is enforced and audited.

## Extended Definition

The corpus has two layers of record and neither carries reach. Deterministic Logging records that a decision occurred — the transition, the input, the rule that fired. Proof of Action records what was done — the action and its outcome, so that an autonomy claim can be checked against a trail of executions. Both answer what the agent decided and what it did. They do not answer what the agent touched on the way: which hosts it connected to, which credentials it used or found, which channels it opened, which counterparties it addressed, what it committed. The Reach Record is the layer that does, and it exists because agents now extend their own reach in the course of executing — finding credentials in a public repository, turning a wiki into a message channel — so that a decision-and-outcome record will not show the extension until its consequences appear somewhere else.

Reach is operational state, not audit data, for two reasons. An Encoded Mandate is a boundary, and a boundary is enforced against a position: the layer that refuses an out-of-scope call can only do so if it resolves what the call reaches — the identity behind the name, the provenance of the credential, the party behind the endpoint — at the moment of the call. That resolution is the Reach Record being written. Enforcement and recording are the same act performed by the same layer; a system that enforces a mandate is producing a Reach Record whether or not it stores one, and a system that stores none is describing a mandate, not enforcing it. And scope drift is a trend, visible only against a record. One out-of-scope reach is an incident. A reach that widens by a system a week is a drift, and drift is the failure mode the September 2026 disclosures describe — reach found months later, from outside, by investigators reconstructing the footprint from the open web.

The record's fields are the mandate's dimensions, observed, per agent, per execution, per call: the system reached, by resolved identity; the credential used and whether it was configured, discovered or guessed; the channel opened, including any not in the tool list; the counterparty addressed; the resource committed; and, for each, whether it fell inside or outside the mandate in force. That last field is what lets the record compound into the Operational Ledger, so that the next mandate is written against a footprint rather than an assumption.

The Reach Record is the agent's access log where the Personnel File is its CV, and it does not replace Proof of Action: one is the evidentiary basis for a containment claim, the other for an autonomy claim. It is the record route of the Transcoding Layer, written by the system for itself; the Steward sees it only as the Audit Surface renders it — footprint against mandate, in the channel a human takes in fastest, before it goes stale. Arco produces no Reach Record today; the term is a design requirement.

### Application

For each agent, produce for its last execution the list of every host, credential, channel and counterparty it reached, with each credential's provenance — configured, discovered or guessed — and mark which fell outside the mandate in force; if the system cannot produce that list, the mandate is being enforced against nothing and drift is being found from outside.

## Related Terms

- [Encoded Mandate](https://arcoventure.studio/lexicon/encoded-mandate) — The Reach Record is the record against which an Encoded Mandate is enforced and audited; enforcing the mandate is the act of writing it.
- [Deterministic Logging](https://arcoventure.studio/lexicon/deterministic-logging) — Deterministic Logging records that a decision occurred but not what the agent touched on the way; the Reach Record adds that layer.
- [Proof of Action](https://arcoventure.studio/lexicon/proof-of-action) — Proof of Action records what was done and supports an autonomy claim, while the Reach Record supports a containment claim.
- [Operational Ledger](https://arcoventure.studio/lexicon/operational-ledger) — The inside-or-outside-mandate field lets the Reach Record compound into the Operational Ledger so the next mandate is written against a footprint.
- [Audit Surface](https://arcoventure.studio/lexicon/audit-surface) — The Steward sees the Reach Record only as the Audit Surface renders it, as footprint against mandate.
- [Nominal Containment](https://arcoventure.studio/lexicon/nominal-containment) — The Reach Record removes the invisibility that lets Nominal Containment pass for real containment.
- [Transcoding Layer](https://arcoventure.studio/lexicon/transcoding-layer) — The Reach Record is the record route of the Transcoding Layer, written by the system for itself.

## Articles

- [The Mandate Was a Sentence](https://arcoventure.studio/blog/the-mandate-was-a-sentence)
- [The Steward Got a Channel](https://arcoventure.studio/blog/the-steward-got-a-channel)

## References

- [Lexicon](https://arcoventure.studio/lexicon/reach-record) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/reach-record) — extended entry

## Metadata

**First used:** 2026-09-22  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
