# Idiomatic Rust

Idiomatic, safe and fast Rust: Apollo's Rust best-practices handbook and a 265-rule guide to ownership, errors, async, unsafe, API design and performance.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/rust-idiomatic

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install rust-idiomatic@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add rust-idiomatic@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Two complementary Rust guides: Apollo's engineering handbook (nine chapters, from error handling to performance) and a rule book of 265 rules in 26 categories that the agent looks up while it writes and reviews code. Context7 brings current crate documentation.

## Skills

- `rust-best-practices`: Guide for writing idiomatic Rust code based on Apollo GraphQL's best practices handbook. Use this skill when: (1) writing new Rust code or functions, (2) review…
- `rust-skills`: Comprehensive Rust coding guidelines with 265 rules across 26 categories. Use when writing, reviewing, or refactoring Rust code. Covers ownership, error handlin…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [apollographql/skills](https://github.com/apollographql/skills) under the MIT and [leonardomso/rust-skills](https://github.com/leonardomso/rust-skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
