Nimbahera Solar Alarm — FIXED GitHub Pages version

Upload ALL files inside this folder to the root of the same GitHub repository.

Fixes:
- Corrected Sunrise-Sunset API endpoint (/json instead of /v2).
- Correct service-worker scope for /SunRiseSunSet/ GitHub Pages deployment.
- Uses persistent ServiceWorkerRegistration.showNotification() for mobile notifications.
- Added clearer permission/data errors.
- Added a real PNG icon.

After upload, open the GitHub Pages URL in Chrome. If the old version remains, clear site data once, then reopen and press Enable daily alarms.

Web limitation: a PWA cannot provide the same guaranteed exact background alarms as native Android AlarmManager if Android completely kills/suspends Chrome. Cached solar data can work offline, but background timing is controlled by the browser/OS.
