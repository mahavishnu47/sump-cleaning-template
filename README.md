# Sump Cleaning Website Template (Demo: Anna Nagar, Chennai)

Plug-and-play SEO template for sump & water tank cleaning businesses in Tamil Nadu.
Live demo: https://mahavishnu47.github.io/sump-cleaning-template/

## Pages
- `index.html` — homepage (Chennai-wide)
- `services/sump-tank-cleaning.html` — service page (pricing, process, offers schema)
- `areas/anna-nagar.html` — hyperlocal area page (PIN, crew, map, area FAQ)

## Per-lead swap list
1. Business name, phone (`tel:` links, `wa.me`, NAP footer, JSON-LD `telephone`)
2. Address + PIN + `geo` lat/lng + `areaServed`
3. Area name + 300 unique words + area FAQ + map embed query
4. Prices in table + `Offer` schema
5. `canonical` / sitemap / JSON-LD URLs → client's domain

## Schema
`HomeAndConstructionBusiness` (most specific correct schema.org type — no cleaning subtype exists) + `Service`/`Offer` (INR) + `FAQPage` + `BreadcrumbList` + `WebSite`. No `aggregateRating` on own business (against Google's guidelines — stars come from GBP).
