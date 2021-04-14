# GEOG 4046 Assignment 10

## Current Weather
This map shows real-time weather radar and alerts from the National Weather Service. Users can view the map and explore the radar by clicking on the map to learn more about severe and extreme weather in their area. 
<https://emmastiening.github.io/weather/>


# Coffee of Baton Rouge Photomap
A Leaflet map that reads data from Google Sheets.  

Created for Assignment 11 GEOG 4046 (https://emmastiening.github.io/photomap/).  

Each row in the sheet will appear as a marker on the map. When the marker is clicked, a popup will appear showing information about the location of the coffee shops, taken from the columns of the spreadsheet.  

This script assumes the Google Sheet has the following columns. These match the attribute names used for the [Story Map Tour](https://www.arcgis.com/home/item.html?id=91d75e9b375e4e9b9b3a4004544bfadf) template in ArcGIS Online.  

Column name | Description
:-----------|--------------------------------------------------------------
name        | A short name for the location, to appear as the popup title |
description | A sentence or two describing the location in more detail    |
lat         | Latitude in decimal degrees                                 |
long        | Longitude in decimal degrees                                |
pic_url     | The URL to an image that will be displayed in the popup     |
