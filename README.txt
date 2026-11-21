MY DAILY RESET — HOME-SCREEN APP PACKAGE

This is a small installable web app (PWA), not a Play Store or App Store app.

IMPORTANT: Android Chrome requires the files to be served from a secure HTTPS website before it will offer the reliable Install app / Add to Home screen experience. Opening index.html directly from Downloads is not enough to enable PWA installation or offline app behavior.

SETUP:
1. Keep all files in this folder together.
2. Publish this folder to a static HTTPS host (for example, a static-site hosting service). The published folder must contain index.html, manifest.webmanifest, service-worker.js, icon-192.png and icon-512.png at the same level.
3. Open the HTTPS website in Chrome on your Android phone.
4. Tap Chrome's three-dot menu, then choose "Install app" or "Add to Home screen" (wording varies).
5. Confirm. The Daily Reset icon will appear on your home screen and open in its own app-style window.

PRIVACY / DATA:
The planner saves its checkboxes and notes in browser storage on that device/browser. It does not include an account or cloud sync. If you publish it to a website, anyone who has the website address may be able to open it unless you add access protection. Ask a parent/guardian to help choose a hosting option and review its privacy settings.

The app shell is cached for offline opening after the first successful visit, but saved planner data remains local to the browser/device. Clearing browser data can erase it.
