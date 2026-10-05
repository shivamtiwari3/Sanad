# Sanad

**Dubai clinical capacity intelligence. Where the city is short on beds, specialists and care, and what to build first.**

[Live demo](https://shivamtiwari3.github.io/Sanad/)

Sanad is a concept prototype written in response to the Dubai Clinical Services Capacity Plan 2026–2040 RFP. It shows how a planning team could see supply and demand in one place, district by district, and turn a gap into a brief someone can act on.

> **Concept prototype.** Not affiliated with or endorsed by the Dubai Health Authority. Every figure, facility and licence number in the demo is illustrative.

## What it does

- **Gap map.** 15 Greater Dubai planning zones on a map, sized by population and coloured by gap severity (critical, emerging, balanced).
- **Gap analysis.** Per district: beds per 1,000 residents, specialist shortfall, and the top service lines that are missing.
- **Demand forecast.** 2026–2040 demand vs planned supply, driven by population growth, an ageing-adjusted utilisation uplift and non-resident demand.
- **Planning brief.** A written brief for each district: why it is short, what to build, and who could co-invest.
- **Supply module.** A facility registration flow (type, ownership, beds, clinical FTEs) with a validation status pipeline, so supply data stays current.
- **Investment view.** Gap data linked to investment opportunities and quick feasibility checks.

## Why

Capacity plans usually live in a PDF that is out of date the day it ships. The useful version is a live view that answers three questions for any district: what is missing, how bad it gets by 2030 and 2040, and what the cheapest fix is. Sanad is a sketch of that product.

## Run it

It is one static HTML file. No build, no backend, no keys.

```bash
open index.html
# or
python3 -m http.server 8000
```

Built with vanilla JS, [Leaflet](https://leafletjs.com/) and [Chart.js](https://www.chartjs.org/). Basemap tiles © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, © [CARTO](https://carto.com/attributions).

## License

MIT
