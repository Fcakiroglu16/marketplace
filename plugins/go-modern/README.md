# Modern Go

Idiomatic Go for your Go version: JetBrains' modern Go guidelines plus skills for errors, concurrency, context, testing, security, linting and naming, with the gopls MCP server.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install go-modern@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add go-modern@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Go code that uses what your Go version offers, not what tutorials from 2016 taught: JetBrains' guidelines pick advice by version, and the community skills cover error wrapping, goroutines and errgroup, context, table tests and fuzzing, gosec and govulncheck, and golangci-lint. gopls answers with real symbol and package information; it must be installed (`go install golang.org/x/tools/gopls@latest`).

## Skills

- `use-modern-go`: Use the Modern Go Guidelines CLI whenever writing, modifying, fixing, or refactoring Go code. Apply its version-specific guidance to generated changes.
- `golang-error-handling`: Idiomatic Golang error handling — creation, wrapping with %w, errors.Is/As, errors.Join, custom error types, sentinel errors, panic/recover, the single handling…
- `golang-concurrency`: Golang concurrency design — goroutine lifecycle and leak prevention, channels and `select`, channel ownership and direction, `sync.Mutex`/`RWMutex`/`sync.Map`/`…
- `golang-context`: Idiomatic context.Context usage in Golang — propagation through API boundaries, cancellation, timeouts and deadlines, request-scoped values, context.WithoutCanc…
- `golang-testing`: Production-ready Golang tests — table-driven tests, testify suites and mocks, parallel tests, fuzzing, fixtures, goroutine leak detection with goleak, snapshot…
- `golang-security`: Security best practices and vulnerability prevention for Golang — injection (SQL, command, XSS), cryptography, path traversal, SSRF and HTTP security headers, c…
- `golang-modernize`: Modernize Golang code to use recent language features, standard library improvements, and idiomatic patterns. Use when reviewing Go code with old-style patterns…
- `golang-lint`: Linting best practices and golangci-lint configuration for Golang projects — running linters, configuring .golangci.yml, suppressing warnings with nolint direct…
- `golang-code-style`: Golang code style conventions — line length and breaking, variable declarations, control flow clarity, when comments help vs hurt. Use when writing or reviewing…
- `golang-naming`: Go (Golang) naming conventions — covers packages, constructors, structs, interfaces, constants, enums, errors, booleans, receivers, getters/setters, functional…

## MCP servers

- **gopls**: The Go team's language server in MCP mode: workspace, package and symbol information, diagnostics and references. Needs gopls v0.20 or later on the PATH.
- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines) under Apache 2.0 and [samber/cc-skills-golang](https://github.com/samber/cc-skills-golang) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
