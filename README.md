# Woodshop Daily (static site)

Static, GitHub Pages–ready digest site for **Woodshop Daily** — dark walnut / cream theme, Oct 6 deal roundup, and a front-vise mount build tip.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Enable GitHub Pages

1. Create a GitHub repository and push this folder to the **`main`** branch (do not use `gh` until you are ready).
2. On GitHub: **Settings → Pages**.
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)` — use this if `index.html` is at the repo root  
     **or** `/docs` — if you move the site files into a `docs/` directory
4. Save. After a minute or two, the site URL appears on the same Pages settings screen (typically `https://<user>.github.io/<repo>/`).

Optional: set a custom domain under **Pages → Custom domain**.

## Contents

| Path | Purpose |
|------|---------|
| `index.html` | Oct 6 digest (featured deal, 2×2 grid, build tip sidebar) |
| `about.html` | Short about page |
| `styles.css` | Responsive dark walnut / cream styles (no framework) |
| `assets/` | Product images copied from digest previews |

## Notes

- Product links go to Rockler, Woodcraft, and SlashGear. Confirm prices at checkout.
- Footer includes draft / affiliate disclosure.
- SEO: title, meta description, Open Graph tags, semantic headings, ItemList-style markup.
