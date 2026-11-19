# Mumbai Connect – Telecom GIS Analysis

## Project Overview
Mumbai Connect is a QGIS-based GIS project focused on exploring telecom infrastructure coverage and spatial distribution in Mumbai.

### Main GIS Layers
- Telecom tower locations
- 250 m, 500 m and 1,000 m tower buffers
- Dissolved 500 m buffer coverage
- Tower heatmap
- Proximity gaps
- Mumbai boundary
- BMC wards
- OpenStreetMap basemap

## Software
- QGIS 3.44.15

## Files Included
- `project.qgs` – QGIS project definition
- `lXSffm_styles.db` – QGIS style database

## Important Data Note
The supplied ZIP contains the QGIS project and style database, but does not include the referenced `Data` folder or spatial datasets.

Some layers may therefore appear as unavailable when opening the project on another computer. The missing datasets have not been recreated or assumed.

## How to Open
1. Download and extract the project ZIP.
2. Open `project.qgs` in QGIS.
3. If QGIS reports missing layers, reconnect the original data sources using **Repair Data Source**.
4. Save the project after repairing the paths.

## Project Status
The QGIS project file and styles are included. The referenced spatial datasets are not included, so this is not yet a fully self-contained QGIS project package.
