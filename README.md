# Available Access Guide

A responsive, single-page wayfinding prototype for Dhoby Ghaut MRT, Plaza Singapura, and Temasek Shophouse.

## Run

Open `index.html` in a browser. No build step or dependencies are required.

## Dhoby Ghaut lift maps

Choose Dhoby Ghaut MRT, open the lift tab, then select a lift to show its Figma map layout. Lift 1 uses the Level 5 map; Lifts 2 and 3 use the Level 3 map. The SVG exports are stored locally in `assets/` so the site does not depend on temporary Figma URLs.

Lift and ramp statuses in this prototype are illustrative values. A facilities data feed is needed for verified live service information.

## Lift photo previews

Dhoby Ghaut lift cards open local photo previews: Lift 1 uses the B5 photo, Lift 2 the B3 photo, and Lift 3 the Plaza Singapura exit photo. Keep these image files in `assets/` when deploying.

Gallery forecourt ramp opens its three-photo carousel. Shophouse side entrance opens a separate four-photo carousel. Both have previous/next arrows. Photos are stored in `assets/`.

## Temasek Shophouse map

The Temasek Shophouse destination uses `assets/temasek-shophouse-map.svg`. Hover over the map for a subtle zoom cue; use Expand to open the full-screen map, then use +/− or drag to zoom and pan.

Dhoby Ghaut opens on the Level 5 map. Select the highlighted central lift to switch to the Level 3 submap; use Back to Level 5 to return. The lift cards continue to open their photo previews without changing the map. Expand opens the current map with zoom and pan controls.
