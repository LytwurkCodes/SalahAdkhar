
Post‑Ṣalāh Adhkār — PWA
================================

What this is
------------
A minimal Progressive Web App (PWA) that runs offline and saves your tap-to-count progress locally. It shows Arabic + transliteration and provides per‑Salah checklists and counters.

How to install on iPhone
----------------------------------
1) Open the site (https://lytwurkcodes.github.io/SalahAdkhar) in Safari.
2) Tap the **Share** icon.
3) Choose **Add to Home Screen** → **Add**.
4) Launch from the Home Screen icon. It will open full-screen and work offline. Counts are saved on-device.

How to install on Android
----------------------------------
Chrome (most common)
1) Open the site (https://lytwurkcodes.github.io/SalahAdkhar) in Chrome.
2) If you see an Install chip in the address bar, tap it → Install.
    – If not, tap ⋮ (top-right menu) → Install app (or Add to Home screen).
3) Open it from your app drawer/Home Screen. It’ll run full-screen and work offline.

Samsung Internet
1) Open the site (https://lytwurkcodes.github.io/SalahAdkhar) in Samsung Internet.
2) Tap ☰ → Add page to → Apps screen (or Home screen).

Microsoft Edge (Android)
1) Open the site (https://lytwurkcodes.github.io/SalahAdkhar) in Edge.
2) Tap ⋯ → Add to phone (or Install app).

Tips & troubleshooting
----------------------------------
| Must be HTTPS: PWAs only install from secure URLs.
| First load online: Open once with internet so the service worker caches files for offline use.
| Update to a new version: Open the site, pull down to refresh (or add ?v=9 to the URL once).
| If it’s still stale, clear browser cache and follow steps to add to home screen again (old version must be deleted first).
| Haptics (vibration) on Android: We use the Vibration API. Make sure system haptics are on:
    Settings → Sound & vibration → Vibrations & haptics (device menu wording varies).
| Offline works: Once cached, it should open without internet. If a first-time open fails offline, connect once to let it cache.

Reset
-----
Use the **Reset All** button in the top-right to clear all saved counts.

Notes
-----
- iOS does not show the install prompt; use Add to Home Screen.
- Data are stored with localStorage only on your device.
- You can customise items by editing the EXTRAS and BENEFICIAL arrays in index.html.
