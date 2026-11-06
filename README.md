# Zohirola (Android app)

Android app that opens the Zohirola website. It supports login sessions, photo upload, downloads, pull to refresh, back navigation and an offline screen.

## Set your website address
Edit `APP_URL` in `gradle.properties` (must start with `https://`), or pass the address when you run the **Build APK** workflow.

## Build
Run the **Build APK** workflow in GitHub Actions, or `gradle assembleDebug` (JDK 17, Android SDK 34).
