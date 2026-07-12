# Yesteryear ATL

Official static homepage for **Yesteryear ATL**, an independent music platform rooted in Atlanta's underground hip-hop scene.

## Live site

https://www.yesteryearatl.com

## About

This is a minimal single-page site: centered branding, footer social links, and no backend or build step. It is hosted as static files on GitHub Pages.

## Project structure

```
Yesteryear/
├── index.html              # Landing page
├── CNAME                   # Custom domain (www.yesteryearatl.com)
├── assets/
│   ├── css/
│   │   └── music.css       # Layout and typography
│   └── images/
│       └── logo.PNG        # Logo and favicon
└── fonts/
    └── akira_expanded.otf  # Custom display font
```

## Features

- Single-page layout with centered logo on a black background
- Footer links to Instagram, music (ffm.bio), and email
- Akira Expanded custom font for text
- Responsive scaling across screen sizes
- SEO meta tags and favicon

## Local preview

Because the site uses root-relative paths (`/assets/...`, `/fonts/...`), serve it locally instead of opening `index.html` directly:

```bash
git clone https://github.com/iambrianwalker/yesteryear.git
cd yesteryear
python -m http.server 8080
```

Then open http://localhost:8080

## Links

- Instagram: https://www.instagram.com/yesteryearatl/
- Music: https://ffm.bio/yesteryear-atl
- Email: contactyesteryearatl@gmail.com

## License

All rights reserved © Yesteryear ATL.
