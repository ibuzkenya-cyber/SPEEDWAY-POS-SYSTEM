# SPEEDWAY BRANDING CYBER POS

A browser-based POS starter for SPEEDWAY BRANDING CYBER, GATITU JUNCTION.

## Included
- `index.html` — latest POS HTML, including the stock-list print / Save as PDF feature.
- `stock-list-template.csv` — stock import/template file.
- `.nojekyll` — supports GitHub Pages publishing.

## Publish on GitHub Pages
1. Create a GitHub repository (for example, `speedway-branding-cyber-pos`).
2. Extract this ZIP and upload the *contents* of this folder to the repository root. Ensure `index.html` is at the root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to publish and open the URL shown in Settings → Pages.

## Important data and security notes
- GitHub Pages hosts static files only. It does not create a shared database or synchronize sales between computers.
- Browser-local data (such as localStorage) stays in the browser/device where it was entered. Clearing browser data may remove it. Export/backup data regularly if the POS provides that option.
- A login screen implemented only in HTML/JavaScript is not secure server-side authentication and must not be treated as protection for sensitive data.
- For shared sales, stock, invoices, and accounts across devices, connect the POS to a backend database and authentication service with access rules; that shared backend is not configured by this ZIP.

## Stock list PDF
Open the POS, go to Stock Items, choose **Print / Save Stock List PDF**, and select **Save as PDF** in the browser print dialog. The report uses inventory currently available in that browser's POS data.
