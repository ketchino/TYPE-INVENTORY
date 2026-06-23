# TYPE://INVENTORY

A fan-made inventory & trading tool for **Type Soul** (Roblox).

Built because I was tired of updating my trade list manually every time, set the font, the color, etc... so I made this up.

**[Live demo](https://ketchino.github.io/TYPE-INVENTORY/)**

The demo above is good for trying it out, but I'd recommend downloading the file instead for regular use — GitHub Pages previews aren't guaranteed to stay online forever, while a downloaded copy is yours to keep no matter what.

---

## Features

- **Inventory tracker** — organize your items by category, with live trade values
- **Trade calculator** — add items to both sides of a trade and instantly see who's winning
- **Wishlist** — keep a "looking for" list, reorder it by drag & drop
- **Live values** — trade values sync automatically from a public community Google Sheet
- **Trade history** — every trade you confirm gets logged, with running profit/loss stats
- **Multiple themes** — several color themes to match your vibe, plus a custom theme editor
- **Import / Export** — save your inventory as a `.txt` file (see disclaimer below before importing anything)
- **Discord-ready export** — copy a formatted preview straight into Discord
- **Value panel** — open a side panel from the left to see live trade values for every item at a glance
- **My KAN / Net Worth** — track your actual KAN balance separately, use it in trades, and see your total net worth (inventory value + KAN)
- **Language switch** — there's a button in the top bar to switch between Italian and English (more languages to come)

## How to use

**Getting started**
1. Open the [live demo](https://ketchino.github.io/TYPE-INVENTORY/) to try it, or download `index.html` and open it locally for everyday use.
2. Everything is saved locally in your browser. Nothing is uploaded anywhere except the read-only fetch of trade values from the Google Sheet — so use the same browser/device each time, or export your data before switching.

**Inventory**
- Click the input field and start typing an item name — pick it from the dropdown, set the quantity, and add it.
- Items are grouped by category automatically, with their current trade value shown next to each one.

**Value panel**
- Open the side panel from the left edge of the screen to see live trade values for every item in the game, sorted and searchable, without needing to add anything to your inventory first.

**My KAN**
- Click the **My KAN** badge in the top bar to open the KAN window.
- Type an amount directly, or use the +/− shortcuts (100, 1k, 10k, 100k, 1M) to adjust it quickly.
- Use "Reset" if you want to zero it out and start over.
- Your KAN balance is added to your inventory value to show your total **net worth**.

**Trade calculator**
- Add items (and/or KAN) to both the "give" and "receive" side.
- The total value updates live on both sides, so you can see immediately who's getting the better deal.
- Confirm the trade to log it — it'll move the items in/out of your inventory and save it to your trade history.

**Wishlist**
- Add items you're looking for. Drag and drop to reorder them by priority.

**Trade history**
- Every confirmed trade is logged automatically, with a running profit/loss total so you can see how your trading has gone over time.

**Themes**
- Pick a preset color theme from settings, or build your own with the custom theme editor.

**Import / Export**
- Export your inventory as a `.txt` file anytime to back it up.
- ⚠️ Only import files you exported yourself — see the disclaimer below.

**Language**
- Click the language button in the top bar to switch between Italian and English.

## ⚠️ Import/Export disclaimer — read this

The Export TXT feature is meant for backing up **your own** inventory.

**Do not import `.txt` files sent to you by other people.** You have no way of knowing what's actually inside a file someone else gives you, even if it looks like a normal export. Only import files that you exported yourself.

## Security

This tool is plain HTML/CSS/JavaScript with no build step — anyone can open it in a text editor and read exactly what it does, there's nothing hidden or compiled. If you want third-party confirmation it's clean, here's a VirusTotal scan of the file: **[VirusTotal report](https://www.virustotal.com/gui/file/dada07a584a413345a1e5055df40bae90c9a4312d9054f27032bae60c6222457)**

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no build step, no dependencies — just open the file or visit the page.

## Disclaimer

This is an **unofficial, non-profit, fan-made tool**. Trade value data comes from a community-maintained Google Sheet and isn't claimed as original work. All names, characters, and IP related to *Type Soul* and *Bleach* belong to their respective owners. This project is not affiliated with, endorsed by, or connected to Type Soul, Bleach, Roblox, or their rights holders.

## License

See [LICENSE](./LICENSE.txt) — all rights reserved on the original code/implementation, with the exceptions noted above for third-party data and IP.

## Credits

Made by **ketchino**.
Trade values courtesy of **[The Trade Hub](https://discord.gg/thetradehub)** — go check them out, the whole values list comes from their work.

---

Found a bug or have a suggestion? Just open an issue.
