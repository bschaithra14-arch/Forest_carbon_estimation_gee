# Forest_carbon_estimation_gee
Carbon stock estimation using Sentinel-2 and Google Earth Engine
# Forest Carbon Stock Estimation using Google Earth Engine

This repository contains a Google Earth Engine (JavaScript) workflow for
estimating forest above-ground carbon stock using Sentinel-2 imagery.

## Objective
To generate a spatially explicit forest carbon stock map using satellite-derived
predictor variables and regression modelling.

## Study Area
Kodagu district, Karnataka, India (can be adapted to other regions).

## Data Used
- Sentinel-2 Surface Reflectance (10 m)
- NDVI (derived from Sentinel-2)
- Dynamic World land cover (tree mask)
- WCMC Biomass Carbon Density dataset

## Methodology
- Tree-covered pixels extracted using Dynamic World
- Sentinel-2 spectral bands and NDVI used as predictor variables
- Linear regression applied in Google Earth Engine
- Regression coefficients applied pixel-wise
- Estimated carbon stock map generated

## Output
- Spatially distributed forest carbon stock map
- RMSE-based accuracy assessment

## Tools & Platform
- Google Earth Engine (JavaScript)
- QGIS (for map styling and export)

## Notes
- Asset IDs may need to be replaced with user-owned assets
- This code is provided as a work sample / portfolio project
