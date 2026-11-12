# Redis

Redis's official skills for data modelling, connections and pipelining, Redis Search and vectors, clustering, security and observability, with the Redis MCP server.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install redis@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add redis@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Redis from Redis: choose the right data structure and key names, pool and pipeline connections, build search and vector indexes, avoid CROSSSLOT errors in a cluster, lock it down with ACLs and TLS, and read SLOWLOG and INFO. The Redis MCP server has no read-only switch, so point `REDIS_URL` at an ACL user with read rights only (`+@read -@write`) unless you want the agent to write.

## Skills

- `redis-core`: Core Redis modeling guidance — choose the right data structure (String, Hash, List, Set, Sorted Set, JSON, Stream, Vector Set) and use consistent colon-separate…
- `redis-connections`: Redis client and connection guidance covering connection pooling, multiplexing, pipelining, client-side caching with RESP3, avoiding slow commands (KEYS, SMEMBE…
- `redis-search`: Redis Search guidance covering FT.CREATE schema design, field type selection (TEXT, TAG, NUMERIC, GEO, GEOSHAPE, VECTOR, JSON path), DIALECT 2 query syntax, FT.…
- `redis-clustering`: Redis Cluster and replication guidance covering hash tags for multi-key operations, avoiding CROSSSLOT errors, and reading from replicas to scale read-heavy wor…
- `redis-security`: Redis security guidance covering authentication (requirepass and ACL users), TLS, ACL-based least-privilege access control, restricting network exposure via bin…
- `redis-observability`: Redis observability guidance — which metrics to monitor (memory, connections, hit ratio, ops/sec, rejected connections), which built-in commands to reach for du…

## MCP servers

- **Redis**: Redis's official MCP server: read and write keys and data structures, search indexes and server info. Needs uv and REDIS_URL; use a read-only ACL user to keep it read-only.

All skills are copied unchanged from [redis/agent-skills](https://github.com/redis/agent-skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
