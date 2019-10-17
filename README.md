# Mapping U.S. Race Demographics

This repository contains all files used in creating an **[interactive map](https://hassenmorad.github.io/race.html)** of race demographics in all 33,000+ U.S. zip codes.

## Workflow Summary:
1. Collection
    - [**Demographics**](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?src=bkmk): 2017 American Community Survey (ACS) data containing race demographics in each zip code.
    - [**Zip Code Cities**](https://simplemaps.com/data/us-zips): Contains city name for each zip code, which I needed since ACS data didn't include city names.
    - [**Zip Code Boundaries Shapefile**](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/zctas.html): For mapping.
2. Cleaning
    - Cleaned & combined city names and race demographics data (**Race_Mapping.ipynb**) then linked to zip codes in shapefile via QGIS. 
3. Visualization
    - Uploaded cleaned file to Mapbox and added interactivity via Mapbox GL JS.
