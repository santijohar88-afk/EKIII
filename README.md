# EKIII Exam Hub - Android app

This folder builds your exam app into an Android APK on GitHub (no Android Studio needed).

## Steps
1. Make a free account at github.com and create a **new repository** (any name, Private is fine).
2. Click **uploading an existing file**, then drag in **everything inside this folder** (including the `.github`, `www` and `assets` folders). Commit to the `main` branch.
3. Open the **Actions** tab. The "Build Android APK" job starts by itself (about 5-8 minutes). If not, click it, then **Run workflow**.
4. When it shows a green check, open the run and download **EKIII-Exam-Hub-APK** at the bottom. Unzip it to get `app-debug.apk`.
5. Send the APK to a phone and install it (allow "Install unknown apps" when asked).

## Updating the app later
Replace `www/index.html` in the repository with your new version and commit. GitHub builds a new APK automatically.

## Notes
- QR scanning uses the phone's built-in scanner. The first scan may download a small Google component, so connect to the internet once.
- Backups, CSV and result files open the Android Share menu so you can save them to Drive, Files or send them.
- The Print Report button does not work inside the Android app. Use the web version in Chrome for printing.
- This builds a *debug* APK, which is fine for installing on your school's phones. Publishing on Google Play needs a signed release build.
