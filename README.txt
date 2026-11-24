LIFE RP — NEON DISTRICT V3

INSTALL ON IPHONE
1. Unzip the package on your PC. Keep index.html, sw.js, manifest.webmanifest and both PNG icons together.
2. Create a new GitHub repository (e.g. life-rp). Upload the files to the repository root, commit them, then go to Settings > Pages. Select Deploy from a branch, main, / (root), Save. Alternatively use any HTTPS static host.
3. Open the published HTTPS URL in Safari on iPhone. Tap Share > Add to Home Screen (look in More if necessary). Enable Open as Web App if offered. Tap Add.
4. Open the new icon while online. After the service worker caches the files, offline use is available.

SAVE SAFETY
Progress is local to the browser/app installation. Export JSON backups regularly from Settings and save to Files/iCloud Drive. Import a previous JSON save if migrating from V2. There is no server or cross-device sync. Do not clear site data or delete the app without backing up. Avoid using multiple copies simultaneously. Focus sessions use wall-clock time and settle when the app resumes; there is no guaranteed background notification.

PREVIEW
Opening index.html directly on a computer is useful for previewing. HTTPS hosting is required for the service worker and normal iPhone installation. Tested JavaScript syntax and core logic in a simulated DOM, not on a physical iPhone.
