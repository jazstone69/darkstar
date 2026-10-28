# DARKSTAR Idle RPG

A free sci-fi idle RPG that runs entirely in the browser. Build a squad, pick a path (3 base jobs, 6 advanced jobs), clear stages, and Ascend for permanent power.

**Play:** https://jazstone69.github.io/darkstar/

- No server and no account. Progress saves on the player's device, with a downloadable backup file.
- Works offline after the first visit, and can be added to an iPhone or iPad home screen (Share → Add to Home Screen).
- Everything is free. The "Holovid Bonuses" are in-game parody sponsors, not real ads, and there are no real purchases.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game (layout, styles and code) |
| `tailwind.css` | Prebuilt styles, so the game doesn't depend on an outside service |
| `logo.svg`, `icon-*.png` | Logo and home-screen icons |
| `manifest.webmanifest`, `sw.js` | Home-screen install and offline play |

After changing any file, bump `CACHE` in `sw.js` (for example `darkstar-v2`) so players get the new version.

Made by Stone Familia Media · https://www.stonefamiliamedia.com
