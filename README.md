# Vienna Trip Planner ✈️

A single-file trip planning web app for exploring day trips and short getaways from Vienna. Covers 27 destinations across 12 European countries, with real cost estimates across four transport modes.

**Live demo:** https://rizabalci.github.io/vienna-trip-planner/

## Features

- 27 destinations across Austria, Slovakia, Slovenia, Czech Republic, Hungary, Italy, Greece, Spain, Belgium, France, Bulgaria, and Malta
- 4 transport modes with live cost calculation: Train (OBB ticket pricing), Car (fuel + parking + tolls), FlixBus, and budget Flights (Ryanair/Wizzair with Bratislava alternatives)
- Multi-stop trips that chain two destinations using haversine distance estimates
- Budget presets (Backpacker / Mid-range / Comfort) for one-tap planning
- 0 to 5 nights with smart recommendations based on travel time
- 54 attractions with per-person pricing
- Day itineraries (morning / afternoon / evening) for every destination
- Animated trip timeline showing the full journey
- Compare mode for up to 3 destinations side-by-side
- Search, filter, and sort by category, distance, price, or speed
- Currency warnings for non-Euro destinations (HUF, CZK, BGN)
- Export to clipboard for sharing or saving a plan
- Dark / light theme toggle
- Mobile-optimized with Add to Home Screen support

## Tech

- React 18 (via CDN)
- Babel Standalone for in-browser JSX
- Zero build step, zero dependencies to install
- Single self-contained HTML file, works fully offline after first load

## Running locally

Just open index.html in any browser. No server, no build, no install.

## Notes

Costs are estimates. Flight and FlixBus prices vary by date and demand. Hotel rates are booking.com averages. Train fares reflect typical OBB one-way pricing. Multi-stop road distances use a haversine calculation with a 1.3x road-factor adjustment.

Built as a personal project.
