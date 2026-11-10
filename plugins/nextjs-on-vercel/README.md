# Next.js on Vercel

Build Next.js apps with Vercel's React rules and the Next.js DevTools MCP server, then inspect and optimize them on Vercel with the Vercel MCP server.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install nextjs-on-vercel@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add nextjs-on-vercel@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

From local dev to production: Next.js DevTools reads errors and routes from your running dev server, and the Vercel MCP server and the vercel-optimize skill read deployments, logs and usage. vercel-optimize may run `vercel link`, which links the folder to a Vercel project.

## Skills

- `vercel-react-best-practices`: React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, reviewing, or refactoring React/Next.js c…
- `vercel-optimize`: Use for Vercel cost and performance optimization on deployed projects, especially Next.js, SvelteKit, Nuxt, and limited Astro apps. Collect Vercel metrics, usag…

## MCP servers

- **Next.js DevTools**: Vercel's official Next.js DevTools MCP server: runtime errors, routes and logs of a running Next.js dev server, plus Next.js docs.
- **Vercel**: Vercel's official remote MCP server: projects, deployments and logs. Signs in with your Vercel account (OAuth).

All skills are copied unchanged from [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
