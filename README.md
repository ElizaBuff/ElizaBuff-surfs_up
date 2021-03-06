# Surfs Up Analysis
## Overview of Project
### Background of Project
I plan to open a surf supply and ice cream shop on O'ahu, Hawaii. After putting together a business plan, I reached out to W. Avy, an investor, and he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in O'ahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
### Purpose of Project
In this project, I demonstrated my proficiency with Python, Pandas functions and methods, and SQLAlchemy to filter the date column of the measurements table in the database to retrieve all the temperatures for the month of June and December. Then I converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics. 

---
## Results
* June’s average temperature is 4 degrees warmer than December. June has an average temperature of 75 degrees while December averages 71 degrees. 
* Temperatures below 64 degrees and above 81 degrees in either month are rare. 95% of the temperatures in June fall between 68 degree and 81 and 95% of the temperatures in December fall between 64 degree and 79 degrees. 
* Although December has a low of 56 degrees in December compared to a low of 64 degrees in June, 56 degrees is so unusual (falls outside of 99.7% of the temperatures recorded in December) that it should not be a factor.  
 
The tables below compare the recorded temperatures in June and December respectively. 


![temps_tables](temps_tables.png) 

---
## Summary 
June is a warmer month than December in O’ahu; however, the temperate difference between the months is inconsequential.  **By and large June is approximately 2-4 degrees warmer across statistical comparisons.** Therefore, the temperatures in June and December are so similar that temperature will not be a hindrance in opening the Surf and Shake shop. 

Two additional weather factors to consider are wind speed and amount of sunlight for June and December. 
* Since wind speed is an important element to surfing vis-à-vi waves, wind speed data may indicate if either month is more, less, or equally lucrative.  Do wind speeds vary from June to December in O’ahu?
* Sunlight is likely to bring in more customers for both surfing and ice cream. How do the number of sunny days, partly sunny days, and total days with sun vary from June to December in O’ahu?







