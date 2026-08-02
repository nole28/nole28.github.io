# Live Portfolio

## [Open Novak Velimirović’s portfolio](https://nole28.github.io)

# Novak Velimirović — iOS Portfolio

## Preview locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Project structure

```text
novak-portfolio/
├── index.html
└── assets/
    ├── portrait.jpg
    ├── espres-demo.mp4
    ├── espres-demo-poster.jpg
    ├── espres-feed.webp
    ├── espres-short-video.webp
    ├── espres-upload.webp
    ├── chatside-demo.mp4
    ├── chatside-demo-poster.jpg
    ├── chatside-inbox.webp
    └── chatside-chat.webp
```

Upload the entire folder when deploying. The HTML uses relative paths, so `index.html` and the `assets` folder must stay together.
