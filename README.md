# India Waste Canvas

A single-file, self-contained **systems-intelligence dashboard** for India's urban municipal solid waste (MSW): generation and disposition flows, infrastructure gaps, unit economics, the informal recovery economy, and the actors trying to close the loop.

**Live:** https://ashwask.github.io/india-waste-canvas/

## What it shows
- National / state / city views (geography is the primary filter)
- Pan-India infrastructure map, waste-flow Sankey, stock-and-flow circularity model
- Unit economics across the value chain, bottlenecks, "exists vs missing" analysis
- Ecosystem of partners and funders
- A **Hidden Dynamics** section that flags where official headlines overstate reality

## Data honesty
Figures are refreshed to 2025-26 from primary sources (MoHUA / SBM-U 2.0, PIB Jan 2026, DRAP, EAC-PM, CAG, CPCB, Lok Sabha answers, MoPNG/SATAT, CSE). The official "~80% processed" headline is shown as *installed processing capacity*, not measured treatment: independent assessments (EAC-PM 2024) put actual treatment closer to half, and genuine material recovery lower still. The dashboard surfaces both.

State and city rows are indicative estimates; ward counts are programme-reported, not audited.

## Tech
Static HTML. Leaflet, D3 / d3-sankey, Chart.js via CDN. Base map: OpenStreetMap / CARTO (ODbL). No backend, no keys, no build step.

## License
Dashboard and data: **CC BY-SA 4.0**. Base map © OpenStreetMap contributors (ODbL).
