# S2 Vector Tile Spec Changelog

# 1.0.0

The `S2 Vector Tile Spec` is derived from [Mapbox's Vector Tile Spec](https://github.com/mapbox/vector-tile-spec).
The intent of this spec is to add 3D support along with better encoding for multipolygons.

* removed "UNKOWN" support... how could that be useful? Create your own spec.
* 3D support
* Another layer of depth for multipolygons. Before you had to waste cpu cycle to check if the polygon was clockwise for outer rings.
