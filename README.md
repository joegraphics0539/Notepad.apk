# Notepad Android APK

This project wraps the supplied HTML app in an Android WebView.

## Build on GitHub
1. Create a new GitHub repository.
2. Upload all files in this folder, preserving `.github/workflows/build-apk.yml`.
3. Open **Actions**.
4. Select **Build Notepad APK**.
5. Click **Run workflow**.
6. When the job finishes, download the **Notepad-debug-apk** artifact.
7. Extract it and install `app-debug.apk` on Android.

## App settings
- App name: Notepad
- Package: com.joesticks.notepad
- Version: 1.0.0 (code 1)
- Orientation: follows device orientation
