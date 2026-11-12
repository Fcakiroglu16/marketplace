# Prisma ORM

Prisma's official skills: set up Prisma ORM 6, 7 and 8 for any provider, the Client API, the CLI and the upgrade from v6 to v7.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install prisma-orm@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add prisma-orm@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Set up Prisma for any database, write Client queries, filters and transactions, use `migrate` and `db` correctly and upgrade from v6 to v7. The CLI skill documents destructive commands (`migrate reset`, `--accept-data-loss`) and requires the user's explicit consent before any of them.

## Skills

- `prisma-orm-setup`: Set up Prisma ORM in an application, connect its database, or troubleshoot the connection of an existing Prisma 6, 7, or 8 app. Defaults new applications to Pri…
- `prisma-client-api`: Prisma Client API reference covering model queries, filters, operators, and client methods. Use when writing database queries, using CRUD operations, filtering…
- `prisma-cli`: Prisma ORM 7 CLI reference for existing Prisma 7 applications or explicitly selected Prisma 7 workflows. Covers prisma init, generate, migrate, db, dev, studio,…
- `prisma-upgrade-v7`: Complete migration guide from Prisma ORM v6 to v7 covering all breaking changes. Use when upgrading Prisma versions, encountering v7 errors, or migrating existi…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [prisma/skills](https://github.com/prisma/skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
