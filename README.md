# Transcend Fastpitch — concept redesigns

Two design directions for transcendfastpitch.com, plus a launcher that flips between them.

## Files

| File | What it is |
|---|---|
| `index.html` | Launcher — A/B switcher with a live preview |
| `design-a.html` | Direction A, "The Circle" — navy + raspberry, interactive pitch arsenal |
| `design-b.html` | Direction B, "App Native" — matches the members app, heavy app-download focus |
| `app-screen.jpg` | Screenshot of the real members app, used in Direction B |

Keep all four in the same folder. No build step, no dependencies.

## Put it on GitHub Pages

1. Create a new repo (e.g. `transcend-concepts`).
2. Upload all four files to the root of the repo.
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, folder: `/ (root)` → Save.
4. Wait about a minute, then open `https://<username>.github.io/transcend-concepts/`.

Direct links once live:

- `.../` — the switcher
- `.../#b` — opens straight to Direction B
- `.../design-a.html` and `.../design-b.html` — full pages, no chrome

## Notes

- Both pages pull Jiana's existing photos from the Wix CDN. If those URLs ever change, the image
  areas fall back to brand-colored gradients rather than breaking.
- Drill names inside the Direction B phone are placeholders except **Arm Slot Snaps** and
  **Butterfly W's**, which come from the real app.
- The QR code in Direction B points to `members.transcendfastpitch.com`.
