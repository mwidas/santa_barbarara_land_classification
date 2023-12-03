# Santa Barbara, California Land Cover Classification

## Visualizations
There will be one main visualization produced in the `.Rmd` file. This visualization will show the different land cover types created from a land cover classification for southern Santa Barbara County based on multi-spectral imagery and data on the location of 4 land cover types:

-   green vegetation\
-   dry grass or soil\
-   concrete\
-   water\


## Highlights
-   extract spectral data at training sites\
-   train and apply decision tree classifier\
-   plot results\


## Data


santa_barbara_land_classification
│   README.md
│   Rmd/Proj files    
│
└───data
    │   gis_osm_buildings_a_free_1.gpkg
    │   gis_osm_roads_free_1.gpkg
    │
    └───ACS_2019_5YR_TRACT_48_TEXAS.gdb
    |   │   census tract gdb files
    |
    └───landsat-data
    |   │   landsat data files