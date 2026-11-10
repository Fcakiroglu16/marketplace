# Frontend design and UI polish

Anthropic's frontend-design skill with Vercel's web interface guidelines, Figma's MCP server for designs and Chrome DevTools for review.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install frontend-design@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add frontend-design@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Turn a Figma design or a rough idea into a distinctive, accessible interface, then review it against Vercel's web interface guidelines in a real browser.

## Skills

- `frontend-design`: Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthetic direction, typography, and making ch…
- `web-design-guidelines`: Review UI code for Web Interface Guidelines compliance. Use when asked to "review my UI", "check accessibility", "audit design", "review UX", or "check my site…
- `writing-guidelines`: Review docs/prose for Writing Guidelines compliance. Use when asked to "review my docs", "check writing style", "audit prose", "review docs voice and tone", or…

## MCP servers

- **Chrome DevTools**: Google's official Chrome DevTools MCP server: open pages, read the console and network, take screenshots and record performance traces.
- **Figma**: Figma's official remote MCP server: read frames, components and variables from a Figma file to build them in code. Signs in with Figma (OAuth).

All skills are copied unchanged from [anthropics/skills](https://github.com/anthropics/skills), [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) under the Apache License 2.0 and MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
