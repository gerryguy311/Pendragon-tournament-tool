# ⚔️ Pendragon Pool Generator
 
A simple web tool for running a casual **Pendragon** Magic: The Gathering tournament. Each player generates a personal random pool of common creatures and legendary equipment, picks one of each for their command zone, then builds their deck.
 
---
 
## 🃏 What is Pendragon?
 
Pendragon is a community-created Commander variant built around two ideas:
 
- **The Arthur** — a common creature that serves as your commander
- **The Excalibur** — a legendary equipment that starts alongside it in the command zone
**Core rules:**
- 100-card singleton deck (98 cards + 2 command zone cards)
- All 98 deck cards must be common (or have a common printing)
- Color identity = combined colors of your Arthur + Excalibur
- Starting life: **30** | Commander damage: **21**
Full rules: [sites.google.com/view/pendragonmtg](https://sites.google.com/view/pendragonmtg/basic-rules-guidelines)
 
---
 
## 🎲 How This Tournament Works
 
1. Each player visits the page and clicks **Generate My Pool**
2. You receive **15 random common creatures** and **10 random legendary equipment** — your personal pool
3. Pick **one Arthur** and **one Excalibur** from your pool (honor system — no rerolling!)
4. Build your 98-card deck using any legal common cards
5. Show up to the event and play
Because every player's pool is randomly generated, no one can tune a perfect command zone in advance — it keeps things fun and fair.
 
---
 
## 🚀 How to Use
 
Just open `index.html` in any browser, or visit the live GitHub Pages link below.
 
**Live site:** `[https://gerryguy311.github.io/Pendragon-tournament-tool`](https://gerryguy311.github.io/Pendragon-tournament-tool)
 
---
 
## 🛠️ Customizing the Card Pool
 
Open `index.html` in any text editor. Near the top of the `<script>` section you'll find two arrays you can freely edit:
 
```js
const COMMONS = [
    // Add or remove common creatures here
];
 
const EQUIPMENT = [
    // Add or remove legendary equipment here
];
```
 
All card names must match exactly as they appear on [Scryfall](https://scryfall.com) — the tool fetches card images live using the Scryfall API.
 
---
 
## 📁 Deployment (GitHub Pages)
 
1. Create a new GitHub repository
2. Upload `index.html` and rename it to `index.html` (it already has this name)
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)`
5. Click **Save** — your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`
---
 
*Card images and data provided by [Scryfall](https://scryfall.com). Pendragon format created by the MTG community.*
