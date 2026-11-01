# Esports Bracket Predictor — Laptop + Phone App

This folder contains your app as an installable Progressive Web App (PWA).

## Important
- Tournament details, team entries and picks are now saved in the browser on the device being used.
- This starter version does **not** sync data between your laptop and phone, or between different users.
- To share one live tournament across devices/users, a cloud database and sign-in/organizer permissions must be added.
- PWA installation requires the app to be served from HTTPS (or localhost). Opening `index.html` by double-clicking is useful for a quick preview, but it will not enable installation/offline caching.

## Easiest way to put it online
1. Create a free account at GitHub.
2. Create a new repository, for example `esports-bracket-predictor`.
3. Upload **all files and folders** from this folder (keep `manifest.webmanifest`, `sw.js`, and `icons`).
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to show your website address.

## Install on Windows laptop
1. Open your published website in Chrome or Edge.
2. Click the install icon in the address bar, or open the browser menu and choose **Install app**.
3. The app will open in its own window. You can pin it to the taskbar or Start menu.

## Install on Android phone
1. Open the same published website in Chrome.
2. Tap the three-dot menu.
3. Tap **Install app** or **Add to Home screen**.
4. Open it from the new home-screen icon.

## Testing before publishing
For a quick preview, open `index.html` in Chrome. For PWA installation testing on your own laptop, run a local web server from this folder (for example, VS Code Live Server) and open its localhost address.
