# Toronto Myositis Centre — website

Static website for the Toronto Myositis Centre at St. Michael's Hospital.
Everything lives in this one folder. Open `index.html` to view it locally, or
deploy the whole folder to any static host (for example, GitHub Pages).

## Key files
- `index.html` — home page (open this first)
- `patients.html` — for patients: what to expect
- `team.html` — our team    `research.html` — research & trials    `education.html` — clinician education
- `resources.html` — patient resources hub    `subtypes.html` — understanding myositis
- `medications.html` — medication library, plus 20 `med-*.html` drug guides
- `nutrition.html`, `exercise.html`, `lifestyle.html` — patient guides
- `contact.html` — location, map, contacts, and the referral pathway
- `styles.css` — shared styles for every page
- `vinik.jpg`, `papachristos.jpg`, `kassardjian.jpg` — team photos
- `Toronto_Myositis_Centre_Referral_Form_fillable.pdf` — fillable referral form
- `myositis-nutrition-guide.docx`, `myositis-vegetarian-nutrition-guide.docx` — recipe guides
- `.nojekyll` — tells GitHub Pages to serve the files exactly as they are

## Notes
- Keep every file in the SAME folder. Pages link to each other and all share `styles.css`.
- Fonts (Google Fonts) and the location map load from the internet, which is normal for a website.
- To change a phone or fax number, open `contact.html` in a text editor. To edit any wording, open that page's `.html` file.
- The medication, nutrition, and exercise content is patient-facing education and should be signed off by the clinical team before public release.
