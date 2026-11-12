# Spring Boot (Java)

Build, test, secure and observe Spring Boot 3 and 4 services, migrate 3.x to 4 and scaffold new projects, with Context7 for current Spring docs.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/spring-boot-java

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install spring-boot-java@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add spring-boot-java@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Write Spring Boot code the way current Spring does it: REST with ProblemDetail, Spring Data, RestClient, test slices with Testcontainers, a SecurityFilterChain, Actuator and Micrometer. One skill moves a 3.x app to Boot 4 (Spring Framework 7, Jackson 3). Context7 serves up-to-date Spring documentation.

## Skills

- `java-springboot`: Write and review application code in an existing Spring Boot 3/4 project: controllers, validation and ProblemDetail errors, Spring Data JPA/JDBC, RestClient and…
- `spring-boot-testing`: Expert Spring Boot testing specialist that selects the best testing techniques for your situation: test slices, Testcontainers with @ServiceConnection, Failsafe…
- `spring-security`: Configure, test and review Spring Security 6/7 in Spring Boot 3/4 apps: SecurityFilterChain lambda DSL, method security, OAuth2 resource server with JWT, OIDC l…
- `spring-observability`: Add and review observability in Spring Boot 3/4 apps: Actuator exposure and health probes, Micrometer metrics, Observation API, OpenTelemetry tracing and OTLP/P…
- `spring-boot-4-migration`: Migrate a Spring Boot 3.x application to Spring Boot 4.0 (Spring Framework 7, Jackson 3, modular starters, JSpecify). Use only for an explicit Boot 3.x to 4 mig…
- `create-spring-boot-java-project`: Create a new Spring Boot Java project (Maven or Gradle) from start.spring.io with sensible defaults for configuration, PostgreSQL, logging, security, testing an…
- `java-testcontainers`: Write reliable integration tests in plain Java with Testcontainers 2.x: JUnit Jupiter lifecycle, singleton containers, reuse, generic containers, wait strategie…
- `java-junit`: Write, review and fix Java unit tests with JUnit 5 and JUnit 6 (Jupiter), AssertJ and Mockito: assertions, parameterized and nested tests, mocking rules, determ…
- `java-hibernate-jpa`: Diagnose and fix Hibernate ORM / Jakarta Persistence problems in plain Java: N+1 queries, lazy loading errors, identifier generation, entity equals/hashCode, ca…
- `kotlin-backend-jpa-entity-mapping`: Model Kotlin persistence code correctly for Spring Data JPA and Hibernate. Covers entity design, identity and equality, uniqueness constraints, relationships, f…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [github/awesome-copilot](https://github.com/github/awesome-copilot) under the MIT and [Kotlin/kotlin-agent-skills](https://github.com/Kotlin/kotlin-agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
