# Android APK build

This repository includes an Android WebView wrapper that bundles the app's HTML locally.

## Build
1. Open the **Actions** tab.
2. Select **Build Android APK**.
3. Press **Run workflow** on the `main` branch.
4. Open the completed run and download the `routine-quest-android-apk` artifact.

The artifact contains a debug APK. Android may show a warning because it is not Play Store-signed. For Play Store distribution, create a signed release build with a private keystore.
