# CyberSOC AI — Project Showcase

A standalone, bilingual (English default / French) static website presenting the **CyberSOC AI** summer internship project at ENSIAS × MARTECH Conseils.

## Structure

- `index.html` — complete single-page project showcase
- `styles.css` — responsive white, navy and cyan design
- `script.js` — EN/FR switch, mobile menu and screenshot lightbox
- `assets/` — genuine project screenshots, architecture diagram, logo and internship report

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8080` in this folder and visit `http://localhost:8080`.

## Publish to GitHub Pages

1. Create a public GitHub repository and upload **the contents of this folder** (not the outer ZIP).
2. Go to **Settings → Pages → Build and deployment**.
3. Choose **Deploy from a branch**, branch `main`, folder `/ (root)` and save.
4. Wait for the published URL to appear in Pages settings.

Alternatively, drag this folder into Netlify Drop.

## Content notes

Descriptions are based on the supplied internship report and screenshots. This is a **project showcase**, not the operational SOC application. Some integrations and AI features depend on configuration in the original project. Do not publish proprietary code, credentials or private screenshots. Review the included internship report before publishing to ensure you have permission to share it publicly. To omit the report, remove `assets/internship-report.pdf` and update the report links in `index.html`.

## Customization

Edit content in `index.html`, French translations in `script.js`, and theme variables at the top of `styles.css`. Screenshots are located in `assets/`.
