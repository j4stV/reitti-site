# Reitti website

Public landing page and privacy policy for Reitti, a personal finance app. This repository contains the static website; the application source code is private.

## Contents

- `index.html` — product overview.
- `privacy.html` — privacy policy.
- `style.css` — shared styles.
- `404.html` — error page.

The website content is currently in Russian.

## Local preview

From the repository root, run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000` in your browser. The site uses plain HTML and CSS and has no build step.
