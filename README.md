# Santa Barbara, California-Land Cover Classification

Exploration of land cover classification for southern Santa Barbara County based on multi-spectral imagery using a decision tree classifier which is a form of supervised classification. Monitoring the distribution and change in land cover types can help us understand the impacts of phenomena like climate change, natural disasters, deforestation, and urbanization. 

## Visualizations
There will be one main visualization produced in the `.Rmd` file. This visualization will show the different land cover types created from a land cover classification for southern Santa Barbara County based on multi-spectral imagery and data on the location of 4 land cover types:

-   green vegetation
-   dry grass or soil
-   concrete
-   water


## Highlights
-   extract spectral data at training sites
-   train and apply decision tree classifier
-   plot results


## Data

The data associated with this project was accessed from this [link](https://drive.google.com/drive/folders/1ON8FbDqcTjg2PKHmNGgyN7odTqpOnXla). Store data locally and add `data` folder to the `.gitignore`.

```{r}
santa_barbara_land_classification
│   README.md
│   Rmd/Proj files    
│
└───data
    │   SB_county_south
    │   |  shp files for southern Santa barbara county
    │
    └───training data
    |   │   training data shp files
    |
    └───landsat-data
    |   │   landsat data files
```
