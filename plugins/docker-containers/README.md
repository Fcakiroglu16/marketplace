# Docker and containers

Docker's official skills to containerize a project, write lean multi-stage Dockerfiles and Compose stacks, and confirm before any destructive Docker command, with the Docker docs MCP.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/docker-containers

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install docker-containers@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add docker-containers@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Containers from Docker's own team: a Dockerfile, `compose.yaml` and `.dockerignore` for a new project, multi-stage builds with good caching and non-root users, Compose services with health checks, volumes and networks. A guardrail skill makes the agent say what will be lost and wait for your confirmation before `rm`, `prune` or `rmi`. The Docker docs server answers from the current documentation without an account.

## Skills

- `docker-project-foundations`: Use this skill when setting up, initializing, or Dockerizing a project, even if the user doesn't explicitly mention Docker but describes a need for containerize…
- `docker-build-strategies`: Use this skill when writing, reviewing, or optimizing Dockerfiles, even if the user just says their image is too large, their build is slow, or they need to har…
- `docker-compose-patterns`: Use this skill when creating, modifying, or debugging Docker Compose configurations, even if the user just says they need to wire services together, add a datab…
- `docker-destructive-guardrails`: Use this skill before running, or recommending, any Docker command that deletes, wipes, resets, or otherwise irreversibly changes state — even if the user just…
- `docker-docs`: Use this skill to answer questions about any Docker product from current official Docker documentation instead of memory, even if the user just asks "how do I…"…

## MCP servers

- **Docker docs**: Docker's official docs MCP server: searches the current Docker documentation. Read-only, no account needed.

All skills are copied unchanged from [docker/skills](https://github.com/docker/skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
