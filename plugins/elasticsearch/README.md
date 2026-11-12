# Elasticsearch

Elastic's official skills for ES|QL, mapping and index design, slow-query profiling, relevance tuning and read-only cluster health checks.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install elasticsearch@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add elasticsearch@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Elastic's own skills for the day-to-day of a search cluster: write ES|QL, design mappings and shards, profile a slow query before changing it, tune relevance with boosts and query rules, and triage cluster health without writing anything. Context7 serves current Elasticsearch documentation.

## Skills

- `elasticsearch-esql`: Execute ES|QL (Elasticsearch Query Language) queries, use when the user wants to query Elasticsearch data, analyze logs, aggregate metrics, explore data, or cre…
- `elasticsearch-index-design`: Design and review Elasticsearch index mappings for stated access patterns: correct field types, text+keyword multi-fields, doc_values tuning, mapping-explosion…
- `elasticsearch-query-optimization`: Diagnose slow Elasticsearch Query DSL searches and propose measured fixes. Use when a search is slow, profile output shows an expensive clause, exact-match filt…
- `elasticsearch-search-relevance`: Improve Elasticsearch search relevance for content and catalog indices: pin or promote results with query rules (correct rule type, criteria, and rule-query wir…
- `elasticsearch-cluster-health`: Diagnose a non-green Elasticsearch cluster and surface the single most likely cause with remediation. Use when an operator reports yellow or red status, unassig…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [elastic/agent-skills](https://github.com/elastic/agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
