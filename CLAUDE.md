# Toastmasters Claude Design Kit

This repo is a structured brand resource for AI-assisted Toastmasters design work.

## What's here

| File | Purpose |
|---|---|
| `brand-tokens.json` | Colors, gradients, typography, logo rules — all brand data |
| `asset-manifest.json` | Every logo, badge, photo, and template with raw GitHub URLs |
| `approved-phrases.json` | 8 official phrases with use-case tags |
| `css-variables.css` | Ready-to-paste CSS custom properties + utility classes |
| `compliance-checklist.md` | Pre-publish brand compliance checklist |
| `design-prompts/` | Task-specific prompt templates |
| `assets/infographic.png` | Brand kit overview card (used in README) |

## Brand rules Claude must follow

1. **Colors only from palette** — Loyal Blue `#004165`, True Maroon `#772432`, Cool Gray `#A9B2B1`, Happy Yellow `#F2DF74`, White, Black. No exceptions.
2. **Logo is untouchable** — never alter colors, proportions, or add effects. Use asset URLs from `asset-manifest.json`.
3. **One approved phrase per piece** — pick from `approved-phrases.json` matched to the use case. Never invent taglines.
4. **Font stack** — Montserrat (or BricolageGrotesque as substitute) for headlines; Source Sans 3 for body. No word art.
5. **Text on dark backgrounds** — White or Happy Yellow only.
6. **Text on light backgrounds** — Loyal Blue, True Maroon, or Black only.
7. **Photography subjects** — people presenting/meeting. No landscapes, food, animals as primary subject.
8. **No custom club logos** — clubs use the official Toastmasters logo, unaltered.

## Asset URL pattern

All assets live in the companion repo. Use raw GitHub URLs for direct embedding:

```
https://raw.githubusercontent.com/Bond7010/tm-brand-kit-assets/main/<path>
```

See `asset-manifest.json` for the full index with `id`, `label`, `url`, and `usage` per asset.

## Contacts

- Brand questions: brand@toastmasters.org
- Trademark questions: trademarks@toastmasters.org
- Brand portal: toastmasters.org (member login required)
