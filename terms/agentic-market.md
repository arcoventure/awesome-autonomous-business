# Agentic Market

> A market in which supply-side resources — inventory, production capacity, logistics capacity — are represented by agents that continuously price and reallocate them in response to changing conditions, rather than agents acting only on behalf of buyers.

## Extended Definition

Existing agent-to-business commerce runs one direction. Agentic Consumption Pricing and the Machine-Readable Interface it depends on describe a buying agent metered and transacting against a catalogue and a price a human already built. Dynamic pricing, algorithmic repricing, and machine-readable inventory feeds are not the same claim. Repricing adjusts a number against a signal on a human-reviewed cadence, and an inventory feed makes a position visible to trading partners; in both cases the underlying resource — the SKU, the pallet, the hour of capacity — remains a listing to be read, not a position another agent can act on. An Agentic Market requires the resource itself to be queryable, transactable, and reallocable by an agent directly, not merely reported to one.

The precondition is addressability at low integration cost. Anthropic's Model Hardware Standard research preview showed the interface-standardisation pattern already familiar from software — a shared specification replacing bespoke integration per device — collapsing physical-equipment integration from weeks to hours. Arco expects the same pattern to reach inventory, capacity, and logistics positions, turning a report generated on a cadence into a live signal an agent responsible for the resource can price against continuously, rather than a spreadsheet a person reviews weekly. Once that holds, a supply-side agent can act on a signal as it arrives — reprice, bundle, reroute, hold — without waiting for the next scheduled review.

Arco frames Agentic Market as a structural projection about where agentic commerce is heading, not a description of a market that already operates this way at scale. The mechanism requires no new economic theory; dynamic pricing already prices to signal. What changes is the cycle time, from a human-reviewed cadence to the agent's own decision latency, and what is exposed, from a number in a pricing system to the resource itself. Not every action in that loop carries the same authority, which is why the Physical Intervention Threshold governs the actions a supply-side agent is cleared to take.

### Application

Treat inventory, capacity, and logistics positions as candidate agent-readable interfaces on the same footing as the demand-side interfaces already priced under Agentic Consumption Pricing. Gate the resulting actions by the Physical Intervention Threshold: an agent should be free to propose, simulate, and reprice continuously, and gated more tightly the closer an action gets to something that cannot be cheaply undone — rerouting a shipment mid-transit, committing capacity to a new order.

### Context

Agent-to-business commerce to date has been demand-side only: an agent searches, compares, negotiates, and purchases on behalf of a buyer, from a catalogue and at a price a human already set. An Agentic Market is Arco's projected extension of that pattern to the supply side, made structurally plausible as the interface standardisation that has collapsed integration cost for software, and is now doing so for physical equipment, reaches inventory and capacity positions.

## Related Terms

- [Agentic Consumption Pricing](https://arcoventure.studio/lexicon/agentic-consumption-pricing) — Agentic Consumption Pricing and the Machine-Readable Interface it depends on describe the demand-side counterpart to an Agentic Market: a buying agent transacting against a catalogue and price a human already set.
- [Machine-Readable Interface (MRI)](https://arcoventure.studio/lexicon/machine-readable-interface) — The interface-standardisation pattern that makes an MRI possible is the same mechanism Arco expects to reach inventory, capacity, and logistics positions, making an Agentic Market's supply-side resources queryable and transactable.
- [Executable Economy](https://arcoventure.studio/lexicon/executable-economy) — An Executable Economy is Arco's projected consequence once Agentic Market signals stop being read-only and the signal itself becomes the decision.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The standard, frequency-based Intervention Threshold is the model the Physical Intervention Threshold extends to govern the supply-side actions an Agentic Market makes possible.
- [Stewardship Model](https://arcoventure.studio/lexicon/stewardship-model) — The Stewardship Model defines the human oversight role that persists even as an Agentic Market shifts supply-side pricing and reallocation to agents.
- [Physical Intervention Threshold](https://arcoventure.studio/lexicon/physical-intervention-threshold) — The Physical Intervention Threshold gates how freely a supply-side agent in an Agentic Market can act, tightening the closer an action gets to something that cannot be cheaply undone.

## Articles

- [The Death of the Seat License: Why Autonomous Businesses Don't Buy SaaS](https://arcoventure.studio/blog/death-of-seat-license)
- [MHS Collapses Hardware Friction, Not Judgment](https://arcoventure.studio/blog/anthropic-mhs-collapses-friction-not-judgment)

## References

- [Lexicon](https://arcoventure.studio/lexicon/agentic-market) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/agentic-market) — extended entry

## Metadata

**First used:** 2026-09-01  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
