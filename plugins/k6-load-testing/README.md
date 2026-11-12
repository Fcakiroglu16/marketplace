# k6 load testing

Grafana's official k6 skills: write load and browser tests for a website or API and keep test scripts maintainable.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install k6-load-testing@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add k6-load-testing@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Performance testing with k6 from Grafana: design a load test for a website or API with sensible stages and thresholds, write browser tests with the k6 browser module and keep a growing suite of scripts maintainable. Load tests send real traffic, so point them only at systems you own, and keep recorded HAR files (they can hold cookies and tokens) out of git.

## Skills

- `k6-perf-test-website`: Use when the user wants to performance-test, load-test, or stress-test a public website end-to-end with k6. Produces a hybrid (protocol + browser) test suite, S…
- `k6-browser-test`: Generate a working k6 browser test (k6/browser) from a plain-language description of a user journey — no CSS selectors or technical detail needed. Explores the…
- `k6-test-maintenance`: Maintain and improve existing k6 test scripts. Covers threshold tightening based on trend data, version migration between k6 releases, auto-fixing tests when th…

All skills are copied unchanged from [grafana/skills](https://github.com/grafana/skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
