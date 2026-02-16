# katieflynndesign.com — Holding Page

A minimal, editorial holding page for [katieflynndesign.com](https://katieflynndesign.com) while the portfolio is being rebuilt.

---

## About

This page serves as a temporary landing page for Katie Flynn's portfolio site. It communicates availability for work, links to LinkedIn, and gives visitors a sense of design sensibility while the full portfolio is under construction.

---

## Built With

- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) — Google Fonts
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) — Google Fonts
- Hosted on GitHub Pages

---

## Features

- Fully responsive (mobile, tablet, desktop)
- Staggered entrance animations on load
- Scrolling skills marquee
- Grain texture overlay for depth
- No build step required — single `.html` file

---

## Local Development

No setup needed. Just open `index.html` in your browser:

```bash
open index.html
```

Or clone the repo:

```bash
git clone https://github.com/yourusername/katieflynndesign.com.git
cd katieflynndesign.com
open index.html
```

---

## Deployment

Hosted via **GitHub Pages** with a custom domain connected through Bluehost DNS.

DNS records in Bluehost point to:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

CNAME `www` points to `yourusername.github.io`

Custom domain set in **GitHub → Settings → Pages → Custom Domain**.

---

## Updating the Page

Since this is a single file, all edits are made directly in `index.html`:

- **Copy/text** — search for the text you want to change and edit inline
- **Colours** — all colours are CSS variables at the top of the `<style>` block
- **Skills marquee** — find the `marquee-item` spans and add/remove skills
- **Stats** — find the `stat` divs in the right column and update clients/numbers

---

## Replacing With Full Portfolio

When the full portfolio is ready:

1. Delete `index.html` from this repo
2. Upload the new portfolio files
3. If moving back to Adobe Portfolio or another platform, update DNS records in Bluehost accordingly
4. Remove the custom domain from GitHub Pages settings before pointing DNS elsewhere

---

## Contact

**Katie Flynn**
- Email: katieaflynn2@gmail.com
- LinkedIn: [linkedin.com/in/katieflynn2](https://linkedin.com/in/katieflynn2)
- Portfolio: [katieflynndesign.com](https://katieflynndesign.com)
