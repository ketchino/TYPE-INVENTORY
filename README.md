# TYPE://INVENTORY

A fan-made inventory & trading tool for **Type Soul** (Roblox).

Built because I was tired of updating my trade list manually every time, set the font, the color, etc... so I made this up.

**[Live demo](https://ketchino.github.io/TYPE_INVENTORY/)**

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
- **Language switch** — there's a button in the top bar to switch between Italian and English (more languages to come)

## How to use

1. Open the [live demo](https://ketchino.github.io/TYPE://INVENTORY/) to try it, or download `index.html` and open it locally for everyday use.
2. Add your items from the dropdown — values update automatically.
3. Use the trade calculator before agreeing to a trade, so you know what's fair.
4. Export your inventory anytime to back it up.

Everything is saved locally in your browser (`localStorage`) — nothing is sent anywhere except the read-only fetch of trade values from the Google Sheet.

## ⚠️ Import/Export disclaimer — read this

The Export TXT feature is meant for backing up **your own** inventory.

**Do not import `.txt` files sent to you by other people.** You have no way of knowing what's actually inside a file someone else gives you, even if it looks like a normal export. Only import files that you exported yourself.

## Security

This tool is plain HTML/CSS/JavaScript with no build step — anyone can open it in a text editor and read exactly what it does, there's nothing hidden or compiled. If you want third-party confirmation it's clean, here's a VirusTotal scan of the file: **[VirusTotal report](https://www.virustotal.com/gui/file/4e6f2c58eb314bc144dbe43b26b818e3da22eabe3357c378b10966bf9dca2ff1/detection)**

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
