# Node.js and TypeScript backend

Modern Node.js 22+ with native TypeScript, Fastify APIs, strict types and ESLint 9 flat config from Matteo Collina (Node.js TSC, Fastify lead), plus Hono's official skill.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/node-typescript-backend

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install node-typescript-backend@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add node-typescript-backend@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Server-side TypeScript the way Node.js maintainers write it: native type stripping on Node 22+, streams and error handling, Fastify routes, plugins and JSON Schema validation, generics without `any`, and ESLint 9 flat config with neostandard. Hono's own skill covers routing, middleware and validation for edge and Node runtimes.

## Skills

- `node`: Provides domain-specific best practices for Node.js development with TypeScript, covering type stripping, async patterns, error handling, streams, modules, test…
- `fastify-best-practices`: Guides development of Fastify Node.js backend servers and REST APIs using TypeScript or JavaScript. Use when building, configuring, or debugging a Fastify appli…
- `typescript-magician`: Designs complex generic types, refactors `any` types to strict alternatives, creates type guards and utility types, and resolves TypeScript compiler errors. Use…
- `linting-neostandard-eslint9`: Configures ESLint v9 flat config and neostandard for JavaScript and TypeScript projects, including migrating from legacy `.eslintrc*` files or the `standard` pa…
- `oauth`: Implements OAuth 2.0/2.1 authorization flows in Fastify applications — configures authorization code with PKCE, client credentials, device flow, refresh token r…
- `hono`: Use when building Hono web applications or when the user asks about Hono APIs, routing, middleware, JSX, validation, testing, or streaming. TRIGGER when code im…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [mcollina/skills](https://github.com/mcollina/skills) under the MIT and [honojs/skills](https://github.com/honojs/skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
