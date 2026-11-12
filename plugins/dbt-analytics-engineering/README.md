# dbt analytics engineering

dbt Labs' official skills: build and test dbt models, add unit tests, define Semantic Layer metrics and run dbt commands the right way, with the dbt MCP server.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dbt-analytics-engineering@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dbt-analytics-engineering@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Analytics engineering with dbt Labs' own skills: model and test with dbt, write unit tests, define Semantic Layer metrics and run the right `dbt` command with the right selectors. `dbt run` and `dbt build` write to your warehouse, so point the dbt MCP server at a development target. Set `DBT_PROJECT_DIR` and `DBT_PATH`; the dbt Cloud admin API and codegen tools are switched off.

## Skills

- `using-dbt-for-analytics-engineering`: Builds and modifies dbt models, writes SQL transformations using ref() and source(), creates tests, and validates results with dbt show. Use when doing any dbt…
- `running-dbt-commands`: Formats and executes dbt CLI commands, selects the correct dbt executable, and structures command parameters. Use when running models, tests, builds, compiles,…
- `adding-dbt-unit-test`: Creates unit test YAML definitions that mock upstream model inputs and validate expected outputs. Use when adding unit tests for a dbt model or practicing test-…
- `building-dbt-semantic-layer`: Use when creating or modifying dbt Semantic Layer components — semantic models, metrics, dimensions, entities, measures, or time spines. Covers MetricFlow confi…

## MCP servers

- **dbt**: dbt Labs' official MCP server: project discovery, lineage, compile, test and run through the dbt CLI. Needs uv, DBT_PROJECT_DIR and DBT_PATH. Admin API and codegen tools are disabled.

All skills are copied unchanged from [dbt-labs/dbt-agent-skills](https://github.com/dbt-labs/dbt-agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
