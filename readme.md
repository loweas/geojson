## Creating a GeoJson File
Creating a GeoJson from a shapefile. I am using data on the geographical regions of Oregon provided by [Oregon Exlporer][].
1. Loading the shape file in QGIS to save vector layer in EPSG:4326 WGS84 formate (more suitable for web mapping)
2. Save as a Geojson file. Located in assests under regions.geojson which holds extensive detail on the boundery of each area.
3. Upload this file to [mapeshaper.org][] and reduce the size of the geojson file. I reduced to 9%
4. Export to folder named assets.
File size:

|name| size(kb)|
|-----|--------|
regions.geojson| 3000 or 3MB|
region-simplified.json| 371|
regions-topo.json| 65|


      name size(kb)
      
      regions.geojson 3000 or 3MB
      region-simplified.json 371
      regions-topo.json 65








[Oregon Exlporer]: https://oregonexplorer.info
[mapeshaper.org]: https://mapshaper.org
