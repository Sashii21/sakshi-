# Hello World Android App

A simple Android "Hello World" application built with Kotlin and AndroidX.

## Requirements

- Android Studio (latest stable version recommended)
- JDK 17 or higher
- Android SDK with API level 24 or higher

## Project Structure

```
HelloWorld/
├── app/
│   └── src/
│       └── main/
│           ├── kotlin/com/example/helloworld/
│           │   └── MainActivity.kt
│           ├── res/
│           │   ├── layout/activity_main.xml
│           │   └── values/
│           │       ├── colors.xml
│           │       ├── strings.xml
│           │       └── themes.xml
│           └── AndroidManifest.xml
├── gradle/wrapper/
├── build.gradle
├── settings.gradle
└── gradle.properties
```

## Opening in Android Studio

1. Clone or download this repository.
2. Open Android Studio.
3. Select **File > Open** and navigate to the repository root folder.
4. Android Studio will sync the Gradle project automatically.
5. Wait for the Gradle sync to finish.

## Building the App

### Using Android Studio

1. Open the project in Android Studio.
2. Click **Build > Make Project** (or press `Ctrl+F9` / `Cmd+F9`).
3. To build a debug APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

### Using the Command Line

Make sure you have the Android SDK installed and `ANDROID_HOME` (or `ANDROID_SDK_ROOT`) set, then run:

```bash
./gradlew assembleDebug
```

The output APK will be located at:
```
app/build/outputs/apk/debug/app-debug.apk
```

## Running the App

1. Connect an Android device or start an emulator.
2. In Android Studio, click the **Run** button (green triangle) or press `Shift+F10`.
3. Select your device/emulator and click **OK**.

## Tech Stack

- **Language**: Kotlin
- **Min SDK**: 24 (Android 7.0 Nougat)
- **Target SDK**: 35 (Android 15)
- **Android Gradle Plugin**: 8.8.0
- **Gradle**: 8.11.1
