# James Perry — Project Management portfolio

A single-page portfolio website. One `index.html` file + an `assets` folder. No build step, no dependencies — it just opens in a browser.

## Folder structure
```
jperrypm-site/
├── index.html            ← the whole website
└── assets/
    ├── img/              ← logo, favicon, all case-study photos
    └── cv/James-Perry-CV.pdf   ← linked by the "Download CV" buttons
```

## What's placeholder (amend these)
Open `index.html` in any text editor and search for the word `PLACEHOLDER`. The made-up bits are:
1. **Case study numbers** — value / sq ft / programme / trades for Cardiff, Stratford, Belfast, Luton, plus the one-line descriptions.
2. **The stats bar** under the hero (£100m, 12+, 230k, 4+).
3. **Tools list** — only *Microsoft Project* and *Airtable* are confirmed; the rest are examples.

Other easy edits:
- **Contact email** — currently `jtp1998@icloud.com`. To use a domain email later, search for `jtp1998@icloud.com` and replace both spots.
- **Swap a photo** — drop a new image into `assets/img/` and update the matching `src="..."` in `index.html`.
- **New CV** — replace `assets/cv/James-Perry-CV.pdf` (keep the same filename and the buttons keep working).

## Publish it (same flow as before)
1. **GitHub** — create a new repo, upload the whole `jperrypm-site` folder (or push it).
2. **Netlify** — New site → import from GitHub → pick the repo. Leave build command blank, publish directory = `/` (root). Deploy.
3. **Domain** — in Netlify: Domain settings → add `jperrypm.co.uk` → follow the DNS records Netlify shows, and point the domain's DNS at them from wherever it's registered.

That's it — every push to GitHub auto-republishes.
