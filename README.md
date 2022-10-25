# Bikesharing
![]()

[link to dashboard](https://public.tableau.com/app/profile/melanie.taylor6095/viz/CityBikeData_16655489967290/Story2?publish=yes)

# Overview 

The purpose of this analysis is to look at trends and key data points from the August bike rentals data set of NYC CitiBike to determine factors that can contribute to the success of a similar business model in Des Moines. I took into consideration Gender, Usertype, and location as the main factors that contribute to success and provide a path for further analysis.

Tools used
- Jupyter notebook and Pandas for data cleaning and  conversions
- Tableau for visualizations

# Results 

Top starting Location:
The larger the circle the more times that was a starting location for a bike rental. 
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/nyc.png

Checkout Times:
This shows the number of checkout bokes on th y-axis and trip durations on the X. THis is divided by hours because the vast majority of rides are under 1 hour and 3 catches almost all rides.  
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/checkout%20times%20for%20users%20.png)

Checkout Times by Gender:

This map is similar to the one above but broken up into gender. this reinforces that men are the primary consummer- but also that most traveling occurs between the same hours of the day, for the work and school commute 
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/checkout%20times%20for%20gender%20.png)

Trips by Weekday per Hour: This graph shows the total number of trips by weekday and hour. The more trips that are accounted for the deeper red, orange, and yellow colors. with the dark blues and purples being the least active timedWe can see that the highest demand times are the morning hours on weekdays from 6am till 9am and in the evening hours on weekdays between 5 pm and 7 pm. Whereas the weekend high-demand hours are middle of the day ‘leisure’ hours between 10 am and 6 pm.
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/trips%20by%20gender%20(weekday%20per%20hour)%20.png)

Trip by Gender Breakdown

This breakdown shows how the vast majority of customers are male
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/gender%20breakdown.png)


Trips By weekdays: 
We can see the same trends here agin, weighing heavily towards commute times. interesting to note that Thursday is the most popular day for bike rentals among male and females whereas others most popular days are Saturday and Sunday.
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/trips%20by%20weekday.png)

User Types by gender and usage by weekday: 
The graph shows the number of trips by weekday, by user type, by subscribers versus customers, and by gender. In the subscriber category. once again we see how, males have the highest number of trips with the most popular days being Thursday, Friday, Tuesday, then Monday. Females also show the same trends but have a lower frequency. The other gender category has the lowest rentals during the week, especially in the subscriber category but shows more usage as customers on Saturday and Sunday.- meaning these could be one-time customers using more casually or for leisure.
![](https://github.com/MellyCodes808/Bikesharing/blob/main/visualizations/user%20trips%20by%20weekday.png)


# Summary 

Overall, we can see that bike rental in August of 2019 were very popular with over 2 million rentals in one month. With the majority of the rentals occur during the weekday around normal work and school commute times. This is important because predictable times lead to better bike placement and scheduled maintenance windows that allow to best serve customers. It is also interesting to note that the user demographic is largely subscriber-based loyal customers. There's a substantial amount of one-time users which provides the opportunity for them to convert to subscribers. Also, gender greatly skews toward male users, which provides a better understanding of target user types for marketing and product features in the future.

For future analysis, I would suggest drilling down into the cost of each trip, and one-time user-to-subscriber conversion rate. This would allow another metric that determines the duration and give a point of reference for one-time user numbers and the suspected amount of subscribers that could be gained. especially given that subscribers are the highest income driver. I would display this similarly to the trip duration graph but replace the number of bikes rented with the amount paid. I would also suggest looking into trip beginning and end locations with conversion rates to further see what factors lead to regular use. I would do this by utilizing the map and placing bigger ticks where the highest conversion rates occur.
