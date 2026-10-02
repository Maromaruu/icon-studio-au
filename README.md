# Icon Studio

Generate icons in one consistent style: tiled, flat, four colors and one pink accent.
Made by Lunch Money.

**Live app:** https://YOUR-USERNAME.github.io/icon-studio/  ← replace after setup

## What it does

- **Object icons:** type a thing ("cloud hosting", "invoice") and get 3 options built from Phosphor, Tabler and Lucide icons and our own set, restyled to the house style.
- **Abstract icons:** type a concept ("sustainability", "foresight") and get compositions made from our hi-fi glyphs, dot fields and a concept symbol.
- **Batch:** switch to Batch and enter one item per line.
- **Collection:** save, search, select, download (SVG, PNG, ZIP) and delete.

## Using it

1. Open the live link. No install, no account.
2. Optional: open **AI settings** (left column) and paste your own API key. AI is only needed for drawing things no library covers, and for the remix text box.
   - **Google Gemini:** free tier available. Get a key at https://aistudio.google.com/apikey. On the free tier Google may use prompts to improve its models.
   - **Anthropic (Claude):** best drawing quality, paid per use. Get a key at https://console.anthropic.com.
   - The key is stored only in your browser and sent only to the provider you chose.

## Good to know

- **Collections are per browser.** Each teammate's saved icons live in their own browser (localStorage). Clearing browser data deletes them, so download a ZIP of anything important. To share icons, send the ZIP.
- **Colors:** change them in the Style panel. Exports always use the current colors.
- **Licenses:** exported ZIPs include license files for any library-based icons. Keep them when sharing or selling.

## Icon libraries and licenses

This project includes restyled icons from:

| Library | License | Copyright |
|---|---|---|
| [Phosphor Icons](https://phosphoricons.com) 2.1.1 | MIT | © 2023 Phosphor Icons |
| [Tabler Icons](https://tabler.io/icons) 3.48.0 | MIT | © 2020-2026 Paweł Kuna |
| [Lucide](https://lucide.dev) 1.49.0 | ISC (parts MIT, from Feather by Cole Bemis) | © 2026 Lucide Icons and Contributors |

Tabler and Lucide icons were converted from outlines to filled shapes. Brand logos are excluded. Full license texts are in [`licenses/`](licenses/).

## Updating

The whole app is one file, `index.html`. To update it, replace that file in the repository (Add file → Upload files) and commit. GitHub Pages republishes within a minute or two.

© 2026 Lunch Money
