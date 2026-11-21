# Portfolio — edits made 2026-11-14

## Update 2026-11-19 — Star's Cafe added
- New first project card: **Star's Cafe — Nalasopara East** — the display and
  owner-management website for Krishna's own cafe (since 2022), live at
  https://stars-cafe-order-online.netlify.app/ with code at
  https://github.com/krishnajais466/stars-cafe-website (real repo).
- Card visual is a CSS tile in the cafe's own cream/brown/purple branding
  (no cafe photo exists yet); it shows the 4.9★ (199 Google reviews) and
  100% Pure Veg marks, the 95-item real menu, and the owner dashboard.
- Projects intro now says "Four projects" and the Open Graph description
  lists Star's Cafe first. Everything else is unchanged.

Edited from the zip you sent (`profile pic 1.zip`): `index.html` + your
profile photo + the 3 project screenshots. No files were renamed, so your
Netlify deploy works the same way: drag this whole folder into Netlify, or
replace the files in your existing site.

## What changed

1. **Live Demo + Code on every project** (this was the biggest gap)
   - Aditi Real Estate — Live Demo: https://aditirealestate.netlify.app/
     Code: links to https://github.com/krishnajais466?tab=repositories
   - Digital Bharat Rail — Live Demo: https://irctc-isomorphism-version-by-krishna.netlify.app/
     Code: links to https://github.com/krishnajais466?tab=repositories
   - Kinetic v3.4 — Live Demo: https://vibee-checker.netlify.app/
     Code: https://github.com/krishnajais466/vibe-checker (real repo, found on your GitHub)

   Why the first two point to your profile, not a repo: I checked
   github.com/krishnajais466 — your public repos are `vibe-checker`,
   `portfolio-krishna`, `personal-budget-spillter`, and
   `wcd-bank-iac-automation`. There is no public repo for Aditi or
   Digital Bharat Rail, so I did not invent repo URLs. When you publish
   those repos, replace the two profile links in `index.html` (search for
   `<!-- No public repo for` — the exact spot is marked in the code).

2. **Proof of what you actually built, per project**
   - Each project now has a short "what I built" list and a
     "What the demo shows:" line with concrete details taken from the
     screenshots you sent (prices and locations for Aditi, speed / routes /
     on-time rate for Rail, the 50-question quiz and its topics for Kinetic).
   - No invented numbers. Nothing here claims a result you did not show.
   - Buzzwords toned down: the hero and About sections now say plainly
     what you do (React, Node.js, Three.js, responsive interfaces) instead
     of "cutting-edge", "isomorphic architectures", "scalable full-stack
     workflows". Project tags now name the actual features (Train Search,
     PNR Status Check, Tatkal Flow, etc.).

3. **LinkedIn, GitHub, and Resume at the top**
   - GitHub (https://github.com/krishnajais466) and LinkedIn
     (https://www.linkedin.com/in/krishna-jaiswal-it/) now have visible
     text labels in the hero, not just icons, plus a Resume link in the
     top nav, the mobile menu, and a "Download Resume" button in the hero.
   - A resume is included: `Krishna-Jaiswal-Resume.pdf` (2 pages, built
     only from facts already in your portfolio — projects, skills,
     education, certifications). If you already have your own resume PDF,
     just replace that file with yours using the exact same filename and
     all three links keep working.

4. **Small fixes**
   - Fixed `sm:w-84` (not a real Tailwind size) to `sm:w-80`.
   - Fixed "Shader Shading Basics" to "Shader Basics".
   - Project images now lazy-load.
   - Added Open Graph tags so the link looks better when shared.

## How to use this zip
- Unzip, then drag the folder into Netlify (or replace the files in your
  current Netlify site). The `index.html` must stay in the same folder as
  the images and the resume PDF.
- To update the two GitHub links later, open `index.html`, search for
  `No public repo for`, and swap the profile URL for the repo URL.
- To use your own resume, replace `Krishna-Jaiswal-Resume.pdf` with your
  file under the same name.

## Files in this zip
- `index.html` — edited portfolio
- `profile pic 1.jpeg` — unchanged
- `Screenshot 2026-10-11 181932.png` — Aditi, unchanged
- `Screenshot 2026-10-11 182014.png` — Digital Bharat Rail, unchanged
- `Screenshot 2026-10-11 181957.png` — Kinetic, unchanged
- `Krishna-Jaiswal-Resume.pdf` — new, generated from your portfolio
- `README-EDITS.md` — this file
