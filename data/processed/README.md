# Processed Data

This directory contains datasets derived from publicly available open data sources used in this project.

All files stored here are the result of spatial preprocessing, filtering, and feature engineering steps documented in the project notebooks. The datasets are provided to ensure transparency and reproducibility of the analysis.

## Contents
- `prague_boundary.gpkg`
- `routes_bus.gpkg`
- `routes_tram.gpkg`
- `routes_metro.gpkg`
- `routes_rail.gpkg`
- `stops_bus.gpkg`
- `stops_tram.gpkg`
- `stops_metro.gpkg`
- `stops_rail.gpkg`
- `price_residential_prague_nearest_stops_by_mode.gpkg`  
  Residential land price polygons filtered to residential and mixed-use areas, enriched with Euclidean distance to the nearest public transport stop by mode (metro, tram, bus, rail), including identifiers of the nearest stops.

## Notes

- The datasets in this directory are not primary data sources.
- All spatial transformations, filtering criteria, and derived variables can be fully reproduced using the notebooks in the `notebooks/` directory.
- Coordinate reference systems and processing assumptions are explicitly documented in the analysis workflow.

## Data Usage

These datasets are shared for research and demonstration purposes. Users are encouraged to refer to the original data sources listed in `data/raw/README.md` for licensing details.
