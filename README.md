# Ground Truth

**What's under your address?** Look up any US address to see its flood zone, soil, and growing zone, explained in plain terms.

**Live app:** https://kensoriano.github.io/ground-truth/

## What it shows

- **Flood risk:** the FEMA flood zone, what it means, and a map of nearby floodplains.
- **How your soil handles rain:** the mapped soil type and how well it drains, with notes on rain gardens and downspouts. In urban areas, it picks out the native soil under the pavement and fill.
- **Growing zone:** the USDA hardiness zone and typical winter lows.

## Data sources

Pulled live from public sources:

- FEMA National Flood Hazard Layer
- USDA NRCS Soil Data Access (SSURGO)
- USDA Plant Hardiness Zone Map, via phzmapi.org
- USGS The National Map (basemaps and imagery)
- Esri World Geocoder, Photon, and OpenStreetMap Nominatim (address lookup)

## How it works

One HTML file, no server. Leaflet draws the map, and the browser queries each data source directly.

## Limitations

For screening only, not an official flood determination or site investigation. Soil maps are broad, so conditions on a given lot can differ, especially in cities.
