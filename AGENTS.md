# AGENTS.md — starter_bazel

## What this is
Android starter project using Bazel build system with a simple Hello World app.

## Stack
- Java (Android)
- Bazel (build system)
- Android SDK

## Build
```bash
bazel build //src/main:app
```

## Run
Install APK on Android device or emulator.

## Structure
- `WORKSPACE` — Bazel workspace config
- `MODULE.bazel` — Bzlmod dependency management
- `src/main/` — Android source
  - `AndroidManifest.xml` — app manifest
  - `java/com/example/bazel/MainActivity.java` — main activity
  - `java/com/example/bazel/Greeter.java` — helper class
  - `java/com/example/bazel/res/` — resources (layouts, values)
  - `java/com/example/bazel/BUILD` — build targets

## Conventions
- No comments in code unless asked.
- Verify: `bazel build //src/main:app`
