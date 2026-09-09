# Finance Tracker v2.4

Mobile-first personal finance PWA for GitHub Pages.

## Fixes in v2.4
- Credit & Loans: Edit button opens the selected item and saves changes.
- Personal Debt and Bills: Edit remains supported.
- Every Add/Edit sheet can be closed with **Close**, tapping the dark backdrop, or Esc/back where supported.
- Close works even when required form fields are blank.
- CSS and JavaScript are embedded in `index.html`, preventing missing `app.js` / `styles.css` deployment issues.
- Service-worker cache changed to `finance-tracker-v24-20260909` so old cached app code is replaced.
- Existing data remains in `localStorage` using the same `financeTrackerV2` key.

## GitHub Pages
Upload all files in this folder to your repository root, then enable **Settings → Pages → Deploy from a branch → main → /(root)**.

If an older installed PWA is still shown on iPhone, visit the GitHub Pages URL once in Safari and reload. If Safari still shows the old build, remove the old Home Screen app, reload the site, then add it to Home Screen again.
