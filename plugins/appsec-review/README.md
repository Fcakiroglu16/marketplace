# Application security review

Secure-by-default code review, threat models grounded in your repository, GitHub Actions hardening and checks for secrets leaking through logs and serialization, with GitHub code-scanning alerts.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/appsec-review

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install appsec-review@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add appsec-review@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Security work an agent can do well: review code against framework-specific secure defaults, write a threat model with trust boundaries and abuse paths from the actual repository, find pwn-request and expression-injection risks in GitHub Actions, and spot secrets leaking through repr, JSON, logs and traces. Some references quote attacker commands as examples; they are there to recognise, never to run. The GitHub code security server is read-only; set `GITHUB_PERSONAL_ACCESS_TOKEN`.

## Skills

- `security-best-practices`: Perform language and framework specific security best-practice reviews and suggest improvements. Trigger only when the user explicitly requests security best pr…
- `security-threat-model`: Repository-grounded threat modeling that enumerates trust boundaries, assets, attacker capabilities, abuse paths, and mitigations, and writes a concise Markdown…
- `gha-security-review`: GitHub Actions security review for workflow exploitation vulnerabilities. Use when asked to "review GitHub Actions", "audit workflows", "check CI security", "GH…
- `secret-serialization`: Finds secrets, tokens, passwords, and API keys that can leak through generated serialization: Python dataclass repr and asdict, attrs, pydantic model_dump, Name…
- `github-actions-hardening`: Security hardening reviewer for GitHub Actions workflow files (.github/workflows/*.yml). Reasons about the Actions threat model that pattern matchers and genera…

## MCP servers

- **GitHub code security (read-only)**: GitHub's official MCP server limited to the read-only code security toolset: code scanning and secret scanning alerts. Needs GITHUB_PERSONAL_ACCESS_TOKEN.

All skills are copied unchanged from [openai/skills](https://github.com/openai/skills) under Apache 2.0, [getsentry/skills](https://github.com/getsentry/skills) under Apache 2.0 and [github/awesome-copilot](https://github.com/github/awesome-copilot) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
