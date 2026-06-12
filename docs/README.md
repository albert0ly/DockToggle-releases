# DockToggle GitHub Pages Site

## Structure

```
docs/
├── index.html          ← main page
├── privacy.html        ← privacy policy
└── assets/
    ├── style.css
    ├── icon.png         ← add your app icon here (also used as apple-touch-icon)
    ├── og-image.png     ← 1200×630 image for link previews (Discord, Slack, iMessage, etc.)
    ├── demo.mp4         ← optional: demo video
    └── screenshots/
        └── screen1.png  ← optional: static screenshot
```

## Deploy

In your `DockToggle-releases` repository:

```
Settings → Pages → Deploy from branch → main → /docs
```

Your site will be live at:
```
https://albert0ly.github.io/DockToggle-releases/
```

## Things to complete

1. **App icon** — copy your icon PNG to `docs/assets/icon.png`

2. **OG image** — create a 1200×630 PNG at `docs/assets/og-image.png`
   This is the preview image shown when someone shares your link on Discord, Slack,
   WhatsApp, Telegram, iMessage, Twitter/X, Reddit, LinkedIn, etc.
   Suggested content: app icon + "DockToggle" text on a dark background.

3. **Demo video (recommended)** — record a short screen recording showing the toggle
   behavior, export as .mp4, place at `docs/assets/demo.mp4`.
   Then in `index.html` find the media section and uncomment the `<video>` block.

4. **Screenshot (alternative to video)** — add to `docs/assets/screenshots/screen1.png`
   and uncomment the `<img>` block instead.

5. **Donation link** — in `index.html`, replace `href="#"` on the donate button:
   - Buy Me a Coffee: `https://buymeacoffee.com/yourusername`
   - PayPal: `https://paypal.me/yourusername`
   - GitHub Sponsors: `https://github.com/sponsors/albert0ly`
   Then delete the `<p class="donate-note">` paragraph below the button.
