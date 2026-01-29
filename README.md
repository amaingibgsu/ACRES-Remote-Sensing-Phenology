# ACRES Remote Sensing Phenology

This repository provides the analytical framework and code for the paper: 
**"Replacing Field Visits with Remote Sensing: Opportunities and Challenges for Agri-Environmental Monitoring."**

## Overview
This project automates the monitoring of biodiversity indicators for Ireland's Agri Climate Rural Environment Scheme (ACRES). By aligning species-specific flowering phenology with remote sensing data (Sentinel-2, LiDAR, and SAR), we identify optimal temporal windows for habitat quality assessment.

## Key Features
- **Phenological Calendar:** Automated generation of flowering windows for A1 indicator species.
- **Habitat Categorization:** Scripts to classify Fossit habitat codes into RS-relevant monitoring groups.
- **Journal Quality Visualization:** High-resolution (600 DPI) plotting for academic publication.

## How to Use
1. **Requirements:** Install dependencies using `pip install pandas matplotlib openpyxl`.
2. **Data:** Ensure the `Verified_ A1_Positive_indicators_Verified.xlsx` is in the root directory.
3. **Execution:** Run the Jupyter Notebook `Flowering_Calendar_ACRES.ipynb` to generate the phenological plots and distribution graphs.

## Results
The analysis establishes that 56% (n=70) of ACRES indicators are suitable for remote sensing integration, with structural and hydrological attributes showing the highest operational readiness (85–98% accuracy)..
