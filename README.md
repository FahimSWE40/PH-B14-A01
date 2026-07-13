# DevConf 2026 - Landing Page

A responsive landing page for a fictional developer conference, **DevConf 2026**, built with
plain HTML and CSS for Programming Hero Batch 14 Assignment-01. The design follows the provided Figma layout.

> **Live Site:** https://fahimswe40.github.io/PH-B14-A01
> **Repository:** https://github.com/FahimSWE40/PH-B14-A01

---

## About

DevConf 2026 is a single-page website for a 3-day developer conference. It was hand-coded
with only HTML5 and CSS3 - no JavaScript, no frameworks, and no CSS libraries. The layout,
colors, and structure are based on the Programming Hero Batch 14 assignment's Figma design.

---

##  Sections

- **Navbar** — Logo on the left, menu links in the center (Speakers, Schedule, Tracks, Venue,
  Blog), and a "Register Now" button on the right.
- **Hero / Banner** — A full-width dark banner image with an overlay, a bold heading
  ("Code. *Connect*. Create"), a short paragraph, and a centered "Register Now" button.
- **Meet the Speakers** — A 2×2 grid of four speaker cards, each with a photo, a track label
  (AI/ML, Frontend, Cloud & DevOps), a name, and a title.
- **Secure Your Spot (Pricing)** — Three pricing cards (Standard, Pro, Team). The middle
  "Pro" card is highlighted with a dark background.
- **The 48-Hour Build Sprint** — My custom AI-challenge section: an on-site hackathon with a
  three-card weekend schedule and a "Grand Prize" box. (See `PROMPTS.md`.)
- **Footer** — Logo on the left, social media icons on the right, a divider, and a copyright
  line.

---

## Tech Stack

- HTML5
- CSS3 (Flexbox & Grid)
- [Google Fonts](https://fonts.google.com/) — Poppins
- [Font Awesome](https://fontawesome.com/) — social media icons

---

## Folder Structure

```
PH-B14-A01/
├── index.html        # main HTML file
├── style.css         # all the styles
├── PROMPTS.md        # AI prompts used for the Build Sprint section
├── Readme.md         # this file
└── assets/           # images (logos, banner, speaker photos)
    ├── logo.png
    ├── footer-logo.png
    ├── banner.jpg
    ├── andrej.png
    ├── demis.png
    ├── gary.png
    └── mustafa.png
```

---

## Run Locally

1. Download or clone this repository:
   ```bash
   git clone https://github.com/FahimSWE40/PH-B14-A01.git
   ```
2. Open the folder.
3. Double-click `index.html` to open it in your browser.

That's it — no build step or server needed.

---

##  Responsive Design

The page adjusts for smaller screens using a CSS media query at `800px`. On mobile, the
navbar stacks, the speaker/pricing/sprint grids become a single column, and the footer
stacks vertically.

---

##  AI Challenge Section

The "Something Missing?" placeholder from the Figma was replaced with a brand-new section,
**The 48-Hour Build Sprint**. The prompts used to ideate and build it are documented in
[PROMPTS.md](PROMPTS.md).

---

**FahimSWE40**

---

*Built for Programming Hero -B14- Assignment-01.*
