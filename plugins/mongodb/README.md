# MongoDB

MongoDB's official skills for schema design, query and index tuning, connection pools and read-only natural-language queries, with the MongoDB MCP server in read-only mode.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/mongodb

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install mongodb@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add mongodb@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

MongoDB's own guidance: when to embed and when to reference, schema validation, finding and fixing slow queries, connection pool and timeout settings for every driver, and read-only `find` and aggregation queries written from plain language. The MongoDB MCP server runs with `--readOnly`; set `MDB_MCP_CONNECTION_STRING` first.

## Skills

- `mongodb-schema-design`: MongoDB schema design patterns and anti-patterns. Use when designing data models, reviewing schemas, migrating from SQL, or troubleshooting performance issues c…
- `mongodb-query-optimizer`: Help with MongoDB query optimization and indexing. Use only when the user asks for optimization or performance: "How do I optimize this query?", "How do I index…
- `mongodb-natural-language-querying`: Generate read-only MongoDB queries (find) or aggregation pipelines using natural language, with collection schema context and sample documents. Use this skill w…
- `mongodb-connection`: Optimize MongoDB client connection configuration (pools, timeouts, patterns) for any supported driver language. Use this skill when working/updating/reviewing o…

## MCP servers

- **MongoDB**: MongoDB's official MCP server in read-only mode: databases, collections, schemas, indexes, find, aggregate and explain. Needs MDB_MCP_CONNECTION_STRING.

All skills are copied unchanged from [mongodb/agent-skills](https://github.com/mongodb/agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
