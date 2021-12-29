# Bike Sharing

## Overview of Analysis

The purpose of this analysis was to look data pertaining to Citibike use in New York City to understand if a similar bike program would work in other cities such as Des Moines, Iowa. The data for this project was gathered from the ride.citibikenyc.com and visualized using Tableau. The data is from the month of August in 2019 and visualizations were created to look at bike usage by gender, time of day, day of the week, length of bike rides and ,start vs end locations. In order to create some visualizations, the data was loaded into Jupyter Notebook and the startime column was converted into a datetime object.

[link to story](https://public.tableau.com/app/profile/leah.ikenberry/viz/NYCCitiBikeChallenge_16407497120350/Story1)

## Results

![Peak August Hours](https://github.com/likenberry/bikesharing/blob/main/Resources/Peak_August_hours.png)
This is a visualization of the number of bikes used during different hours of the days. It is easy to see the peak hours or when the most bikes are in use. Peak hours are from 8-9AM in the morning and 5-6PM at night which would concide with people traveling to and from work. The lowest number of bike rides occurs between 2-4AM which would indicate the best time for bike maintainance so that all bikes are ready for peak hours. The month of August was chosen since it would be a busier month to show usage trends more clearly.
![Checkout Times by Users](https://github.com/likenberry/bikesharing/blob/main/Resources/Checkout_times.png)
This visualization shows the duration of all of the bike trips. It is clear that a majority of the bike trips were under an hour with most only lasting between 5-10 minutes. This indicates that most bike trips are very short commutes probably to and from work and it probably a faster option than public transporation. Very few bike trips are longer than 30 minutes and almost none longer than an hour, so the bikes are mostly used for commuting instead of tours or scenic rides which might be possibilities in other cities.
![Checkout Times by Gender](https://github.com/likenberry/bikesharing/blob/main/Resources/Checkout_gender.png)
The visualization above shows a similar visualization as above but the duration of bike rides is broken down by gender. The bike rides taken by males are shown in yellow, the bike rides taken by females are shown in blue and a third category of gender "unknown" is shown in red. Most trips were taken by males followed by females and very few trips were taken where the gender was unknown.
![Top Starting Locations](https://github.com/likenberry/bikesharing/blob/main/Resources/Start_locations.png)
Above is a visualization of New York City and the surrounding area where the most popular starting locations for a bike ride are indicated by a darker blue color and a larger circle size. Lighter blue circles with a smaller radius indicate a less popular starting location. The highest concentration of starting locations in Manhatten and around tourist locations.
![Top Ending Locations](https://github.com/likenberry/bikesharing/blob/main/Resources/End_locations.png)
This is a similar visualization as before but instead shows the most popular ending locations of bike rides. It has a very similar trends to the starting locations indicating that a lot of bike rides might be round trips like to and from work. The larger, darker red circles show the most popular ending locations and the smaller yellow cirles show the less popular ending locations. The less popular ending/starting locations might be dependent on bike availability with a higher concentration of bikes located in the city with less in more rural areas and therefore less riding opportunities.
![Trips by Weekday per Hour](https://github.com/likenberry/bikesharing/blob/main/Resources/Trips_weekday.png)
This is a visualization of the number of trips taken by start time and weekday. It is a heatmap with the darker red color indicating more trips taken and a yellow color meaning less trips taken. It is clear to see that the most popular day to ride a bike is Thursday but there is still the trend of more bike trips taken to commute to and from work. The bike usage on the weekends is mostly in the afternoon probably for more leisurely trips.
![Trips by Gender (Weekday per Hour)](https://github.com/likenberry/bikesharing/blob/main/Resources/Trips_gender.png)
This is a similar visualization as the one previously but has a breakdown by gender. There are three heatmaps following the same color scheme as before. The same trend is observed with peak hours for commmuting and males still taking the most trips but females following the same trend and less trips taken by people with their gender unknown. However, the unknown gender has an increase in usage on Saturday afternoons which could be tourists without a subscription to the bike service.
![User Trips by Gender by Weekday](https://github.com/likenberry/bikesharing/blob/main/Resources/Trips_gender_weekday.png)
There are two types of bike users: customers and subscribers. Subscribers are people that need to use the bikes regularly and therefore have an account with Citibike. Customers are probably more casual users or tourists who only need limited access to bikes and therefore might not have an account. This visualization is a heatmap showing the breakdown of bike rides per weekday by gender and by user type. Most bike rides are by subscribers with only a few taken by customers. The trends notice previously are again observed clearly here where subscriber males use the bikes the most frequently.

## Summary

All of this analysis and visualizations show that the most popular bike user is a male subscriber who uses the bike to commute to and from work from somewhere in downtown NYC.
Further analysis of this data could be done to look at specific starting and ending locations by user type to understand where bikes need to be stocked to meet user demand but differentiating between regular users and tourists. It might also be useful to consider when popular starting/ending locations are the busiest to have these locations properly stocked for weekday vs. weekend use.

## Resources

- Data Source: 201908-citibike-tripdata.csv
- Software: Tableau Desktop (Public Edition) version 2021.4.2, Jupyter Notebook
