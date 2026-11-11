# max.mouries.net

Portfolio site for Max Mouries, violinist. Plain HTML and CSS, no build step.

## Editing

- All content is in `index.html`. Search for `EDIT` to find every placeholder.
- Photos go in `images/` (e.g. `images/max.jpg`).
- Styling is in `style.css`.

To preview locally: `open index.html`.

## Publishing

The site is hosted on Cloudflare Pages, connected to this GitHub repo.
Every push to `main` redeploys automatically within a minute:

```sh
git add -A && git commit -m "Update concerts" && git push
```
