# Quarkus

Create, test and ship Quarkus apps with Dev Services, native images and containers, migrate Spring Boot to Quarkus and keep versions current, with the official Quarkus agent MCP.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install quarkus@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add quarkus@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Quarkus from the first `quarkus create` to a native image: REST, CDI, Panache and Mutiny, `@QuarkusTest` with Dev Services, and Mandrel/GraalVM builds for Kubernetes. The Quarkus team's own skills migrate a Spring Boot app module by module and keep a project on current Quarkus.

## Skills

- `migrate-spring-to-quarkus`: Migrates Spring Boot applications to Quarkus using a modular, gate-driven approach.
- `quarkus-update`: Use when working in a Quarkus project and the user wants to check if their build files are up-to-date, compare project structure against a reference, or upgrade…
- `create-quarkus-project`: Create a new Quarkus project (Maven or Gradle) with the Quarkus CLI, code.quarkus.io API or Maven plugin, choose extensions, and run it in dev mode. Use when as…
- `quarkus-application-development`: Write Quarkus application code: REST with Quarkus REST, validation, exception mappers, OpenAPI, configuration, CDI (ArC), Hibernate ORM with Panache, Mutiny and…
- `quarkus-dev-services-and-testing`: Quarkus Dev Services and testing: zero-config containers, @QuarkusTest, @QuarkusIntegrationTest, test resources, RestAssured, @InjectMock, profiles and continuo…
- `quarkus-native-and-container`: Build Quarkus native executables (Mandrel/GraalVM), fix native failures with reflection registration, test the native binary, and produce container images and K…

## MCP servers

- **Quarkus Agent**: The Quarkus team's agent MCP server: Quarkus docs, extensions and project tooling. Needs JBang and a JDK on the PATH.
- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [quarkusio/skills](https://github.com/quarkusio/skills) under Apache 2.0 and [github/awesome-copilot](https://github.com/github/awesome-copilot) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
