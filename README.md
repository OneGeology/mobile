# mobile-app

## Current Web Portal Features

### Find maps

Search by geographic region or thematic keyword
Go to location by user selection (zoom in/out, drawn bounding box, coordinate entry, gazetteer)
Automatic loading of maps depending on scale or region
Choice of base maps

### View maps 

(internal ~ layers registered in the catalogue and external ~ public services)
WMS ~ GetCapabilities, GetMap, GetFeatureInfo (HTML response), GetLegendGraphic
WCS ~ GetCapabilities, GetCoverage.

As well as default view of maps 
Access service metadata
View legends
Query/reportrayal of WMS layers, using generated SLD.
Qury complex feature WFS (associated with WMS)

#### Reproject maps 

(EPSG:3031, EPSG:3034, EPSG:3413, EPSG:3857, EPSG:4258, EPSG:4326)
2-D Globe and planar views (CRS:84) for WMS

### Save maps

for sharing and resuse in the portal and/or view elsewhere.
WMC ~ Save (WMS layers as WMC), load WMC layers (internal and external data sources)
KML ~ Save KML (WMS layers as image source, not as vectors
