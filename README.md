# The Republic — A Companion

An interactive, single-page reader's companion to Plato's *Republic*. It is not
the text of the dialogue itself but a way *in*: a compact guide to the argument,
the cast, the imagined city, and the ideas that have kept the book alive for
two and a half thousand years.

**Live site:** https://bip-river.github.io/Plato-s-Republic/

## What's inside

The companion is organized into a few ways of approaching the work:

- **Start Here** — what the book is, the situation it stages, and how to use the guide.
- **The Proof** — a walk through the central argument (is it better to be just?).
- **The Room** — the speakers at Cephalus' house and the figures who haunt the book.
- **The City** — the ideal city built in speech as a model of the soul.
- **Index** — every entry, cross-linked, browsable by type.

## Running it locally

There is no build step and there are no dependencies. Everything — markup,
styles, and behavior — lives in a single self-contained `index.html`.

```bash
# clone, then just open the file
open index.html          # macOS
xdg-open index.html      # Linux
```

Or serve it over HTTP if you prefer:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing (GitHub Pages)

The site is a static file, so GitHub Pages serves it directly:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the branch and the `/ (root)` folder, then **Save**.

An empty `.nojekyll` file is included so Pages serves the HTML as-is without
running it through Jekyll. Once enabled, the site is available at
`https://bip-river.github.io/Plato-s-Republic/`.

## License

This project is dual-licensed:

- **Code** (the HTML/CSS/JS that renders the site) — [MIT License](LICENSE.md).
- **Written content** (the companion's commentary and design) —
  [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE.md).

Plato's *Republic* itself is in the public domain; only the original commentary
and presentation in this companion are covered. See [LICENSE.md](LICENSE.md) for
the full terms.
