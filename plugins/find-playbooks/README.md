# Find playbooks

Lets your agent search PlaybookRun for a reviewed playbook that fits the task and gives the install command for your tool.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/find-playbooks

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install find-playbooks@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add find-playbooks@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Install this once and ask your agent things like "is there a playbook for Postgres indexing?" or "what should I install for .NET testing?". The skill searches PlaybookRun's public catalog, shows the best matches with their pages, and gives the install commands for Claude Code, Codex or Copilot CLI.

It installs nothing on its own: it shows the commands first and runs them only when you ask.

## Skills

- `find-playbooks`: searches the catalog through `https://playbookrun.com/api/public/search` (no account, no key) and explains the results.

Written and maintained by PlaybookRun.
