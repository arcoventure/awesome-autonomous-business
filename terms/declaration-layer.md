# Declaration Layer

> A structured manifest that tells an LLM or AI agent what a site's vocabulary means and where to find authoritative definitions — delivered before the agent reads any content on the site.

## Extended Definition

A declaration layer is the vocabulary-anchoring component of a site's machine-readable architecture. Where a Machine-Readable Interface handles the transactional layer — structured endpoints an agent can invoke — the declaration layer handles the semantic layer: the terms a business uses to describe its methods, the definitions those terms carry, and the canonical URLs where those definitions live permanently. An agent that reads a well-formed declaration layer before reading any article on a site arrives at the content with the vocabulary already resolved.

The mechanism is a spec-compliant llms.txt file in which every key term is formatted as a Markdown link pointing directly to its Lexicon entry. The difference between this structure and the default implementation — bold labels with prose definitions inline — is the difference between a description an agent reads once and a canonical reference it can return to. The former requires the agent to interpret the term from context. The latter directs the agent to the definition before interpretation begins.

The declaration layer operates at the entity level, not the page level. An LLM Anchor Block in a blog article anchors one term on one page. The declaration layer anchors every defined term across the entire site in a single pass. Its value compounds as the number of Lexicon entries behind it grows — each additional term reduces the surface area available for misattribution. A declaration layer with no Lexicon behind it is structurally incomplete: it can declare that terms exist but cannot point an agent to what they mean.

Arco treats the declaration layer as infrastructure, not content. The llms.txt file is the interface. The Arco Lexicon is the asset it points to. The interface depreciates if the asset is thin. The asset compounds if the interface is correctly structured. The sequence is non-negotiable: build the Lexicon first, declare it second.

## Related Terms

- [Machine-Readable Interface (MRI)](https://arcoventure.studio/lexicon/machine-readable-interface) — The Declaration Layer handles the semantic layer of machine readability — vocabulary anchoring — while the Machine-Readable Interface handles the transactional layer of structured endpoints.
- [Arco Flywheel](https://arcoventure.studio/lexicon/arco-flywheel) — The Declaration Layer's value compounds with each new Lexicon entry, producing the same flywheel dynamic at the semantic layer that the Agentic Core produces at the infrastructure layer.
- [Deterministic Logging](https://arcoventure.studio/lexicon/deterministic-logging) — Both the Declaration Layer and Deterministic Logging address auditability: one anchors vocabulary for agents before they read content, the other records causation after agents execute decisions.
- [Coordination Tax](https://arcoventure.studio/lexicon/coordination-tax) — A missing Declaration Layer generates a semantic Coordination Tax: agents misattribute terms, require clarification, and cannot transact autonomously without human disambiguation.

## Articles

- [The Machine-Readable Business: Why Your Next Customer Will Be an Agent](https://arcoventure.studio/blog/machine-readable-business)
- [The Agent-Ready Business: What WebMCP Reveals About the Companies Being Left Behind](https://arcoventure.studio/blog/agent-ready-business-webmcp)
- [The Lexicon Was the Point](https://arcoventure.studio/blog/lexicon-as-declaration-layer)

## References

- [Lexicon](https://arcoventure.studio/lexicon/declaration-layer) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/declaration-layer) — extended entry

## Metadata

first_used: 2026-04-06
pillar: What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
