# Android app (WebView) for Kota Fresh Veggie

This module is a minimal Android WebView wrapper that loads the web prototype located in app/src/main/assets/www/index.html.

How to build (recommended):
1. Open `android-app` in Android Studio (File → Open) and let it sync Gradle.
2. Run the app on an emulator or connected device (Run → Run 'app').

How to build from command line (if you have Gradle installed):
1. cd android-app
2. gradle assembleDebug

Notes:
- This project does not include a Gradle wrapper. If you prefer builds in CI, either add the wrapper or use Android Studio's build.
- The WebView requires INTERNET permission (already added).
- To customize the app icon or app name, update the AndroidManifest and resources.
