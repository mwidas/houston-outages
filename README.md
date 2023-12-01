# Power Outages in Houston, TX February 2021

Exploration of Houston, TX power outages after 3 storms in February 2021 which caused a power crisis. The storms occurred on February 10-11, 13-17, and 15-20. 

## Visualizations

There will be two main visualizations produced in the `.Rmd` file. The first will be a visual representation of median household income per census tract in Houston, TX for homes affected by the blackouts and for homes not affected by the blackouts. The second will be the distribution of icome in impacted and unimpacted census tracts in the Houston area.

## Highlights

- vector and raster data manipulation
- vector and raster operations
- spatial joins
- plotting with `ggplot`

## Data
The data associated with this project was accessed from this [link](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view) . Unzip the folder and all the contents and store in your directory as follows. All data will be in the `.gitignore`.

```{r}
Houston-Outages
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
    └───VNP46A1
    |   │   VIIRS data files
```
