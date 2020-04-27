# Plot.ly_auto-calibration_map
The demo is an auto-calibration from GPS coordinates to map scale, developed on top of Plot.ly in JavaScript.

A temporary test ground before integrating into [Open Energy Dashboard](https://github.com/OpenEnergyDashboard/OED).

Since Plot.ly only accepts url or data uri strings as image source, images used for this demo are converted to data uri stored in a .txt file under the same name as the image.


Use case example: 

1. Open BeloitMap.txt to load up the map stored as BeloitMap.png.

2. Click graph to display map.

3. Click anywhere inside the map, input gps coordinates of the point in degrees, press cancel to discard this point.

4. Click calibrate after at least 2 data points are accepted, we recommend 5 points to be more accurate. 
