# Web UI testing

Anthropic's webapp-testing skill with Playwright and Chrome DevTools MCP servers: drive the app, check behaviour, capture screenshots and logs.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install web-ui-testing@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add web-ui-testing@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Test a local web app like a user would: start it, click through with Playwright, and read the console, network and screenshots when something breaks.

## Skills

- `webapp-testing`: Toolkit for interacting with and testing local web applications using Playwright. Supports verifying frontend functionality, debugging UI behavior, capturing br…

## MCP servers

- **Chrome DevTools**: Google's official Chrome DevTools MCP server: open pages, read the console and network, take screenshots and record performance traces.
- **Playwright**: Microsoft's Playwright MCP server: drive a browser to check Blazor and web UI changes.

All skills are copied unchanged from [anthropics/skills](https://github.com/anthropics/skills) under the Apache License 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
