# Korone Trading Tool

[![Install Script](https://img.shields.io/badge/Install-KoroneTradingTool-blue)](https://raw.githubusercontent.com/blufed/Korone-Trading-Tool/main/KoroneTradeTool.user.js)

Korone Trading Tool is a Tampermonkey/Violentmonkey userscript for pekora.zip with the following features:

🔑 License System

Cryptographically signed keys tied to your pekora.zip account — keys can't be shared or used on another account
Keys persist across script updates (no re-entry needed when you install a new version)
Admin panel hidden behind a hashed UID check — admin never sees the key gate

💡 Blast Tab

Mass-send trades to every owner of a target item in one click
Offer value calculator showing your offer vs their item value with a color-coded ratio
Owner filters: min/max value, skip duplicates, skip owners you already have a pending trade with
Auto-retry failed trades once before marking them failed
Adjustable delay between trades and exponential rate-limit backoff
Export blast results to CSV

📋 Trade Templates

Save up to 5 offer loadouts and reload them instantly

❌ Cancel Trades

Load and cancel all outbound trades in bulk
Filter by partner username, or select all trades older than X days with one click

📜 Trade History

View completed, declined, and expired trades with partner avatars, item counts, and dates
Export to CSV

💼 Portfolio

Load your full inventory and see total Value + RAP with a per-item breakdown

🔔 Price Alerts

Watch any item and get a browser notification when its value moves by a set percentage
Checks every 15 minutes automatically

🔍 Lookup

Item lookup: search by name or asset ID, shows value, RAP, demand, rarity
Player lookup: search by user ID, shows avatar, value, join date

⚙️ Settings

6 themes (Dark, Midnight, Rose Gold, Forest, Light, Purple Haze)
6 custom FAB button icons
User blacklist
Adjustable rate-limit backoff

✨ UX

"Hi, [Username]!" chip with your profile picture in the header
Minimize to a floating HUD while blasting runs in the background
Draggable modal and FAB button
Sidebar injection on pekora.zip
Completion sound on finish

