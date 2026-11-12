# Android with Compose and Kotlin

Google's official Android skills (Compose performance, XML to Compose, adaptive UI, Navigation 3, edge-to-edge, testing, AGP 9, ANRs, intent security) plus JetBrains' Kotlin skills.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install android-kotlin@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add android-kotlin@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Android work the way the Android team describes it: fix recomposition jank, move XML views to Compose, adapt layouts to foldables and tablets, adopt Navigation 3 and edge-to-edge, set up tests and upgrade to AGP 9. JetBrains' skills convert Java to idiomatic Kotlin and speed up Kotlin Multiplatform builds.

## Skills

- `jetpack-compose-performance`: Diagnose and optimize Android Jetpack Compose UI code. Use this skill
- `migrate-xml-views-to-jetpack-compose`: Provides a structured workflow for migrating an Android XML View to Jetpack
- `adaptive`: Instructions to make or update an app's UI so that it adapts to different
- `navigation-3`: Learn how to install and migrate to Jetpack Navigation 3, and how to
- `edge-to-edge`: Use this skill to migrate your Jetpack Compose app to add adaptive edge-to-edge
- `testing-setup`: Analyze and create a testing strategy for Android apps - install testing
- `agp-9-upgrade`: Upgrades, or migrates, an Android project to use Android Gradle Plugin
- `anr-audit-and-fix`: Audits Android codebases for ANR risks and diagnoses ANR stack dumps.
- `android-intent-security`: Audits, detects, and remediates Android Intent and component security
- `kotlin-tooling-java-to-kotlin`: Use when converting Java source files to idiomatic Kotlin, when user mentions "java to kotlin", "j2k", "convert java", "migrate java to kotlin", or when working…
- `kotlin-tooling-agp9-migration`: Migrates Kotlin Multiplatform (KMP) projects to Android Gradle Plugin 9.0+. Handles plugin replacement (com.android.kotlin.multiplatform.library), module splitt…
- `kotlin-tooling-native-build-performance`: Diagnoses and fixes slow Kotlin/Native compilation and linking in Kotlin Multiplatform projects that target iOS. Use when the user reports slow iOS or shared-fr…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [android/skills](https://github.com/android/skills) under Apache 2.0 and [Kotlin/kotlin-agent-skills](https://github.com/Kotlin/kotlin-agent-skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
