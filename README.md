# Data Repository for  
**“Multi-scale Greening Dynamics in Türkiye’s Ecoregions (2001–2024): The Effects of Elevation and Land Cover on NDVI Trends”**

This repository contains the processed NDVI datasets and supporting R scripts used in the analysis presented in the manuscript.

All 13 CSV files contain stratified NDVI values for Türkiye’s terrestrial ecoregions, structured by:

- **Date**  
- **Elevation range** (0–250, 250–500, 500–1000, 1000–1500, 1500–2000, 2000–2500)  
- **Land-cover type** (Trees, Shrubland, Grassland, Cropland, Bare, etc.)  
- **NDVI value**  
- **Year**

Each CSV corresponds to a specific ecoregion.

---

## 📁 Repository Structure

```text
.
├── data/
│   ├── Eco_region1.csv
│   ├── Eco_region2.csv
│   ├── Eco_region3.csv
│   ├── Eco_region4.csv
│   ├── Eco_region5.csv
│   ├── Eco_region6.csv
│   ├── Eco_region7.csv
│   ├── Eco_region8.csv
│   ├── Eco_region9.csv
│   ├── Eco_region10.csv
│   ├── Eco_region11.csv
│   ├── Eco_region12.csv
│   └── Eco_region13.csv
├── scripts/
│   ├── 01_import_and_merge.R
│   ├── 02_trend_analysis_MK_TheilSen.R
│   ├── 03_ecoregion_landcover_elevation_summary.R
│   └── 04_figures_timeseries_boxplots.R
└── README.md

The full analysis workflow, including data import, processing, and visualizations, is provided in the R Markdown file:
[`Eco_region_proje.Rmd`](Eco_region_proje.Rmd)

