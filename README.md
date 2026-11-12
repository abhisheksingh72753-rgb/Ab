# DUNE Android Starter

An Android Studio starter project for DUNE, an Instagram-inspired social app UI.

## Included
- Jetpack Compose Android app shell
- Home feed with sample posts and stories
- Bottom navigation: Home, Explore, Reels, Chat, Profile
- Demo inbox UI

## Build an APK
This workspace does not include the Android SDK or Gradle, so an APK cannot be compiled directly here. The project includes a GitHub Actions workflow to build it in the cloud:

1. Create a GitHub repository and upload the contents of this folder.
2. Open the repository's **Actions** tab.
3. Select **Build DUNE APK** and press **Run workflow** (or push to `main`).
4. When the workflow finishes, open the run and download the **DUNE-debug-apk** artifact.
5. Extract the artifact ZIP on your Android phone and install `app-debug.apk`. If Android asks, allow installation from that source.

You can also open this folder in Android Studio, let Gradle sync, and run it on a connected Android device.

## Important
This is a UI starter, not a production social network. The inbox uses sample data; real accounts, cross-device messaging, media upload, push notifications, calls, moderation, and privacy controls require a secure backend (for example Firebase Authentication, Firestore, Storage, and Cloud Messaging), security rules, and testing.

Package: `com.dune.social`
