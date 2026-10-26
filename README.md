# OUTPOST: LAST STAND

A self-contained top-down tactical survival shooter made with HTML Canvas, CSS and vanilla JavaScript. No server, build tools, packages, or API keys are required.

## Play locally

Open `index.html` in a modern desktop browser. For best results, use Chrome, Firefox, or Edge and play with a keyboard and mouse.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, `game.js`, and this `README.md` into the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select the `main` branch and `/(root)`, then save.
5. Open the published Pages URL after deployment finishes.

## Controls

- **W A S D** — move
- **Mouse** — aim
- **Left mouse button** — fire
- **R** — reload
- **1 / 2 / 3** — switch rifle, pistol, marksman rifle
- **Shift** — sprint
- **Space** — dash (temporary invulnerability and cooldown)
- **B** — open field shop between waves or during combat
- **Esc** — pause/resume

## Features

- Infinite escalating enemy waves with raiders, runners, gunners, and a heavy enemy every fifth wave
- Three weapons with individual damage, rate of fire, spread, reload time and ammunition
- Weapon projectiles, line-of-sight checks for ranged enemies, destructible hit states, collision, enemy bullets, knockback and screen shake
- Medkit and ammunition pickups
- Supply credits and a field shop with eight purchasable upgrades
- Level-ups, score, kill counts, wave reward bonuses, minimap and best score saved to local storage
- Generated sound effects via Web Audio (no external audio files)
- Responsive interface; keyboard and mouse are recommended for full playability

All art is drawn in Canvas at runtime; fonts are loaded from Google Fonts when internet access is available and fall back to local system fonts. The game itself has no external runtime dependencies.
