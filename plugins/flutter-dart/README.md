# Flutter and Dart

The Flutter and Dart teams' skills for architecture, responsive layout, layout errors, widget and integration tests, routing, JSON, localization and static analysis, with the Dart MCP server.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/flutter-dart

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install flutter-dart@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add flutter-dart@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Flutter apps built the way the Flutter team recommends: layered architecture, responsive layouts, fixes for overflow and unbounded constraints, widget and integration tests, go_router, JSON serialization and localization. The Dart team's skills run static analysis, write unit tests, fix runtime errors and untangle `pub get` conflicts. The Dart MCP server needs Dart SDK 3.9 or later.

## Skills

- `flutter-apply-architecture-best-practices`: Architects a Flutter application using the recommended layered approach (UI, Logic, Data). Use when structuring a new project or refactoring for scalability.
- `flutter-build-responsive-layout`: Use `LayoutBuilder`, `MediaQuery`, or `Expanded/Flexible` to create a layout that adapts to different screen sizes. Use when you need the UI to look good on bot…
- `flutter-fix-layout-issues`: Fixes Flutter layout errors (overflows, unbounded constraints) using Dart and Flutter MCP tools. Use when addressing "RenderFlex overflowed", "Vertical viewport…
- `flutter-add-widget-test`: Implement a component-level test using `WidgetTester` to verify UI rendering and user interactions (tapping, scrolling, entering text). Use when validating that…
- `flutter-add-integration-test`: Configures Flutter Driver for app interaction and converts MCP actions into permanent integration tests. Use when adding integration testing to a project, explo…
- `flutter-setup-declarative-routing`: Configure `MaterialApp.router` using a package like `go_router` for advanced URL-based navigation. Use when developing web applications or mobile apps that requ…
- `flutter-implement-json-serialization`: Create model classes with `fromJson` and `toJson` methods using `dart:convert`. Use when manually mapping JSON keys to class properties for simple data structur…
- `flutter-setup-localization`: Add `flutter_localizations` and `intl` dependencies, enable "generate true" in `pubspec.yaml`, and create an `l10n.yaml` configuration file. Use when initializi…
- `dart-run-static-analysis`: Execute `dart analyze` to identify warnings and errors, and use `dart fix --apply` to automatically resolve mechanical lint issues. Use during development to en…
- `dart-add-unit-test`: Write and organize unit tests for functions, methods, and classes using `package:test`. Use when creating new logic or fixing bugs to ensure code remains correc…
- `dart-fix-runtime-errors`: Uses get_runtime_errors and lsp to fetch an active stack trace, locate the failing line, apply a fix, and verify resolution via hot_reload.
- `dart-resolve-package-conflicts`: Workflow for fixing package version conflicts. Use this when `pub get` fails due to incompatible package versions.

## MCP servers

- **Dart and Flutter**: The Dart team's MCP server: analyze and fix code, run tests, search pub.dev, and inspect and hot reload a running Flutter app. Needs Dart SDK 3.9 or later.

All skills are copied unchanged from [flutter/agent-plugins](https://github.com/flutter/agent-plugins) under BSD 3-Clause and [dart-lang/skills](https://github.com/dart-lang/skills) under BSD 3-Clause; each skill folder includes its licence and `SOURCE.md` with the source commit.
