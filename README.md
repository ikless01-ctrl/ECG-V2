# ECG Lab v8

A browser-based ECG study guide, adaptive practice tool, mock exam, and professor-style simulator.

## New in v8

- Professor mode with no topic or difficulty hints
- Structured interpretation checklist in every answer review
- Interactive finding overlays for selected ECGs
- Confidence scoring: Very / Maybe / Guess
- Adaptive practice weighted toward mistakes, guessed answers, and weak topics
- Bookmarked ECG collection
- Side-by-side ECG comparison
- Searchable study guide and topic-specific practice
- Expanded runtime question engine with multiple professor-style variants

## Run locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## GitHub Pages update

Replace `index.html`, `questions.js`, `script.js`, `style.css`, and `README.md`. Keep the `assets/ecgs` directory in place.

Educational use only. The site is not a substitute for clinical judgement.
