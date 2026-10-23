The Greenhouse Data Integration Project:
This project combines data from three IoT devices used in a greenhouse: soil sensors, a weather station, and a water controller. The goal is to organize information from these devices into one dataset that can be used to compare greenhouse conditions and irrigation activity.
The Project Files:
source-data/batch102.csv — Soil sensor readings, including soil moisture and soil temperature.
source-data/feed102.xml — Weather station observations, including air temperature, humidity, and wind speed.
source-data/stream102.json — Water controller events, including irrigation zones, flow rates, and pump status.
integrated_greenhouse.csv — Combined greenhouse dataset with readings sampled between 6:00 AM and 12:00 PM on July 15, 2026.
integration_report.md — Report explaining the integration process, design decisions, benefits, and limitations.
data_dictionary.xlsx — Excel data dictionary describing the fields in the integrated dataset.
The integrated dataset uses CSV format. Each record begins with a soil sensor reading and includes matching weather observations and any water controller event recorded at the same time.
Missing values are left blank rather than estimated. Dates and times are standardized to make the data easier to compare.
The combined data can help greenhouse staff investigate relationships between soil moisture, environmental conditions, and irrigation activity.