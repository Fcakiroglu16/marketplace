# .NET MAUI apps

Official .NET MAUI skills: environment doctor, Shell navigation, data binding, CollectionView, DI, theming, safe areas and lifecycle.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install dotnet-maui@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add dotnet-maui@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Build cross-platform apps with .NET MAUI: get the workloads right first, then follow the .NET team's patterns for navigation, binding and lists.

## Skills

- `dotnet-maui-doctor`: Diagnoses and fixes .NET MAUI development environment issues. Validates .NET SDK, workloads, Java JDK, Android SDK, Xcode, and Windows SDK. All version requirem…
- `maui-shell-navigation`: Guide for implementing Shell-based navigation in .NET MAUI apps. Covers AppShell setup, visual hierarchy (FlyoutItem, TabBar, Tab, ShellContent), URI-based navi…
- `maui-data-binding`: Guidance for .NET MAUI XAML and C# data bindings — compiled bindings, INotifyPropertyChanged / ObservableObject, value converters, binding modes, multi-binding,…
- `maui-collectionview`: Guidance for implementing CollectionView in .NET MAUI apps — data display, layouts (list & grid), selection, grouping, scrolling, empty views, templates, increm…
- `maui-dependency-injection`: Guidance for configuring dependency injection in .NET MAUI apps — service registration in MauiProgram.cs, lifetime selection (Singleton / Transient / Scoped), c…
- `maui-theming`: Guide for theming .NET MAUI apps — light/dark mode via AppThemeBinding, ResourceDictionary theme switching, DynamicResource bindings, system theme detection, an…
- `maui-safe-area`: .NET MAUI safe area and edge-to-edge layout guidance for .NET 10+. Covers the new SafeAreaEdges property, SafeAreaRegions enum, per-edge control, keyboard avoid…
- `maui-app-lifecycle`: .NET MAUI app lifecycle guidance — the four app states, cross-platform Window lifecycle events (Created, Activated, Deactivated, Stopped, Resumed, Destroying),…
- `apple-crash-symbolication`: Symbolicate .NET runtime frames in Apple platform .ips crash logs (iOS, tvOS, Mac Catalyst, macOS). Extracts UUIDs and addresses from the native backtrace, loca…
- `android-tombstone-symbolication`: Symbolicate the .NET runtime frames in an Android tombstone file. Extracts BuildIds and PC offsets from the native backtrace, downloads debug symbols from the M…

## MCP servers

- **Microsoft Learn**: Official Microsoft Learn MCP server: search and fetch current Microsoft and .NET documentation and code samples.

All skills are copied unchanged from [dotnet/skills](https://github.com/dotnet/skills) under the MIT License; each skill folder includes `LICENSE` and `SOURCE.md` with the source commit.
