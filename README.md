# Rang o Roop: AI WhatsApp Store Bot (demo)

A demo storefront for a made-up fashion and beauty shop (clothes, jewelry, shoes, sandals, makeup).
It shows what a WhatsApp AI assistant does for a shop owner:

- Answers price, size and stock questions in Roman Urdu, Urdu and English
- Suggests items by budget ("2000 ke andar sandal")
- Takes orders and shows them on an owner dashboard
- Hands over to a human when the customer asks
- Light and dark mode

The chat on this page is a **scripted demo** (plain JavaScript, no API key needed).
The real bot is planned with n8n + Gemini API + Google Sheets + WhatsApp Cloud API.

## Run it

No install needed. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

In Antigravity: open this folder as a workspace and run the command above in its terminal.

## Files

- `index.html`: the whole site (HTML, CSS, JS in one file)
- `data/demo-store-sheet.xlsx`: demo catalog and orders sheet (import into Google Sheets)

All products, prices and orders are made-up demo data.
