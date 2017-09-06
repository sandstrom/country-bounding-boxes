# Country Bounding Boxes

Useful when zooming a map to a specific country in Mapbox, Google Maps or similar services.

If complete polygons for each country is needed, use the raw data in the Natural Earth dataset instead (see source below).

## Example

```json
{
  "AF": ["Afghanistan", [60.5284298033, 29.318572496, 75.1580277851, 38.4862816432]],
  "AO": ["Angola", [11.6400960629, -17.9306364885, 24.0799052263, -4.43802336998]],
  "AL": ["Albania", [19.3044861183, 39.624997667, 21.0200403175, 42.6882473822]],
  "AE": ["United Arab Emirates", [51.5795186705, 22.4969475367, 56.3968473651, 26.055464179]],
  "AR": ["Argentina", [-73.4154357571, -55.25, -53.628348965, -21.8323104794]],
  "AM": ["Armenia", [43.5827458026, 38.7412014837, 46.5057198423, 41.2481285671]],
  "AQ": ["Antarctica", [-180.0, -90.0, 180.0, -63.2706604895]],
  "…"
}
```

## Source
Extracted from http://www.naturalearthdata.com (110m cultural vectors, admin 0)

## License
Public Domain
