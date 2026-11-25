# Pocket Dice

A minimalist dice roller for tabletop RPGs, made for phones.

- Tap dice (d4, d6, d8, d10, d12, d20, d100) to build a roll, set a modifier, then tap **Roll**.
- **Adv / Dis** rolls each d20 twice and keeps the higher / lower.
- Each die tumbles in its own shape before landing; max rolls are outlined in red, and a lone d20 calls out natural 20s and 1s.
- Recent rolls sit in a row of bubbles — tap one to roll it again. Your setup and history are saved on your own device only.
- Add it to your home screen (Share → **Add to Home Screen** on iPhone, ⋮ → **Add to Home screen** on Android) and it opens like an app.

## Files
- `index.html` — the whole app (no build step).
- `manifest.json`, `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — home-screen install and icons.

## Publishing
Hosted on Cloudflare Pages from the `main` branch: merging a pull request publishes it.
