# Accra Life

A browser-based life and hustle simulator set in Greater Accra, inspired by Lagos Life.
Manage hunger, energy, fun, social, hygiene and bladder; work seven career tracks; study at
Legon; pay Saturday rent; survive ECG dumsor; flip thrift bales at Kantamanto; rent billboards
and waterfront plots.

## Run it

It is a single static file. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Progress is saved in the player's browser (`localStorage`). There are no accounts yet, and the
other players and leaderboard are simulated.

## Deploy

Works on GitHub Pages, Netlify or Vercel with no build step. For GitHub Pages, open **Settings**,
then **Pages**, and deploy from the `main` branch and root folder.