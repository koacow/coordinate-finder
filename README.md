# Coordinate Finder

## Overview

Python notebook that uses the Google Places API to search for Australian health centers' coordinates using a text query.
Accepts a .csv file with placenames under 'Facility' and exports an csv file with selected columns from the original dataset appended with the coordinates ('Latitude' and 'Longitude') of each facility. If the query returned no results or invalid results (e.g. not in Australia), then the coordinates for that facility is recorded as 'None.'

## How to use

1. Fork repo

2. Edit input and output filepath

```python
input_file_path = 'path/to/your/input/file.csv'
export_file_path = 'path/to/your/input/file.csv'
```

3. Add your Google API key
   
4. Click Run All
