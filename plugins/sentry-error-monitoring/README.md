# Sentry error monitoring

Sentry's official skills to find, root-cause and fix production errors, set up releases and source maps and instrument apps, with the Sentry MCP server.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install sentry-error-monitoring@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add sentry-error-monitoring@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

From a Sentry issue to a fix: pick the issue, read the stack trace, trace and logs, fix the code and close it with a `Fixes` commit. Other skills add release and deploy tracking to CI, upload source maps and debug files and instrument an app for errors, traces and logs. Resolving an issue writes to your Sentry organization, so the agent confirms which issue first. The Sentry MCP server signs in with OAuth.

## Skills

- `sentry-debug-issue`: Debug and fix a Sentry issue — find it (by link, ID, or search), pull full context (stack trace, breadcrumbs, trace, logs), optionally run Seer root-cause / aut…
- `sentry-setup-releases`: Set up Sentry releases and deploy tracking — tag events with a version and environment, create the release in CI with its commits, and wire up suspect commits a…
- `sentry-fix-stack-traces`: Make Sentry stack traces readable — upload source maps for JavaScript/TypeScript, or debug files for native and mobile (dSYM, ProGuard/R8, NDK symbols, Dart obf…
- `sentry-instrument`: Instrument an application with Sentry — detect the platform, install and initialize the SDK if needed, and wire up any signal — error monitoring, tracing/perfor…

## MCP servers

- **Sentry**: Sentry's official remote MCP server: issues, events, traces, releases and Seer analysis for your organization. Signs in with OAuth.

All skills are copied unchanged from [getsentry/agent-plugin](https://github.com/getsentry/agent-plugin) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
