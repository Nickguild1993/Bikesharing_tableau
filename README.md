# bikesharing

## Overview of the statistical analysis:  

The purpose of this analysis was to delve into the Citi Bike program in New York City and see how it works, who rides them, and when.  Because we're looking to open up a Citi Bike branch in the city of Des Moines, which as everyone knows, is much like New York City so the observations and conclusions we arrive at will of course have a high degree of external validity.

In order to analyze the Citi Bike data, we used Tableau to create charts that are dynamic and visually appealing. Those charts were then combined into a "story" which allows us to convey the results we found in an informatative and engaging way.

## Results: 

There are at least seven visualizations for the NYC Citibike analysis (7 pt)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Bike_usage_by_hour_bins.png)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Bikes_hour_minute.png)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Bikes_hour_minute_gender.png)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Heatmap_weekday_gender.png)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Usertype_gender_bins.png)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Usertype_gender_weekday.png)

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/heatmap_weekday_hours.png)

There is a description of the results for each visualization (7 pt)
## Summary: 

Citi Bike is clearly a very popular program across the spectrum- both men and women of all ages (New York definetely has some spry 145 year olds biking around!) utilize the bikes in a pretty consistent pattern throughout the day. The compact, heavily urbanized nature of New York City means that the bike users really get alot out of the service- they're able to get from point a -> b much faster than walking, with the added benefit of not using a mode of transportation that emits pollutants, which we think will be a great selling point when we launch in Des Moines.

While Des Moines does seem to have a beautiful downtown grided area that would likely be where the grand majority of the bikes would likely be used, it is hard to asertain with any degree of confidence how applicable the NYC data is to Des Moines.  One has to consider all the differences between the two cities- population, weather patterns, average age of potential user, whether individuals commute a distance that isn't feasible for biking, etc.  So while this is a great starting point, we believe more research should be done on Des Moines and its urban area population.

One visualization I'd like to see would be distance that each bike trip covered by the amount of time the bike was in use.  I tried to figure out how to do this messing with the start/stop latitude and longtitudes, but I couldn't get it to overlay on a map of NYC, which would be by far the most useful way to look at this potential data.

Another visualization that I think would be interesting would be looking at the amount of time passes from when someone gets off the bike to when a new user activates the same bike, based on where the bike's End Station Id is. That would allow you to see which stations have the fastest turnaround time (because the bikes aren't generating any revenue when they're idle) and make sure the those End Stations that have the lowest turnaround time are always well stocked with bikes and concurrently, those stations that do have a long turnaround time don't horde a bunch of bikes that are idle.
