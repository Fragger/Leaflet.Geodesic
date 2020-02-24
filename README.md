[Leaflet.Geodesic][example]
================

Geodesic polylines, polygons and circles for [Leaflet](https://github.com/Leaflet/Leaflet) 1.x.

These will follow the curvature of the Earth and are used just like the normal versions of the constructors that are rendered as straight lines on the screen.

[example]: https://raw.githack.com/IITC-CE/Leaflet.Geodesic/master/examples/index.html


`L.GeodesicPolyline`
------------------

**L.geodesicPolyline**(<LatLng[]> _latlngs_, <[Polyline options]> _options?_)

- [Example]

[Polyline options]: https://leafletjs.com/reference-1.5.0.html#polyline-option


`L.GeodesicPolygon`
------------------

**L.geodesicPolygon**(<LatLng[]> _latlngs_, <[Polyline options]> _options?_)


`L.GeodesicCircle`
------------------

**L.geodesicCircle**(<[LatLng]> _latlng_, <[Circle options]> _options?_)

- [Example][example-circle]

[example-circle]: https://raw.githack.com/IITC-CE/Leaflet.Geodesic/master/examples/circle.html

<details><summary>
(obsolete way)
</summary>

**L.geodesicCircle**(<[LatLng]> _latlng_, <Number> _radius_, <[Circle options]> _options?_)
</details>

[LatLng]: https://leafletjs.com/reference-1.5.0.html#latlng
[Circle options]: https://leafletjs.com/reference-1.5.0.html#circle-option
