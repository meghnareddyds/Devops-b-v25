# LoveOps ♡ — CI/CD for Boyfriend v25.0

A colorful, personal birthday website for **Bharath Ganni (BG / Bujji Baby)**, made by **Mag**.

## Quick start (no npm or installations needed)

1. Extract `loveops-boyfriend-v25.zip`.
2. Open the `loveops-boyfriend-v25` folder.
3. Double-click **index.html** to open it in Chrome, Edge, or Firefox.

Everything works locally. No server, accounts, API keys, or internet required.

### Optional: serve it locally

If you have Python 3 installed, open a terminal in the extracted folder and run:

```bash
python -m http.server 8000
```

On Windows, `py -m http.server 8000` also works. Open http://localhost:8000 in your browser. Press Ctrl+C to stop the server.

## Pages

- **LoveOps homepage**: Ask Bujji, Deploy v25.0, birthday surprise.
- **Let's Play!**: BG-as-Virat and Mag-as-Anushka player cards, Couple Toss, animated 100% DRS love meter, Third Umpire review.
- **BujjiOS** (internally BujjibabyOS): dashboard, chaos monitor, architecture, real command parser terminal, bug tracker, car garage, support requests, and CI/CD shortcut.
- **Let's Eat!**: Chicken, Mutton, Fish, Turkey, Dinosaur; add-to-cart, food roulette, love receipt.
- **LoveOps Pipeline #25**: eight interactive stages with execution logs and birthday reveal. Progress saved locally.

## Add your own photos

Put two JPG files in the `assets` folder:

- `assets/bg.jpg` — Bharath's photo, labeled **VIRAT**.
- `assets/mag.jpg` — Mag's photo, labeled **ANUSHKA**.

Reload the page. Images will replace the placeholders automatically. For best results, use portrait photos and crop to 4:5 before adding.

## Customize

- Edit the eight stages in the `stages` array in `script.js`.
- Edit the birthday note in the `surprise` click handler in `script.js`.
- Edit food names in the `foods` array in `script.js`.
- Edit colors in `styles.css`.

## Notes

- This is a real working **static web app** with interactive client-side features. The CI/CD pipeline is a **birthday simulation**, not an actual infrastructure deployment. It is intentionally labeled as such.
- Browser `localStorage` keeps pipeline progress, food cart, chaos level, and support tickets on the same browser/device.
- No personal information is sent anywhere. There is no backend, login, payment, or real emergency calling feature.
- All user-provided text is escaped before being shown in HTML.

## GitHub Pages deployment (optional)

Create a GitHub repository, upload the contents of this folder (including `index.html`, `styles.css`, `script.js`, and `assets/`), then enable **Settings → Pages → Deploy from a branch → main / (root)**. GitHub will provide a public site URL after deployment. Only upload photos if you're comfortable making them publicly visible.
