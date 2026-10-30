AMIT BUSINESS MANAGER — ANDROID TEST APK SOURCE PROJECT

This is an Android WebView wrapper around the local prototype. It is source code, not a prebuilt APK.

BUILD A TEST APK USING GITHUB ACTIONS (Android phone is enough)
1. Sign in or create an account at https://github.com
2. Create a new repository, e.g. AmitBusinessManager. A private repository is fine.
3. Upload the CONTENTS of this ZIP to the repository root (not the ZIP itself):
   settings.gradle, build.gradle, app/ folder, .github/ folder.
4. Open repository > Actions. If prompted, enable workflows.
5. Select "Build test APK" > "Run workflow" (or push to main to trigger it).
6. Wait for the run to finish successfully.
7. Open the completed run, scroll to Artifacts, and download
   "Amit-Business-Manager-test-APK".
8. Extract the downloaded artifact ZIP to get app-debug.apk.
9. Open app-debug.apk on your Android phone and allow installation from that source if Android asks.
   Only install APKs you built from this project and trust.

NOTES
- This is a TEST/debug APK, not ready for Google Play Store.
- App records use local WebView browser storage on the phone and are not cloud synced.
- The prototype is not yet secure/complete enough for real business records.
- Before Play Store release: production database, backups, authentication/permissions,
  audit logs, privacy policy, signed release build, store listing, and policy review are needed.
