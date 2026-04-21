# Agent-Accessible

> A business that an AI agent can reach and invoke at the interface layer but cannot complete a transaction with autonomously — because the operational processes behind the interface remain human-dependent.

## Extended Definition

Agent-Accessible is the false positive of agent-readiness. A business scores well on agent-readiness frameworks — it has a correctly formatted robots.txt, it serves Markdown on content negotiation, it has declared MCP Server Card capabilities — but when an agent invokes one of those declared operations, it encounters a human-dependent process on the other side. The checkout flow is annotated. The fulfilment queue behind it requires manual approval. The API endpoint is discoverable. The exception handling behind it routes to a phone call. The agent can reach the front of the business. It cannot complete the transaction. It is agent-accessible at the entry point and agent-blocked at the back.

The distinction matters because agent-readiness scoring tools cannot detect it. A site that implements the correct headers, declares its capabilities as structured schemas, and exposes an MCP Server Card will score well on any available agent-readiness framework regardless of what those declared capabilities actually connect to. The score measures the presence of the declaration. It does not measure whether the declared operations are backed by deterministic, autonomous execution. A legacy business that completes a sprint to add the required annotations passes the same test as a business that was built for autonomous operation from its first transaction. The score cannot distinguish between them. The agent that attempts a transaction will.

This is what the Cloudflare agent-readiness data — fewer than 15 sites supporting MCP Server Cards across the top 200,000 domains — understates. The 15 sites that pass the MCP check include businesses that have annotated their front end without changing their back end. The number of businesses capable of completing an agentic transaction end-to-end without human involvement at any stage is smaller still. Agent-Accessible businesses will represent the majority of agent-readiness investment over the next two years, because the annotation layer is achievable in a sprint and the architectural layer is not.

## Related Terms

- [Machine-Readable Interface (MRI)](https://arcoventure.studio/lexicon/machine-readable-interface) — A Machine-Readable Interface is what separates a genuinely agent-capable business from an Agent-Accessible one: the MRI is built for autonomous transaction completion, not merely for discovery.
- [Declaration Layer](https://arcoventure.studio/lexicon/declaration-layer) — The Declaration Layer is the annotation layer that makes a business Agent-Accessible; it is necessary but not sufficient for autonomous transaction completion.
- [Architectural Certainty](https://arcoventure.studio/lexicon/architectural-certainty) — Architectural Certainty is the architectural condition that distinguishes a truly agent-capable business from an Agent-Accessible one: the system runs without human decisions for days at a time.
- [Legacy Liability](https://arcoventure.studio/lexicon/legacy-liability) — Legacy Liability is the structural reason most businesses are Agent-Accessible rather than agent-capable: the coordination architecture behind the annotated front end cannot be rebuilt in a sprint.
- [Architectural Decoupling](https://arcoventure.studio/lexicon/architectural-decoupling) — Architectural Decoupling is the structural condition an Agent-Accessible business lacks: its operational processes remain governed by individual human agency rather than encoded logic.
- [Coordination Trap](https://arcoventure.studio/lexicon/coordination-trap) — An Agent-Accessible business is in the Coordination Trap: it has reduced the friction of agent discovery without removing the human coordination dependencies that prevent autonomous transaction completion.
- [Automated Business](https://arcoventure.studio/lexicon/automated-business) — An Agent-Accessible business is typically an Automated Business with a machine-readable annotation layer: technology has been overlaid on a human-centric structure without replacing the structure.

## Articles

- [Cloudflare Just Measured the Agent-Readiness Gap. The Numbers Are What We Expected.](https://arcoventure.studio/blog/cloudflare-measured-the-agent-readiness-gap)
- [The Agent-Ready Business: What WebMCP Reveals About the Companies Being Left Behind](https://arcoventure.studio/blog/agent-ready-business-webmcp)
- [The Lexicon Was the Point](https://arcoventure.studio/blog/lexicon-as-declaration-layer)

## References

- [Lexicon](https://arcoventure.studio/lexicon/agent-accessible) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/agent-accessible) — extended entry

## Metadata

**First used:** 2026-04-19  
**Pillar:** What We Observe

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
