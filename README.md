# Spatial Modelling of Residential Land Values and Transport Accessibility in Prague

This project investigates how public transport accessibility is capitalized into residential land values in Prague using spatial econometric and geographically weighted regression models.

The analysis explicitly addresses spatial autocorrelation and spatial heterogeneity, moving from global linear models to local and multiscale spatial regressions.

---

## Research Question

How does proximity to different public transport modes (metro, tram, bus, rail) affect residential land prices, and how do these effects vary across space?

---

## Key Contributions

- Construction of a clean, reproducible spatial dataset of residential land prices and transport accessibility
- Formal diagnosis of spatial autocorrelation using Moran’s I and LISA
- Comparison of global (OLS), local (GWR), and multiscale (MGWR) regression models
- Identification of distinct spatial regimes in the capitalization of transport accessibility
- Interpretation of variable-specific spatial scales using MGWR bandwidths

---

## Methodological Workflow

1. Data preprocessing and residential land filtering  
2. Computation of Euclidean distance to nearest public transport stops by mode  
3. Exploratory spatial data analysis (EDA)  
4. Spatial autocorrelation analysis (Global Moran’s I, LISA)  
5. Global OLS regression as a diagnostic benchmark  
6. Geographically Weighted Regression (GWR)  
7. Multiscale Geographically Weighted Regression (MGWR)

---

## Technologies Used

- Python (GeoPandas, PySAL, MGWR)
- NumPy / Pandas
- Matplotlib
- Jupyter Notebook
- GIS (vector-based spatial analysis)

---

## Project Status

MGWR estimation and interpretation in progress.

---


# Data Sources

All datasets used in this project are publicly available open data.

## Land Price Zones
Source: Prague City Hall  
Licence: CC BY 4.0  
Description: Official land price map used for taxation and planning purposes.

## Land Use / Zoning
Source: Prague Institute of Planning and Development (IPR)  
Licence: CC BY  
Description: Land use classification used to identify residential and mixed-use areas.

## Public Transport Stops
Source: Prague Open Data Portal (GTFS-derived)  
Licence: CC BY  
Description: Locations of public transport stops, filtered by transport mode.

## Administrative Boundaries
Source: Czech Office for Surveying, Mapping and Cadastre  
Licence: CC0  
Description: Administrative units used to derive Prague city boundary.

## Notes
Processed datasets were derived from the above sources and are fully reproducible using the notebooks in the `notebooks/` directory.

---

## Author

Vilém Knap  
Transport modelling & spatial analytics  
