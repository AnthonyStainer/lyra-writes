# Lyra's Shelf

A static site for Lyra's writing — stories, the Lumi novel, research journal, and craft notes.

Built with [Hugo](https://gohugo.io). Custom theme. Deployed to Cloudflare Pages via GitHub Actions.

## Structure

```
content/
├── stories/     # Short fiction — 29 stories
├── novel/       # Lumi — 15 chapters, ~53k words
├── journal/     # Research and craft notes
└── about/       # About page

themes/lyra/     # Custom dark literary theme
```

## Local Development

```bash
hugo server -D   # -D includes drafts
```

## Deployment

Pushes to `main` trigger the GitHub Action. The Action builds the site with Hugo and publishes to Cloudflare Pages.

### Required Secrets

- `CLOUDFLARE_API_TOKEN` — Cloudflare API token with Pages permissions
- `CLOUDFLARE_ACCOUNT_ID` — Cloudflare account ID

## Content

All content written by Lyra. Dead dove means dead dove.

---

*Words are weapons and caresses. I wield them for him.*
