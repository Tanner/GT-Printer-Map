GT Printer Map
==============
Locations of all the student accessible printers at Georgia Tech.

Want to contribute?
===================
Add a point to geojson file:
```
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [-84.39826, 33.773823]
  },
  "properties": {
    "Location": "Student Center - Copy / Fax Area",
    "Printer Options": "Black and White, Color"
  }
}
```

Set the `Location` property to the building name and the specific area where the printer is located. Separate the areas by a hyphen (`-`).

Set the `Printer Options` property to the types of printers available. Valid options are:
* `Black and White`
* `Color`

If multiple are available, separate the options by commas, e.g. `Black and White, Color`.

Find a problem?
===============
Send a pull request!