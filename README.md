# AIBrain.com — Minimal Website v1.0 (October 20, 2026)

## What is included
- `index.html` — responsive single-page corporate website
- `assets/styles.css` — responsive design, no external fonts, libraries, trackers or JS
- `assets/favicon.svg` — *provisional* favicon; replace with approved corporate asset

## Scope
This minimal release covers: corporate positioning; Sports AI / SSOT; Clinical Trials AI Copilot (clearly labelled in development); technology; company; and contact. Legacy pages are **not** replaced or deleted. Certain links point to existing `aibrain.com` pages, so those remain accessible even before migration.

The site is a standalone **prototype and publication handoff**, not a live update to `aibrain.com`.

## Preview
Open `index.html` directly in a desktop/mobile browser, or serve the folder with:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## To publish before Stanford SEP
1. Have the site administrator confirm hosting, CMS, deployment method, available access, and staging environment. **Do not overwrite WordPress/CMS root files or blindly upload this `index.html` over a server-side application.**
2. Back up files and database; document a one-click rollback path.
3. In a staging environment, implement the new homepage's sections (copy and layout) using the existing CMS theme/templates, or deploy the static file if hosting setup permits safely.
4. Replace the provisional lettermark with the approved AIBrain logo if available.
5. Review and approve legal name, California location, product maturity, clinical AI wording, privacy/analytics policies, link destinations and contact inbox routing.
6. Preserve `/technology/`, `/products/`, `/about/`, `/news/`, `/contact/` and existing SEO permalinks and historical content.
7. Test mobile, keyboard navigation, HTTPS, SSOT links, mailto links and tracking after changes. Ensure no internal links point to a removed route. Publish and verify production, then keep rollback ready.

## Links used
- `https://www.superstarsoftomorrow.football/` (flagship Sports AI app)
- `https://aibrain.com/technology/` (historical technology content)
- `https://aibrain.com/products/` (prior innovations)
- `https://aibrain.com/news/` (news archive)
- `mailto:help@aibrain.com` (public contact email)

## Content limitations
- No unsupported product adoption figures, client logos, FIFA certification claims, clinical efficacy claims, unsanctioned university or partner associations, or private patent/funding details.
- Youth player data safeguards, consent and privacy compliance must be reviewed separately before introducing new forms or accounts.
- A static page has no server-side contact form or customer database. The contact link opens the user's mail client.
- No external scripts are loaded: this sample does not set up analytics, cookie consent, or CRM tracking.

## Suggested release decision
Publish homepage-only *minimal* update before Friday Oct 23 if QA passes. Keep the older pages online. Revise the other pages or the complete CMS implementation after launch as the next stage. Avoid making an unreviewed theme migration two days before SEP.
