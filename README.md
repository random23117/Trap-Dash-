# TRAP DASH — Android APK Project

This Android Studio project wraps the original `trap_dash_100_levels.html` game in a fullscreen Android WebView.

## Design preservation
The original HTML, CSS, JavaScript, game visuals, lobby, controls, and 100-level logic are copied unchanged to:
`app/src/main/assets/index.html`

Only a small Android wrapper was added so the game can be packaged as an APK.

## Build APK with GitHub Actions
1. Create a new GitHub repository and upload the contents of this project (not the ZIP file itself).
2. In the repository, create `.github/workflows/android.yml` with the workflow below, or upload the included workflow file.
3. Open **Actions** in GitHub and run **Build Android APK**.
4. When the workflow completes, open the run and download the `trap-dash-debug-apk` artifact.
5. The APK is a debug APK for testing. For a Play Store release, create a signed release build.

## Build locally
Open this folder in Android Studio and run **Build > Build APK(s)**.
