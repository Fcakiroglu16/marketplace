# React apps

Vercel's official React skills: performance rules, component composition and view transitions, with shadcn/ui components and Chrome DevTools.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/react-apps

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install react-apps@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add react-apps@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Write fast, well-composed React with the rules Vercel uses: waterfalls, bundle size, re-renders and composition. shadcn/ui adds components from its registry; Chrome DevTools checks the result in a real browser.

## Skills

- `vercel-react-best-practices`: React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, reviewing, or refactoring React/Next.js c…
- `vercel-composition-patterns`: 
- `vercel-react-view-transitions`: Guide for implementing smooth, native-feeling animations using React's View Transition API (`<ViewTransition>` component, `addTransitionType`, and CSS view tran…

## MCP servers

- **Chrome DevTools**: Google's official Chrome DevTools MCP server: open pages, read the console and network, take screenshots and record performance traces.
- **shadcn/ui**: The official shadcn/ui MCP server: browse, search and add components from shadcn registries to the project.

All skills are copied unchanged from [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
