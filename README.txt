IMPERIUM AETERNUM II — VERSION 2.6 PWA-COMPATIBLE EDITION

PWA support included:
- Valid web app manifest with app ID, scope, categories, and install icons
- 192 px, 512 px, maskable, and iOS Home Screen icons
- Service worker with offline app-shell caching
- Safe navigation fallback when offline
- Standalone display and iPhone safe-area support
- Existing v2.x saves remain in the imperiumV2 localStorage slot

All in-game artwork is generated at runtime with Canvas 2D, CSS, and JavaScript.
The included app icons were also generated programmatically and use no third-party art.

DEPLOYMENT
PWA installation requires HTTPS, except on localhost. Upload this entire folder without changing its structure to GitHub Pages, Netlify, Cloudflare Pages, or another HTTPS static host.

IPHONE / IPAD
1. Open the deployed HTTPS URL in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Launch Imperium II from its new Home Screen icon.

ANDROID / DESKTOP CHROME
Open the deployed URL and choose Install when the browser offers it.

Opening index.html directly from the Files app will not activate the service worker or offline installation because browsers do not permit PWAs from file:// URLs.
