# MyPrize Sponsored LED Activation

A single-page site presenting the MyPrize fan-worn LED wristband activation. Static — open `index.html` in a browser, or serve the folder from any static host.

## Structure

```
.
├── index.html
└── assets/
    ├── og-preview.jpg              # Open Graph / social share preview (1200x630)
    ├── images/
    │   ├── led-in-arena.jpg        # LED activation - crowd lit
    │   └── led-on-wrist.jpg        # LED activation - on-wrist close-up
    ├── videos/
    │   ├── v1.mp4                  # PFL Lyon LED Activation - V1
    │   └── v2.mp4                  # PFL Lyon LED Activation - V2
    ├── logos/
    │   ├── pfl-logo.png            # Transparent
    │   └── myprize-logo.png        # Transparent
    └── favicons/
        ├── favicon.ico             # Blue MyPrize flame (multi-res 16/32/48)
        ├── favicon-16.png ... favicon-512.png
        ├── apple-touch-icon.png
        └── site.webmanifest
```

## Watch In Action

A pulsing blue **Watch In Action** button sits beneath the activation images. It opens a
modal titled **PFL Lyon LED Activation** containing two embedded videos (V1 and V2), each
playable with sound. Playing one pauses the other; Esc or the backdrop closes the modal.

## Hosting

Works on any static host - GitHub Pages, Netlify, Vercel, Cloudflare Pages, S3. No build
step, no server-side code.

### GitHub Pages quick start

1. Push this folder to a repo
2. Settings -> Pages -> Source: `main` branch, `/ (root)`
3. Visit `https://<your-username>.github.io/<repo-name>/`

## Local Preview

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

---

**Status:** Confidential - For Discussion
