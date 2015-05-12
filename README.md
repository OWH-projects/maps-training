#Making interactive maps
Brown-bag session: Maps!

###Points and polygons
<b>This is a point:</b><br><br>
<img src="http://i.imgur.com/n6l60p0.png" width="400" style="max-width:100%; border:1px solid #ccc" />

<hr>

<b>This is a polygon:</b><br><br>
<img src="http://i.imgur.com/y7kf6z1.png" width="400" style="max-width:100%; border:1px solid #ccc" />

###Choropleths
<img src="http://dataomaha.com/media/news/2015/wildfires/img/latest.png" width="400" style="max-width:100%;" />

###Using Fusion Tables
Today, we're going to use <a href="https://support.google.com/fusiontables/answer/2571232?hl=en">Fusion Tables</a>, a Google data management and visualization tool. You can use <a href="http://shpescape.com/">SHPescape</a> to get your shapefile into Fusion Tables, or you can open it in, say, <a href="http://www.qgis.org/">QGIS</a> and save as a different format, or if you're comfortable using the command line you could use <a href="http://www.gdal.org/ogr2ogr.html">ogr2ogr</a> to convert.

###Do you really need a map?
Is geography/location important to your analysis or presentation? If not, maybe you don't need a map.

###Data sources
Whenever you come across something like this in a report --

<img src="http://i.imgur.com/KYyzEXQ.jpg" width="400" style="max-width:100%;" />

-- chances are you can request the underlying data to make your own map. ESRI is the GIS vendor for a lot of government agencies, so they'll probably at least have a shapefile to give you.

Typically, a shapefile comes packaged with a group of related files: .prj, .dbf, .cpg, .shx, etc. (You can read up on the file format specifications <a href="https://www.esri.com/library/whitepapers/pdfs/shapefile.pdf">here</a>, if that sounds like a thing you would enjoy.) Other formats you might encounter: KML/KMZ, geoJSON, topoJSON.

###Some agencies that post GIS data online:
<ul>
<li><a href="http://www.census.gov/geo/maps-data/data/tiger.html">Census TIGER data</a>
<li><a href="http://catalog.data.gov/dataset?metadata_type=geospatial">data.gov</a></li>
<li><a href="http://www.nws.noaa.gov/gis/">National Weather Service</a></li>
<li><a href="http://water.usgs.gov/maps.html">USGS</a></li>
<li><a href="http://www.nebraska.gov/data.html">State data portal</a></li>
<li><a href="http://odb.sarpy.opendata.arcgis.com/datasets?">Sarpy County open GIS</a></li>
<li><a href="http://data.dogis.opendata.arcgis.com/datasets?">Douglas County/City of Omaha open GIS</a></li>
<li><a href="https://data.opennebraska.io/">Open Nebraska</a></li>
</ul>

A non-exhaustive list of some locally available GIS data. (If you can't find it online, ask a geek to help you locate it.)

<ul>
<li>Counties</li>
<li>School districts</li>
<li>Legislative boundaries</li>
<li>Congressional districts</li>
<li>Schools</li>
<li>Tornado touchdowns/tracks</li>
<li>ZIP codes</li>
<li>Census tracts</li>
<li>Leaking Underground Storage Tanks</li>
<li>Hazardous spills</li>
<li>Water quality</li>
<li>Dams</li>
<li>DEQ permitted facilities -- air/water</li>
<li>Game and Parks land</li>
<li>Public hunting access</li>
<li>Trails</li>
<li>Public fishing areas/spots</li>
<li>Mountain lion established populations</li>
<li>Mountain lion units (available for other game, as well)</li>
<li>Voting precincts</li>
<li>Property parcels</li>
<li>Zoning</li>
<li>Zoning board of appeals</li>
<li>TIF districts</li>
<li>Roads</li>
<li>Speed limits</li>
<li>Mile markers</li>
<li>Rivers and streams</li>
<li>Neighborhood associations</li>
<li>Fire stations</li>
<li>Fire districts</li>
<li>Fire hydrants</li>
<li>Census blocks</li>
<li>Trash pickup</li>
<li>Emergency sirens</li>
<li>Bike lanes</li>
<li>Red Cross shelters</li>
<li>Bridges</li>
<li>Flood maps</li>
<li>SIDs</li>
<li>City boundaries and ETJs</li>
<li>Polling places</li>
<li>Restaurant inspection scores</li>
<li>Omaha parking meters</li>
<li>Omaha growth since 1850</li>
<li>Omaha city and ETJ limits</li>
<li>Papio NRD dam sites, current and future</li>
<li>Omaha lead contamination</li>
<li>Omaha bike racks</li>
<li>Blight</li>
<li>Omaha planning inspector areas</li>
</ul>