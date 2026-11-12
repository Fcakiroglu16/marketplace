# Terraform infrastructure as code

HashiCorp's official skills to write, test and refactor Terraform in HashiCorp style, with live provider and module docs from the Terraform MCP server.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/terraform-iac

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install terraform-iac@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add terraform-iac@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Terraform from HashiCorp: HCL in the official style, `.tftest.hcl` tests with mocks and splitting a monolithic configuration into modules. `terraform test` in apply mode creates real resources, and a refactor ends with `terraform apply`, so read the plan and approve each of those yourself. The Terraform MCP server (Docker) reads provider, module and policy docs from the public Registry and needs no account.

## Skills

- `terraform-style-guide`: Generate Terraform HCL code following HashiCorp's official style conventions and best practices. Use when writing, reviewing, or generating Terraform configurat…
- `terraform-test`: Comprehensive guide for writing and running Terraform tests. Use when creating test files (.tftest.hcl), writing test scenarios with run blocks, validating infr…
- `refactor-module`: Transform monolithic Terraform configurations into reusable, maintainable modules following HashiCorp's module design principles and community best practices.

## MCP servers

- **Terraform**: HashiCorp's official Terraform MCP server with the Registry toolset: provider, module and policy documentation. Read-only; needs Docker.

All skills are copied unchanged from [hashicorp/agent-skills](https://github.com/hashicorp/agent-skills) under MPL 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
