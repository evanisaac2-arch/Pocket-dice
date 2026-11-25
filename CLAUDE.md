# Rules for Claude in this repo

Owner: Evan Isaac (evanisaac2-arch). Not a full-time developer: explain in plain language and give click-by-click steps with links. Short answers; no jargon without a one-line explanation.

## First session in a new repo made from this template
1. Ask Evan what the app is for, if he hasn't said.
2. Fill in the **Project** section below and replace README.md with a short description of the app.
3. Do this in the same pull request as the first working version.

## Project
- **What it is:** [FILL IN]
- **Where it runs / how it's published:** [FILL IN — e.g. a Claude artifact, Cloudflare Pages/Workers, local only]
- **Live link:** [FILL IN]

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
