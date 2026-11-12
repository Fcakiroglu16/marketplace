# ClickHouse

ClickHouse's official skills: review schemas, queries and settings against 31 rules and choose ingestion and modelling patterns, with the ClickHouse MCP server, read-only by default.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/clickhouse

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install clickhouse@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add clickhouse@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Design ClickHouse tables (ORDER BY, partitioning, codecs), write fast queries and pick ingestion and modelling patterns with ClickHouse's own rules and decision frameworks. The ClickHouse MCP server is read-only unless you set `CLICKHOUSE_ALLOW_WRITE_ACCESS`; set the `CLICKHOUSE_*` connection variables first.

## Skills

- `clickhouse-best-practices`: MUST USE when reviewing ClickHouse schemas, queries, or configurations. Contains 31 rules that MUST be checked before providing recommendations. Always read rel…
- `clickhouse-architecture-advisor`: MUST USE when designing ClickHouse architectures, selecting between ingestion or modeling patterns, or translating best practices into workload-specific system…

## MCP servers

- **ClickHouse**: ClickHouse's official MCP server: list databases and tables and run SELECT queries; read-only unless CLICKHOUSE_ALLOW_WRITE_ACCESS is true. Needs uv and the CLICKHOUSE_* variables.

All skills are copied unchanged from [ClickHouse/agent-skills](https://github.com/ClickHouse/agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
