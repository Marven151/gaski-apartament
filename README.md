# Apartament Gąski

Landing page with a booking calendar for a holiday apartment on the Polish Baltic coast. Demo project — contact details on the page are placeholders.

**Live:** https://marven151.github.io/gaski-apartament/

## Features

- Availability calendar: pick a date range, see the number of nights, send an enquiry by e-mail with the dates pre-filled
- Admin mode (localhost only): toggle days between free and booked, export/import availability as JSON (stored in `localStorage`)
- Photo gallery with a lightbox (arrow keys, Esc)
- Location map (Leaflet + OpenStreetMap)
- Responsive layout, no build step

## Stack

Plain HTML, CSS and JavaScript. Leaflet 1.9 for the map, Google Fonts (Poppins, Inter).

## Run locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.
