HyperControlCenter - Android Studio project (Kotlin)
================================================
This is an open-source, simple Control Center-style Android app (demo).
It targets Android 13 (API 33). This repository contains:
- A minimal app with a main Activity showing quick toggles and a brightness slider.
- Gradle build files (use Android Studio to open and build).

How to build
1. Option A (Recommended): Open this folder in Android Studio (Arctic Fox or newer), let it download SDKs, then Build > Make Project. 
   The APK will be under: app/build/outputs/apk/debug/app-debug.apk
2. Option B (CI): Push to GitHub and use GitHub Actions to build an APK (I can provide a workflow file if you want).
3. Option C (Termux / CLI) — more advanced: install OpenJDK + Android SDK + Gradle; then run: ./gradlew assembleDebug

Notes
- This app is a demo UI only. It does NOT require root and does NOT modify SystemUI.
- You can integrate the generated APK into the Magisk module I created earlier.

If you want, I can also add a GitHub Actions workflow that builds the APK automatically when you push the repo.
