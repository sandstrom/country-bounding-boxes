# Country Bounding Boxes

A list of ISO 3166-1 country codes and their bounding boxes. Useful when zooming a map 
to a specific country in Mapbox, Google Maps or similar services.

The boxes are confined to the primary area for each country. Outlying territory are excluded 
(for example, the US bounding box does not contain Pacific islands such as Guam).

Feel free to PR suggested changes (bounding boxes for missing countries or updates to existing boxes).

*If complete polygons for each country is needed, use the raw data in the Natural Earth 
dataset instead (see source below).*

## Example

```json
{
  "AF": ["Afghanistan", [60.53, 29.32, 75.16, 38.49]],
  "AO": ["Angola", [11.64, -17.93, 24.08, -4.44]],
  "AL": ["Albania", [19.3, 39.62, 21.02, 42.69]],
  "AE": ["United Arab Emirates", [51.58, 22.5, 56.4, 26.06]],
  "AR": ["Argentina", [-73.42, -55.25, -53.63, -21.83]],
  "AM": ["Armenia", [43.58, 38.74, 46.51, 41.25]],
  "AQ": ["Antarctica", [-180.0, -90.0, 180.0, -63.27]],
  "…"
}
```

## Source
Extracted from http://www.naturalearthdata.com (110m cultural vectors, admin 0)

## License
Public Domain
