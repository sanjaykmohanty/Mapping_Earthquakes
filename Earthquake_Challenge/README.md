# Earthquake Challenge

## Overview
The purpose of this project is to create a earthquake map with three different views and the 3 overlays that include earthquake data in last seven days, the tectonic plates’ location on the earth, and all the earthquakes with a magnitude greater than 4.5 in last seven days on the map.

The scope of project includes:
- Three different maps
  -   Map view 1: Streets
  -   Map view 2: Satellite
  -   Map view 3: Dark
- Three overlays
  -   Layer 1: Earthquake
  -   Layer 2: Tectonic plate location
  -   Layer 3: Earthquakes with a magnitude greater than 4.5    

The project was delivered using JavaScript, Leaflet.js, and geoJSON data.

## Result

**Streets View**
![image](https://user-images.githubusercontent.com/31812730/204368961-03ebde36-5357-4f29-b5d5-037a5cbd6efa.png)

**Satellite View**
![image](https://user-images.githubusercontent.com/31812730/204369658-26264b77-5997-481a-a8fb-07e731ad3adf.png)

**Dark View**
![image](https://user-images.githubusercontent.com/31812730/204370922-d39513c5-7bcf-4a55-b14e-30a9e9bf655f.png)

## summary
Three tile layers were created as the background of the map. Based on user's selection, map background is set. The default map background is set to streets view. Check boxes are added for the three overlay layers. When the map is loaded for the first time, all the three layers are checked. User can uncheck one or all three of the overlay layers. A legend has been added to the map to indicate the color code used to indicate the magnitude of the earthquake. The size of the circle also indicates the magnitude of the earthquake.

