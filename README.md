# Skylark campus storefront mirror — procurement desk

Quarterly mirror of the Skylark Instruments campus-program storefronts, kept by the campus technology
procurement desk.

## Contents

- `storefront/portal.html` — regional listings page. Every market listing is reachable from here.
- `storefront/<market>/retail/bundle.html` — open storefront listing for a market.
- `storefront/<market>/campus-price-list/bundle.html` — campus-program listing for a market.
  Each market bundle page links to its campus-program counterpart.
- `storefront/archive/` — retired promotions, kept for audit history only.
- `finance/contract-fx-2026Q4.json` — contractual FX table used for internal comparison.
- `ops/` — desk working files; audit submissions land in `ops/audits/`.

## House rules

- Quote campus-program pricing from the campus-program listing; never quote the open storefront listing as a campus price.
- Compare markets only through the contractual FX table in `finance/`; spot rates are not used for internal comparison.
- Anything under `storefront/archive/` is historical and must not be quoted.
