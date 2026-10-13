WEARWISE — INSTALLABLE PWA PACKAGE

This folder contains the existing Wearwise outfit picker, prepared as a Progressive Web App (PWA). Wardrobe data uses browser local storage; the app does not upload wardrobe data.

IMPORTANT: It cannot be installed properly when opened as file:// from Downloads. It must first be served from an HTTPS website. This package is ready to publish, but has not been published online for you.

FREE ROUTE: GITHUB PAGES
1. On a computer, sign in to GitHub and create a new PUBLIC repository named wearwise.
2. Upload these five files from this folder to the repository root: index.html, manifest.json, sw.js, icon-192.png, icon-512.png.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose “Deploy from a branch”. Select branch “main” and folder “/ (root)”, then Save.
5. Wait for GitHub Pages to publish. The URL will look like https://YOUR-GITHUB-USERNAME.github.io/wearwise/
6. Open that HTTPS address on your Android phone in Chrome.
7. Open Chrome's ⋮ menu and choose “Install app” or “Add to Home screen”. Wording varies by Chrome version.
8. Open the installed app and use Backup to export a compact JSON backup after adding clothes.

DATA NOTE: Wardrobe data stays in the browser storage on the device/browser where you add it. Opening the app in another browser or clearing browser data may not carry data over. Export the compact JSON backup regularly and import it if needed.
