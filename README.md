# HydroSight Prototype

A static frontend prototype for an online hydrology application.

## Features

- Upload fields for:
  - Drone DEM/DSM raster
  - Rainfall data
  - LULC layer
  - Soil layer
  - AOI/outlet boundary
- Return period input for flood depth raster generation.
- Output cards for:
  - Watershed boundary
  - Stream network
  - Longest stream
  - Flood depth rasters by return period

## Run locally

Open `index.html` in a browser.

## Note

The current version simulates processing in the browser. Connect the submit action to a backend geospatial pipeline (e.g., GDAL + TauDEM + HEC-RAS/HMS stack) for production analytics.
