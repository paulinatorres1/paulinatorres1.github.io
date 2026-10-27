# paulinatorres1.github.io

Personal website for Paulina Torres Martínez.

The site is a standalone, responsive static page in `index.html`. Open that
file in a browser to preview it locally. Update the page copy as career,
interests, and achievement details are ready to share.

## Sections and how to update them

The page is one HTML file, organized top to bottom as: About → Career →
Career Development → Certifications → Races → Writing → Interests. Each
section is clearly commented in `index.html`. A few notes on the newer ones:

- **Career Development** (`#career-development`): a lightweight CTA that
  lists current focus areas (edit the `.tag-row` chips) and routes to
  LinkedIn for the full, always-current record of roles and coursework —
  intentionally kept light rather than duplicating LinkedIn content here.
- **Certifications** (`#certifications`): this is a static site with no
  database or upload button, so "adding" a certificate means committing a
  file to the repo. Put the image/PDF in an `assets/certifications/` folder
  (create it if it doesn't exist yet), duplicate a `.cert-card` block, and
  point its "View credential" link at that file or at the issuer's
  verification URL.
- **Races** (`#races`): add a row to `.races-table` for each race, and keep
  the three summary numbers above it (races completed, favorite distance,
  personal best) up to date.
- **Writing** (`#writing`): currently a "coming soon" placeholder. Once the
  Substack is live, replace the `.writing-card` content with a link to it
  (and consider adding it to the top navigation and footer too).

A couple of other things that update periodically:

- **Hero illustration** (`.hero-art`): a little desk illustration (laptop,
  plant, coffee, books) with two factual callouts layered on top — a red
  "Open to opportunities" chip and a "Currently: …" status card. Update or
  remove the chip once no longer job-searching, and keep the status card's
  program/employer text current. See the photo section below for how to
  replace the illustration with a real photo.
- **Snapshot stats strip** (just below the hero): four quick facts (degrees,
  languages, CPA status, Ironman distance). Update the numbers as they
  change — e.g. once the CPA is earned, swap "CPA · Candidate" for the
  credential itself.

### Adding your own photos

There's a photo placeholder between every section (and the hero
illustration can become a photo too) — see
[`assets/images/README.md`](assets/images/README.md) for the exact file
names to use. Since this is a static site, "uploading" just means saving a
correctly-named image in that folder and committing it; the page already
looks for those files and swaps them in automatically, no HTML edits
needed.

## Polish ideas worth considering later

- Swap the inline favicon/social preview for a real headshot or illustration.
- Add a downloadable resume/CV link near the LinkedIn button.
- Pull in the three most recent Substack posts automatically via its RSS
  feed once the newsletter exists.
- Add a lightweight, privacy-friendly analytics snippet (e.g. Plausible or
  GoatCounter) to see which sections get visited.
- Add `sitemap.xml` and `robots.txt` for better search indexing.
- Consider splitting the CSS/JS out of `index.html` into separate files if
  the page keeps growing, for easier maintenance.
- Add a custom 404.html page for GitHub Pages.
