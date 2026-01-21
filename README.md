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
  - Eugene–Mahlon Sweet Field  
  - Leaburg  

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

## Method / Approach 
-  The project uses Google Colab to run script. Colab is a hosted Jupyter Notebook service that requires no setup to use and provides free access to computing resources.
-  The script establishes a directory to a shared Lookout Drive,
-  The code uses stations code in the script to pull it from ACIS and into Collab. This effectiely retrieves rain, snow depth, and snowfall data from ACIS.
-  Details of the coding is explained in text cells above code in the Google Collab script. 
-  Data is then exported into a spreadsheet in the same folder, allowing us to plug the data into datawrapper for visualization.

## Processed Data

- A bar chart or histogram of 2025 monthly data compared to  the last 10 years. 
