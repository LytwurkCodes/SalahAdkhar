
Post‑Ṣalāh Adhkār (Hanafi) — PWA
================================

What this is
------------
A minimal Progressive Web App (PWA) that runs offline and saves your tap-to-count progress locally. It shows Arabic + transliteration and provides per‑ṣalāh checklists and counters.

How to host (GitHub Pages)
--------------------------
1) Create a new repo, e.g. `adhkar-pwa`.
2) Upload all files from this folder (index.html, manifest.webmanifest, service-worker.js, icons/).
3) In repo settings → Pages → Build and deployment → Branch: `main` → `/ (root)` → Save.
4) Open your Pages URL once (to warm the service worker).

How to install on iPhone (iOS 18+)
----------------------------------
1) Open the site in Safari.
2) Tap the **Share** icon.
3) Choose **Add to Home Screen** → **Add**.
4) Launch from the Home Screen icon. It will open full-screen and work offline. Counts are saved on-device.

Reset
-----
Use the **Reset** button in the top-right to clear all saved counts.

Notes
-----
- iOS does not show the install prompt; use Add to Home Screen.
- Data are stored with localStorage only on your device.
- You can customise items by editing the EXTRAS and BENEFICIAL arrays in index.html.
