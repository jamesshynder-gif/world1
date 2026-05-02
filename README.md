# world1

Interactive, browser-based 3D Earth digital twin built with **MapLibre GL JS**.

## Features
- 3D globe projection with atmosphere/fog effects.
- Seamless zoom from planetary view down to street-level OSM tiles.
- Terrain-enabled rendering (raster DEM).
- Efficient loading via tiled raster/vector/DEM sources and GPU rendering.
- Navigation, fullscreen, and scale controls.

## Run locally
Because this app loads remote tiles/assets, serve it over HTTP:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Data sources (free/public)
- OpenStreetMap raster tiles
- OpenMapTiles demo vector tiles
- MapLibre public demo terrain tiles
