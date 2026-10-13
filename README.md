# RiskShield AI — Digital Risk Protection Demo

A responsive, single-page cybersecurity dashboard for a hackathon demo. It includes:
- Dashboard and sample findings
- Manual risk scanner for social profiles, URLs, email addresses, mobile app names, and brand details
- Explainable heuristic risk scoring
- Finding history for the current browser session
- CSV export and print / Save as PDF
- Responsive sidebar and mobile layout

## Run locally
No build tools or dependencies are required. Open `index.html` in a modern browser.

## Deploy with GitHub Pages
1. Create a new **public** GitHub repository named `riskshield-ai`.
2. Extract the ZIP and upload `index.html`, `README.md`, and `.nojekyll` to the repository root (not inside another nested folder).
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait a few minutes and refresh the Pages section. Open the published URL shown there.

## Important limitations
This is a frontend-only demo. It does not connect to live social media, app stores, email providers, or threat-intelligence feeds. The scoring is a transparent heuristic, not a trained AI model and not proof that an account is fraudulent. Sample findings are fictional. Logo similarity requires a future image-analysis integration and human review.

For a production version, add approved platform APIs, a secure backend, scheduled monitoring, verified threat-intelligence sources, authentication, database storage, audit logs, and a human review / takedown workflow. Never put API secrets in frontend code.
