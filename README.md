# purlo-site

Marketing site for [Purlo](https://purlo.dev) — served by GitHub Pages at the
apex domain `purlo.dev`.

Static single page (`index.html`), no build step. The signup form and pricing
buttons call the live API at `https://api.purlo.dev` (`/v1/signup`,
`/v1/billing/checkout`), which must allow the `https://purlo.dev` origin via CORS.

## Files

- `index.html` — the whole site (styles + markup + script inline).
- `favicon.svg` — brand tile icon.
- `CNAME` — custom domain (`purlo.dev`); GitHub Pages reads this.
- `.nojekyll` — serve files as-is, skip Jekyll.

## Source of truth

Developed in the main app repo under `site/` and pushed here. Edit there, then
push to this repo (or edit here directly for small fixes).

© Axiom Testing Ltd.
