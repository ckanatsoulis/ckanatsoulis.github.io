# Barron-style HTML version

Single-page personal academic site in the Jon Barron / Shirley Wu style. Card-based paper layout with images, tabbed research topics, hash navigation. Zero dependencies.

## Preview locally

Open `index.html` in your browser.

## Files

```
kanatsoulis_barron/
├── index.html              # whole site, one file
├── assets/
│   ├── pdf/kanatsoulis_cv.pdf
│   └── img/                # drop prof_pic.jpg and paper preview images here
└── README.md
```

## Optional: add paper preview images

Each paper card has an image placeholder. To use real images, replace each `<div class="paper-img-placeholder">...</div>` with `<img class="paper-img" src="assets/img/paper-name.png" alt="...">`. Recommended size 320×220 px (2× for retina).

## Deploy

Same as the plain HTML version. Create the `marhar19.github.io` repo, push, point `kanatsoulis.com` DNS at GitHub Pages.
