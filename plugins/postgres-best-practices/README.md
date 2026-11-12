# PostgreSQL best practices

Schema design, indexing, query tuning, zero-downtime migrations, schema exploration and pgvector search for any PostgreSQL database, from Supabase and Tiger Data.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/postgres-best-practices

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install postgres-best-practices@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add postgres-best-practices@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Postgres guidance that works wherever your database runs: data types, constraints and indexes, reading EXPLAIN, RLS, migrations that take the right locks, and semantic or hybrid search with pgvector. Postgres MCP Pro connects in restricted mode, so the agent reads and analyses but runs only read-only transactions; set `DATABASE_URI` first. The Tiger Data docs server searches the PostgreSQL manual.

## Skills

- `supabase-postgres-best-practices`: Postgres best practices maintained by Supabase, for Postgres running anywhere. Load this skill BEFORE writing or changing anything that lives in a Postgres data…
- `design-postgres-tables`: Use this skill for general PostgreSQL table design. Trigger when user asks to: - Design PostgreSQL tables, schemas, or data models when creating new tables and…
- `postgres-database-migration`: Use this skill for planning, testing, and safely executing PostgreSQL schema migrations — especially when working with production data or shared databases. Trig…
- `schema-exploration`: Explore an existing PostgreSQL database before answering questions about its data or writing SQL. Use this skill whenever a user asks for a query or a data-back…
- `pgvector-semantic-search`: Use this skill for setting up vector similarity search with pgvector for AI/ML embeddings, RAG applications, or semantic search. Trigger when user asks to: - St…
- `postgres-hybrid-text-search`: Use this skill to implement hybrid search combining BM25 keyword search with semantic vector search using Reciprocal Rank Fusion (RRF). Trigger when user asks t…
- `design-postgis-tables`: Comprehensive PostGIS spatial table design reference covering geometry types, coordinate systems, spatial indexing, and performance patterns for location-based…

## MCP servers

- **Postgres MCP Pro**: Crystal DBA's Postgres MCP Pro in restricted mode: schema browsing, EXPLAIN plans, index tuning advice and health checks, with read-only transactions and time limits. Needs uv and DATABASE_URI.
- **PostgreSQL docs (Tiger Data)**: Tiger Data's public docs server: searches the PostgreSQL, TimescaleDB and PostGIS documentation. No account needed.

All skills are copied unchanged from [supabase/agent-skills](https://github.com/supabase/agent-skills) under the MIT and [timescale/pg-aiguide](https://github.com/timescale/pg-aiguide) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
