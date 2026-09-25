# Dr. José A. Mancera Profile Page

Live site: **https://josemancera.datasciencelab.ch** (GitHub Pages, custom domain set in `CNAME`)

This repository contains the GitHub Pages site for Dr. José A. Mancera. The site is a public professional profile that combines academic background, research interests, public ORCID publications, public code activity, and project context into a single static homepage.

## Site highlights

- Editorial, warm-neutral design (Source Serif 4 + Inter) with automatic and manual light/dark mode
- Hero section with portrait, summary, and profile links
- Doctoral research feature for the completed PhD (thesis, framework pipeline, links)
- Education, research interests, and an experience timeline
- Interactive career Sankey with a year selector that scrolls to each milestone
- Publications list aligned with the full public ORCID record, filterable by theme
- Recently active GitHub repositories plus a theme-by-year heatmap of public repositories and gists
- Research ecosystem section that preserves the SmartRehab context

## Main files

- `index.html` - the full one-page site, including styles, content, SVG, and interaction logic
- `jose-mancera-headshot.jpg` - the portrait used in the hero/profile section
- `2835968c-9b0c-43d7-b596-12b9c6bfeb06.png` - HSLU logo
- `7c4df955-e75c-4cca-80de-0c9d93106421.png` - Swiss Paraplegic Centre logo
- `snsf_logo.png` - Swiss National Science Foundation logo

## Updating the content

- Edit `index.html` to update biography, experience, publications, or layout
- Replace `jose-mancera-headshot.jpg` if you want to use a different portrait
- All data lives in JavaScript objects near the bottom of `index.html`:
  - `publicationCatalog` (one entry per ORCID work, tagged with a `theme` from `publicationThemes`)
  - `repoCatalog` (the recently active repository cards)
  - `heatmap` (qualitative level 0–5 per theme and year, with a short evidence note)
  - `trajectoryCatalog` and `trajectoryGraph` (career Sankey summaries and layout)
- Update the stats row and footer review date in the HTML when the counts change

## Local preview

Open `index.html` directly in a browser, or serve the repository with any static file server if you want a closer preview of the deployed GitHub Pages experience.

## Public sources used for the current profile

- LinkedIn: `https://www.linkedin.com/in/jose0628/`
- ORCID: `https://orcid.org/0000-0003-3837-6524`
- GitHub: `https://github.com/jose0628`
- HSLU public profile: `https://www.hslu.ch/en/lucerne-school-of-business/about-us/people-finder/person-detail-site/?pid=5892`

## Notes

- The Sankey diagram is interactive: select a year in the top bar to scroll the continuous timeline to that milestone, or scroll the chart horizontally to move through the path
- All public ORCID works currently shown on the page are grouped into topic categories
- The code heatmap is qualitative, not a raw GitHub contribution graph
- Private or organization-only code activity is not represented in the public GitHub section
