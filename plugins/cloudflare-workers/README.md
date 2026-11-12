# Cloudflare Workers

Cloudflare's official skills to choose the right Cloudflare product, build and debug Workers to Cloudflare's best practices and use Wrangler safely, with Cloudflare's API and docs MCP servers.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install cloudflare-workers@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add cloudflare-workers@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Build on Cloudflare with Cloudflare's own skills: pick between Workers, Pages, D1, R2, KV, Queues and Durable Objects, follow the Workers best practices, develop and debug locally, and use Wrangler with `--dry-run` first and an explicit target environment. Production deploys and secrets need your clear intent. The docs server needs no account; the API server signs in with OAuth and gets only the scopes you grant.

## Skills

- `cloudflare`: Discover and choose Cloudflare products for apps, APIs, AI agents, storage, networking, and security. Use for architecture and product selection, including when…
- `workers-best-practices`: Cloudflare Workers best practices for production applications. Use when writing, reviewing, or configuring Workers.
- `workers-development`: Run, inspect, and debug Cloudflare Workers during local development with cf dev, wrangler dev, or the Cloudflare Vite plugin, using Local Explorer to read and s…
- `wrangler`: Run or troubleshoot Wrangler CLI commands in projects that have a wrangler.jsonc, wrangler.json, or wrangler.toml file, including local development, Previews, d…
- `durable-objects`: Build, debug, or review Cloudflare Durable Objects code for persistent state and coordination.

## MCP servers

- **Cloudflare docs**: Cloudflare's official docs server: searches the Cloudflare developer documentation. Read-only, no account needed.
- **Cloudflare API**: Cloudflare's official API server: works with your account's Workers, DNS, R2, D1 and other resources. Signs in with OAuth; grant only the scopes you need.

All skills are copied unchanged from [cloudflare/skills](https://github.com/cloudflare/skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
