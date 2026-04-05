# Australian Tax & Housing Dashboard

An interactive dashboard showing where the Australian median salary goes, 1970–2025.

## What it covers

- **Median Worker** — Income tax, Medicare, superannuation and GST burden across every year, CPI-adjusted to 2025 dollars. Every ATO bracket since 1983 sourced from official ATO tables.
- **Housing + Tax** — Mortgage principal/interest as % of take-home pay, price-to-income ratios, stamp duty burden, and a direct 1990 vs 2025 real-dollar comparison.
- **Student Debt** — Average HECS/HELP debt and annual repayment as % of median salary since 1989.

## Data sources

- **Earnings:** ABS Cat. 6302.0 / 6310.0 median full-time adult weekly earnings
- **Tax brackets:** ATO official tables (every year 1983–2025), ABS Year Book pre-1983
- **Medicare:** ATO historical rates 1984–present
- **Superannuation:** ATO/APRA SG schedule 1992–present
- **House prices:** REIA / Abelson-Chung / ABS / CoreLogic national weighted median
- **Mortgage rates:** RBA F5 standard variable rate series
- **Stamp duty:** State revenue office historical bracket schedules (NSW/VIC/QLD/WA weighted)
- **CPI:** RBA G1 series, rebased to 2025 = 1.000
- **HECS/HELP:** ATO Taxation Statistics annual releases, Australia Institute, BCEC

## Running locally

```bash
npm install
npm run dev
```

## Deploying

```bash
npm run build
```
Then deploy the `dist/` folder to Vercel, Netlify, or any static host.

## Tech stack

- React 18
- Recharts
- Vite
