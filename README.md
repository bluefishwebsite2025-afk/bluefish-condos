# Bluefish Condos — GitHub Pages Package

This folder is ready to upload to a GitHub repository and serve via **GitHub Pages**.

## What’s inside
- `index.html` — a copy of your "BLUEFISH CONDOS PERLA MARINA DOMINICAN REPUBLIC.html" set as the homepage
- All other HTML pages and their matching `*_files/` asset folders
- `robots.txt` and `sitemap.xml` (domain set to https://bluefishcondos.com; change if needed)

## Publish steps (quick)
1. Create a new GitHub repo (e.g. `bluefish-condos`) and upload all these files at the repo root.
2. In the repo: **Settings → Pages → Source**: choose `main` branch and `/(root)`, then Save.
3. Your site will appear at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Custom domain (optional)
If you want `bluefishcondos.com`:
1. Add a file named `CNAME` containing just:
   ```
   bluefishcondos.com
   ```
2. In your domain DNS, add A records to GitHub’s IPs:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
   Or point `www` to `YOUR-USERNAME.github.io` via CNAME.
3. In GitHub Pages settings, enable **Enforce HTTPS** after DNS propagates.

## Notes
- Some pages referenced assets that were not included in the export (we saw ~51 missing relative paths). 
  The site will load, but some images/scripts may be missing until those files are added or the links updated.
- Keep each HTML file next to its own matching `*_files/` folder — don’t rename or move them.
- If you rename pages or folders, update any links inside the HTML accordingly.

Prepared: 2025-09-19 18:45:45Z UTC
