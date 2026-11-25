# Laxmipuram Voter Search – Android project

This Android Studio project wraps the supplied self-contained HTML voter-search page in a local WebView. The HTML, voter data, and embedded photos are bundled inside the app, so the search works offline and the app does not request internet access.

## Build an installable APK

1. Install Android Studio (current stable version) on a computer.
2. Open this folder (`LaxmipuramVoterSearch`) in Android Studio.
3. Allow Gradle sync and install the Android SDK Platform 35 if prompted.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Android Studio creates the APK at `app/build/outputs/apk/debug/app-debug.apk`.
6. Copy that APK to your Android phone and install it. You may need to allow installation from that file manager.

For sharing publicly, create a signed release APK from **Build → Generate Signed Bundle / APK**.

## App details
- App name: Laxmipuram Voter Search
- Package: `in.aniltours.laxmipuram`
- Offline local HTML; no network permission is declared.
- Includes the uploaded voter data and embedded voter photos without changing the source page.

## Important privacy note
The bundled source includes personal voter information and photographs. Share the APK only with people who are authorized to access that information, and confirm you have permission to distribute it.
