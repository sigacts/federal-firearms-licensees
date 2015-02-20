# Analyzing Federal Firearms Licensee Data


### Workflow
* Create a SQLite database with a `licensees` table
```
touch dbFFLicensees.sqlite
sqlite3 dbFFLicensees.sqlite
sqlite3 dbFFLicensees.sqlite <createTable.txt
```
* Parse the txt file and load each row into the SQLite database

### To Do
* Geocode each licensee using the `Premise` address attributes
* Export the geocoded results as GeoJSON

### Data
* Source: [Listing of Federal Firearms Licensees](http://www.atf.gov/content/firearms/firearms-industry/listing-FFLs)
* January 2015 dataset: 78,011 licenses
