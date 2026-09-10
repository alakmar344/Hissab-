# Hissab (حساب) — Daily Sales Tracker for Small Businesses

[![Live](https://img.shields.io/badge/live-hisaab.esamz.info-brightgreen?style=for-the-badge)](https://hisaab.esamz.info)
[![Also on Vercel](https://img.shields.io/badge/vercel-hissab--6fla-brightgreen?style=flat-square)](https://hissab-6fla.vercel.app)

> **A bookkeeping ledger for Indian small businesses — log daily sales, watch profit calculate itself, and see the month at a glance. Built mobile-first, no signup, no cloud dependency.**

This is the **landing page** for the Hissab product line — an 827-line, single-file,
dependency-light static site (custom CSS design system, Inter + Space Grotesk
typography) that presents the product: what it does, how it works, and why it
exists. The product concept it presents:

- **Daily Sales Log** — record each day's takings in seconds
- **Auto Profit Calculation** — revenue minus expenses, computed as you type
- **Monthly Overview** — totals, trends and comparisons per month
- **Loan Tracker** — track borrowed amounts and repayments alongside sales
- **Visual Analytics** — charts that make the month's story readable
- **Mobile-First** — designed for the shop counter, not the office desk
- **No Signup Required** — opens and works immediately

## What's in this repo

| Path | What it is |
|---|---|
| `index.html` | The complete landing page — markup, styles and behaviour in one hand-crafted file |
| `README.md` | This file |

A single-file, no-build-tool approach was deliberate: it keeps the project trivially
hostable anywhere (Vercel, Netlify, GitHub Pages) and readable end-to-end in one
sitting. The site is live at **[hisaab.esamz.info](https://hisaab.esamz.info)**
(and on Vercel at [hissab-6fla.vercel.app](https://hissab-6fla.vercel.app)).

## Run locally

No build step. Any static file server works:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Design notes

- Dark editorial palette (`#0c0c0e` base, layered surfaces) with Inter for UI text
  and Space Grotesk for display type
- Fully responsive, mobile-first layout
- Zero JavaScript frameworks — the page is CSS + a small amount of vanilla JS

## Lineage & related

Hissab is one of the **eSAMz Worlds** — the fleet of products shipped from
[esamz.me](https://esamz.me). Sibling products include eSAMz AI, Gati, PivotIQ,
RealLearn, MindEase, CiboCocinar, and See-market. The full portfolio of Worlds
lives at [esamz.me](https://esamz.me).

## License

Personal project — all rights reserved unless stated otherwise.
