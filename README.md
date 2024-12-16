# habitat-suitability
[![DOI](https://zenodo.org/badge/892297527.svg)](https://doi.org/10.5281/zenodo.14449380)

This code is designed to combine several data sets in order to predict the impact of climate change on a key grassland species in two national grasslands: Sheyenne National Grassland and Little Missouri Grassland

The goal of the project is to create a habitat suitability model for Yellow Indian Grass (Sorghastrum Nutans).In particular, the model should determine if the selected grassland will be suitable habitats for this grass in the future. 

** Notebooks

The project is broken into several notebooks: 

* Notebook #0 - Introduction to the project, data selection, and justification for the selection of grasslands and other variables
* Notebook #1 - Grassland selection (called Habitat1 and Habitat2)
    Data Source: [USFS National Grassland Units](https://data.fs.usda.gov/geodata/edw/edw_resources/shp/S_USA.NationalGrassland.zip)
* Notebook #2 - Soil variable - where to find the soil data, select a variable, and download and process it
    Data Source: [POLARIS Dataset](http://hydrology.cee.duke.edu/POLARIS/PROPERTIES/v1.0/)
* Notebook #3 - Elevation data - Getting elevation data and overlaying that on the respective habitats
    Data Source: [earthaccess API](https://github.com/nsidc/earthaccess/) - you will need to login
* Notebook #4 - Climate data - selecting two climate scenarios and applying them to your habitats
    Data Source: [MACAv2 THREDDS Data Server](http://thredds.northwestknowledge.net:8080/thredds/reacch_climate_CMIP5_macav2_catalog2.html)
* Notebook #5 - Harmonize Data - make sure the grids for each layer match up
* Notebook #6 - Building a fuzzy logic model

