# Spatial Equity Analysis: MTR Accessibility in Kai Tak Development (KTD)

[![License: MIT](https://shields.io)](https://opensource.org)
[![Python 3.8+](https://shields.io)](https://python.org)
[![Leaflet](https://shields.io)](https://github.io)

## 📌 Research Overview
This project examines the **Spatial Equity** of transit-oriented development within Hong Kong's Kai Tak Development (KTD) area. Using **Isochrone Mapping**, the study visualizes walking accessibility to MTR stations (Tuen Ma Line) to identify disparities in transport infrastructure distribution.

### Key Insights:
*   **The Paradox of Accessibility:** While public housing estates in the North-West enjoy a "5-10 minute transit life circle," the high-end residential "Runway Area" remains an accessibility vacuum.
*   **Infrastructure Gap:** Highlights the socio-economic implications of the cancelled Environmentally Friendly Linkage System (EFLS) monorail.

## 🛠️ Methodology & Tech Stack
The analysis is built on a routing-network-based approach rather than simple Euclidean distance:
*   **Language:** Python
*   **Mapping Engine:** `Folium` (Leaflet.js wrapper)
*   **Data Sources:** OpenStreetMap (OSM) via `Geoapify API`
*   **Analysis:** Walk-time isochrones at 5, 10, and 15-minute intervals.

## 🗺️ Live Demo
Experience the interactive map here:
👉 **[View Interactive Kai Tak Map](https://github.io)**

## 🖼️ Preview
*(Tip: Replace the placeholder below with an actual screenshot from your repository)*
![Project Visualization](img width="940" height="601" alt="image" src="https://github.com/user-attachments/assets/0da35d0d-445b-4789-964d-0a859d0674da" />)
