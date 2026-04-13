# Machine-Readable Interface (MRI)

> A structured, API-first interaction layer that allows external autonomous agents to discover, evaluate, and transact with a business's services without a human intermediary — built specifically for agent inference, not developer integration.

## Extended Definition

A Machine-Readable Interface is not an API in the conventional sense. A standard API was built for developer integration: it assumes a human engineer on the other end who reads documentation, writes code to call the endpoint, and handles the response in a custom application. An MRI is built for agent inference: it assumes an autonomous agent on the other end that is evaluating a service as a procurement option, comparing it against alternatives, and making a transaction decision without a human in the loop. The distinction is not the technology. It is the design intent.
An MRI exposes pricing, availability, service specification, and transaction initiation in the schemas that leading LLMs and agentic frameworks use to identify and qualify service providers. It is a designed discovery mechanism, not a data access layer. A business with a well-built API but no MRI is accessible to developers. It is invisible to agents. In the A2A economy, that invisibility is a structural commercial liability.

## Related Terms

- [Deterministic Failure](https://arcoventure.studio/lexicon/deterministic-failure) — An MRI without proper Deterministic Failure handling at integration points will produce hallucinated fixes when schema mismatches occur, propagating incorrect data through the agent's workflow.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — A well-structured MRI is a prerequisite for Architectural Certainty at the market interface layer: a business that cannot reliably serve agent queries cannot achieve autonomous revenue generation.
- [Turnkey Margin](https://arcoventure.studio/lexicon/turnkey-margin) — An MRI extends the Turnkey Margin concept to the revenue side: a business with a well-built MRI can be discovered and transacted by agent buyers without human sales involvement.
- [Handoff Friction](https://arcoventure.studio/lexicon/handoff-friction) — Handoff Friction is the primary risk in MRI implementation: an agent encountering an unexpected schema at an MRI endpoint will attempt to resolve the mismatch autonomously, producing hallucinated data.

## Articles

- [Engineering for Liquidity: Why Autonomous Companies Are the Ultimate Acquisition Targets](https://arcoventure.studio/blog/engineering-for-liquidity)
- [The Mechanics of Failure: Three Things That Break in Autonomous Systems](https://arcoventure.studio/blog/mechanics-of-failure)

## References

- [Lexicon](https://arcoventure.studio/lexicon/machine-readable-interface) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/machine-readable-interface) — extended entry

## Metadata

first_used: 2026-03-23
pillar: What We Observe

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
