# Supabase

Build on Supabase (database, auth, RLS, Edge Functions, Realtime, Storage, CLI) with Supabase's own skills and the Supabase MCP server in read-only mode.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/supabase

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install supabase@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add supabase@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Supabase's own agent skills: client and SSR libraries, auth and row level security, migrations with the CLI, Edge Functions, Realtime and Storage, plus their Postgres rules. The Supabase MCP server connects read-only with only the database and docs tools; it signs in with OAuth the first time. Confirm before the agent runs destructive SQL, and never let it run SQL against a linked remote project without your approval.

## Skills

- `supabase`: Use when doing ANY task involving Supabase. Triggers: Supabase products (Database, Auth, Edge Functions, Realtime, Storage, Vectors, Cron, Queues); client libra…
- `supabase-postgres-best-practices`: Postgres best practices maintained by Supabase, for Postgres running anywhere. Load this skill BEFORE writing or changing anything that lives in a Postgres data…

## MCP servers

- **Supabase**: Supabase's official MCP server, read-only, with the database and docs tools only: list tables, run read-only SQL, read logs and search the Supabase docs. Signs in with OAuth.

All skills are copied unchanged from [supabase/agent-skills](https://github.com/supabase/agent-skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
