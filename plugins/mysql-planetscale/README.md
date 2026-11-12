# MySQL and Vitess

PlanetScale's skills for MySQL schema design, indexing and query tuning, and for Vitess sharding, keyspaces and online schema changes.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install mysql-planetscale@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add mysql-planetscale@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

MySQL and Vitess guidance from PlanetScale's database team: InnoDB-friendly schemas and primary keys, indexes the optimizer actually uses, reading EXPLAIN, and for Vitess, keyspaces, vindexes, sharding and online schema changes.

## Skills

- `mysql`: Plan and review MySQL/InnoDB schema, indexing, query tuning, transactions, and operations. Use when creating or modifying MySQL tables, indexes, or queries; dia…
- `vitess`: Vitess best practices, query optimization, and connection troubleshooting for PlanetScale Vitess databases. Load when working with Vitess databases, sharding, V…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [planetscale/database-skills](https://github.com/planetscale/database-skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
