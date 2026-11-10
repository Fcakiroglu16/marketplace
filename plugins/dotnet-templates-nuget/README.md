# Templates and NuGet packages

Official skills for dotnet new templates (find, use, author, validate) and NuGet: central package management and trusted publishing.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dotnet-templates-nuget@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dotnet-templates-nuget@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Scaffold with the right template, write your own, and ship packages the modern way: central package management and keyless publishing from GitHub Actions.

## Skills

- `template-discovery`: Helps find, inspect, and compare (at a high level) .NET project templates. Resolves natural-language project descriptions to ranked template matches with pre-fi…
- `template-instantiation`: Creates .NET projects from templates with validated parameters, smart defaults, Central Package Management adaptation, and latest NuGet version resolution. USE…
- `template-smart-defaults`: Applies cross-parameter default rules when creating .NET projects with dotnet new, filling gaps consistently without overriding values the user set explicitly.…
- `template-comparison`: Compares two or more dotnet new templates side by side to help users choose between them based on parameters, feature support, frameworks, and classifications.…
- `template-authoring`: Guides creation and validation of custom dotnet new templates from existing projects. Generates a .template.config/template.json that preserves the source proje…
- `template-validation`: Validates custom dotnet new templates for correctness before publishing. Catches missing fields, parameter bugs, shortName conflicts, constraint issues, and com…
- `convert-to-cpm`: Convert .NET projects and solutions (.sln, .slnx) to NuGet Central Package Management (CPM) using Directory.Packages.props. USE FOR: converting to CPM, centrali…
- `nuget-trusted-publishing`: Set up NuGet trusted publishing (OIDC) on a GitHub Actions repo — replaces long-lived API keys with short-lived tokens. USE FOR: trusted publishing, NuGet OIDC,…

## MCP servers

- **NuGet**: Official NuGet MCP server: package search, versions, vulnerabilities and updates. Needs the .NET 10 SDK (dnx).

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
