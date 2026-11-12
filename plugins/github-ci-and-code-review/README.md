# GitHub CI and code review

Fix failing GitHub Actions checks, work through PR review comments, cut CI minutes, review branches for bugs and write conventional commits, with the read-only GitHub MCP server.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/github-ci-and-code-review

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install github-ci-and-code-review@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add github-ci-and-code-review@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

The pull request loop: find out whether a red check is your change, fix failing GitHub Actions jobs, answer review comments, audit workflows for wasted minutes, review a branch for bugs and security problems before merge, and write conventional commits. The CI skills plan first and change code after you agree. The GitHub MCP server uses the read-only endpoint; set `GITHUB_PERSONAL_ACCESS_TOKEN`.

## Skills

- `gh-fix-ci`: Use when a user asks to debug or fix failing GitHub PR checks that run in GitHub Actions; use `gh` to inspect checks and logs, summarize failure context, draft…
- `gh-address-comments`: Help address review/issue comments on the open GitHub PR for the current branch using gh CLI; verify gh auth first and prompt the user to authenticate if not lo…
- `diagnose-ci-gate`: Determine whether a failing CI check was caused by the current change, then recommend exactly one action. Use when a required check fails on a pull request, whe…
- `github-actions-efficiency`: Audit GitHub Actions workflow efficiency and recommend fixes to reduce CI minutes and costs.
- `code-review`: Perform code reviews following Sentry engineering practices. Use when reviewing pull requests, examining code changes, or providing feedback on code quality. Co…
- `find-bugs`: Find bugs, security vulnerabilities, and code quality issues in local branch changes. Use when asked to review changes, find bugs, security review, or audit cod…
- `commit`: Use for every request to commit changes or draft a commit message. Creates Sentry-style conventional commits with issue references.

## MCP servers

- **GitHub (read-only)**: GitHub's official remote MCP server on its read-only endpoint: repositories, issues, pull requests, Actions runs and logs. Needs GITHUB_PERSONAL_ACCESS_TOKEN.

All skills are copied unchanged from [openai/skills](https://github.com/openai/skills) under Apache 2.0, [github/awesome-copilot](https://github.com/github/awesome-copilot) under the MIT and [getsentry/skills](https://github.com/getsentry/skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
