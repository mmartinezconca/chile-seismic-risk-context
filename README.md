# Seismic Risk Context Mapping of Chile (2004-2024)

## Summary

![Seismic risk context map of Chile](figures/chile_seismic_context_map.png)

[Download full-resolution map (PDF)](figures/chile_seismic_context_map_github.pdf)

*Optimized for web viewing; original high-resolution file available upon request.*





This project maps earthquake activity in Chile from 2004-2024 and places it in context with population centers, emergency hospitals, and tectonic plate boundaries. The visualization highlights where high seismic concentration overlaps with urban areas and critical infrastructure, using clear, defensible, cartographic design.

---

## What This Shows
- Earhquakes (M 4.0-8.8) visualized by magnitude
- Kernel Density Estimation (KDE) of earthquake occurrence, shown as percentiles
- Major population centers and hospitals with emergency services
- Nazca-South America subduction zone
- Inset map of central Chile for high-detail context

**Note:** KDE represents relative concentration, not hazard or probability.

---

## Data & Methods
- **Earthquake data:** USGS Earthquake Catalog (2004-2024)
- **Healthcare & infrastructure:** OpenStreetMap
- **Population centers:** OpenStreetMap
- **CRS:** EPSG:5361 (SIRGAS-Chile 2002)

Earthquake epicenters were summarized using KDE and classified by percentiles to emphasize spatial patterns while avoiding false precision. Contextual were added to support interpretation of potential exposure rather than risk modeling.

---

## Why This Matters
- Chike is one of the most esismically active regions in the world. This map demonstrates how spatial analysis and thoughful cartography can be used to communicate seismic context and exposure in a clear, professional way.

---

## Tools
- QGIS 3.44
- QuickOSM
- GDAL (via QGIS Processing)



