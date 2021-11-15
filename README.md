# Analysis of Weather Patterns in Oahu
## *Data for Surf n' Shake Business Proposal*
### Purpose: determine whether the island's historical weather patterns are fit for opening new business
---
## Weather Analysis
### Analysis Based on June Temperatures
During our analysis of Oahu's historical temperatures, we pulled in 1,700 pieces of data, each piece of data equating to a temperature taken in the month of June over the span of the years 2010 to 2017.  All data was queried from a SQLite database and filtered by available month and temperature data.  We then performed a statistical analysis to determine the average, standard deviation, minimum, maximum and quartiles of the June temperature data. 

### Analysis Based on December Temperatures
We ran the same analysis for December, pulling in an additional 1,700 pieces of data, each piece of data equating to a temperature taken in the month of December over the span of the years 2010 to 2017.  All data was queried from a SQLite database and filteres by available month and temperature data.  We then performed a statistical analysis to determine the average, standard deviation, minimum, maximum and quartiles of the December temperature data.  

## Results
Our analysis of the weather data shows, between the years 2010 and 2017:<br/>
- The average temperature in June was 74 degrees
- The maximum temperature in June was 85 degrees
- The minimum temperature in June was 64 degrees
- The standard deviation of the June temperature data is 3.26
- The average temperature in December was 71 degrees
- The maximum temperature in December was 83 degrees
- The minimum temperature in December was 56 degrees
- The standard deviation of the December temperature data is 3.75

## Resources
* Data Source: SQLite file 'hawaii.sqlite'
* Software: Jupyter Server via VS Code, Version 1.62.2

## Summary
The average temperature for June and December are within 3 degrees and within a considerable and optimal range for comfortable outdoor activities.  It is worth noting that maximums for both months reached the 80s, which is fairly warm but not too hot, and the temperature minimum for December only dropped to 56 degrees.</br></br>
The standard deviation of the data is fairly large at 3.26 for the June data and 3.75 for the December data, meaning that the data is fairly spread out and may compromise the average temperatures provided. However, multiple temperatures were taken for a single day, meaning the outlier temperature may have been procured during the early hours of the morning or late at night when the potential business would be closed.</br></br>
December and June were selected to show a reasonable span of temperatures in different parts of the year.  While the temperature data and analysis provided appropriate and reasonable temperatures to move forward with the business proposal, it may be worth taking a deeper look at the data in analyzing temperatures for all months of the year.  Analyzing precipitation levels may also be helpful, as it can rain on a day with reasonable or optimal temperatures, which my curtail business.  
