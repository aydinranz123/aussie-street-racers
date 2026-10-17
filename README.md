# Aussie Street Racers — Prototype v0.1

A mobile-first 3D browser game, featuring an original BA Falcon XR6-inspired sedan (not a licensed Ford model), 2-lap race against an AI rival, touchscreen driving controls, garage paint and engine upgrades, and saved in-game cash.

## Run on a computer
1. Install Python 3 if needed.
2. Open a terminal in the folder containing `index.html`.
3. Run `python -m http.server 8000` (or `python3 -m http.server 8000`).
4. Visit http://localhost:8000 in Chrome, Safari, or Edge.

## Run on iPhone or Android
1. Host `index.html` on any HTTPS static hosting service, e.g. GitHub Pages, Netlify, or Cloudflare Pages.
2. Open the HTTPS address in Safari or Chrome on your phone.
3. Optionally use Add to Home Screen in the browser's share menu.

You can also test from a phone on the same Wi-Fi as your computer by visiting `http://COMPUTER-LAN-IP:8000`, provided the computer firewall permits it. HTTPS hosting is generally more reliable.

## Controls
Touch ◀ ▶ to steer; hold GO to accelerate; BRAKE to decelerate. On keyboard use arrows or WASD. Open GARAGE to pause. Engine tunes cost in-game cash, earned after races.

## Technical notes
Uses Three.js 0.160.1 imported from jsDelivr CDN. Internet access is required to load the engine. No backend, account, payments, real-world street racing, or multiplayer. Race circuit is fictional and closed. This is a lightweight prototype, not a native Android APK or iOS IPA, and the car is a stylized approximation rather than a licensed 3D scan. Engine upgrades and race results are saved in localStorage.

## Next steps
Replace primitive car with an appropriately licensed glTF model; add physical steering/handling, collisions, opponent racing AI, lap timing, audio, garage camera, and a native wrapper (Capacitor) for app-store distribution.
