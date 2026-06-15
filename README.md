# 2026 Budget Tracker

A single-page app for tracking spending against your 2026 budget with AI-powered insights.

## Features

- **CSV Import** — Load transactions from Revolut and BNP Paribas
- **Manual Categorization** — Assign transactions to your 7 budget categories
- **Budget Dashboard** — Compare actual vs. budgeted spending by category
- **AI Insights** — Get Claude-powered analysis and recommendations
- **Local Storage** — All data stays in your browser, never sent to a server

## Budget Categories

- Fixed Commitments
- Variable Living
- Health & Recovery
- Relationships & Social
- Work & Leverage
- Optional Joy & Lifestyle
- Travel & Residency

## Getting Started

1. **Add your API key** — Go to Setup tab, enter your Anthropic API key from [console.anthropic.com](https://console.anthropic.com/account/keys)
2. **Import transactions** — Export CSV from Revolut and/or BNP Paribas, upload via Import tab
3. **Categorize** — Assign each transaction to a budget category
4. **View dashboard** — See your spending vs. budget by category
5. **Get insights** — Claude analyzes your patterns and provides recommendations

## Export Instructions

### Revolut
- Mobile: Accounts > [Select account] > Statements > Export > CSV
- Web: Accounts > [Select account] > Download CSV

### BNP Paribas
- VIREMENTS ET SERVICES > Téléchargement des opérations
- Select account, date range, format: Excel (.csv, ";")

## Deployment

This app runs entirely in your browser. Deploy to GitHub Pages:

```bash
git add .
git commit -m "Initial commit: Budget tracker app"
git push origin main
```

Then enable GitHub Pages in repo settings (Deploy from main branch).

## Notes

- Your API key is stored only in browser localStorage
- Transaction data persists across sessions
- All processing happens locally—no data is sent anywhere except to Anthropic for AI insights
- Revoke your API key anytime from Settings tab

## License

MIT
