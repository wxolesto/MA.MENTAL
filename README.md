# MENTAL — Android-ready starter

This repository contains the MENTAL web app wrapped with Capacitor for Android builds.

## Build an APK with GitHub Actions

1. Upload the **contents** of this folder to the root of a GitHub repository.
2. Make sure `.github/workflows/build-apk.yml` is included.
3. Open the repository's **Actions** tab.
4. Select **Build MENTAL APK**.
5. Press **Run workflow** (or push a commit to `main` to trigger it automatically).
6. Wait for the run to finish with a green check.
7. Open the completed run, scroll to **Artifacts**, and download `MENTAL-debug-apk`.
8. Extract the ZIP artifact. The APK inside is `app-debug.apk`.

## Important

- This workflow creates a **debug APK** for testing and installing on your own Android device.
- It is not a signed release build for publishing on Google Play.
- The Android project is generated during the workflow, so you do not need to upload an `android/` folder.
- The web app source files are in `web/`. After editing them, push the changes to `main`; Actions will build a fresh APK.
- The current MENTAL app is still an early prototype. Test its screens, calculations, and saved progress before treating it as a finished product.

## App details

- App name: MENTAL
- Android application ID: `com.mental.app`
- Capacitor major version: 8
