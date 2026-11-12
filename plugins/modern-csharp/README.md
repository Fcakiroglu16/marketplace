# Modern C#

Official C# skills: expert guidance, safe refactoring, C# scripts, P/Invoke, SIMD vectorization and the new .NET 11 APIs.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/modern-csharp

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install modern-csharp@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add modern-csharp@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Write and reshape C# the way the .NET team does, from everyday refactors to interop and vectorized code, with the newest library APIs.

## Skills

- `csharp-expert`: Route C# and .NET requests to the exact installed specialist or smallest dotnet/skills marketplace plugin. USE FOR: "which specialist should own this" or "how d…
- `csharp-refactoring`: Safely refactors C#/.NET code without changing behavior. USE FOR any request to refactor, rename, move, extract, inline, merge, consolidate, deduplicate, split,…
- `csharp-scripts`: Run file-based C# apps with the .NET CLI when the user explicitly wants C#/.NET code without creating a project. Use for C# language/API experiments, one-file C…
- `dotnet-pinvoke`: Correctly call native (C/C++) libraries from .NET using P/Invoke and LibraryImport. Covers function signatures, string marshalling, memory lifetime, SafeHandle,…
- `vectorization`: Design, implement, optimize, and review SIMD code in .NET. USE FOR: vectorizing scalar loops with TensorPrimitives, Vector64/128/256/512, or platform hardware i…
- `process-api-net11`: Provides guidance on the new System.Diagnostics.Process APIs introduced in .NET 11: Process.Run, Process.RunAndCaptureText, Process.StartAndForget, Process.Read…
- `system-text-json-net11`: Imperative guidance for the System.Text.Json APIs added in .NET 11: the built-in `JsonNamingPolicy.PascalCase` naming policy, and the strongly-typed generic `Js…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
