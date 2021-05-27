# Displaying Bike Share Data/Conducting Analysis with Tableau and Pandas

### Link to Data Story:
https://public.tableau.com/app/profile/dean.arnold/viz/Module14Assignment/NYCCitibikeStory

## Overview
The Bike Share company Citibike has provided a large dataset for the month of August tracking every single ride in New York City, and all the data that comes with it. This includes start/end coordintes, length of trip, gender of user, etc. As shown in the link above, multiple types of analysis are able to be conducted, and displayed in an interactive manner with Tableau.

## Results
We first clean the dataset using Python/Pandas, by simply converting the column with trip times (displayed in whole seconds) into datetime, then our new dataset is loaded into Tableau for analysis.

With the link above opened, our story shows us the following, while additional information is showed where the mouse is hovered over:

- Total count of rides logged in the dataset
- Busiest hours throughout the entire month
- Length/count of trips displayed in a line chart, then filtered by gender
- Heatmaps demonstrating the amount of rides by hour, day, gender, and customer type 

## Summary
While our Tableau charts are visually appealing, dynamic, and allowing of different types of analysis to be made (such as when to do maintenance/adjust rates) some general conlcusions can be made:

- Of the 2+ million trips logged for august, 5pm is the most popular time, and 3-4am is the least
- Most trips are around 5 minutes long, and most popular among males, mostly on Thursdays
- Most Citibike customers are subscribers to the service, as opposed to just regular customers.


