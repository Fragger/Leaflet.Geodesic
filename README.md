[Leaflet.Geodesic][example]
================

Description
-----------

Geodesic polylines, polygons and circles for [Leaflet](https://github.com/Leaflet/Leaflet) 1.x

Adds:
```
L.GeodesicPolyline( <LatLng[]> latlngs, <Polyline options> options? )

L.GeodesicPolygon( <LatLng[]> latlngs, <Polyline options> options? )

L.GeodesicCircle( <LatLng> latlng, <Circle options> options? )
L.GeodesicCircle( <LatLng> latlng, <Number> radius, <Circle options> options? ) -- obsolete way
```

These will follow the curvature of the Earth and are used just like the normal versions of the constructors that are rendered as straight lines on the screen.

See **[example]**.


[example]: https://raw.githack.com/IITC-CE/Leaflet.Geodesic/master/examples/index.html
