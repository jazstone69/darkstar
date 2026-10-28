# DARKSTAR Idle RPG

A free sci-fi idle RPG that runs entirely in the browser. Build a squad, pick a path (3 base jobs, 6 advanced jobs), clear stages, and Ascend for permanent power.

**Play:** https://jazstone69.github.io/darkstar/

- No server and no account. Progress saves on the player's device, with a downloadable backup file.
- Works offline after the first visit, and can be added to an iPhone or iPad home screen (Share → Add to Home Screen).
- Everything is free, with no real purchases. The optional "Holovid Bonus" button shows a Google rewarded ad once an AdSense ID is set (see below), and otherwise a built-in fictional sponsor transmission.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game (layout, styles and code) |
| `tailwind.css` | Prebuilt styles, so the game doesn't depend on an outside service |
| `logo.svg`, `icon-*.png` | Logo and home-screen icons |
| `manifest.webmanifest`, `sw.js` | Home-screen install and offline play |
| `privacy.html` | Privacy policy (needed for ads) |

## Turning on real ads

1. Get approved for AdSense H5 Games Ads.
2. In `index.html`, set `ADSENSE_CLIENT` to your publisher ID (`ca-pub-…`). Leave `ADS_TEST_MODE = true` to see Google test ads first, then set it to `false` to go live.
3. If Google has no ad ready, or an ad blocker stops it, the button falls back to the built-in transmission.

`privacy.html` explains the ads to players.

After changing any file, bump `CACHE` in `sw.js` (for example `darkstar-v2`) so players get the new version.

Made by Stone Familia Media · https://www.stonefamiliamedia.com
