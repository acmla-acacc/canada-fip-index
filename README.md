# canada-fip-index
Canadian Fire Insurance Plan Index (Geolocated Place Names)
(digitize index of 'Catalogue of Canadian fire insurance plans, 1875-1975 / Lorraine Dubreuil, Cheryl A. Woods.Ottawa : Association of Canadian Map Libraries and Archives, 2002.')

## Process
- Information has come from [this Google Sheet](https://docs.google.com/spreadsheets/d/1lgdZendLE0A31_LldNS8bkRWa6p5nedHnSEH9LWVT6Y/edit#gid=1021922479).
- locations geocoded using Google Maps API in Google Sheets [example](https://docs.google.com/spreadsheets/d/1hxatV525kOBaT-t7FwEqCsM6KY8NP4tR3GIh4ipFOrw/edit#gid=594864751)
- Download as csv
- Use [Convertcsv.com](http://convertcsv.com/csv-to-geojson.htm) to convert to GeoJSON
- Upload to Github

## Issues
- In Github, no way to explode overlapping markers (you see only the first record
  - possible to export as a leaflet map? 
- Need to improve information display
- Provide links to main collection pages (or sub-collection pages) for each organization listed in a collection's holdings.

