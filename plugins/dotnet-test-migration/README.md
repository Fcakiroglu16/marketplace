# .NET test migration

Official skills to move test projects: MSTest v1/v2 to v3 to v4, NUnit or xUnit to MSTest, xUnit v3, VSTest to Microsoft.Testing.Platform.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dotnet-test-migration@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dotnet-test-migration@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Upgrade or switch test frameworks one step at a time, then run the suite to prove nothing broke. NuGet finds the right package versions.

## Skills

- `migrate-mstest-v1v2-to-v3`: Use this skill before answering or editing whenever an MSTest v1/v2 project is being upgraded or repaired for v3. Triggers include QualityTools assembly referen…
- `migrate-mstest-v3-to-v4`: Use this skill before answering, planning, or editing any MSTest 3.x-to-4.x upgrade or post-upgrade failure. Triggers include "MSTest v4 breaking changes"; CS05…
- `migrate-nunit-to-mstest`: Convert .NET tests from NUnit 3/4 to MSTest v4 while preserving VSTest or MTP. Use for replacing NUnit/NUnit3TestAdapter packages, Test/TestCase/ TestCaseSource…
- `migrate-xunit-to-mstest`: Convert .NET tests from xUnit.net v2/v3 to MSTest v4 while preserving VSTest or MTP. Use for replacing xunit packages, Fact/Theory/InlineData/MemberData, assert…
- `migrate-xunit-to-xunit-v3`: Migrate .NET test projects from xUnit.net v2 to xunit.v3 and fix v3 breaks. Use for package/CPM conversion, OutputType=Exe, preserving the VSTest or MTP runner…
- `migrate-vstest-to-mtp`: Use this skill before answering, planning, or editing whenever .NET tests or CI are switching from VSTest to Microsoft.Testing.Platform (MTP), or an MTP migrati…
- `run-tests`: ALWAYS USE before running .NET tests or answering with a test command or flags. Trigger on "run the tests", "exact dotnet test command", one test/class/category…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.
- **NuGet**: Official NuGet MCP server: package search, versions, vulnerabilities and updates. Needs the .NET 10 SDK (dnx).

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
