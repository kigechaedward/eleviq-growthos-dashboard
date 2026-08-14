# Eleviq GrowthOS — Operating Dashboard

Live marketing command center for **Eleviq Technologies**, focusing on the MyHobbyPlan 90-day download campaign (2,000 installs, organic-first).

## Access

Open **index.html** in a browser, or visit the GitHub Pages URL once published.

## Features

- Web-app dashboard: KPI cards, install-trajectory chart, market priority, campaign table, roadmap timeline, blocker watch, experiment queue, to-dos.
- **Live sync**: on load (and every 5 minutes) the page fetches `dashboard.md` — the single source of truth — re-parses it, and re-renders all sections.
- Honest data: metrics without a source are marked `UNKNOWN`; never invented.

## Source of truth

- `dashboard.md` — the operating dashboard (edit this, then refresh the site).
- `index.html` — the dashboard UI (generated from the Eleviq GrowthOS workspace).

## Re-syncing after edits

1. Update `dashboard.md`.
2. Refresh the page (or press the `↻ Refresh` button) — no rebuild needed.
3. If the HTML itself changed, re-copy `dashboard.html` → `index.html` and push.

## Stack

Zero dependencies, single-file HTML + vanilla JS + inline SVG. Runs offline from `file://` (snapshot mode) and over HTTP/HTTPS (live sync).
