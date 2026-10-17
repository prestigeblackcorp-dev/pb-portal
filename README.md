# pb-portal (generated mirror)

This repository exists **only** to serve the Prestige Black **client portal** at
`https://portal.prestigeblackrentals.com/`.

It is a **generated mirror** -- do **not** hand-edit `index.html` or `pb-config.js` here.

- **Canonical source of truth:** [`prestigeblackcorp-dev/PB-Dashboard`](https://github.com/prestigeblackcorp-dev/PB-Dashboard) -> `docs/portal.html` and `docs/pb-config.js`.
- `index.html` / `404.html` here are byte-copies of the canonical `docs/portal.html`; `pb-config.js` is a byte-copy of the canonical `docs/pb-config.js`. They are **refreshed from canonical whenever the portal is deployed** (same pattern as `docs/index.html` being built from `main.html` in PB-Dashboard).
- The admin dashboard (`index.html` in PB-Dashboard) is **intentionally not in this repo**, so it is never reachable at the portal domain. Any unknown path serves the portal (`404.html`), so nothing about the site's structure is exposed.

**To update the portal:** edit it in PB-Dashboard (`docs/portal.html`) and deploy as usual, then re-push the mirror from canonical. (This can be fully automated with a GitHub Action if a token with `workflow` scope is added.)
