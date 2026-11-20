1081 — Time Counter (prototype 1.0)

Features:
- Arabic and English UI, RTL/LTR switching
- Multiple named date/time counters
- One pinned counter displayed prominently
- Calendar-aware remaining time: years, months, weeks, days, hours, minutes, seconds
- Small elapsed-since-created reminder for every counter
- Local storage; no account or network needed after first load
- JSON backup export/import
- Installable PWA manifest and offline service worker

How to run:
Serve this folder from an HTTPS host or localhost, then open index.html in an Android browser.
For installation, use the browser menu > Add to Home screen / Install app.

Important:
This package is an installable web app (PWA), not a compiled Android APK.
A native APK build requires Android SDK/Gradle tooling, which is not installed in this build environment.
