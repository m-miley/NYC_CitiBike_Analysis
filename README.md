# NYC_CitiBike_Analysis

- Resources 
    - Tableau
    - Extract Files: NYC_CitiBike_Challenge.csv, NYC_CitiBike_Challenge_datetime.csv


## Overview

Tableau Analysis to Visualize data from New York City's Bike Share program, CitiBike, for the month of August with an intent to present to investors for a startup implementation in Des Moines, Iowa. Similar business strategies can be applied. The most practical insights drawn from this analysis concern resource availability and usage, customer base demographics and user type, and trip duration and distribution patterns.

## Results

[Tableau Public Link to Workbook Story 1](https://public.tableau.com/app/profile/marshall3619/viz/NYCCitiBikeAnalysis-DUStory1/Story1)<br>
[Tableau Public Link to Workbook Story 2](https://public.tableau.com/app/profile/marshall3619/viz/NYCCityBike-DUStory2/Story2)<br>
[Tableau Public Link to my Tableau Public Profile](https://public.tableau.com/app/profile/marshall3619#!/)<br>
<br/><br/>

## Story 1

Story 1 Walks us through "Where?", "Who?, "When?", and "What Age?" questions identifying the customer base and their riding habbits and patterns.
<br/><br/>

**Dashboard**
![Screen Shot 2022-06-25 at 5 34 24 PM](https://user-images.githubusercontent.com/100544761/175792353-337e2876-1d23-469d-8306-481a471bce77.png)
- Overview of snapshots explained in following storyline.  It can be interactively filtered by clicking on the Gender Breakdown Pie Chart.  The most significant insights that can only be discovered from this visual is filtering the start/end locations by clicking a start location bubble.  This shows the ending locations for each top start location.  With further data manipulation with SQL, or perhaps a calculated field, we can see which stations end with more bikes than they start with to help plan re-distribution schedules to avoid overcrowding and undersupplied stations.  This will maximize user experience when interacting with our services.
<br/><br/>

**Top Starting Locations**
![Screen Shot 2022-06-25 at 5 27 15 PM](https://user-images.githubusercontent.com/100544761/175792239-4d4b3c7a-8f4f-4985-9955-d9725d60bac1.png)
- First up, we see a high concentration of activity near Downtown Manhattan where there is booming economy and tourism.  Filtered to show only stations with at least 5,000 rides to help dashboard filter functionality.
<br/><br/>

**Subscriber and Gender Breakdown in Ride Count, Percent, and Avg Trip Duration**
![Screen Shot 2022-06-25 at 5 40 19 PM](https://user-images.githubusercontent.com/100544761/175792476-de1ae53c-907e-4590-bd30-aa8ce5000478.png)
- Next, we get a clear view of which genders are using our resources in exact proportions and for how long they ride.  Male Subscribers do a majority of the riding at 58.1 percent, however, Females generally spend more time per trip.
<br/><br/>

**Peak Hours by User Type and Weekend vs. Weekday**
![Screen Shot 2022-06-25 at 5 43 28 PM](https://user-images.githubusercontent.com/100544761/175792536-4460fbd4-26f0-489d-bad7-46d1f2778344.png)
- Here it's easy to see how riding patterns for our users by time of day comparing weekends to weekdays.  For Subscribers, throughout the workweek, have a very clear spike in usage during commuting hours and relatively calm and spread out activity through the weekend.  Customers on the other hand, steadily increase their riding as the hours of the day progress up to 5pm before declining during the weekdays.  Contrarily, on the weekend, their activity doesn't decline but we see more riding earlier in the day with the peak 11am - 5pm.
<br/><br/>

**Overall Weekly Activity by Hour** <br>
![Screen Shot 2022-06-25 at 5 49 17 PM](https://user-images.githubusercontent.com/100544761/175792633-7af08d4b-28ad-47c0-987c-54ff24e3f8a2.png)
- Similar information is conveyed in the Highlight table showing the significance for resource availability during weekday commuting hours and most of the day Saturday.  Clearly, any attempts at maintenance should be scheduled outside of peak hours.
<br/><br/>

**Birth Year Subscriber Histogram**
![Screen Shot 2022-06-25 at 5 52 56 PM](https://user-images.githubusercontent.com/100544761/175792685-64ec9eae-0640-4f76-9ec5-1dde3a83d6f8.png)
- To better understand our user base, we can clearly see that the largest subscriber groups are born between 1980-1995.  
<br/><br/>

**Trip Duration by Birth Year**
![Screen Shot 2022-06-25 at 5 56 09 PM](https://user-images.githubusercontent.com/100544761/175792752-443fa354-4d91-4eda-9bbc-402fae09b7eb.png)
- This visualization shows the trip duration patterns per age group.  The outlier at 1965 is because it's the default birth year programmed in for single use customers without an age input.  Average Trip Duration is 17.5 minutes.
<br/><br/>

## Story 2

Story 2 Walks us through finer detail of trip duration patterns, Overall and by Gender, with a pair of line charts.  Then, similarly describing weekday patterns from Story 1 and further breaking it down to Gender and User Type.  Ending on Bike Utilization circle graph showing bikes most used and in need of maintenance.  Finally, culminating in a stunning Dashboard bringing all the insights together for interactive analysis.
<br/><br/>

**Overall Trip Duration by Number of Rides per Minute**
![Screen Shot 2022-06-25 at 6 36 15 PM](https://user-images.githubusercontent.com/100544761/175793596-3bb4de7d-3592-4216-89f4-9b616a907c08.png)
- From this graph, it's clear that highest ride counts are 4-7 minutes long overall.  However, the average ride duration is still 17.5, calculated in another sheet.
<br/><br/>

**Trip Duration by Gender**
![Screen Shot 2022-06-25 at 6 38 38 PM](https://user-images.githubusercontent.com/100544761/175793648-568d3140-2c61-4876-8e7b-b06597f4c5f7.png)
- A finer look at how genders compare with trip with ride count and trip duration.  They all seem to follow a similar pattern overall, peaking near 5 minutes before dropping off. However, female and unknown genders declines more gradually than males.
<br/><br/>

**Weekly Trips by User Type by Gender**
![Screen Shot 2022-06-25 at 6 42 31 PM](https://user-images.githubusercontent.com/100544761/175793796-71927301-4214-45a6-8ebe-64e8fc65547b.png)
- Highlight Table shows how Male Subscribers are by far the biggest customer base by nearly 3x compared to Females and more compared to Unknowns.
<br/><br/>

**Bike Utilization**
![Screen Shot 2022-06-25 at 6 45 34 PM](https://user-images.githubusercontent.com/100544761/175793787-944332a1-6795-422d-82ca-b77310d80166.png)
- Circle Graph showing which bike Ids are experiencing the most usage and therefore in need of maintenance and checkup.  Larger and Darker Circles show higher ride counts.  This data can be compiled in a more usable list format easily at the request of an interested party.  
<br/><br/>

**Dashboard**
![Screen Shot 2022-06-25 at 6 52 23 PM](https://user-images.githubusercontent.com/100544761/175793924-ca775de9-2069-4a23-bbc5-79e221a2f133.png)
- The Dashboard nicely packages the insights gleaned from the story data into one window.  In addition, BANs are provided up top explaining number of rides, number of bikes used, and average trip duration, rounded up to nearest whole number.  All charts and graphs can be filtered using Gender Filter and User Type Filters to produce more detailed visualizations.  Feel Free to explore and see what else you discover!
<br/><br/>

## Summary
In Conclusion, we now have a clarification of the required resources, usage implicatioins, location, and demographic data concerning our overall system and customer base.  Although this is New York City, we can easily bring in additional, external data about Des Moines and compare city layout, distances, economy, demographics, population and generate a custom strategy that fits the city needs. We can scale the data to predict an initial startup cost for resources, bike count and station locations.  Furthermore, we could perhaps predict number of rides based on population and economic activity specific to Des Moins yet similary proportional to NYC.

Meanwhile, we do have enough clear insights that help our marketing strategy, age and gender.  A closer look at starting and ending Locations in terms of the surrounding resources as well could offer insights to custom marketing. For maintenance, we could track individual bike Id's and send them to maintenance after a certain ride count or trip duration sum.  Also and clearly, the busy hours should be avoided for routine maintenance and redistribution.  

Given more time, with a broader data set including all the months of the year and perhaps several years, I could suggest maintenance schedules for best time of year to perform an annual mainenance checkup.  

Thereafter, in regards to deeper analysis and additional visualizations, I would like to create a calculated field to determine the rate of accumulation / bike loss at each station to record which stations should be actively monitored for redistributing / resupplying.  I would also like data on the specific bike models being used and could visualize data based on that to help restructure our menu.  Users with shorter trips, typically male commuting subscribers, would likely like a light frame, thin tires, and short wheel base that can zip around the city quickly, aka road bike.  Touring bikes to assist those with more baggage and longer trips.  Electric bikes for tourists and customers who wish for leisurely travel or with physical disability.  Scooters for the non-pedalers.

Let's keep this going, the more data, the better!
