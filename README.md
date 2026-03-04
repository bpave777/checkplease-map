# 🍽️ Check Please! Bay Area – Restaurant Map

An interactive map of every restaurant featured on [KQED's *Check Please! Bay Area*](https://www.kqed.org/checkplease), the long-running Bay Area dining show hosted by Leslie Sbrocco.

**Live site:** [bpave777.github.io/checkplease-map](https://bpave777.github.io/checkplease-map/)

---

## Features

- **767 restaurants** spanning all 20+ seasons of the show
- Filter by region: San Francisco, East Bay, North Bay, Peninsula/South Bay, Monterey Bay, or Closed
- Search by restaurant name or cuisine type
- Click any pin or sidebar entry to open a popup with:
  - **Watch on KQED** — links to the episode
  - **Open in Google Maps** — Google search results for the restaurant
  - **Open in Yelp** — Yelp search results for the restaurant
- Satellite/terrain view toggle
- Marker clustering for smooth navigation across the full map
- Dark map theme

## Regions & Colors

| Color | Region |
|-------|--------|
| 🟠 Orange | San Francisco |
| 🟢 Green | East Bay |
| 🟣 Purple | North Bay |
| 🔵 Blue | Peninsula / South Bay |
| 🩵 Teal | Monterey Bay |
| ⚫ Gray | Closed |

## Tech Stack

- Pure HTML/CSS/JavaScript — no build step
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript) for the map
- [@googlemaps/markerclusterer](https://github.com/googlemaps/js-markerclusterer) for performance with large marker sets
- Hosted on [GitHub Pages](https://pages.github.com/)

## Data Sources

Restaurant list sourced from KQED's official [Check Please! Bay Area restaurant directory](https://www.kqed.org/checkplease/restaurants-a-z/). Coordinates verified via street address geocoding.

## Branches

| Branch | Description |
|--------|-------------|
| `main` | Original Leaflet/OpenStreetMap version |
| `google-maps` | Current live version using Google Maps |
