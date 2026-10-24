# Verdant Finance

A premium, responsive, nature-inspired financial calculation lab with tactile 3D-styled buttons, animation, interactive investment projections, locally saved scenarios and no external tracking.

## [Live site](https://coderc1.github.io/verdant-finance/)

13 calculators: stock profit after commissions and simplified gain-tax estimate; average share purchase price; compound returns; dividends; position sizing; CAGR; 2026 US ordinary income tax; custom-rate income tax; capital gains; sales tax/VAT; amortized loan payments; inflation; savings goals.

**Requirements:** any modern browser. Entirely static JavaScript ES modules; no runtime dependencies, API keys or accounts. Financial results depend on provided inputs; no live prices. Tax functions are simplified estimates and are **not** a tax filing tool or professional advice.

## Test

`npm test` runs 17 regression tests with Node 22. `npm run build` creates the Pages-ready `dist/` folder.

Run locally with `python3 -m http.server 8080` and open `http://localhost:8080`.

## Publish

Open **Repository Settings → Pages → Build and deployment → Source: GitHub Actions**. The workflow at `.github/workflows/pages.yml` tests, builds, and deploys on every push to `main`. Enable GitHub Actions if prompted.

## Privacy

All calculations happen locally. Saved scenarios use browser localStorage. No ads, analytics, trackers, remote storage or personal accounts.

## License

MIT © 2026 Verdant Finance contributors.
