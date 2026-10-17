# Aussie Street Racers — v0.2

Mobile-first, playable 3D browser racing prototype with fictional Australian-inspired performance cars and city.

## What's new
- Free roam in a grid-based fictional Queensland-inspired city, with buildings, parks, lighting, and moving AI traffic.
- Six Australian-inspired vehicles: BA XR6, BF XR6 Turbo, FG XR6 Turbo, VE SS, AU XR8 and a V8 club sedan.
- Redesigned garage with car purchasing, paint, engine tuning and saved progress.
- Touchscreen steering, throttle and brake, plus keyboard WASD / arrow controls.
- A simple four-checkpoint circuit race, rewards, and minimap.

## Publish on GitHub Pages
1. Open your `aussie-street-racers` repository.
2. Replace the root `index.html` with the `index.html` in this folder; replace `README.md` too.
3. Commit changes to the `main` branch.
4. Under Settings > Pages, choose Deploy from a branch > `main` > `/ (root)` and Save.
5. Wait for deployment and open `https://YOUR-USERNAME.github.io/aussie-street-racers/`.

## Controls
- Phone: on-screen left/right, GO and BRAKE buttons.
- Desktop: WASD or arrow keys.
- MENU switches between free roam and a circuit race.
- GARAGE allows buying cars, changing paint and engine tuning.

## Notes and limitations
- Internet connection required for the Three.js module hosted on jsDelivr.
- Models are stylized, original approximations; no official Ford/Holden assets or licensing.
- Traffic is simple moving AI and may cross intersections without full traffic rules.
- Physics and collision are arcade-style; buildings are scenery, not fully collidable.
- Racing is a fictional closed-course game experience; this is not a production-ready native mobile app.
- Progress uses localStorage on each device/browser. v0.1 saves are not migrated automatically.
