Galaxy Y Archive Android app — source project

This is a source project, not a prebuilt APK. It has not yet been compiled or tested on a real Galaxy Y.

Features:
- Opens https://galaxyyarchive.run.place inside a WebView.
- Back button navigates to the previous page.
- Minimum Android API 9 (Android 2.3 Gingerbread).
- Target SDK 28 for installation on modern Android versions.
- Internet required; old Android WebView may not render every modern website feature.

Build from a phone using GitHub Actions:
1. Create a new GitHub repository.
2. Upload the contents of this ZIP into the repository root (including the hidden .github folder).
3. Open the repository's Actions tab.
4. Run "Build Galaxy Y Archive APK" or push to the main branch.
5. Open the workflow run and download artifact "GalaxyYArchive-debug-apk".
6. Extract app-debug.apk and install it on Android 10 first, then test on the Galaxy Y.

This project uses Android Gradle Plugin 8.6.1 and compile SDK 35. Older on-device IDEs such as older AIDE versions may not support this Gradle setup. GitHub Actions is the recommended no-PC build route.

Package: com.galaxyyarchive.app
Version: 1.0
