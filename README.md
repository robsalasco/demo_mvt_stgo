# Santiago MVT tiles example

Requirements

- Tippecanoe
- MBUtil
- VectorGrid.Protobuf

How to generate:

Using Tippecanoe

```
tippecanoe -o stgo2016.mbtiles R13.geojson --projection="EPSG:4326" --maximum-zoom=14 --no-tile-compression
```

Using MBUtil

```
/mb-util ../stgo2016.mbtiles ../mvt --image_format=pbf
```
