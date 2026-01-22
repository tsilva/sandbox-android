<div align="center">
  <img src="logo.png" alt="sandbox-android" width="512"/>

  **🤖 Minimal Android sandbox for experimenting with Kotlin and Gradle builds**

</div>

## Overview

A minimal Android application template using Kotlin and Gradle Kotlin DSL. Perfect for quickly testing Android concepts, exploring new APIs, or prototyping features.

## Features

- **Kotlin-first** - Modern Kotlin with JVM target 17
- **Gradle Kotlin DSL** - Type-safe build configuration
- **AndroidX** - AppCompat, ConstraintLayout, Material components
- **Minimal setup** - Ready to build and run immediately

## Quick Start

```bash
# Clone the repository
git clone https://github.com/tsilva/sandbox-android.git
cd sandbox-android

# Build debug APK
./gradlew assembleDebug

# Install on connected device/emulator
./gradlew installDebug
```

## Requirements

- **JDK**: 17+
- **Android SDK**: API 24+ (min), API 31 (target)
- **Gradle**: 8.x (wrapper included)

## Project Structure

```
sandbox-android/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/helloworld/
│   │   │   └── MainActivity.kt
│   │   ├── res/
│   │   │   ├── layout/activity_main.xml
│   │   │   └── values/
│   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── build.gradle.kts
└── settings.gradle.kts
```

## Build Commands

| Command | Description |
|---------|-------------|
| `./gradlew assembleDebug` | Build debug APK |
| `./gradlew assembleRelease` | Build release APK |
| `./gradlew installDebug` | Install on device |
| `./gradlew clean` | Clean build artifacts |
| `./gradlew check` | Run lint and checks |

## License

MIT
