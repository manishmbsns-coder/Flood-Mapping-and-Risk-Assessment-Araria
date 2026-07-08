# Flood Mapping and Risk Assessment of Araria District using Google Earth Engine

## Overview

This project maps flood inundation in Araria District, Bihar, India, using Sentinel-1 Synthetic Aperture Radar (SAR) imagery and Google Earth Engine (GEE). The workflow estimates the extent of flooding, exposed population, affected cropland, and affected urban areas to support disaster management and climate resilience planning.
## Study Area
- District: Araria
- State: Bihar
- Country: India
## Objectives
- Detect flood extent using Sentinel-1 SAR imagery.
- Estimate flood inundation area.
- Assess the exposure of the population.
- Estimate affected cropland.
- Estimate affected urban areas.
- Generate flood maps for disaster management.
## Datasets
| Dataset | Source |
|---------|--------|
| Sentinel-1 GRD SAR | Copernicus |
| FAO GAUL Level-2 | FAO |
| HydroSHEDS DEM | WWF |
| Global Surface Water | JRC |
| GHSL Population | European Commission |
| MODIS Land Cover | NASA |
## Methodology
1. Define the Araria district boundary.
2. Acquire Sentinel-1 images before and after the flood.
3. Apply preprocessing and speckle filtering.
4. Compute flood extent using image ratio thresholding.
5. Remove permanent water bodies.
6. Remove steep slopes.
7. Estimate:
   - Flood area
   - Exposed population
   - Affected cropland
   - Affected urban area
8. Export flood raster and vector layers.
## Outputs

- Flood extent raster
- Flood polygons (Shapefile)
- Exposed population map
- Cropland affected map
- Urban affected map
## Author
Manish Kumar (MSc Climate Change and Sustainability), Azim Premji University
