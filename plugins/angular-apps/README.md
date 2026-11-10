# Angular apps

The Angular team's official skills and CLI MCP server: new apps with current defaults, signals, forms, routing, SSR, testing and CLI.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install angular-apps@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add angular-apps@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Write Angular the way the Angular team recommends for the version you have installed. The CLI's MCP server answers from your workspace and the docs for that version; Chrome DevTools lets the agent see the running app.

## Skills

- `angular-new-app`: Creates a new Angular app using the Angular CLI. This skill should be used whenever a user wants to create a new Angular application and contains important guid…
- `angular-developer`: Generates Angular code and provides architectural guidance. Trigger when creating projects, components, services, or HTTP communication, or for best practices o…

## MCP servers

- **Angular CLI**: The Angular CLI's official MCP server: workspace and project info, best practices for the installed version, docs search and examples.
- **Chrome DevTools**: Google's official Chrome DevTools MCP server: open pages, read the console and network, take screenshots and record performance traces.

All skills are copied unchanged from [angular/skills](https://github.com/angular/skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
