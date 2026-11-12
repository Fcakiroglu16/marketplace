# Pulumi infrastructure as code

Pulumi's official skills: best practices, debugging failed `pulumi up` and preview runs, Pulumi ESC secrets and config, and migrating Terraform to Pulumi.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install pulumi-iac@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add pulumi-iac@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Infrastructure in real programming languages with Pulumi's own guidance: project and stack structure, components, debugging a failed preview or update, secrets and configuration with Pulumi ESC, and converting Terraform to Pulumi. `pulumi up` changes real infrastructure, so run it yourself after reading the preview. The Pulumi MCP server signs in with OAuth.

## Skills

- `pulumi-best-practices`: Load when the user is writing, reviewing, or debugging Pulumi TypeScript/Python programs; asks about Output<T> or apply() usage; wants to create ComponentResour…
- `pulumi-component`: Guide for authoring Pulumi ComponentResource classes. Use when creating reusable infrastructure components, designing component interfaces, setting up multi-lan…
- `pulumi-debug-failed-operation`: Debug a Pulumi update or preview that failed: read the failure Pulumi already recorded, find what caused it, and fix it. Load this skill when the user asks to d…
- `pulumi-esc`: Guidance for working with Pulumi ESC (Environments, Secrets, and Configuration). Use when users ask about managing secrets, configuration, environments, short-t…
- `pulumi-terraform-to-pulumi`: Migrate Terraform/OpenTofu projects to Pulumi, including translating HCL source code and/or importing Terraform state into a Pulumi stack. Use when a user wants…

## MCP servers

- **Pulumi**: Pulumi's official remote MCP server: registry docs for every provider, stacks, resources and Pulumi Cloud. Signs in with OAuth; use a read-only organization token if you want no changes.

All skills are copied unchanged from [pulumi/agent-skills](https://github.com/pulumi/agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
