# PFL x MyPrize - Extension v2

A two-page static site for the PFL x MyPrize partnership:

- **`index.html`** - Event Asset Wish List one-pager (the landing page)
- **`led/`** - MyPrize Sponsored LED Activation microsite (with playable videos)

The "View LED Microsite" link on the wish-list opens the LED microsite at `/led/`.
Both pages are fully mobile-optimised and need no build step.

## Live URLs (GitHub Pages)

- Wish list:  https://pfl-2026.github.io/MyPrize-Extension-v2/
- LED micro:  https://pfl-2026.github.io/MyPrize-Extension-v2/led/

## Structure

```
.
├── index.html                     # Wish-list one-pager (self-contained)
├── PFL_MyPrize_Wish_List.pdf       # Downloadable PDF copy
└── led/
    ├── index.html                  # LED microsite
    └── assets/
        ├── images/                 # in-arena + on-wrist
        ├── videos/                 # v1.mp4, v2.mp4
        ├── logos/                  # transparent PFL + MyPrize
        ├── favicons/               # blue MyPrize flame
        └── og-preview.jpg
```

## Deploy (GitHub Pages)

1. Push these files to the repo root of `PFL-2026/MyPrize-Extension-v2`
2. Settings -> Pages -> Source: `main` branch, `/ (root)`
3. Wait for the build, then visit the URLs above

## Downloads

- The wish-list header has a **Download PDF** button (saves the one-pager).
- The LED microsite topbar has a **Download** button (saves the page as a
  self-contained HTML file with the videos embedded).

---

**Status:** Confidential - For Discussion
