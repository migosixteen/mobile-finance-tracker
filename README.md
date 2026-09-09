# Finance Tracker

Mobile-first personal finance PWA for tracking:
- Credit cards and loans
- Personal debt (money owed to/from people)
- Bills
- Payoff priority (Avalanche / Snowball)
- Paycheck payment planning
- Payment history

## Run locally
Open the folder with a local web server. Example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Commit and push.
4. In GitHub, go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select your main branch and `/ (root)`.
7. Save. GitHub will provide your public URL.

## Install on iPhone
Open the GitHub Pages URL in Safari → Share → **Add to Home Screen**.

## Install on Android / desktop
Open the GitHub Pages URL in Chrome/Edge and use the Install option when available.

## Data storage
Data is stored locally in the browser using `localStorage`. It is not synced to a server.
