# max.mouries.net

Portfolio site for Max Mouries, violinist. Plain HTML and CSS, no build step.

**Test site:** https://marcmouries.github.io/max.mouries.net/

## Editing

- All content is in `index.html`. Search for `EDIT` to find every placeholder.
- Photos go in `images/` (e.g. `images/max.jpg`). Keep full-size originals in `originals/`, which is not committed.
- Styling is in `style.css`.

To preview locally: `open index.html`.

## Publishing

A test version is hosted on GitHub Pages from the `main` branch (the final home will be max.mouries.net).
Every push to `main` redeploys automatically within a minute or two:

```sh
git add -A && git commit -m "Update concerts" && git push
```
