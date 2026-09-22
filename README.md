# openwonderful.github.io

Plain static site for https://openwonderful.github.io — no build step, no framework.

- `index.html` — the page. Add links in the `<ul class="links">` lists.
- `style.css` — styling, light/dark aware.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Publish

1. Create a **public** repo named exactly `openwonderful.github.io` under the openwonderful account.
2. Push this folder to its `main` branch.
3. On GitHub: Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `/ (root)`.

The site goes live at https://openwonderful.github.io within a minute or two.

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```
