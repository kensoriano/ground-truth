# Ground Truth

**What's under your address?** Type any US address to see its flood risk, how its soil handles rain, and its growing zone, explained in plain language with simple graphics.

**Live app:** https://kensoriano.github.io/ground-truth/

## What it shows

- **Flood risk:** the FEMA flood zone at the address, what it means for the household, and a map overlay of nearby floodplains.
- **How your soil handles rain:** the mapped soil and its hydrologic group, translated into practical guidance on drainage, rain gardens, and downspout disconnection. For urban soil complexes, it identifies the native soil mixed in with pavement and fill.
- **Growing zone:** the USDA Plant Hardiness Zone and typical winter low temperatures.

## Data sources

All data is public and pulled live when you search:

- FEMA National Flood Hazard Layer
- USDA NRCS Soil Data Access (SSURGO soil survey)
- USDA Plant Hardiness Zone Map, via phzmapi.org
- USGS The National Map (basemaps and imagery)
- Esri World Geocoder, Photon, and OpenStreetMap Nominatim (address lookup)

## How it works

The whole app is a single HTML file with no server or database. It uses Leaflet for the map and queries each public data service directly from the browser.

## Limitations

This is a screening tool, not an official flood determination or site investigation. Soil maps are drawn at a broad scale, so conditions on a specific lot can differ, especially in urban areas.

Built by Kendall Soriano.
