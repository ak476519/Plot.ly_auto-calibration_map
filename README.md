# Plot.ly_auto-calibration_map
The demo is an auto-calibration from GPS coordinates to map scale, developed on top of Plot.ly in JavaScript.
A more complete version of this feature is being incorporated into [Open Energy Dashboard](https://github.com/OpenEnergyDashboard/OED) through a forked [mapChart](https://github.com/ak476519/OED/tree/mapChart) branch.

The map accepts an image upload and asks for several data points to calibrate.


Use case example: 

1. Open BeloitMap.txt to load up the map stored as BeloitMap.png.

2. Click graph to display map.

3. Click anywhere inside the map, input gps coordinates of the point in degrees, press cancel to discard this point.

4. Click calibrate after at least 2 data points are accepted, we recommend 5 points to be more accurate. 
