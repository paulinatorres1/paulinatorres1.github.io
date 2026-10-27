# Adding photos to the site

This is a static site with no upload button, so "adding" a photo means
saving a file in this folder with the **exact name** listed below, then
committing it. The page already looks for these files — once one exists,
it replaces the placeholder automatically. No HTML editing required.

| File to add                            | Where it shows up                  | Suggested photo                                  |
| --------------------------------------- | ----------------------------------- | ------------------------------------------------- |
| `identity-left.jpg`                     | Left side of the "Analyst / Researcher / Strategist / Future CPA" block | A small portrait photo |
| `identity-right.jpg`                    | Right side of that same block       | A small portrait photo                             |
| `about.jpg`                             | Between About and Career            | A headshot or candid photo                        |
| `career.jpg`                            | Between Career and Career Development | A role, internship, or presentation photo       |
| `career-development.jpg`                | Between Career Development and Certifications | Studying, in class, or at a conference  |
| `certifications.jpg`                    | Between Certifications and Races    | Exam day, a ceremony, or your workspace            |
| `races.jpg`                             | Between Races and Writing           | Race day — finish line, bib, or medal              |
| `writing.jpg`                           | Between Writing and Interests       | Writing, reading, or at a coffee shop              |
| `interests.jpg`                         | Between Interests and the footer    | Karate, triathlon training, or travel              |

Tips:

- Any common image format works (`.jpg`, `.png`, `.webp`...), but file
  names must match exactly (including the extension) since the HTML
  references the exact path. If you use a different extension, update the
  matching `src="assets/images/…"` in `index.html`.
- Landscape/wide photos work best for the between-section placeholders
  (they display in a wide banner). `identity-left.jpg` and
  `identity-right.jpg` fill portrait (3:4) frames, so an upright or
  centered photo works best there.
- The top of the page uses a decorative "P" monogram medallion (not a
  photo), so there's no upload slot for a hero photo anymore.
- Keep file sizes reasonable (under ~500KB each) so the page stays fast.
