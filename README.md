# Geospatial Analysis and Visualization

This repository contains geospatial analysis workflows for flood risk assessment and population exposure analysis in Bulacan, Philippines. The project demonstrates spatial operations, flood risk modeling, and publication-quality cartographic visualization techniques.

## Folder Contents

### figures/
- 05_choropleth_population_risk.pdf - Population risk choropleth map
- 05_bivariate_choropleth_facilities.pdf - Bivariate map with facility proximity overlay
- 05_true_bivariate_choropleth.pdf - True bivariate choropleth combining population risk and facility density
- 05_classification_comparison.pdf - Comparison of different classification methods
- Bulacan_flood_exposure_analysis.png - Main flood exposure analysis maps
- Bulacan_facility_proximity.png - Health facility proximity classification
- Bulacan_summary_charts.png - Statistical summary charts

### Data/interim/
- top_10_barangays_flood_exposure.csv - Summary of top 10 most exposed barangays
- detailed_top_10_barangays_flood_exposure.csv - Extended analysis with additional metrics

## Setup

1. Download dataset from this [Google Drive link](https://drive.google.com/drive/u/2/folders/1tZrWJY1q3PifcFuAdP7oOfmb0G7sO3pX?fbclid=IwY2xjawOZTbJleHRuA2FlbQIxMABicmlkETFXVG9Wc0Q4WFF2M3BJV1pCc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHmyALCP_j7-6vfwfAnNSTJ3gc8psOimXhTRSo7e_uy-SfpN0EdUnbaN5Zklk_aem_8rIrEI8WCeXLs0vu-8hnzA)
2. Create Data/ folder and put the folders
3. Run 01_read_inspect.ipynb
4. Run 02_spatial_ops.ipynb
