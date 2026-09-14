# Round-Trip Commit

> The commit rule under which a Steward command that would trigger an action above the Physical Intervention Threshold is not executed as heard, but is rendered back to the Steward on the verification route as the specific state change it will produce, and executed only on the Steward's confirmation of that rendering — the Transcoding Layer's response to a command that is transient for the human, lossy for the agent, and irreversible in effect.

## Extended Definition

Voice is the Steward's fastest output, and the Transcoding Layer routes the command route through it for that reason. Voice is also the channel least suited to committing something that cannot be undone. A spoken command is gone the moment it is said, so the human cannot re-read what they asked for. It reaches the agent as audio and is converted to structured intent, so the agent may have heard something other than what was meant. And when the action on the far side is physical — a shipment released, a machine started, a commitment made against inventory another agent will now count on — the Rollback Cost of acting on a misheard or misspoken command is the full cost of the action. Round-Trip Commit is the rule that reconciles the fast channel with the irreversible action.

The rule has three parts and the order matters. The command is received on the command route, by voice. Before anything executes, the system renders back to the Steward, on the verification route, what it will do: not a transcript of the words, which would only confirm that the audio was captured, but the specific state change the intent resolves to — this line, these hours, this counterparty, this commitment. The Steward confirms that rendering, and only then does the action proceed. The round trip converts a transient, lossy command into a checked one by passing it through the channel where the Steward sees fastest, which is the same channel the Transcoding Layer already uses for verification. Nothing new is built; an existing route is used twice.

The rule is scoped by reversibility, not by modality. A command that is cheap to undo does not round-trip, whether spoken or typed, because the delay would be an Authorization Trap — a gate that no longer serves a function and that the operator cannot remove. A command that clears the Physical Intervention Threshold round-trips regardless of how it was issued, because the threshold is set by the cost of a single wrong action and a typed command can be wrong too. Voice raises the probability of a mismatch between intent and instruction; irreversibility sets the cost. The rule fires on the cost.

Round-Trip Commit is distinct from Exception Architecture, which governs what the system does when it meets a state it does not recognise. Here the system has recognised the state perfectly well. What it does not yet know is whether the human meant what the system heard, and the only party who can answer that is the human — quickly, by looking. Arco projects the rule as a requirement of any Steward surface that accepts voice commands with physical effect; it is not a description of a surface Arco has built.

### Application

Attach the rule to the action's reversibility, not to the command's channel: any command whose Rollback Cost clears the Physical Intervention Threshold round-trips, whether spoken or typed, and the rendering the Steward confirms is the system's own reading of the intent, not an echo of the words.

## Related Terms

- [Transcoding Layer](https://arcoventure.studio/lexicon/transcoding-layer) — Round-Trip Commit reuses the Transcoding Layer's verification route a second time, rendering back the specific state change a voice command will produce before it executes.
- [Physical Intervention Threshold](https://arcoventure.studio/lexicon/physical-intervention-threshold) — A command round-trips whenever it would trigger an action above the Physical Intervention Threshold, regardless of how the command was issued.
- [Rollback Cost](https://arcoventure.studio/lexicon/rollback-cost) — The rule exists because the Rollback Cost of acting on a misheard or misspoken voice command is the full cost of an irreversible action.
- [Authorization Trap](https://arcoventure.studio/lexicon/authorization-trap) — A command that is cheap to undo skips the round trip, because forcing the delay anyway would make the gate an Authorization Trap the operator cannot remove.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — Round-Trip Commit is distinct from Exception Architecture: here the system has recognised the state correctly and only needs the human to confirm that the reading matches their intent.
- [Verification Blindness](https://arcoventure.studio/lexicon/verification-blindness) — Round-Trip Commit uses the same visual verification route that prevents Verification Blindness, rendering state instead of echoing words back to the Steward.

## Articles

- [The Steward Speaks. The Steward Sees. The System Reads.](https://arcoventure.studio/blog/the-steward-speaks-the-steward-sees-the-system-reads)
- [The Threshold Was Never Priced for Irreversibility](https://arcoventure.studio/blog/priced-for-irreversibility)

## References

- [Lexicon](https://arcoventure.studio/lexicon/round-trip-commit) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/round-trip-commit) — extended entry

## Metadata

**First used:** 2026-09-14  
**Pillar:** How We Think

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
