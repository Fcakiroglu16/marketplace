# Deploy .NET to Azure

Official Azure skills with the Azure MCP server: prepare, validate and deploy an app, instrument it with App Insights and diagnose it.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/azure-for-dotnet

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install azure-for-dotnet@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add azure-for-dotnet@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Take a .NET or Aspire app to Azure with Microsoft's own skills: the Azure MCP server works against your subscription with your Azure CLI login.

## Skills

- `azure-prepare`: Prepare azd-based Azure projects for deployment: generates azure.yaml, infrastructure (Bicep/Terraform), and Dockerfiles for the Azure Developer CLI (azd) workf…
- `azure-validate`: Pre-deployment validation for Azure readiness. Run deep checks on configuration, infrastructure (Bicep or Terraform), RBAC role assignments, managed identity pe…
- `azure-deploy`: Execute Azure deployments for ALREADY-PREPARED applications that have existing .azure/deployment-plan.md and infrastructure files. DO NOT use this skill when th…
- `azure-diagnostics`: Debug Azure production issues using AppLens, Azure Monitor, resource health, and safe triage, including evidence-only diagnosis without live access. WHEN: debug…
- `appinsights-instrumentation`: Guidance for instrumenting webapps with Azure Application Insights. Provides telemetry patterns, SDK setup, and configuration references. WHEN: how to instrumen…
- `azure-resource-lookup`: List, find, and show Azure resources across subscriptions or resource groups. Handles prompts like "list the websites in my subscription", "list my web apps", "…
- `azure-storage`: Azure Storage Services including Blob Storage, File Shares, Queue Storage, Table Storage, and Data Lake. Answers questions about storage access tiers (hot, cool…
- `azure-messaging`: Troubleshoot and resolve issues with Azure Messaging SDKs for Event Hubs and Service Bus. Covers connection failures, authentication errors, message processing…
- `entra-app-registration`: Guides Microsoft Entra ID app registration, OAuth 2.0 authentication, and MSAL integration. USE FOR: create app registration, register Azure AD app, configure O…
- `aspire-deployment`: **WORKFLOW SKILL** — Deploy Aspire apps from AppHost models to Docker Compose, Kubernetes, Azure, AWS, or preview Radius. WHEN: "deploy Aspire app", "publish As…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.
- **Azure**: Official Azure MCP server (pinned as in microsoft/azure-skills): Azure resources, deployment and diagnostics. Signs in with your Azure CLI login.

All skills are copied unchanged from [microsoft/aspire-skills](https://github.com/microsoft/aspire-skills), [microsoft/azure-skills](https://github.com/microsoft/azure-skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
