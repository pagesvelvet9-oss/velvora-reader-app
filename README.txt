VELVORA READER APP — DEPLOY PACKAGE

This is the reader-only Progressive Web App (PWA) for VELVORA.
It is separate from your existing VELVORA website and does not include Host Studio/admin publishing tools.

IMPORTANT: The icons folder is included in this package. Keep it beside index.html. Do not upload only index.html.

Files at the package root:
- index.html
- styles.css
- app.js
- manifest.webmanifest
- sw.js
- icons/ (icon-192.png, icon-512.png, logo.png)

For deployment, extract this ZIP and deploy the CONTENTS of the velvora-reader-app folder as the root of a NEW Vercel project. The icons folder must remain in the same location beside index.html.

After deployment, these paths must load without 404:
/icons/logo.png
/icons/icon-192.png
/icons/icon-512.png

Then open the app URL in Chrome on Android and use the browser menu > Install app (or Add to Home screen if Chrome offers that instead).

Note: This package is a PWA website build, not a signed Android APK. Play Store publication and APK/AAB packaging are separate steps.
