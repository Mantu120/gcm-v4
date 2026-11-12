BUILD THE APK WITH GITHUB (no Android Studio needed)

1. Create a free account at github.com and make a new repository (private is fine).
2. Upload everything in this folder to the repository, keeping the folder structure
   (including the hidden .github folder). On the "Add file > Upload files" page you can
   drag the whole unzipped folder in.
3. Open the repository's "Actions" tab. The "Build APK" workflow runs by itself after
   the upload. If it does not, open it and press "Run workflow".
4. When it finishes (about 3 to 5 minutes), open the run and download the
   "grass-cutting-log-apk" file under Artifacts. Unzip it to get app-debug.apk.
5. Copy app-debug.apk to your phone and open it. Android will ask you to allow
   installing from this source. Allow it once, then install.

To change the app later, edit app/src/main/assets/index.html and upload it again.
Saved work log entries and templates stay inside the app on the phone.
