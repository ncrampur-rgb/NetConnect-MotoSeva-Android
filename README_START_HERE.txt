NETCONNECT & MOTOSEVA — ANDROID OFFLINE V1

WHAT IT DOES
- Two shop profiles: NetConnect Online Services and MotoSeva
- Create/edit/delete/search shipping bills locally in SQLite
- Export a 4 x 6 inch PDF shipping label with sender LEFT, receiver RIGHT, shop logo at upper-right, faint logo watermark
- Android system Save As dialog lets you choose a PDF folder
- No internet or permissions required after installation

HOW TO BUILD APK USING GITHUB (phone or computer)
1. Sign in to GitHub and create a new PRIVATE repository.
2. Upload the CONTENTS of this extracted project folder, preserving the directory structure (including .github/workflows/build-apk.yml).
3. Open your repository > Actions > Build Android APK > Run workflow.
4. Wait for a successful run; open the run and download the artifact NetConnect-MotoSeva-Offline-APK.
5. Unzip the artifact to obtain app-debug.apk; transfer to your Android phone and install. You may need to allow Install unknown apps for your file manager.
6. Test a sample bill and Save 4x6 PDF to Phone. Check print preview before printing.

IMPORTANT
- This ZIP is ANDROID SOURCE, NOT AN INSTALLABLE APK.
- Build was NOT run in this environment. The APK is unsigned for release (debug-signed for testing).
- Windows V9 data are NOT automatically migrated. Android uses its own local SQLite database.
- Back up important PDFs separately. Uninstalling the app can erase locally stored bills.
- This first Android version covers basic bills and PDF export. It does NOT yet replicate V9 bulk billing, reports, password, backups, courier status, or advanced design settings.
- PDF text uses Android built-in fonts; Bengali/complex-script PDF rendering may vary and should be tested.
