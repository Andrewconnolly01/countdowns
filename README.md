# Countdowns

A personal countdown app for iPhone. Add events with a background picture, see the days, hours and minutes left, theme the main page, and set a calendar reminder for each one. All data is stored on your phone only.

## Files (all go in the top level of the repository, no folders)

- `index.html` – the app
- `manifest.webmanifest` – lets it install as a home-screen app
- `sw.js` – lets it open offline
- `icon-180.png`, `icon-192.png`, `icon-512.png` – app icons

## Put it online with GitHub Pages

1. Sign in at github.com, click **+** (top right) then **New repository**.
2. Name it `countdowns`, set it to **Public**, tick **Add a README file**, and click **Create repository**.
3. On the repository page click **Add file → Upload files**. Drag in all 6 files (`index.html`, `manifest.webmanifest`, `sw.js` and the three `icon-` PNGs). Click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait 1–2 minutes and refresh the Pages screen. A link appears at the top: `https://YOUR-USERNAME.github.io/countdowns/`

## Install it on your iPhone

1. Open that link in **Safari** (it has to be Safari).
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open it from the new **Countdowns** icon on your home screen.

## Good to know

- Your data lives inside the home-screen app. If you used the link in Safari first, that data is separate, so add your countdowns inside the home-screen app.
- Deleting the app from your home screen also deletes its data.
- Photos are shrunk when you add them. Storage is roughly 5 MB, which is plenty for dozens of pictures.
- The in-app alert at zero only shows while the app is open (or the next time you open it). For alerts when the app is closed, use **Add to Calendar** on the countdown.
- To update the app later, upload the new `index.html` to GitHub (and change `countdowns-v1` to `countdowns-v2` in `sw.js`), then open the app twice.
