POP CONTROL STUDIO 15.0 — PHONE-ONLY PROJECT

FILES
- index.html: the full dashboard.
- manifest.json and icon.svg: PWA install metadata/icon.
- sw.js: small offline cache service worker.

TRY IT
1. Extract this ZIP using your Android file manager.
2. Open index.html in a browser to preview the dashboard. Some browser features only work when hosted over HTTPS.
3. To install it like an app, upload the project to a free HTTPS host (GitHub Pages works) using your phone, then open the hosted page in Chrome and choose ⋮ > Add to Home screen / Install app.

IMPORTANT LIMITATIONS
This is a web dashboard, not a native Android app or APK. Quick toggles, brightness, volume, battery, and media player are visual demos and cannot change Android system settings or read the phone's actual battery. The weather widget requests browser location permission and internet access and uses Open-Meteo.

Built as a single-page project with no paid services required for the basic UI.
