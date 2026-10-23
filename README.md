# The Legacy of Redlining in Los Angeles County

## About

This repository contains Homework 2 for EDS 223 (Geospatial Analysis & Remote Sensing) in the UCSB Master of Environmental Data Science program. It explores how historical HOLC redlining grades relate to present-day conditions in Los Angeles County:

- **Part 1:** Maps the HOLC redlining grades and summarizes the share of census block groups in each grade. It then compares average PM2.5 and percent low-income households across grades using EJScreen data.
- **Part 2:** Compares pedestrian and bicycle crash rates and fatality rates across HOLC grades using SWITRS collision records.

## Repository Structure

```
eds223-hw2
├── README.md
├── .gitignore
├── hw2.qmd              # Quarto document with analysis and figures
├── hw2.html             # Rendered report
├── hw2_files/           # Figures generated when rendering
└── data/                # Not tracked (see Data Access)
    └── data 2/
        ├── ejscreen/
        │   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
        │   ├── EJSCREEN_2023_BG_Columns.xlsx
        │   └── ejscreen-tech-doc-version-2-2.pdf
        ├── mapping-inequality/
        │   └── mapping-inequality-los-angeles.json
        └── SWITRS_LA/
            └── Crashes.csv
```

## Data Access

The data is **not stored in this repository** because `data/` is listed in `.gitignore`. To run the analysis, obtain the following datasets and place them in `data/` following the structure shown above:

- **EJScreen (2023):** the Block Group geodatabase (state percentiles) from the U.S. EPA.
- **Mapping Inequality:** HOLC redlining boundaries for Los Angeles (GeoJSON).
- **SWITRS:** crash records for Los Angeles County (CSV).


## Author

Calvin Fu ([@cuvlin](https://github.com/cuvlin))

## References

- U.S. Environmental Protection Agency (EPA). (2023). *EJScreen: Environmental Justice Screening and Mapping Tool* (Version 2.2) [Data set].
- Nelson, R. K., Winling, L., et al. *Mapping Inequality: Redlining in New Deal America*. Digital Scholarship Lab, University of Richmond. https://dsl.richmond.edu/panorama/redlining/
- California Highway Patrol. *Statewide Integrated Traffic Records System (SWITRS)* [Data set].
- EDS 223 Class Page (found [here](https://eds-223-geospatial.github.io/assignments/HW2V2.html))
## Acknowledgements

This assignment was completed as part of EDS 223 at the Bren School of Environmental Science & Management, UC Santa Barbara.
