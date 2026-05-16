# IceNav Tilemap Generator
An automated generator of IceNav Vector Tilemaps.

## Settings
### Included maps
The default maps can be changed in the file "maps-list.txt", where maps are separated by a new line. For example, to include the map https://download.geofabrik.de/europe/germany/berlin-latest.osm.pbf, add europe/germany/berlin to "maps-list.txt".
### Resolution
The resolution of the maps is set to 1-17 by default. This can be changed in the file ".github/workflows/generator.yml".
### Water polygons
By default, water polygons are already set up, but disabled for the sake of size and time. If you wish to change this, you can un-comment the lines in the file ".github/workflows/generator.yml".

## Releases
Tilemaps will be regenerated every week following the maps included in the "maps-list.txt" file, or when the file is updated. They will be automatically published as the latest release in zip files for easy download.
