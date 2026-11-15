# SME Credit Risk & Early Warning Portal

A single-page prototype for SME credit scoring and early-warning (EWS) monitoring.

## Tabs
1. **Client Scorecard** – quantitative (60%) and qualitative (40%) scoring, grade A–E, risk alerts.
2. **EWS Monitoring** – monitoring indicators, flag count, Green/Amber/Red status.
3. **Portfolio** – all saved clients, filters, summary counts.
4. **Decision Matrix** – Grade × EWS status → recommended action.

## Run locally
Open `index.html` in any modern browser. No build step or server needed.

## Deploy on GitHub Pages
1. Push this folder to a new GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- Data is stored in the browser (`localStorage`) only; nothing is sent to a server.
- Grade cutoffs, scoring bands and EWS thresholds are illustrative. Recalibrate them with your portfolio performance and default data.
- "Download PDF report" uses the browser print dialog (Save as PDF).

## Structure
```
sme-credit-risk-ews-portal/
├── index.html    # the whole app (HTML, CSS, JS)
├── README.md
└── .nojekyll     # tells GitHub Pages to serve files as-is
```
