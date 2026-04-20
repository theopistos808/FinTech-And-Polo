# Where is FinTech Changing Lives

Static Vercel-ready site for the `Company One Pagers.pdf` deck.

## What is included

- `index.html`: landing page
- `companies/<slug>/index.html`: one detail page per company
- `assets/companies/jpg/`: one JPG per PDF page
- `assets/companies/pdf/`: one single-page PDF per company
- `assets/companies/qr/`: one QR code per company page
- `data/companies.json`: generated metadata
- `scripts/build_site.py`: rebuilds all generated assets and pages

## Regenerate with your real Vercel URL

Run this after you know the final public domain:

```bash
python3 scripts/build_site.py --base-url "https://fin-tech-company-qr-and-landing-pag.vercel.app/"
```

That updates:

- QR code images
- per-company page URLs
- `data/companies.json`

## Deploy

Import this folder into Vercel as a static project.

# FinTech-Company-QR-and-Landing-Page
