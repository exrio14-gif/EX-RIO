EX RIO Billing — Android Studio project

This project wraps the supplied EX RIO Billing HTML interface in an Android WebView app.

Build an APK:
1. Install Android Studio on a computer.
2. Extract this ZIP.
3. Open the extracted EXRIOBilling folder in Android Studio.
4. Allow Gradle sync and install any requested Android SDK Platform 35 / Build Tools.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Android Studio will show a link to the generated APK (usually app/build/outputs/apk/debug/app-debug.apk).
7. Transfer that APK to your Android phone and install it. You may need to allow installation from that source.

Notes:
- The billing HTML is bundled locally; the app does not require a website to open it.
- App data currently follows the HTML app's own storage behavior. Back up invoices/data regularly.
- This ZIP is an Android Studio project, not a precompiled APK. It has not been compiled or device-tested in this environment.
