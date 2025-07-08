# Canyon Alliance 3D Map

This project is a 3D web map built with [MapLibre GL JS](https://maplibre.org/projects/maplibre-gl-js/) to visualize the Canyon Alliance service area. It includes extruded building structures, color-coded neighborhoods, and interactive parcel-level popups.

The goal is to support planning, fire preparedness, and community communication by making key spatial data more accessible and understandable.

## Features

- 📍 **Extruded Structures**  
  3D building visualizations using `fill-extrusion`, with height data in feet.
  
- 🏘️ **Neighborhood Visualization**  
  Parcels are color-coded by neighborhood (e.g., Boca, Upper/Lower Santa Monica and Rustic Canyons).

- 🔍 **Interactive Popups**  
  Clicking on parcels or structures reveals info like AIN, address, height, and neighborhood.

- 🧭 **Navigation Controls**  
  Basic pan/zoom functionality is included via the MapLibre UI.

- 🗺️ **Custom Legend**  
  A toggleable on-screen legend describes the visual symbology used in the map.

## Technologies

- [MapLibre GL JS](https://maplibre.org/)
- [Turf.js](https://turfjs.org/) for bounding box fit
- HTML/CSS/JS (no framework)
- GeoJSON data loaded from `/data/` folder

## Folder Structure

