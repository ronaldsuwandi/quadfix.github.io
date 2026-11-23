# quadfix.github.io

Marketing site for QuadFix, a Photos editing extension for iPhone, iPad and Mac that straightens photos of
artwork and documents.

- `index.html` / `style.css`: the landing page (no build step, no web fonts; system font)
- `support/`, `privacy-policy/`: linked from the App Store listing
- `img/`: icon (`logo.svg` is `design/icon/full.svg` from the app repo), screenshots, App Store badge

Copy follows `docs/app-store.md` in the app repo; keep them in sync.
Screenshots come from `design/ios` and `design/macos` in the app repo, resized with `sips` (iOS to 1200 px tall
JPEG) and `cwebp` (Mac). The privacy policy describes Cloudflare Web Analytics (auto-injected via the Cloudflare proxy, no script tag here); update it if that changes.

Served via GitHub Pages.
