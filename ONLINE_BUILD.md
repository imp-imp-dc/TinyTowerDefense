# Build the APK online (no PC needed)

This project includes a GitHub Actions workflow. Upload the project to a GitHub repository, then open **Actions → Build APK → Run workflow**. When it finishes, open the workflow run and download the artifact named **TinyTowerDefense-debug-apk**. The artifact contains `app-debug.apk`.

No signing key is required for this debug APK. Android may show a warning when installing an APK downloaded outside the Play Store.
