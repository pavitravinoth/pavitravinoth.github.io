# Pavitra G — Portfolio

Personal portfolio site for Pavitra G, landscape horticulturist in Coimbatore.

**Live site:** https://pavitravinoth.github.io

## What's here

```
index.html          the whole site — markup, styles and scripts in one file
cv.pdf              CV, linked from the "Download CV" button   (add this)
images/             photos used on the page                    (add these)
assets/linkedin/    LinkedIn banner artwork, 1584x396
```

## Still to add

| File | Used for |
| --- | --- |
| `cv.pdf` | the Download CV button in the hero |
| `images/pavitra.jpg` | hero portrait (portrait crop, ~800x900) |
| `images/about.jpg` | About section (portrait crop, ~800x1000) |
| `images/project-1.jpg` … `project-4.jpg` | project cards (landscape, ~1200x750) |

Until a photo is added, its slot shows a labelled placeholder — nothing breaks.

Project titles, descriptions and tags in the Work section are placeholders too.
Edit them in `index.html` under `<!-- ================= WORK ================= -->`.

## Contact form

The form carries Netlify's `data-netlify` attributes, so it works as-is if the
site is ever hosted on Netlify. On GitHub Pages it needs an external handler —
sign up at formspree.io and set:

```html
<form action="https://formspree.io/f/YOUR_ID" method="POST">
```

Until then the email and phone links above the form work fine.

## Editing

No build step and no dependencies. Open `index.html` in a browser to preview,
commit, and GitHub Pages redeploys within a minute.
