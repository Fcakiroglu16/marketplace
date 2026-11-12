# Blazor web apps

Official .NET skills for Blazor: create a project, author components, forms, auth, data, prerendering and JS interop.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/blazor-web-apps

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install blazor-web-apps@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add blazor-web-apps@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Build and grow Blazor web apps with the .NET team's own skills. Playwright lets the agent open the app and check a UI change; Microsoft Learn keeps it on current APIs.

## Skills

- `create-blazor-project`: Create a new ASP.NET Core web application or web site using Blazor. USE FOR: creating a new Blazor web app, scaffolding a new web project, starting a new web si…
- `plan-ui-change`: Plan complex Blazor UI features by decomposing them into focused components. USE FOR: building a complex Blazor page with multiple sections, planning component…
- `author-component`: Create or review Blazor components (.razor files) with correct architecture. USE FOR: writing new Blazor components that do NOT involve JavaScript interop, impl…
- `coordinate-components`: Share state between components that don't have a direct parent-child parameter relationship, using cascading values, scoped services with change events, or Casc…
- `collect-user-input`: Build forms, validate data, and react to user input in Blazor. USE FOR adding forms, search boxes, filter panels, inline editing, data-entry UI, file uploads, v…
- `fetch-and-send-data`: Call APIs, load data into components, and handle the async lifecycle in Blazor. USE FOR fetching data from a backend, submitting data to an API, displaying load…
- `configure-auth`: Add authentication and authorization to a Blazor Web App, accounting for the app's render mode. USE WHEN the user needs [Authorize] on pages, AuthorizeView, rol…
- `support-prerendering`: Make interactive Blazor components work correctly with prerendering. USE FOR fixing duplicate data loads, UI flicker during prerender-to-interactive handoff, nu…
- `use-js-interop`: Add, review, or fix JavaScript interop in Blazor components. USE FOR: calling JavaScript from Blazor, calling .NET from JavaScript, collocated .razor.js modules…
- `convert-blazor-server-to-webapp`: Guides conversion of a pre-.NET 8 Blazor Server app into a .NET 8+ Blazor Web App. USE FOR: migrating apps that use AddServerSideBlazor and MapBlazorHub to the…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.
- **Playwright**: Microsoft's Playwright MCP server: drive a browser to check Blazor and web UI changes.

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
