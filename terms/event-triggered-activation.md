# Event-Triggered Activation

> The infrastructure pattern by which a dormant agent is initialised and executed in response to a defined external signal — a document arrival, a usage threshold breach, a time condition, a human action, or a downstream agent output — rather than running as a continuous process, making the compute cost of agentic operation proportional to actual execution rather than to elapsed time.

## Extended Definition

The Operational Arbitrage of agentic deployment depends on compute cost remaining proportional to execution volume. An agent that processes 100 transactions per hour at a compute cost of $0.01 per transaction generates $1 of compute cost per hour. The same agent architecture running continuously during an eight-hour period in which it processes zero transactions generates eight hours of compute cost. At single-agent scale, this is an engineering inefficiency. At a production autonomous business running dozens of specialised agents across multiple Revenue Loop steps, idle compute cost can exceed execution compute cost and eliminate the Operational Arbitrage that justified the architecture.

Event-Triggered Activation resolves this by separating agent availability from agent execution. The agent's definition — its system prompt, its tool set, its context configuration — is stored as a specification rather than a running process. When the defined trigger fires (a webhook, a scheduled cron, a message queue event, a threshold breach detected by a monitoring agent), the infrastructure deserialises the specification, instantiates the agent process, executes the triggered workflow, and terminates the process when execution completes. The compute cost is incurred only during the execution window, not during the waiting period between triggers.

The relationship to Suspend/Resume Architecture is complementary but distinct. Suspend/Resume Architecture governs workflows that have already started executing and must pause mid-execution to wait for an external signal. Event-Triggered Activation governs agents that have not yet started executing and must be initialised by an external signal. Together, they ensure that compute cost is tied to actual work at both the activation boundary (before execution begins) and the suspension boundary (during execution, when waiting is required).

Define the trigger specification for every agent before deployment: what event, threshold, or condition causes this agent to activate, and at what latency requirement? Triggers with latency requirements below one second require pre-warmed infrastructure (a small pool of pre-initialised agent processes ready to execute). Triggers with latency requirements above ten seconds can use cold-start infrastructure. The trigger specification is part of the agent's design document, not an infrastructure configuration decision made separately. Test activation latency under production-representative trigger volumes before deployment — activation latency under low trigger frequency does not predict activation latency under concurrent triggers, which is the production condition that matters.

## Related Terms

- [Suspend/Resume Architecture](https://arcoventure.studio/lexicon/suspend-resume-architecture) — Suspend/Resume Architecture is the complementary pattern to Event-Triggered Activation: where Event-Triggered Activation governs agents not yet executing, Suspend/Resume governs workflows mid-execution that must pause and resume without holding compute.
- [Agentic Infrastructure](https://arcoventure.studio/lexicon/agentic-infrastructure) — Agentic Infrastructure is the broader layer that Event-Triggered Activation is a component of: it is the infrastructure designed specifically for agent workloads, of which event-driven activation is the first principle.
- [Operational Arbitrage](https://arcoventure.studio/lexicon/operational-arbitrage) — Event-Triggered Activation preserves Operational Arbitrage at scale by ensuring idle compute cost does not accumulate to eliminate the cost advantage of agentic operation over human-staffed equivalents.
- [Infrastructure Drag](https://arcoventure.studio/lexicon/infrastructure-drag) — Event-Triggered Activation eliminates one of the primary sources of Infrastructure Drag: continuous-process agent architectures that pay for compute during idle periods transfer foundational engineering cost into ongoing operational cost.
- [Intervention Threshold](https://arcoventure.studio/lexicon/intervention-threshold) — The Intervention Threshold governs which triggered executions require Steward involvement: a well-specified trigger with a well-set Intervention Threshold ensures the agent activates, executes, and terminates without human involvement at the defined rate.
- [Exception Architecture](https://arcoventure.studio/lexicon/exception-architecture) — Exception Architecture governs what happens when an Event-Triggered Activation encounters an operational state its logic cannot resolve: the trigger fires correctly but the execution requires escalation.
- [Task Tiers (T1 / T2 / T3)](https://arcoventure.studio/lexicon/t1-t2-t3) — Task Tiers determine the trigger specifications and latency requirements for Event-Triggered Activation: T1 tasks with high volume may require pre-warmed infrastructure while T3 tasks with lower frequency can use cold-start activation.

## Articles

- [Infrastructure Is Architecture](https://arcoventure.studio/blog/infrastructure-is-architecture)

## References

- [Lexicon](https://arcoventure.studio/lexicon/event-triggered-activation) — canonical definition
- [Wiki](https://wiki.arcoventure.studio/lexicon/event-triggered-activation) — extended entry

## Metadata

**First used:** 2026-05-15  
**Pillar:** What We've Learned

---

*Part of the [Arco Lexicon Ecosystem](https://arcoventure.studio/lexicon) — maintained by [Arco Venture Studio](https://arcoventure.studio)*
