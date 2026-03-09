---
aliases:
  - Terrinoth
tags:
  - mapas
---
```leaflet  
id: MapOfTerrinoth ### Must be unique with no spaces  
image: [[Baronies_of_Terrinoth_-_Borders.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1517, 1785]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 750px ### Size of the leaflet embed in px on your screen  
width: 84% ### Size of the leaflet embed in your note  
lat: 758.5 ### To center the map, make this half of the map height.  
long: 890 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 0 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: true  
darkmode: false ### marker
```
