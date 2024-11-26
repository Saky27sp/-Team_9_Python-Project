# Team_9_Python-Project
This repository contains our team's Python project, which explores and analyzes a comprehensive world airport dataset.
We aim to uncover trends, patterns, and insights related to airport locations, passenger traffic, and infrastructure worldwide through data cleaning, manipulation, and visualization.

**Dataset Focus:**
The project uses the International Airports Dataset, offering a comprehensive overview of global airports.

**Dataset Highlights**
The following CSV files were used in our analysis
	1. airports.csv
	2. countries.csv
	3. navaids.csv
	4. regions.csv
	5. runways.csv

Data Dictionary:

### airports.csv Columns:
1. *id*: Unique identifier for each airport.
2. *ident*: Airport’s identifier code (often an ICAO or IATA code).
3. *type*: Type of airport (e.g., "heliport," "small_airport," "medium_airport").
4. *name*: Full name of the airport.
5. *latitude_deg*: Latitude coordinate of the airport in degrees.
6. *longitude_deg*: Longitude coordinate of the airport in degrees.
7. *elevation_ft*: Elevation of the airport above sea level, in feet.
8. *continent*: Continent code where the airport is located.
9. *iso_country*: ISO country code of the airport’s location.
10. *iso_region*: ISO region code (state/province).
11. *municipality*: Primary city or town served by the airport.
12. *scheduled_service*: Indicates if the airport offers scheduled airline services ("yes" or "no").
13. *gps_code*: GPS code (typically matching the ICAO code).
14. *iata_code*: IATA code for the airport.
15. *local_code*: Local code representing the airport.
16-18. *Unnamed columns*: Extra columns without descriptions or content.

### countries.csv Columns:
1. *Unnamed: 0*: Unlabeled unique identifier.
2. *code*: Country code in ISO format.
3. *name*: Country name.
4. *continent*: Continent code for the country.

### runways.csv Columns:
1. *id*: Unique identifier for each runway.
2. *airport_ref*: ID reference to the associated airport.
3. *airport_ident*: Airport identifier where the runway is located.
4. *length_ft*: Runway length in feet.
5. *width_ft*: Runway width in feet.
6. *surface*: Runway surface type (e.g., asphalt, grass).
7. *lighted*: Indicates if the runway is lighted (1 for yes, 0 for no).
8. *closed*: Indicates if the runway is closed (1 for yes, 0 for no).
9. *le_ident*: Identifier for the runway end.

### navaids.csv Columns:
1. *id*: Unique identifier for each navigational aid.
2. *filename*: Name associated with the navigational aid.
3. *ident*: Identifier code for the navigational aid.
4. *name*: Name of the navigational aid.
5. *type*: Type of navigational aid (e.g., NDB, DME).
6. *frequency_khz*: Frequency of the navigational aid in kHz.
7. *latitude_deg*: Latitude of the navigational aid in degrees.
8. *longitude_deg*: Longitude of the navigational aid in degrees.
9. *elevation_ft*: Elevation above sea level in feet.
10. *iso_country*: Country code where the navigational aid is located.
11. *magnetic_variation_deg*: Magnetic variation at the location, in degrees.
12. *usageType*: Type of usage (e.g., LO for low-level usage).
13. *power*: Power level of the navigational aid.
14. *associated_airport*: Identifier of the associated airport.
