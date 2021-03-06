
# Analysis of Weather Patterns in Oahu
## *Data for Surf n' Shake Business Proposal*
### Purpose: Determine whether the island's historical weather patterns point to suitable conditions for launching new business in Oahu
---

</br>
During our analysis of Oahu's historical temperatures, we pulled in 1,700 pieces of data, each piece of data equating to a temperature taken in the month of June over the span of the years 2010 to 2017.  All data was queried from a SQLite database and filtered by available month and temperature data.  We then performed a statistical analysis to determine the average, standard deviation, minimum, maximum and quartiles of the June temperature data. We ran the same analysis for December, pulling in an additional 1,700 pieces of data and completing the same steps as above.  The results were as follows:
</br>
</br>

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
</br>

Summary Statistics for June Historical Weather Data   |  Summary Statistics for December Historical Weather Data
:-------------------------:|:-------------------------:
<img src="https://github.com/ajcurtis916/surfs_up/blob/main/resources/June_summ_stats.png" width="200" />|<img src="https://github.com/ajcurtis916/surfs_up/blob/main/resources/Dec_summ_stats.png" width="200"/>
</br>

## Resources
* Data Source: SQLite file 'hawaii.sqlite' in "resources" folder
* Software: Jupyter Server via VS Code, Version 1.62.2
</br>

## Summary
The average historical temperatures during the months of June and December were within 3 degrees of each other, and within an optimal range for outdoor activities.  It is worth noting that maximum temperatures for both months reached the 80s, and the minimum temperature for December dropped to only 56 degrees.

The standard deviation of the data is fairly large at 3.26 for the June data and 3.75 for the December data, meaning that the data is fairly spread out and may compromise the average temperatures provided. However, multiple temperatures were taken for a single day, meaning the outlier temperatures may have been procured during the early hours of the morning or late at night when the potential business would be closed.

December and June were selected to show a reasonable span of temperatures in different parts of the year.  While the temperature data and analysis provided appropriate and reasonable temperatures to move forward with the business proposal, it may be worth taking a deeper look at the data and analyzing temperatures for all months of the year.  Analyzing precipitation levels may also be helpful, as it can rain on a day with reasonable or optimal temperatures, which my curtail business.  
