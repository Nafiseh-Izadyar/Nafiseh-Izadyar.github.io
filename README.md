# Nafiseh Izadyar — portfolio website

A GitHub Pages–ready, responsive 5-page website. No build step, npm, or framework required.

## How to publish

1. Open your personal website repository: https://github.com/Nafiseh-Izadyar/Nafiseh-Izadyar.github.io
2. Download the ZIP and unzip it. Upload/commit the new `index.html`, `research.html`, `publications.html`, `teaching.html`, `about.html`, and `assets/` folder to the repository root.
3. **Keep your existing `NafisehIzadyar.pdf` file** in the repository root. The CV button links to that existing file; this archive deliberately does not overwrite it.
4. Commit to the branch configured for GitHub Pages. Your site will update at https://nafiseh-izadyar.github.io/ after GitHub Pages finishes publishing.

## Contents

- `index.html` — homepage matching the selected white / purple modern design.
- `research.html` — detailed research cards and actual figures sourced from the arXiv HTML pages.
- `publications.html` — verified paper titles, authors, years, and links.
- `teaching.html` — Summer and Fall 2026, Spring 2027.
- `about.html` — bio, education, experience and contact.
- `assets/style.css` and `assets/main.js` — responsive design and accessible mobile menu.
- `assets/*.jpg` — **illustrative visual assets cropped from the design mockup**, not scientific results.

## Images / external dependencies

The hero and homepage research-card artwork are *conceptual design illustrations*, not figures from a research publication. On the Research page, Better STEP and LLM-Guided Material Inference use real paper figure images from arXiv, with local illustrative fallbacks if the arXiv image cannot be loaded. To make all paper figures self-hosted, obtain the images from your paper sources and update their `src` paths on `research.html`.

The fonts load from Google Fonts; the site uses system-font fallbacks when offline. The website itself needs no runtime dependencies.

## Things to check before publishing

- Verify your LinkedIn URL and the contents of your existing PDF CV.
- Update course information as terms change.
- Google Scholar was intentionally omitted because the old site's profile link used a placeholder (`YOUR_ID`); add your actual Scholar URL when available.
