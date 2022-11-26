<h1 align="center"> Exploring Marine Protected Area Data </h1>
<h3> EDS220_Fall2022 Final Project </h3>

<img align="right" src="santa_barbara_coastline.jpg" width="300">


The purpose of this repository is to provide a walk-through of how to utilize NOAA's marine protected area (MPA) dataset located at the [MPA Inventory website](https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/). There are many packages that can potentially be used to visualize this dataset, but we chose a handy one called 'folium'. Folium is a python library built off a JavaScript Library called Leaflet. Both of these packages are free, open-source libraries that allow the user to create maps and visualize data in a similar way to google maps. This dataset is useful in visualizing MPAs, and understanding how MPAs interact with marine processes. This can include timeseries data to examine the effect of MPAs on factors such as fishing, IUCN marine species risk status, and ecosystem resiliency in light of ocean acidification and changes in sea surface temperature. Ultimately, we hope that this notebook will be a useful educational tool for those looking to explore this dataset. 

# Included in the Notebook:
- Notebook Purpose
- Description of the Data
- Data Input and Output (I/O)
- Metadata Display and Basic Visualization
- Use Case Examples
- References

# Data Citation:
The responsible party for the NOAA's Marine Protected Areas Inventory - 2020 - IUCN MPAs includes the Department of Commerce (DOC), National Oceanic and Atmospheric, Administration (NOAA), Office Of National Marine Sanctuaries (ONMS), and National Marine Protected Areas Center (MPAC).

# Folder Structures:
The raw data read into the file is housed under a shared folder in a server called “Taylor”. Access to the data from the server is limited. The data can be downloaded [here](https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/).

# Libraries Used:
- Geopandas
- Pandas
- Folium
- Matplotlib
- Scipy
- Datetime
- OS
- GeoJson
- CSV

# Authors:
 Colleen McCamy, Master of Environmental Data Science Student, (colleenmccamy@bren.ucsb.edu)
 Atahualpa Gomez, Master of Environmental Data Science Student, (atahualpa@ucsb.edu)
 Jared Petry, Master of Environmental Data Science Student, (jaredpetry@ucsb.edu)
 Adelaide Robinson, Master of Environmental Data Science Student, (adelaide_robinson@ucsb.edu)
