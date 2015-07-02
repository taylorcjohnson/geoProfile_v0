# geoProfile_v0
Create custom elevation profiles from hosted ESRI web services.

### Description
This single page application allows the user to draw a custom line or polyline feature that intersects an ESRI ArcGIS for Server web service endpoint (specifically, an image service containing elevation values).  Once a line has been created, the user can generate an interactive graph of the elevation profile for the service at that location.  The application is designed for image services with 1 meter resolution (projected in NAD83 State Plane Arizona Central Zone).  FYI, the page might need an immediate page refresh if the ESRI service does not load.

### Components
* [mapbox.js](https://www.mapbox.com/mapbox.js/api/v2.2.1/)
* [leaflet.js](http://leafletjs.com/)
* [leaflet-draw] (https://github.com/leaflet/Leaflet.Draw#readme)
* [esri-leaflet] (https://github.com/Esri/esri-leaflet)
* [amCharts] (http://www.amcharts.com/)

### Version
This is considered a still-in-development application (version 0.1 for now)
