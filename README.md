# DecideAhead — Website

The public site for DecideAhead (incident-command training). Single-page, static HTML — no build step.

## Files
- `index.html` — the entire site (HTML + CSS + a little JS, all inline).
- `CNAME` — tells GitHub Pages to serve the site at `decideahead.com`.

## How to edit
Open `index.html` and edit the text directly. It's one file — search for the words you want to change. Commit and push; GitHub Pages redeploys automatically in ~1 minute.

## How it's hosted
GitHub Pages serves this repo at https://decideahead.com. To change hosting settings: repo **Settings → Pages**.

## The early-access form
The signup form lives in the `EARLY ACCESS` section of `index.html`. It's wired to send submissions to either a HubSpot form embed (preferred — logs to CRM) or a Formspree endpoint. See the comment block above the `<form>` tag for the one line to set.

## Notes
- No demo link or pricing yet — this is an interest-gathering launch.
- Brand assets (logo, palette) live in the project's `/Brand` folder.
