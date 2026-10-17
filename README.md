# pb-portal (generated mirror)

This repository exists **only** to serve the Prestige Black **client portal** at
`https://portal.prestigeblackrentals.com/`.

It is a **generated mirror** -- do **not** hand-edit `index.html` or `pb-config.js` here.

- **Canonical source of truth:** [`prestigeblackcorp-dev/PB-Dashboard`](https://github.com/prestigeblackcorp-dev/PB-Dashboard) -> `docs/portal.html` and `docs/pb-config.js`.
- The **`Sync portal from PB-Dashboard`** workflow pulls those two files and publishes them here (runs daily + on manual dispatch).
- The admin dashboard (`index.html` in PB-Dashboard) is **intentionally not in this repo**, so it is never reachable at the portal domain.

To update the portal: edit it in PB-Dashboard and deploy as usual, then run the **Sync portal** workflow (Actions tab -> Run workflow) for an immediate refresh.
