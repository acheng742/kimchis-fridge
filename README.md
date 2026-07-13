# 🥕 Kitchen Inventory

A single-page app to track every ingredient in your refrigerator, freezer, pantry, and spice drawer — with AI photo recognition and meal suggestions.

## Features
- **Four storage locations** with tabs, search, and quantity +/- controls
- **📷 Photo recognition** — snap a picture of groceries; Claude identifies the ingredients, you confirm, they're added
- **🍽️ Meal ideas** — AI looks at what you have and suggests meals, showing what you'd still need to buy
- **Backup** — export/import your inventory as JSON from Settings

## Setup
1. Open the app and tap ⚙️ Settings
2. Paste an Anthropic API key (get one at https://console.anthropic.com/settings/keys)
3. Start adding ingredients!

Your inventory and API key are stored only in your own browser (localStorage) — nothing is sent anywhere except photos/inventory to the Anthropic API when you use the AI features.

## Hosting
This is a single `index.html` — host it on GitHub Pages: repo → Settings → Pages → deploy from the `main` branch.
