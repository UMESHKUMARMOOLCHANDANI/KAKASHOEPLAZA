# Kaka Shoe Plaza

Static, single-file HTML e-commerce catalogue site for Kaka Shoe Plaza (Satna, MP) — no backend, WhatsApp-enquiry only.

`index.html` fetches `kaka-shoe-plaza-data.json` for its product/category/FAQ data at load time, falling back to its own embedded data if the fetch fails (e.g. when opened via `file://` instead of a real web server).

## Running locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

Can be published as-is to GitHub Pages, Netlify, or any static host — just keep `index.html` and `kaka-shoe-plaza-data.json` in the same folder.
