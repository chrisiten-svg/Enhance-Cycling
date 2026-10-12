# Saddle Strength

Enhance Cycling Team strength program for 100 to 200k endurance events. Phone app with lift drawings, a set checklist, machine swaps, a knee-care circuit, a rest timer and a session log. Works offline after the first visit.

## Put it online (GitHub Pages, free)

1. Sign in at github.com and click **New repository**. Name it `saddle-strength`, set it to **Public**, and create it.
2. On the new repo page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. Click **Commit changes**.
3. Go to **Settings > Pages**. Under **Branch**, pick `main` and `/ (root)`, then **Save**.
4. Wait a minute or two. The page shows your link, like `https://YOUR-USERNAME.github.io/saddle-strength/`.

## Install on a phone

- **Android (Chrome):** open the link, tap the three-dot menu, then **Install app** or **Add to Home screen**.
- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.

## Good to know

- Each person's checklist, weights and log are saved on their own phone only.
- To update the program, replace `index.html` in the repo, then change `VERSION` in `sw.js` (for example `v1` to `v2`) so phones load the new version.
