# Coverage Management

A self-contained, single-file backoffice prototype for **Coverage Management**, built in the same theme/coloring as the Reporting section. Pure vanilla JS with rich mock data — no build step, no dependencies. Open `index.html` in any browser.

## Live link

- **GitHub Pages:** https://tigransharafyan-corwyn.github.io/coverage-management/
  *(enable once under repo Settings → Pages → Source: `main` / root)*
- **Instant preview (no setup):** https://htmlpreview.github.io/?https://github.com/tigransharafyan-corwyn/coverage-management/blob/main/index.html
  *(requires the repo to be public)*

## What it covers

**Coverage tree** (Sport → Category → Tournament → Event → Market) with, in one place:

- Enable/disable **Sport / Category / Tournament / Event** — independently for **Live** and **Prematch**, cascading to children.
- Disable a **market** at Sport / Tournament / Event level — independently for Live and Prematch.
- **Ordering** on every level (Sport / Category / Tournament / Event / Market). *Per-country (IP-based) ordering is noted as a later stage.*
- **Feed providers** — add and prioritize per level (Sport / Tournament / Event / Market) **per partner**.
- **Market coverage templates** — defined per sport, applied at tournament/event level for Live & Prematch. *(Margins are intentionally managed elsewhere.)*
- **Exclusions** — re-enable a market on a tournament/event that was disabled higher up.
- **Age groups** — assign to tournaments and filter them for bulk enable/disable.
- **"What's disabled" audit overlay** — the effective switched-off view per client (nodes, markets, exclusions).

**Picked Tournaments / Picked Events**

- Pinned tournaments at the top of the left tree for one-click access to their events.
- A dedicated **Picked Events** left-menu item with a curated, fast-access event list.

> Mock/in-memory data. Wire the `NODES` model to your coverage API to go live.
