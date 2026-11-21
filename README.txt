INVOICE MAKER - APK BUILD
1. Create a free account at github.com and click New repository (name: invoice-maker, Public or Private).
2. On the new repo page click "uploading an existing file", then drag in EVERYTHING from this unzipped folder
   (www, res-overrides, package.json, capacitor.config.json, build.yml, .gitignore). Click Commit changes.
3. Click Add file > Create new file. In the name box type:  .github/workflows/build.yml
   Paste the full contents of build.yml into it and click Commit. (Skip if the Actions tab already shows "Build APK".)
4. Open the Actions tab > Build APK > wait about 5-8 minutes for a green tick.
   If it did not start, click Run workflow.
5. Open the finished run, scroll to Artifacts, download InvoiceMaker-apk (a zip containing app-debug.apk).
6. Unzip, send app-debug.apk on WhatsApp, tap it on the phone and allow "Install unknown apps".
