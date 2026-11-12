# Grafana, Prometheus and incidents

Grafana's official skills for PromQL, LogQL and OpenTelemetry, plus blameless postmortems, with the Grafana MCP server in read-only mode.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/grafana-observability

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install grafana-observability@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add grafana-observability@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Observability with Grafana's own skills: write PromQL and LogQL that answer the question and instrument services with OpenTelemetry. A postmortem skill turns an incident into a blameless write-up in Google SRE format. The Grafana MCP server runs with `--disable-write`, so dashboards, alerts and silences stay as they are; set `GRAFANA_URL` and `GRAFANA_SERVICE_ACCOUNT_TOKEN`.

## Skills

- `promql`: Write, validate, and optimize PromQL for Prometheus / Grafana Mimir / Grafana Cloud Metrics. Covers `rate` vs `irate` vs `increase`, label matchers and regex,…
- `loki`: Grafana Loki log aggregation and LogQL query language. Covers LogQL syntax (log queries, metric queries, label matchers, line filters, parsers: json/logfmt/patt…
- `opentelemetry`: Instrument any app with OpenTelemetry and ship metrics / logs / traces to Grafana Cloud or self-hosted Mimir / Loki / Tempo / Pyroscope. Covers SDK auto-instrum…
- `incident-postmortem`: Use when an outage, production incident, or significant service degradation has occurred and the team needs a blameless post-mortem / RCA document in the Google…

## MCP servers

- **Grafana**: Grafana's official MCP server in read-only mode with usage statistics off: search dashboards, query Prometheus and Loki, read alerts and incidents. Needs uv, GRAFANA_URL and GRAFANA_SERVICE_ACCOUNT_TOKEN.

All skills are copied unchanged from [grafana/skills](https://github.com/grafana/skills) under Apache 2.0 and [github/awesome-copilot](https://github.com/github/awesome-copilot) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
