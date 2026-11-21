MOTIVIA PLUS — COMPLETE STARTER
Files:
- index.html: the app
- manifest.json: installable PWA settings and app icons
- service-worker.js: basic offline caching
- icons/: app icons

Publish using GitHub Pages:
Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
Then open the published HTTPS address in Chrome on Android and use Chrome menu > Add to Home screen / Install app.

Progress is stored in localStorage on this device and browser origin. It does not sync between devices. Export a backup from Progress before clearing browser data. Keep the existing live app until the replacement is tested.
