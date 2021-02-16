# Web Map of United States Airports
---

## Description
This web map provides an interface to view locations and minor details of airports located in the United States.

Beyond the initial ability to view the map of airports, this web app shows a choropleth of states by airport count, and allows the clicking of either airports or states to view their names/identifiers and counts, respectively. Also included is a heatmap of the airports, along with the option to toggle this on and other layers off. The bins used in the making of the choropleth are based off the quartiles of airport count data by state, with a 5th bin added for states with more than 30 airports (ca, tx, fl, and ak). As the primary purpose of this map is to convey raw airport numbers, I did not find it necessary to account for state population.

## Libraries and Resources
Libraries used include leaflet primarily, as well as its ajax plugin, jquery, chroma, and heatmapjs/its leaflet plugin counterpart. Other resources include the fonts Open Sans and Lobster, as well as font awesome.

## Data Sources
Airport data was sourced from Mike Bostock of D3.
United States shapefile was sourced from USGS.
Basemap was sourced from CartoDB.
Inspiration and minor code snippets sourced from Bo Zhao.
