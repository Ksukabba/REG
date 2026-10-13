# KSU Kabba - Student Registration 2026/2027

Website (GitHub Pages) + Google Apps Script backend (Google Sheet + Drive + email).

## Files
- index.html, css/, js/, assets/  -> upload these to GitHub
- apps-script/Code.gs             -> paste into Apps Script (do NOT upload to GitHub)

## Setup
1. Apps Script: new project, paste Code.gs, Save, run `authorize` (allow Sheets, Drive, Mail).
2. Deploy > New deployment > Web app > Execute as: Me, Who has access: Anyone. Copy the /exec URL.
   Open it in a browser: it must say "KSU registration API v3 - uploads enabled".
3. Put the URL in js/config.js.
4. GitHub: new repository, upload index.html + css + js + assets, Settings > Pages > main /(root).
5. After any change to Code.gs: Deploy > Manage deployments > Edit > New version > Deploy.
