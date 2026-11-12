# .NET API with Aspire

Official .NET and Aspire skills: Web API, EF Core, tests, AppHost wiring, orchestration, monitoring and deployment.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/dotnet-api-aspire

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dotnet-api-aspire@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dotnet-api-aspire@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Official skills for building a .NET Web API that runs under .NET Aspire.

**.NET side** (from [dotnet/skills](https://github.com/dotnet/skills)): ASP.NET Core Web API endpoints and OpenAPI, data-driven scaffolding, EF Core query optimization, C# guidance, running tests and scaffolding a test project.

**Aspire side** (from [microsoft/aspire-skills](https://github.com/microsoft/aspire-skills)): adding Aspire to a repo, wiring the AppHost (Postgres, Redis, frontends), starting and stopping the app, logs and traces, and deployment.

All skills are copied unchanged under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
