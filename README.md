# Bikes!

## Overview of the statistical analysis:  

The purpose of this analysis was to delve into the New York City's Citi Bike program and see how it works, who rides them, and when.  Because we're looking to open up a Citi Bike branch in the city of Des Moines, which as everyone knows, is much like New York City so the observations and conclusions we arrive at will of course have a high degree of external validity.  Given the throughness of the dataset, we had many different variables to explore- parameters like gender, age, duration of trip, the coordinates of where each trip started and ended, among many others helped us find out key results and display those results visually. To do this, we used Tableau, which allowed us to make charts of our results that are dynamic and visually appealing.  We combined the charts we found to be most interesting into a *story* that helps us create a narrative with which to pitch to our investors about our Des Moines project.

## Results: 


![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Bike_usage_by_hour_bins.png)

- this visualization charts bike usage throughout the day, filtered by bins (groups) we created. Each bin is comprised of a 15 year range. For example, the two age groups that use the Citi Bike system the most, represented by 1965 (purple) and 1980 (orange) in the legend, are made up of the years 1965-1980 and then 1980-1995 respectively.

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Bikes_hour_minute.png)

- This chart shows the breakdown of bikes in use by both hour (top x-axis) and minute (bottom x-axis) throughout the day. Bikes are used the most in the early morning, and then usage rate slowly tails off throughout the day.

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Bikes_hour_minute_gender.png)

- This chart further breaks down bike usage throughout the day by filtering the users by their gender.  Males make up the majority of users, but there seems to be no difference in the usage patterns throughout the day when it comes to gender- both men and women (and those who identify as unknown) have the same peak usage times and have the same downward slope of usage rate as the day progresses.

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Heatmap_weekday_gender.png)

- This heatmap breaks down bike usage by the users gender filtered by weekday.  This chart further illustrates how female and males have similiar usuage patterns- it's just that men are more likley to use the service in the first place.

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Usertype_gender_bins.png)

- This chart helps visualize the breakdown in the two user types: **Customer** (one time user) and **Subscriber** (a user who has an Citi Bike account and likely utlizes the service often.  Overall, most of the users of the service are **Subscribers** which makes sense, if you plan on using the service more than once, you'd want to set up an account that lets you easily and quickly get a bike.  

- It's tough to infer too much from the Customer part of the chart- as a large majority of the users who fall under that description selected "unknown" for gender (almost all the users born between 1965-1980 did this).  This again though, makes sense.  These individuals are maybe tourists who don't plan to use the service again, and skip through the process to begin riding a bike as quickly as possible.

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/Usertype_gender_weekday.png)

- This heatmap breaks down bike usage by gender and by user type throughout the week. Subscribers have much heavier usage rates throughout the week, espeically male customers.  The most popular day for male subscribers to use the service is Thursday.  Users that're identified as customers have a much lower usage rate, especially on weekdays.  Peak customer usage comes on Saturday, followed by Sunday. Which again gives creedence to the idea that most customers are likely from out of town and are simply visiting New York for the weekend.

![alt_image](https://github.com/Nickguild1993/bikesharing/blob/main/Tableau_visualizations/heatmap_weekday_hours.png)

- This heatmap shows bike usage by weekday by hour.  The darker the tile, the more bikes that're in use during that time. This chart lines up with the idea that many people use the bikes to commute to and from work.  The highest rate of start times are between 8:00 a.m. - 9:00 a.m. and then 5:00 p.m. - 6:00 p.m. which coincides with the daily schedule of working people.


## Summary: 

Citi Bike is clearly a very popular program across the spectrum- both men and women of all ages (New York definetely has some spry 145 year olds biking around!) utilize the bikes in a pretty consistent pattern throughout the day. The compact, heavily urbanized nature of New York City means that the bike users really get alot out of the service- they're able to get from point a -> b much faster than walking, with the added benefit of not using a mode of transportation that emits pollutants, which we think will be a great selling point when we launch in Des Moines.

While Des Moines does seem to have a beautiful grided downtown area that would likely be where the grand majority of the bikes would be used, it is hard to ascertain with any degree of confidence how applicable the NYC data is to Des Moines.  One has to consider all the differences between the two cities- population, weather patterns, average age of potential user, whether individuals commute a distance that is feasible for biking, etc.  So while this is a great starting point, we believe more research should be done on Des Moines and its urban area population.

One visualization I'd like to see would be distance that each bike trip covered by the amount of time the bike was in use.  I tried to figure out how to do this by experimenting with the start/stop latitude and longtitudes, but I couldn't get it to overlay on a map of NYC, which would be by far the most useful way to look at this potential data.  You could see which routes that people take are the most efficient and which routes encounter the heaviest traffic.

Another visualization that I think would be interesting would be looking at the amount of time that passes from when someone gets off the bike to when a new user activates the same bike, based on where the bike's End Station Id is. That would allow you to see which stations have the fastest turnaround time (because the bikes aren't generating any revenue when they're idle) and make sure the those End Stations that have the lowest turnaround time are always well stocked with bikes and concurrently, those stations that do have a long turnaround time don't horde a bunch of bikes that are idle.
