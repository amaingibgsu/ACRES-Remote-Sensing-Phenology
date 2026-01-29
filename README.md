# ACRES Remote Sensing Phenology

![Visual Abstract](Visual_Abstract_ACRES_Final.png)

**Visual Abstract.** Multi-panel summary of Remote Sensing (RS) integration potential for ACRES monitoring. **(A)** Overall operational readiness showing 56% (n=70) indicator suitability; **(B)** Temporal sensing window derived from species-specific flowering phenology, identifying the peak detectability period (June–July); and **(C)** Hierarchy of operational readiness across 10 habitat-specific scorecards, ranging from high-feasibility avian habitats (Chough, 91%) to complex structural habitats (Rough Grazing, 23%). All visualizations were generated using the provided Python analytical framework.

---

This repository provides the analytical framework and code for the paper:  
**"Replacing Field Visits with Remote Sensing: Opportunities and Challenges for Agri-Environmental Monitoring."**

## Overview
This project automates the monitoring of biodiversity indicators for Ireland's Agri-Climate Rural Environment Scheme (ACRES). By aligning species-specific flowering phenology with remote sensing (RS) data, we identify optimal temporal windows to maximize spectral detectability of indicator species.

## Key Features
* **Phenological Window Analysis:** Quantifies the peak survey window (**April–October**) by calculating the monthly sum of flowering species (Figure 4). This informs the selection of multi-temporal satellite imagery.
* **Habitat-Specific Monitoring Logic:** Scripts to cross-reference **Fossitt classification** with botanical flowering periods, enabling automated habitat-specific tasking for UAV or satellite sensors.
* **A1 Positive Indicator Mapping:** A specialized logic to visualize the flowering duration of A1 species across 10 ACRES scorecards, grouped by habitat type (Figure 2).
* **High-Resolution Data Visualization:** Generates 600 DPI publication-ready plots that illustrate the sharp increase in flowering activity from April, peaking in June/July.

## How to Use
1. **Requirements:** Install dependencies via `pip install -r requirements.txt`.
2. **Data:** The script requires `Verified_ A1_Positive_indicators_Verified.xlsx` to be present in the root folder.
3. **Execution:** Run the Jupyter Notebook `Flowering_Calendar_ACRES.ipynb` to regenerate the phenological calendars and distribution graphs used in the paper.

## Results
The analysis supports the paper's findings that **56% (n=70)** of ACRES indicators are suitable for RS integration. The code demonstrates that peak detectability for A1 species is synchronized across most habitats during the mid-summer window, supporting the shift from manual field visits to automated spectral monitoring.
