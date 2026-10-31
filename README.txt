MY Bharat Tamil Nadu Resource Hub - Android wrapper project

This app opens the existing hosted website:
https://heroic-selkie-182e4b.netlify.app/

MOBILE-ONLY BUILD (no computer required)
1. On your phone, open https://github.com and create/sign in to your account.
2. Create a NEW repository. Give it a name such as mybharat-tn-resource-hub. You can keep it private.
3. Upload the contents of this ZIP to the repository, keeping the folder structure. Upload the files inside MYBharatAndroidApp, not the outer folder itself. Make sure .github/workflows/build-apk.yml is included.
4. Open the repository's Actions tab and enable Actions if asked.
5. Open the workflow named "Build MY Bharat Android APK". Tap "Run workflow" if it has not started automatically.
6. Wait for the workflow to finish with a green tick.
7. Open the completed workflow run, scroll to Artifacts, and download MYBharat-TN-Resource-Hub-APK.
8. Extract the downloaded ZIP on your phone. Open app-debug.apk and install it. Android may ask you to allow installing unknown apps for the browser or Files app.

If the repository upload from mobile does not preserve folders or hidden files, use GitHub's web upload from a browser with Desktop site enabled, or upload the project files individually while preserving paths.

IMPORTANT
- This is a WebView wrapper, not a fully native app.
- It needs internet and uses the website and Supabase backend online.
- It does not repair website/backend errors.
- Test login, email verification, saving, search, filters and logout before sharing with other officers.
- APK is unsigned for release/distribution; this workflow builds a debug APK for testing.

Package: in.mybharat.tnhub
Version: 1.0
