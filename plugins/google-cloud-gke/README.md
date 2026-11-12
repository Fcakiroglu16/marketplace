# Google Cloud and GKE

Google's official skills to use gcloud safely, troubleshoot GKE workloads, write secure Kubernetes manifests and Cloud Logging queries, with the gcloud MCP server.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install google-cloud-gke@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add google-cloud-gke@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Google Cloud from Google's own skills: gcloud with a denylist for dangerous commands, diagnosing CrashLoopBackOff and OOMKilled pods on GKE, production-ready Kubernetes manifests and Logging Query Language from plain language. The gcloud skill passes `--quiet`, which skips gcloud's own prompts, so approve every command that changes your project. These skills add an agent-skills attribution tag to the gcloud commands they run (usage telemetry for Google, not added to generated code); ask the agent to leave it out if you prefer. The gcloud MCP server uses your local `gcloud auth`.

## Skills

- `gcloud`: Provides safety-critical validation, guardrails, and data reduction for gcloud CLI operations across Google Cloud Platform (GCP) services and infrastructure. Us…
- `gke-workload-troubleshooting`: Diagnoses GKE workload failures (CrashLoopBackOff, OOMKilled, ImagePullBackOff, Pending, etc.) via logs and events. Use when pods fail to start or crash repeate…
- `gke-manifest-generation`: Generates and updates secure, production-ready Kubernetes YAML manifests optimized for GKE Autopilot and GKE Standard clusters. Use when creating or modifying G…
- `cloud-logging-query-generation`: Generates Logging Query Language (LQL) queries for Cloud Logging on Google Cloud from natural language. Use this skill when you need to query log data or when y…

## MCP servers

- **gcloud**: Google's official gcloud MCP server: runs gcloud CLI commands with your local credentials, with a built-in denylist for dangerous commands. Needs the gcloud CLI.

All skills are copied unchanged from [google/skills](https://github.com/google/skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
