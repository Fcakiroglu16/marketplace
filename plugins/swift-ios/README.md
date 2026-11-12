# Swift and SwiftUI

Paul Hudson's SwiftUI, SwiftData, Swift Testing and Swift Concurrency skills, plus MobileBuildMCP to build, run, test and debug on simulators.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/swift-ios

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install swift-ios@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add swift-ios@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Swift code that uses current Apple APIs: SwiftUI views, navigation, performance and accessibility, SwiftData models and predicates, Swift Testing instead of XCTest, and structured concurrency without data races, all written by Paul Hudson (Hacking with Swift). MobileBuildMCP builds, runs and tests on simulators and reads logs; it needs macOS and Xcode.

## Skills

- `swiftui-pro`: Comprehensively reviews SwiftUI code for best practices on modern APIs, maintainability, and performance. Use when reading, writing, or reviewing SwiftUI projec…
- `swiftdata-pro`: Writes, reviews, and improves SwiftData code using modern APIs and best practices. Use when reading, writing, or reviewing projects that use SwiftData.
- `swift-testing-pro`: Writes, reviews, and improves Swift Testing code using modern APIs and best practices. Use when reading, writing, or reviewing projects that use Swift Testing.
- `swift-concurrency-pro`: Reviews Swift code for concurrency correctness, modern API usage, and common async/await pitfalls. Use when reading, writing, or reviewing Swift concurrency cod…
- `mobilebuildmcp`: Official skill for MobileBuildMCP. Use when doing iOS/macOS/watchOS/tvOS/visionOS work (build, test, run, debug, log, UI automation).

## MCP servers

- **MobileBuildMCP**: Sentry's MobileBuildMCP (formerly XcodeBuildMCP): build, run and test Xcode projects on simulators and devices, read logs and drive the UI. Needs macOS and Xcode; sends crash telemetry to Sentry unless you opt out.

All skills are copied unchanged from [twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill) under the MIT, [twostraws/SwiftData-Agent-Skill](https://github.com/twostraws/SwiftData-Agent-Skill) under the MIT, [twostraws/Swift-Testing-Agent-Skill](https://github.com/twostraws/Swift-Testing-Agent-Skill) under the MIT, [twostraws/Swift-Concurrency-Agent-Skill](https://github.com/twostraws/Swift-Concurrency-Agent-Skill) under the MIT and [getsentry/MobileBuildMCP](https://github.com/getsentry/MobileBuildMCP) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
