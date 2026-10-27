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
| `images/about.jpg` | About section — optional. A planting-plan drawing shows until one is added; a real on-site photo would be stronger. |
| `images/project-1.jpg` … `project-4.jpg` | project cards (landscape, ~1200x750) |

Until a photo is added, its slot shows a labelled placeholder — nothing breaks.

Project titles, descriptions and tags in the Work section are placeholders too.
Edit them in `index.html` under `<!-- ================= WORK ================= -->`.

## Contact

No contact form. GitHub Pages serves static files only and answers a POST with
405, so a form here would silently lose messages. The section lists email,
phone and LinkedIn instead, with a mailto button.

If a form is ever wanted, formspree.io handles the backend on a free tier.

## Editing

No build step and no dependencies. Open `index.html` in a browser to preview,
commit, and GitHub Pages redeploys within a minute.
