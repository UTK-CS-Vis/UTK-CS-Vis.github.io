---
layout: default
---

# Resources

## Datasets

### NOAA HURDAT2 Dataset Subset (2004 to 2017)

The National Oceanic and Atmospheric Administration (NOAA) National Hurricane Center publishes the Atlantic hurricane database, also known as HURDAT2.  This dataset has a comma-delimited, text format with six-hourly information on the location, maximum winds, central pressure, and (beginning in 2004) size of all known tropical cyclones and subtropical cyclones.  We have created a subset of the HURDAT2 dataset with records from 2004 through 2017.  The subset file differs slightly from the NHC file format to make it easier to read as a standard comma-separated value (CSV) text file.  This file can be opened in Excel or other spreadsheet applications.  It can also be read by d3.js and p5.js built-in file I/O functions.  The first line of the file contains the names for each column.  The subset CSV file is available [here](./datasets/AtlanticHURDAT_2004_2017.csv)

The column names and descriptions are listed below:
1. ID: Storm identifier
2. Name: Storm name
3. DateTime: The date and time of the storm information
4. Record: Record identifier
	- C: Closest approach
	- G: Genesis
	- I: An intensity peak in terms of both pressure and wind
	- L: Landfall (center of system crossing a coastline)
	- P: Minimum in central pressure
	- R: Provides additional detail on the intensity of the cyclone when rapid changes are underway
	- S: Change of status of the system
	- T: Provides additional detail on the position of the cyclone
  - W: Maximum sustained wind speed
5. Status: Status of system
  - TD: Tropical cyclone of tropical depression intensity (< 34 knots)
  - TS: Tropical cyclone of tropical storm intensity (34-63 knots)
  - HU: Tropical cyclone of hurricane intensity (> 64 knots)
  - EX: Extratropical cyclone (of any intensity)
  - SD: Subtropical cyclone of subtropical depression intensity (< 34 knots)
  - SS: Subtropical cyclone of subtropical storm intensity (> 34 knots)
  - LO: A low that is neither a tropical cyclone, a subtropical cyclone, nor an extratropical cyclone (of any intensity) WV – Tropical Wave (of any intensity)
  - DB: Disturbance (of any intensity)
6. Lat: Latitude 
7. Lon: Longitude
8. Wind: Maximum sustained winds (in knots)
9. Pressure: Minimum pressure (in millibars)
10. NE_34kt: 34 kt wind radii maximum extent in northeastern quadrant (in nautical miles)
11. SE_34kt: 34 kt wind radii maximum extent in southeastern quadrant (in nautical miles)
12. SW_34kt: 34 kt wind radii maximum extent in southwestern quadrant (in nautical miles)
13. NW_34kt: 34 kt wind radii maximum extent in northwestern quadrant (in nautical miles)
14. NE_50kt: 50 kt wind radii maximum extent in northeastern quadrant (in nautical miles)
15. SE_50kt: 50 kt wind radii maximum extent in southeastern quadrant (in nautical miles)
16. SW_50kt: 50 kt wind radii maximum extent in southwestern quadrant (in nautical miles)
17. NW_50kt: 50 kt wind radii maximum extent in northwestern quadrant (in nautical miles)
18. NE_64kt: 64 kt wind radii maximum extent in northeastern quadrant (in nautical miles)
19. SE_64kt: 64 kt wind radii maximum extent in southeastern quadrant (in nautical miles)
20. SW_64kt: 64 kt wind radii maximum extent in southwestern quadrant (in nautical miles)
21. NW_64kt: 64 kt wind radii maximum extent in northwestern quadrant (in nautical miles)

