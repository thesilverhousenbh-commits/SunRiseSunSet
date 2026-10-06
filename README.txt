NIMBAHERA SOLAR ALARM - WEB APP / PWA

1. Extract this ZIP.
2. Host the folder on HTTPS (GitHub Pages, Netlify, Vercel, your own HTTPS server, etc.). A service worker/PWA normally requires HTTPS (localhost is also allowed for development).
3. Open the HTTPS site on Android Chrome.
4. Choose Add to Home screen / Install app.
5. Open the installed app, tap "Enable daily alarms" and allow notifications.
6. The app fetches and stores up to 90 days of sunrise/sunset data in local storage.
7. Once cached, the solar data is available offline. The app uses the stored times to schedule its in-page timers.

FIXED LOCATION
Nimbahera, Rajasthan, PIN 312601
Coordinates: 24.62166, 74.67999
Timezone: Asia/Kolkata

DEFAULTS
- Sunrise alarm: 15 minutes before sunrise
- Sunset alarm: 15 minutes before sunset
- Ring duration: 5 minutes

IMPORTANT LIMITATION
A web/PWA app cannot guarantee alarms if Android/browser completely kills or suspends its JavaScript process. The app does NOT depend on internet for cached solar times, but background execution is still controlled by Android/browser. For best reliability, install the PWA, allow notifications, disable battery optimization for the browser/PWA where possible, and keep it running.
