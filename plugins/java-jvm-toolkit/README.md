# Java and Gradle toolkit

Modern Java day to day, JDK upgrades from 11 to 25, javax to jakarta, JVM diagnostics and debugging, plus Gradle's official build audit and wrapper upgrade.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/java-jvm-toolkit

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install java-jvm-toolkit@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add java-jvm-toolkit@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

For plain Java projects and the JVM underneath them: modern idioms, a guided JDK upgrade one version step at a time, the javax-to-jakarta move, and runtime diagnostics with jcmd, JFR and GC logs. Gradle's own skills audit a build against the official best practices and upgrade the wrapper.

## Skills

- `java-development`: Day-to-day plain Java development without a framework: Maven and Gradle usage and wrappers, project layout, dependency and vulnerability management, modern Java…
- `java-upgrade`: Upgrade a Java project to a newer JDK (11 to 17, 17 to 21, 21 to 25) and adopt the new language and library features. Detects the current Java version from the…
- `javax-to-jakarta-migration`: Migrate Java code from javax.* to jakarta.* namespace. Use only when the user explicitly asks for a javax to jakarta namespace or framework migration (for examp…
- `java-diagnostics`: Symptom-first runtime diagnostics for JVM applications using JDK tools: jcmd, jstack, jmap, jstat, JFR, GC logs, async-profiler, Native Memory Tracking, and Ecl…
- `java-debugging`: Debug Java applications systematically: JDWP remote debugging, jdb, VS Code and IntelliJ attach, debugging Maven/Gradle tests, Spring Boot and Quarkus dev mode,…
- `gradle-best-practices`: Audit a Gradle project against the official Gradle best practices, report findings, and propose code changes to bring the build into compliance. Use this skill…
- `gradle-wrapper-upgrade`: Use whenever the user asks to upgrade, bump, or update the Gradle wrapper, `gradlew`, `distributionUrl`, `gradle-wrapper.properties`, or the build's Gradle vers…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [github/awesome-copilot](https://github.com/github/awesome-copilot) under the MIT and [gradle/gradle-skills](https://github.com/gradle/gradle-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
