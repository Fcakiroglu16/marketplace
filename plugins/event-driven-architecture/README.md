# Event-driven and distributed architecture

Event sourcing, projections, sagas and microservice boundaries for distributed systems.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install event-driven-architecture@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add event-driven-architecture@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

For systems that grow past one process: an event store and event-sourced aggregates, projections that build read models, sagas that coordinate work across services with compensation, and how to draw microservice boundaries and keep them resilient.

## Skills

- `event-store-design`: Design and implement event stores for event-sourced systems. Use when building event sourcing infrastructure, choosing event store technologies, or implementing…
- `projection-patterns`: Build read models and projections from event streams. Use when implementing CQRS read sides, building materialized views, or optimizing query performance in eve…
- `saga-orchestration`: Implement saga patterns for distributed transactions and cross-aggregate workflows. Use this skill when implementing distributed transactions across microservic…
- `microservices-patterns`: Design microservices architectures with service boundaries, event-driven communication, and resilience patterns. Use when building distributed systems, decompos…

All skills are copied unchanged from [wshobson/agents](https://github.com/wshobson/agents) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
