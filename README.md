# SESI Portal - Cloud APK Builder

This package is designed to build the Android APK using GitHub Actions without a PC/Android Studio on the user's device.

1. Create a public GitHub repository.
2. Upload `SESI-Portal-Android.zip` and the `.github/workflows/build-apk.yml` file, preserving the `.github/workflows/` path.
3. Push/commit to `main`. GitHub Actions will build the APK automatically.
4. Open Actions -> Build SESI Portal APK -> latest run -> Artifacts -> SESI-Portal-APK.
5. Download the artifact ZIP on Android, extract it, and install `app-debug.apk`.
