# .NET performance and diagnostics

Official skills to measure and investigate: BenchmarkDotNet, dotnet-trace, dumps, performance analysis and crash symbolication.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/dotnet-performance-diagnostics

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dotnet-performance-diagnostics@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dotnet-performance-diagnostics@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Find out why a .NET app is slow or crashing: collect traces and dumps, benchmark the hot path, and read native crash reports from mobile apps.

## Skills

- `analyzing-dotnet-performance`: Scans .NET code for ~50 performance anti-patterns across async, memory, strings, collections, LINQ, regex, serialization, and I/O with tiered severity classific…
- `microbenchmarking`: Activate this skill when BenchmarkDotNet (BDN) is involved in the task — creating, running, configuring, or reviewing BDN benchmarks. Also activate when microbe…
- `dotnet-trace-collect`: Guide developers through capturing diagnostic artifacts to diagnose production .NET performance issues. Use when the user needs help choosing diagnostic tools,…
- `dump-collect`: Configure and collect crash dumps for modern .NET applications. USE FOR: enabling automatic crash dumps for CoreCLR or NativeAOT, capturing dumps from running .…
- `clr-activation-debugging`: Diagnoses .NET Framework CLR activation issues using CLR activation logs (CLRLoad logs) produced by mscoree.dll. Use when: the shim picks the wrong runtime, fai…
- `apple-crash-symbolication`: Symbolicate .NET runtime frames in Apple platform .ips crash logs (iOS, tvOS, Mac Catalyst, macOS). Extracts UUIDs and addresses from the native backtrace, loca…
- `android-tombstone-symbolication`: Symbolicate the .NET runtime frames in an Android tombstone file. Extracts BuildIds and PC offsets from the native backtrace, downloads debug symbols from the M…
- `optimizing-ef-core-queries`: Review and optimize application data access that uses Entity Framework Core (EF Core). Use for EF Core performance and correctness reviews of services, reposito…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
