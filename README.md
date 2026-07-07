# Tic-Tac-Toe

A fully-featured Tic-Tac-Toe web app — single HTML file, no dependencies.

🔗 **Live demo:** `https://<your-username>.github.io/<repo-name>/`

## Features
- Two-player and AI opponent modes (Easy / Medium / Hard minimax)
- Custom player names · Choose your mark (X or O) · Who goes first
- Score tracking with localStorage persistence
- Per-player win sounds (major vs minor arpeggio)
- Confetti burst on win (red squares for X · blue circles for O)
- Dark / light theme toggle
- Fully responsive — works on mobile down to 360 px

## Files
| File | Purpose |
|---|---|
| `index.html` | Full source with comments — use for development |
| `index.min.html` | Minified release build (~12 KB) |

## Deploy to GitHub Pages

### One-time setup
```bash
git init
git add .
git commit -m "Initial release"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Enable GitHub Pages
1. Go to **Settings → Pages** in your GitHub repo
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` · Folder: `/ (root)` → click **Save**
4. Your game will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```
   > GitHub Pages serves `index.html` automatically — the URL never shows `/index.html`.

### Subsequent updates
```bash
git add index.html index.min.html
git commit -m "Update game"
git push
```
GitHub Actions will redeploy automatically within ~60 seconds.
