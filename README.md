# Plant Operation APK project

This project wraps the supplied Plant Operation HTML page in an Android app using Capacitor.

## GitHub upload
Upload the contents of this folder to the root of a new GitHub repository. Keep the `.github/workflows/build-apk.yml` file and its folder structure.

## Build
After uploading to the `main` branch, open the repository's Actions tab. Select the successful "Build Plant Operation APK" run and download the `Plant-Operation-APK` artifact. Extract the downloaded ZIP to get `app-debug.apk`.

The workflow creates a debug APK for testing and direct installation. A signed release APK or Android App Bundle is needed for Play Store distribution.
