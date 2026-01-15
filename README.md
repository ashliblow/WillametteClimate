# WillametteClimate

## Project Details
This repository is part of a climate data project from Lookout Eugene–Springfield by Ashli Blow and Michael Zhang. The project produces a monthly concise article using rainfall, snowpack, and drought data to track climate conditions in the southern Willamette Valley. This README serves as a guide to standardize how data are collected, processed, and reported for the monthly articles. 

## Data Sources

### Rain and Snow Data
Rainfall and snow data come from the Applied Climate Information System (ACIS), managed by NOAA’s Regional Climate Centers.  
Source: [https://scacis.rcc-acis.org/](https://scacis.rcc-acis.org/)

**Rainfall (Sum)**  
- Product selection: Precipitation (Sum)  
- State/Area: Oregon / Lane County  
- Stations used:  
  - McKenzie  
  - Cougar Dam  
  - Eugene–Mahlon Sweet Field  
  - Mapleton  
  - Florence #2  

**Snowfall (Sum)**  
- Product selection: Snowfall (Sum)  
- State/Area: Oregon / Lane County  
- Station used:  
  - McKenzie  

**Snow Depth (Sum)**  
- Product selection: Snow Depth (Sum)  
- State/Area: Oregon / Lane County  
- Station used:  
  - McKenzie  

### Drought Data
Drought data come from the U.S. Drought Monitor.  
Source: [https://droughtmonitor.unl.edu/DmData/DataTables.aspx?state=or](https://droughtmonitor.unl.edu/DmData/DataTables.aspx?state=or)

- Select county-level data.  
- Use the Drought Severity and Coverage Index (DCSI).

The DCSI ranges from 0, indicating no abnormal dryness or drought, to 500, indicating exceptional drought. Values near 250 reflect moderate to severe drought conditions.

## Directory / Folders
- Is there a directory?
- We need the shared folder clearly in the LO Eugene-SPringfield Drive. 

## Method / Approach 
-  The project uses Google Colab to run script. Colab is a hosted Jupyter Notebook service that requires no setup to use and provides free access to computing resources.
- The project uses a short Python script that relies only on the Python standard library to fetch, process and format climate data.
  - `__future__` — enables forward-compatible language features
  - `csv`, `json`, `os` — file handling and data formats
  - `dataclasses` — simple data structures
  - `datetime` — dates and time ranges
  - urllib.request, urllib.error — fetching data from the web
- The script exports data into a spreadsheet to be located in a 
-  API (is this covered?) 
- Exported into a spreadsheet 
- Flourish? Datawrapper? 

## Processed Data

- A bar chart or histogram of 2025 monthly data compared to 2020 and 2015 months. 
