Bigane MapLibre port - first test build

Files:
- index.html: MapLibre GL JS version of the current map.
- style-maplibre.json: converted original Bigane world 2.0 style.
- mapbox-style-license.txt: license bundled with the exported Mapbox style.

This first port intentionally still reads the existing Mapbox-hosted vector tiles, sprites, fonts and current DEM through ordinary HTTPS Mapbox APIs. The renderer itself is MapLibre GL JS. The non-working Threebox/GLTF code has been removed.

For GitHub Pages upload all files to the same directory and publish that directory.
