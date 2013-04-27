[Leaflet.Geodesic](http://fragger.github.io/Leaflet.Geodesic/)
================

### Description
Geodesic polylines and polygons for [Leaflet](https://github.com/Leaflet/Leaflet)

Adds:
```
L.GeodesicPolyline( <LatLng[]> latlngs, <Polyline options> options? )
L.GeodesicPolygon( <LatLng[]> latlngs, <Polyline options> options? )
L.GeodesicMultiPolyline( <LatLng[][]> latlngs, <Polyline options> options? )
L.GeodesicMultiPolygon( <LatLng[][]> latlngs, <Polyline options> options? )
```
These will follow the curvature of the Earth and are used just like the normal versions of the constructors that are rendered as straight lines on the screen