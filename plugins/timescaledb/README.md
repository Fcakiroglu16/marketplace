# TimescaleDB time series

Tiger Data's skills for time-series Postgres: find tables that should be hypertables, set them up, migrate existing tables and query with hyperfunctions.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/timescaledb

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install timescaledb@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add timescaledb@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Time-series data in Postgres with TimescaleDB: spot the tables that belong in hypertables, create them with the right chunking, compression and retention, migrate existing tables without downtime and write queries with hyperfunctions. The Tiger Data docs server answers from the current TimescaleDB documentation.

## Skills

- `find-hypertable-candidates`: Use this skill to analyze an existing PostgreSQL database and identify which tables should be converted to Timescale/TimescaleDB hypertables. Trigger when user…
- `setup-timescaledb-hypertables`: Use this skill when creating database schemas or tables for Timescale, TimescaleDB, TigerData, or Tiger Cloud, especially for time-series, IoT, metrics, events,…
- `migrate-postgres-tables-to-hypertables`: Use this skill to migrate identified PostgreSQL tables to Timescale/TimescaleDB hypertables with optimal configuration and validation. Trigger when user asks to…
- `timescaledb-hyperfunctions`: Use this skill when writing analytical SQL over time-series data with the TimescaleDB Toolkit (timescaledb_toolkit extension) hyperfunctions: approximate percen…

## MCP servers

- **PostgreSQL docs (Tiger Data)**: Tiger Data's public docs server: searches the PostgreSQL, TimescaleDB and PostGIS documentation. No account needed.
- **Postgres MCP Pro**: Crystal DBA's Postgres MCP Pro in restricted mode: schema browsing, EXPLAIN plans, index tuning advice and health checks, with read-only transactions and time limits. Needs uv and DATABASE_URI.

All skills are copied unchanged from [timescale/pg-aiguide](https://github.com/timescale/pg-aiguide) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
