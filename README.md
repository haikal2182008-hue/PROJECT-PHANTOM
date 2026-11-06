# PROJECT PHANTOM

Android WebView wrapper for an early 3D open-world prototype.

## Build APK using GitHub Actions
1. Upload the extracted project files to the root of your GitHub repository.
2. Ensure `.github/workflows/android-apk.yml` is included.
3. Open the repository's **Actions** tab.
4. Select **Build PROJECT PHANTOM APK** and press **Run workflow**.
5. Open the completed run and download the **PROJECT-PHANTOM-APK** artifact.
6. Extract the artifact ZIP and install `app-debug.apk` on Android.

## Current prototype
- Original fictional city layout with roads and buildings
- Third-person player
- Drivable sports car
- Touch joystick, run, and drive/exit controls
- Landscape full-screen Android app

## Limitations
This is an early prototype, not a GTA-scale or photorealistic production game. Three.js is loaded from a CDN, so an internet connection is required when launching the game. The APK produced by this workflow is a debug build.
