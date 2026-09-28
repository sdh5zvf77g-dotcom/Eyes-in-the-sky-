# Eyes in the Sky

Free live NASA / satellite camera feeds. Works as an iPhone Home Screen app.

## Upload to GitHub (important)

1. Create a **new public repository** named e.g. `eyes-in-the-sky`
2. **Do not** put files inside another folder — upload so that `index.html` is at the **root** of the repo
3. Upload these items:

```
index.html
manifest.json
sw.js
.nojekyll
README.md
eyes-icons/   (entire folder)
```

4. Go to **Settings → Pages**
5. Source: **Deploy from a branch**
6. Branch: `main` (or `master`) · Folder: `/ (root)`
7. Click Save and wait 1–2 minutes

Your site will be at:

```
https://YOUR-USERNAME.github.io/eyes-in-the-sky/
```

Open that exact URL in **Safari** on iPhone.

## Add to iPhone Home Screen

1. Open the GitHub Pages link in **Safari** (Chrome will not work for Add to Home Screen)
2. Tap the **Share** button
3. Tap **Add to Home Screen**
4. Confirm — the alien icon appears on your Home Screen

## Wallpaper

Use `eyes-icons/iphone-wallpaper.jpg` → Share → Use as Wallpaper.

## Common fixes if it "doesn't work"

| Problem | Fix |
|--------|-----|
| 404 / blank page | `index.html` must be at repo root, not inside a subfolder |
| Pages not live | Settings → Pages → make sure branch is published |
| No icon / can't install | Must use **Safari**, not Chrome or in-app browser |
| Old version | Clear Safari cache or open in Private tab, or wait a minute after push |
| YouTube black | Normal if ISS is on night side or feed is offline |

## Test checklist

- [ ] Open `https://YOUR-USERNAME.github.io/REPO/` in Safari
- [ ] You see the dark space UI and live camera cards
- [ ] YouTube videos play (may need to tap)
- [ ] Share → Add to Home Screen works
- [ ] Opening from Home Screen is full-screen

Not affiliated with NASA.
