# Where is FinTech Changing Lives

Static Vercel-ready site for the `Company One Pagers.pdf` deck.

## What is included

- `index.html`: landing page
- `companies/<slug>/index.html`: one detail page per company
- `assets/companies/jpg/`: one JPG per PDF page
- `assets/companies/pdf/`: one single-page PDF per company
- `data/companies.json`: generated metadata
- `scripts/build_site.py`: rebuilds all generated assets and pages

## Regenerate with your real Vercel URL

Run this after you know the final public domain:

```bash
python3 scripts/build_site.py --base-url "https://your-project-name.vercel.app"
