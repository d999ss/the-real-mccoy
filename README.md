# The Dispatch

A living investigation into surveillance, procurement, and disclosure in Utah's Wasatch Back.

## Current investigation

**Is Park City Flocked?** — Twenty automated license plate readers form a perimeter around the Park City basin. Eight sit inside city limits. The only public acknowledgment that the system exists is a single sentence inside a 2025 sole-source procurement waiver, signed by a police captain in February 2025.

The article is `index.html`. Open it in a browser. Every claim is hyperlinked to a primary public source.

## Records requests

The `grama/` directory contains the public-records requests that would close the remaining gaps in the investigation.

- `01-park-city-insight-cdw.md` — Park City Municipal Corporation: purchase orders and invoices to Insight Public Sector and CDW Government, FY2022–FY2026, with line-item detail
- `02-06-bundle.md` — UDOT, CCJJ, MIDA, Utah DPS, and Park City PD direct (Flock accounts, query logs, audit records)

Each is ready to file. Fill in name and email at the bottom.

## Methodology

Every dataset cited in the article was pulled directly from a government API or open-data endpoint between April 24 and April 26, 2026:

- OpenStreetMap surveillance node dataset via Overpass API
- Transparent Utah vendor payment API (`tu-query-handler-prod-uewlhjwsua-wm.a.run.app`)
- UDOT ROW Permits ArcGIS REST endpoint
- Utah AGRC Municipal Boundaries feature service
- Direct PDF extraction of Park City PD's Lexipol policy manual, 2024 Annual Report, and FY2025 Budget Document
- Direct PDF extraction of Summit County Sheriff's Policy 460

Raw data files are not included in this repository. The endpoints are documented inline in the article's "Methodology &amp; Sources" section.

## Hosting

This site is a single static `index.html` with no build step. It deploys directly to Vercel, Netlify, GitHub Pages, or any static host.

```
vercel --prod
```

## License

Reporting is original work; raw underlying data is public record. Source datasets retain their original licenses (OpenStreetMap data ODbL, Transparent Utah data CC BY 4.0, etc.). All linked external sources cited inline in the article.

## Author

Hawk Mikado
