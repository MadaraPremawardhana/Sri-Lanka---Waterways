# Sri Lanka Hydrology Testbed – QGIS Project

This repository contains a fully prepared **QGIS project** that integrates key geospatial datasets for **hydrological modeling, research, education, and extreme-event forecasting in Sri Lanka**. It serves as a practical testbed for analyzing terrain, waterways, and topography within a unified GIS environment.

## Included Data Layers

- **Digital Elevation Model (DEM)**  
  High-resolution elevation data sourced from:  
  [Mendeley Data – “SRTM DEM for Sri Lanka”](https://data.mendeley.com/datasets/hzf2fpndpt/1)

- **Waterways**  
  Extracted from **OpenStreetMap** using the **QuickOSM** plugin in QGIS.  
  Includes:  
  - **Line features:** rivers, streams, drainage paths  
  - **Polygon features:** lakes, reservoirs, wetlands, water bodies  
  - **Point features:** springs, confluences, hydrological reference points  

- **Contour Lines**  
  Derived from **OpenStreetMap** data via QuickOSM extraction.

## Project Snapshots

Here are some example views from the QGIS project:

| Full Project Overview | DEM with Contours | Layer information|
|----------------------|-----------------|----------------|
| ![Full Project Overview](https://github.com/MadaraPremawardhana/Sri-Lanka---Waterways/blob/main/Full%20map.PNG) | ![Close-up DEM](https://github.com/MadaraPremawardhana/Sri-Lanka---Waterways/blob/main/a%20close%20look.PNG) | ![Layer info](https://github.com/MadaraPremawardhana/Sri-Lanka---Waterways/blob/main/layer%20info.PNG) |

> **Tip:** Replace the paths in the image links with your actual file paths. It’s recommended to create an `images` folder in the repository and store all screenshots there.

## Purpose

This project provides a ready-to-use foundation for:

- Hydrological and watershed modeling  
- Flood risk and extreme precipitation event forecasting  
- Terrain analysis (slope, aspect, flow direction, runoff pathways)  
- Testing hydrological algorithms and open-source workflows  
- Teaching and training in QGIS and hydro-GIS techniques  

## Features

- Pre-configured and cleanly organized QGIS project  
- Intuitive layer styling for rapid interpretation  
- Compatible with external hydrological tools (e.g., HEC-HMS, SWAT, TauDEM)  
- Focused on Sri Lanka’s complex and diverse hydrological landscape  

## Data Sources

- DEM: Mendeley Data (CC-BY) – [https://data.mendeley.com/datasets/hzf2fpndpt/1](https://data.mendeley.com/datasets/hzf2fpndpt/1)  
- Waterway & Contour Data: Extracted from **OpenStreetMap** via **QuickOSM** (© OpenStreetMap contributors)

## Getting Started

1. Clone or download the repository.  
2. Open the `.qgz` project in QGIS.  
3. Ensure that the data paths are relative (or update paths if needed).  

The project is ready to use immediately for hydrological analysis and research.
