⚔️ Pendragon Pool Generator
A simple web tool for running a casual Pendragon Magic: The Gathering tournament. Each player generates a personal random pool of common creatures and legendary equipment, picks one of each for their command zone, then builds their deck.

🃏 What is Pendragon?
Pendragon is a community-created Commander variant built around two ideas:

The Arthur — a common creature that serves as your commander
The Excalibur — a legendary equipment that starts alongside it in the command zone

Core rules:

100-card singleton deck (98 cards + 2 command zone cards)
All 98 deck cards must be common (or have a common printing)
Color identity = combined colors of your Arthur + Excalibur
Starting life: 30 | Commander damage: 21

Full rules: sites.google.com/view/pendragonmtg

🎲 How This Tournament Works

Each player visits the page and clicks Generate My Pool
You receive 15 random common creatures and 10 random legendary equipment — your personal pool
Pick one Arthur and one Excalibur from your pool (honor system — no rerolling!)
Build your 98-card deck using any legal common cards
Show up to the event and play

Because every player's pool is randomly generated, no one can tune a perfect command zone in advance — it keeps things fun and fair.

🚀 How to Use
Just open index.html in any browser, or visit the live GitHub Pages link below.
Live site: https://YOUR-USERNAME.github.io/YOUR-REPO-NAME

🛠️ Customizing the Card Pool
Open index.html in any text editor. Near the top of the <script> section you'll find two arrays you can freely edit:
jsconst COMMONS = [
    // Add or remove common creatures here
];

const EQUIPMENT = [
    // Add or remove legendary equipment here
];
All card names must match exactly as they appear on Scryfall — the tool fetches card images live using the Scryfall API.

📁 Deployment (GitHub Pages)

Create a new GitHub repository
Upload index.html and rename it to index.html (it already has this name)
Go to Settings → Pages
Under Source, select main branch and / (root)
Click Save — your site will be live at https://YOUR-USERNAME.github.io/YOUR-REPO-NAME


Card images and data provided by Scryfall. Pendragon format created by the MTG community.
