# AIW · Coaching Calls

Live coaching decks for the AIW 2.0 cohort. Each deck is a single self-contained HTML file — works offline, no build step.

## Decks

| # | Session | Deck |
|---|---|---|
| 01 | Welcome to AIW | [`coaching-call-1.html`](./coaching-call-1.html) |
| 02 | The Easy Part | [`coaching-call-2.html`](./coaching-call-2.html) |

The [`index.html`](./index.html) landing page links to all decks.

## Run it locally

Just double-click any `.html` file. No server needed.

Or serve the folder with any static server:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy

**GitHub Pages** — push this folder to a repo, then in Settings → Pages, point to `main` / `/ (root)`.

**Vercel** — drop the folder onto https://vercel.com/new, click Deploy.

**Netlify** — drop the folder onto https://app.netlify.com/drop.

## Controls

- **← →** or **Space** — navigate slides
- **F** — fullscreen
- **#5** at end of URL — jump to slide 5

## Updating

Re-export the deck HTML and replace the corresponding file. Same filename, same URL.
