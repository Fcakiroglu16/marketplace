# .NET upgrade

Official skills to move .NET 8 to 9 to 10 to 11, adopt nullable references, check AOT compatibility and handle breaking changes.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/dotnet-upgrade

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dotnet-upgrade@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dotnet-upgrade@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Upgrade a solution release by release with the .NET team's migration skills. NuGet resolves package updates and vulnerabilities; Microsoft Learn has the breaking-change notes.

## Skills

- `migrate-dotnet8-to-dotnet9`: Migrate a .NET 8 project to .NET 9 and resolve all breaking changes. USE FOR: upgrading TargetFramework from net8.0 to net9.0, fixing build errors after updatin…
- `migrate-dotnet9-to-dotnet10`: Migrate a .NET 9 project or solution to .NET 10 and resolve all breaking changes. USE FOR: upgrading TargetFramework from net9.0 to net10.0, fixing build errors…
- `migrate-dotnet10-to-dotnet11`: Migrate a .NET 10 project or solution to .NET 11 and resolve all breaking changes. This is a MIGRATION skill — use it when upgrading from .NET 10 to .NET 11, NO…
- `migrate-nullable-references`: Enable nullable reference types in a C# project and systematically resolve all warnings. USE FOR: adopting NRTs in existing codebases, file-by-file or project-w…
- `dotnet-aot-compat`: Make .NET projects compatible with Native AOT and trimming by systematically resolving IL trim/AOT analyzer warnings. USE FOR: making projects AOT-compatible, f…
- `thread-abort-migration`: Guides migration of .NET Framework Thread.Abort usage to cooperative cancellation in modern .NET. USE FOR: modernizing code that calls Thread.Abort, catching Th…
- `dotnet-breaking-changes`: Use before changing .NET/C# code whose callers you do not control: a NuGet library, or a repo with PublicAPI.Shipped/Unshipped.txt, ApiCompat, multiple TargetFr…
- `setup-local-sdk`: Install a .NET SDK locally for safe preview testing, specific-version pinning, or reproducible team setups — without modifying the system-wide installation. USE…
- `convert-to-cpm`: Convert .NET projects and solutions (.sln, .slnx) to NuGet Central Package Management (CPM) using Directory.Packages.props. USE FOR: converting to CPM, centrali…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.
- **NuGet**: Official NuGet MCP server: package search, versions, vulnerabilities and updates. Needs the .NET 10 SDK (dnx).

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
