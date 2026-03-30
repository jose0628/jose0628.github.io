# Jose A. Mancera Profile Page

This repository contains the GitHub Pages site for Jose A. Mancera. The site is a public professional profile that combines academic background, research interests, public ORCID publications, public code activity, and project context into a single static homepage.

## Site highlights

- Professional hero section with portrait, summary, and profile links
- Education, research interests, and selected experience
- Interactive dark-theme career timeline with one continuous Sankey and a year selection bar that scrolls to each milestone
- Publications section aligned with the full public ORCID record and grouped by category
- Category-based GitHub heatmap based on public repositories and gists
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
- Update the publication catalog when new ORCID items should be included
- Update the GitHub heatmap manually when public repositories or categories change
- Update the career timeline summaries in `trajectoryCatalog` and the shared graph layout in `trajectoryGraph` near the bottom of `index.html`
- Update the grouped publication data in the `publicationCatalog` JavaScript object near the bottom of `index.html`

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
