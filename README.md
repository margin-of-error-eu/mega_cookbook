# Receptek — Ízmátrix

A personal, interactive cookbook: flavour matrix, tagged recipe collection,
curated menus and a next-week planner. One self-contained HTML file.

## Tabs
- **Ízmátrix** — cores × seasonings × sauces, filterable by region, flavour, season, mood
- **Szakácskönyv** — the recipes, progressive filtering, inline tag + recipe editor
- **Minden** — full list grouped by region; click a dish to open its recipe
- **Menük** — curated spreads (Christmas menus, hors d'oeuvres), fully editable
- **Menü** — next week's picks + pooled shopping list

## Data
Everything lives in `index.html`. Edits (tags, recipe text, menus, ✦ ticks) are
saved to the browser's localStorage, per device. Use **export backup** on the
Menü tab to download `izmatrix-state.json`, and **import backup** to restore it
on another device.

## Publishing
Served as a static site — no build step. See SETUP.md.
