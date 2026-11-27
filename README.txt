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

V4 — FITNESS & MISSION CONTROL
Upgrade on the same hosting URL to retain your existing lifeRP.v1 local save. Export a backup first.
Fitness: check exercises for 10 XP each; six exercises unlock 60 bonus XP once per day. A rest day or six exercises plus at least one food log qualifies for the fitness streak. Nutrition targets are optional and do not affect penalties. Calorie calculator estimates adult maintenance needs.
Tasks: choose a duration and credit penalty, save, then explicitly start the countdown. Expiration charges once; late completion remains possible. Time is based on stored timestamps, so reopening reconciles missed deadlines. No background notifications are promised. Credit penalties do not remove earned XP or levels.
Deploy all files together at the existing HTTPS URL. Open online to update the service worker. Local storage is not cloud sync.
Daily tasks are tracked by their start calendar day; after midnight a new daily occurrence is available. One-time tasks can span days. Old daily deadlines still reconcile.

V5 GYM DISTRICT
Gym attendance uses local calendar dates, Monday–Sunday weeks, and a configurable 1–7 day target. A current incomplete week is not counted as a failure until it closes. Goal changes after a check-in apply next week. Gym XP is separate (50 per unique visit, 10 per lifting record). The equipment library uses original generic schematic illustrations, not exact manufacturer photos. Add custom equipment as needed. All data stays in the existing local save; export a backup before updating. Cardio entries currently use the same sets/reps/kg form as strength machines. No physical iPhone testing was performed.

V6 — Fuel District overhaul
- Dedicated nutrition page, editable dated meal records, 12 approximate food presets and optional macros.
- Saved adult maintenance/resting energy estimator and optional calorie reference target.
- Player and gym rank ladders, dashboard 28-day category heatmaps, new responsive visual theme.
- Retains lifeRP.v1 save key. Export a backup before replacing all files, including v6.css and sw.js.
- Browser DOM smoke tests passed with simulated local storage. Hosted service worker and physical iPhone not tested.
