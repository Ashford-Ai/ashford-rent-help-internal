# Rent Help Finder – Ashford Communities

Staff tool for finding rent and utility help for residents, by county, in English, Spanish and Vietnamese. It's one self-contained static page (`index.html`) with no build step.

## Tabs
- **Find help** / **Training**: work fully on any host.
- **Early outreach**, **Referral log**, **Dashboard**, **Funding calendar**: these use shared storage that only exists when the page runs as a Claude artifact. On Vercel the page shows "offline copy" and these tabs don't save.

## Deploy (Vercel)
Import this repo at vercel.com/new. Framework preset: **Other**. Leave the build command empty and set the output directory to `.` (the repo root). Each push to `main` redeploys.

## Updating
Edit `index.html` and push. To update agencies, change the inline agency data in the `<script>` block.
