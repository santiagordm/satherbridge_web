# Sather Bridge website: how we work

One-page website for Sather Bridge (executive marketing advisory), live at https://satherbridge.com via GitHub Pages. Read DESIGN.md before any design work.

## Rule zero: privacy and security first
This repository is public. Commit only what the website needs. Never commit client information, contracts, personal data, credentials, internal notes or strategy documents. When in doubt, leave it out and ask the owner.

## Workflow for changes
1. The owner gives feedback.
2. Edit `index.html` and review a private preview at desktop and phone width.
3. The owner approves.
4. Commit and push to `main`. GitHub Pages publishes in 1–2 minutes; every version stays in git history.
- Redesigns or new sections follow the two-pass process in DESIGN.md. Small text edits skip Pass 1.

## Files
- `index.html`: the whole site (inline CSS and JS).
- `legal.html`: legal notice and privacy.
- `assets/img/`, `assets/logos/`: web-optimized images. Logos are shown in grey via CSS filters.
- `CNAME`: custom domain.
- `_config.yml`: keeps documentation files out of the published site.

## Content rules
- English, plain language, no AI buzzwords (leverage, unlock, navigate, seamless, journey, landscape, ecosystem, empower, elevate…).
- Never invent or round up metrics.
