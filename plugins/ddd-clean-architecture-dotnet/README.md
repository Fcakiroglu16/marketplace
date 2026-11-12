# DDD and Clean Architecture (.NET)

Choose and apply Vertical Slice, Clean Architecture, DDD or a modular monolith in ASP.NET Core, with aggregates, value objects, domain events and messaging.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/ddd-clean-architecture-dotnet

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install ddd-clean-architecture-dotnet@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add ddd-clean-architecture-dotnet@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Start with the architecture advisor: it asks about the domain, team and lifetime of the system and picks Vertical Slice, Clean Architecture, DDD with Clean Architecture or a modular monolith. The other skills then apply the choice: Clean (onion) layering with the dependency rule pointing inwards, tactical DDD (aggregates, value objects, strongly typed ids, domain events, repositories), feature slices, and messaging with an outbox and sagas.

## Skills

- `architecture-advisor`: Architecture selection advisor for .NET applications. Asks structured questions about domain complexity, team size, system lifetime, compliance, and integration…
- `clean-architecture`: Clean Architecture for .NET applications. Covers the 4-project layout (Domain, Application, Infrastructure, Api), dependency inversion, use case handlers, domai…
- `ddd`: Domain-Driven Design tactical patterns for .NET applications. Covers aggregates, aggregate roots, value objects, domain events, domain services, strongly-typed…
- `vertical-slice`: Vertical Slice Architecture (VSA) for .NET applications — one of several supported architectures in dotnet-claude-kit. Covers feature folders, endpoint grouping…
- `messaging`: Asynchronous messaging patterns for .NET applications. Covers Wolverine and MassTransit, outbox pattern, saga and choreography, and broker configuration for Rab…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.

All skills are copied unchanged from [codewithmukesh/dotnet-claude-kit](https://github.com/codewithmukesh/dotnet-claude-kit) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
