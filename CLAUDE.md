# Rules for Claude in this repo

Owner: Evan Isaac (evanisaac2-arch). Not a full-time developer: explain in plain language and give click-by-click steps with links. Short answers; no jargon without a one-line explanation.

## First session in a new repo made from this template
1. Ask Evan what the app is for, if he hasn't said.
2. Fill in the **Project** section below and replace README.md with a short description of the app.
3. Do this in the same pull request as the first working version.

## Project
- **What it is:** Pocket Dice — a minimalist phone dice roller for tabletop RPGs (d4–d100, modifier, advantage/disadvantage, animated rolls, recent-roll history). A single static page: `index.html` (all CSS + JS inline), plus `manifest.json` and icons so it can be added to a phone's home screen. No build step, no server, no secrets.
- **Where it runs / how it's published:** Cloudflare Pages, connected to this repo's `main` branch, so merging a pull request publishes the site. (A Claude artifact copy also exists for quick previews; this repo is the master.)
- **Live link:** [PLACEHOLDER — Cloudflare Pages address, e.g. https://pocket-dice.pages.dev, once set up]

## Source of truth and workflow
- **This GitHub repo is the master copy.** Don't let the live version drift from it: if something is changed elsewhere, bring the change back here.
- Work on a `claude/…` branch, commit with clear messages, push, and open a pull request. **Evan reviews and clicks Merge. Never push to `main`.**
- Say plainly whether a merged change is live yet or still needs publishing.
- Test before opening a PR (run it, check it at phone width if it has a screen) and say what you tested.

## Never commit
- Passwords, passphrases, API keys, tokens, `.env` / `.dev.vars` files. Secrets go in the hosting service's settings only.
- Large media (videos, big image sets) — keep them in Google Drive or cloud storage; `.gitignore` blocks common types.
- Client files or models (EDI samples, client spreadsheets) unless Evan says the repo is meant for them.

## Facts
- Don't invent facts, numbers or testimonials about Evan; use a visible `[PLACEHOLDER]` and flag it.
