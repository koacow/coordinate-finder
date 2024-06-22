# Coordinate Finder

## Overview

Python notebook that uses the Google Places API to search for Australian health centers' coordinates using a text query.
Accepts a .csv file with placenames under 'Facility' and exports an excel file with original data appended with the coordinates of each facility or 'None' if the query returned no results or invalid results (not in Australia).

## How to use

1. Fork repo

2. Edit input filepaths and exported file's name

```python
input_file_path = 'path/to/your/input/file.csv'
```

```python
export_file_name = 'name_of_your_export.xlsx
```

3. Click Run All Cells