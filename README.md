# Game of Life

John Conway's cellular automaton — playable in the browser.

**Live demo:** https://\<your-github-username\>.github.io/game_of_life_v1

## Features

- Green = alive cells, Red = dead cells
- Click or drag on the grid to toggle cells
- Play / Pause / Step controls
- Adjustable simulation speed (1–30 fps)
- Randomise button
- Built-in presets: Glider, Blinker, Toad, Beacon, Pulsar, Glider Gun

## Deploy to GitHub Pages (one-time setup)

1. Create a new repository on GitHub named `game_of_life_v1` (or any name you like).
2. Push this folder to the `main` branch:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/game_of_life_v1.git
git push -u origin main
```

3. Go to **Settings → Pages** in your repository.
4. Under **Source**, select `Deploy from a branch`, choose `main` and `/ (root)`, then click **Save**.
5. Your site will be live at `https://<your-username>.github.io/game_of_life_v1` within ~60 seconds.

## Run locally

Just open `index.html` in any browser — no server or dependencies needed.

The original Python terminal version is in `game_of_life.py`.
