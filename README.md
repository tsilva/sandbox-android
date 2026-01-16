<div align="center">
  <img src="logo.svg" alt="Sandbox Android" width="150"/>

  # Sandbox Android

  [![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com/)
  [![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
  [![Min SDK](https://img.shields.io/badge/Min%20SDK-24-blue?style=flat-square)](https://developer.android.com/about/versions/nougat)
  [![Target SDK](https://img.shields.io/badge/Target%20SDK-34-blue?style=flat-square)](https://developer.android.com/about/versions/14)
  [![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

  **A minimal Android starter app for quick prototyping and learning**

  [Quick Start](#quick-start) · [Build Commands](#build-commands) · [Project Structure](#project-structure)

</div>

---

## Overview

A clean, minimal Android application built with Kotlin that serves as a starting point for Android development. Perfect for learning Android basics, testing new libraries, or prototyping features.

## Features

- **Single-activity architecture** with ConstraintLayout for flexible UI design
- **Modern Kotlin** with JVM target 17 for latest language features
- **AndroidX libraries** including AppCompat, Material Design, and ConstraintLayout
- **Gradle Kotlin DSL** for type-safe, IDE-friendly build configuration
- **ProGuard-ready** release builds with minification support

## Requirements

| Component | Version |
|-----------|---------|
| Android Studio | Hedgehog (2023.1.1)+ |
| JDK | 17 |
| Android SDK | API 34 |

## Quick Start

```bash
# Clone the repository
git clone <repository-url>
cd sandbox-android

# Build and install on connected device
./gradlew installDebug
```

The app displays "Hello World!" centered on screen.

## Build Commands

| Command | Description |
|---------|-------------|
| `./gradlew assembleDebug` | Build debug APK |
| `./gradlew assembleRelease` | Build release APK |
| `./gradlew installDebug` | Install debug APK on device |
| `./gradlew clean` | Clean build outputs |
| `./gradlew check` | Run lint and other checks |

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
├── gradle.properties
└── settings.gradle.kts
```

## Configuration

### Build Tools

| Component | Version |
|-----------|---------|
| Android Gradle Plugin | 8.1.0 |
| Kotlin | 1.9.0 |
| Min SDK | 24 (Android 7.0) |
| Target SDK | 34 (Android 14) |
| Compile SDK | 34 |

### Dependencies

| Library | Version |
|---------|---------|
| androidx.core:core-ktx | 1.7.0 |
| androidx.appcompat:appcompat | 1.4.1 |
| com.google.android.material:material | 1.5.0 |
| androidx.constraintlayout:constraintlayout | 2.1.3 |

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## License

This project is available under the MIT License.

---

<div align="center">
  Built with Kotlin and AndroidX
</div>
