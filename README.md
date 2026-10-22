# Woodboard Designer — Browser Edition

This edition runs entirely in the browser using HTML, CSS and JavaScript. It does not require Python, a server-side calculation service, or third-party libraries.

## Publish with GitHub Pages

1. Create a **public** repository named `woodboard-designer` under your GitHub account.
2. Upload the contents of this folder to the repository root (especially `index.html`, `manifest.webmanifest`, `icon.svg`, and `service-worker.js`). Do not upload the enclosing folder itself as a nested folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for the deployment to complete. Your site should be at `https://sampletime.github.io/woodboard-designer/`.

GitHub Pages sites and repositories on the Free plan are public. Only upload files you are comfortable making public. The app's calculations and SVG export are performed locally in your browser. This static version does not send your designs to a server.

## Install on a device

After publishing, open the site in Safari on iPhone/iPad and use **Share → Add to Home Screen**. The service worker caches the app for later use after it has loaded once, subject to browser storage policies.

## Local testing

Open `index.html` directly for a basic test. Service-worker/offline installation features require a secure context such as the published HTTPS site or a local development server.
