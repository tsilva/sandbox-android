# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands

```bash
# Build debug APK
./gradlew assembleDebug

# Build release APK
./gradlew assembleRelease

# Clean build
./gradlew clean

# Install debug APK on connected device/emulator
./gradlew installDebug

# Run all checks (lint, etc.)
./gradlew check
```

## Project Architecture

This is a minimal Android application using:
- **Kotlin** with JVM target 17
- **Gradle Kotlin DSL** for build configuration
- **AndroidX** libraries (AppCompat, ConstraintLayout, Material)
- **Min SDK 24** / **Target SDK 31**

### Structure
- `app/` - Main application module
  - `src/main/java/com/example/helloworld/` - Kotlin source code
  - `src/main/res/` - Android resources (layouts, values, etc.)
  - `src/main/AndroidManifest.xml` - App manifest
- Root `build.gradle.kts` - Plugin versions (Android 8.1.0, Kotlin 1.9.0)
- `app/build.gradle.kts` - App dependencies and configuration
