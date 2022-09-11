# Citi Bike Viz: Module 14 Challenge

## Overview of Project

### Background and Purpose

After a two week vacation in New York City with your friend, Kate, where the two of you utilized a bike-sharing service to get around town, you and Kate get the idea to bring a bike-sharing business to your hometown of Des Moines, Iowa. After some brainstorming over a few weeks, Kate has good news - she has found a potential angel investor who might be interested in providing seed-funding to explore a bike-share program in Des Moines. You get to work analyzing and creating visualizations to show the investor how the program works in New York City, using sample data pulled from https://ride.citibikenyc.com/system-data for the month of August 2019.

### Resources

- Data Sources: 201908-citibike-tripdata.csv
- Software: Anaconda 4.13, Jupyter Notebook, Python 3.7.13, Tableau Public 2022.2, Visual Studio Code 1.68.1

## Results

### Visualization Analysis

For the presentation to the investor, the following visualizations were created:

1. Checkout Times for Users (line graph)
2. Checkout Times by Gender (line graph)
3. Trips by Weekday per Hour (heat map)
4. Trips by Gender (Weekday per Hour) (heat map)
5. Gender Breakdown (pie chart)
6. Trips by Gender by Weekday and User Type (heat map)
7. User Types (pie chart)

*Figure 1: Checkout Times for Users*

![Checkout_Times_for_Users](https://user-images.githubusercontent.com/106830513/189510860-fe21a281-208e-4c1f-a119-e61c49526a12.png)

This line graph shows the length of time a Citi Bike was used by number of trips and can be filtered by hour. The majority of users take trips lasting less than one hour, with the most common trip duration being five minutes.

*Figure 2: Checkout Times by Gender*

![Checkout_Times_by_Gender](https://user-images.githubusercontent.com/106830513/189510857-a0b00ba5-583b-4ba7-af83-bae698f4da46.png)

This line graph is the same as Figure 1, with the added breakdown by gender. Most users are males and have a trip duration lasting 5 minutes. We can now see that the most common trip duration for females is a little longer at 6 minutes and those who did not specify their gender had the highest number of trips at 11 minutes in duration.

*Figure 3: Trips by Weekday per Hour*

![Trips_by_Weekday_per_Hour](https://user-images.githubusercontent.com/106830513/189510877-f990d646-ec47-45d3-8380-b7e2b37dff82.png)

This heat map shows the number of trips taken per hour for each day of the week. The hours of 7-10am and 5-8pm during the week have the highest use rate.

*Figure 4: Trips by Gender (Weekday per Hour)*

![Trips_by_Gender_Weekday_per_Hour](https://user-images.githubusercontent.com/106830513/189510872-1b06ecc6-84a7-4ca2-85d2-3b8cd84d0766.png)

This heat map is the same as Figure 3, with the added breakdown by gender. Weekday mornings from 7-10am and weekday late afternoons/early evenings from 5-8pm have the highest frequency of use for both males and females. Those who did not specify their gender tended to utilize Citi Bike the most on weekends during the middle of the day.

*Figure 5: Gender Breakdown*

![Gender_Breakdown](https://user-images.githubusercontent.com/106830513/189510864-d6ee26cf-7d15-4c6d-8831-0161aad91d2d.png)

This pie chart shows the breakdown of total users by gender. It further demonstrates how the male gender makes up the largest Citi Bike user population at 65% of all users. Females make up 25% of the user population and those who did not specify their gender make up 10% of the user population.

*Figure 6: Trips by Gender by Weekday and User Type*

![Trips_by_Gender_by_Weekday_and_User_Type](https://user-images.githubusercontent.com/106830513/189510866-d0de33fc-fde8-4304-b4b4-635f18a4387e.png)

This heat map shows the number of trips by weekday, gender, and user type. Male subscribers make up most of the user population for Citi Bike. They are the largest user population every day of the week, with their most used days being Thursday and Friday.

*Figure 7: User Types*

![User_Types](https://user-images.githubusercontent.com/106830513/189510879-583e68d4-093b-4d71-9ab0-0dee800e6e4e.png)

This pie chart shows the breakdown of total users by user type. Most users are subscribers, making up 81% of the user population. The remaining 19% of the user population is customers.

To see these visualizations as a story on Tableau, visit the Module 14 NYC Citi Bike Challenge story on Tableau Public - [link to story](https://public.tableau.com/app/profile/danielle.fulgenzi/viz/Module14NYCCitiBikeChallenge/NYCCitiBikeChallenge?publish=yes).

## Summary

### High-Level Summary

Based on the analysis performed, there are a few key conclusions we can draw from the data to provide insight for a potential bike-sharing service in Des Moines.

+ Since the busiest times of day for use line up with the typical hours of "rush hour" traffic, we can draw the conclusion that most users utilize Citi Bike as a means of transportation on their commute to and from work.

+ Men are by far the largest user population. Installing new bike stations close to locations where males most commonly gather would help boost bike trips for the new business in Des Moines.

+ The most frequent trip duration is only 5 minutes, which could be explained by one of two things:
    - Users live close by to their place of employment, within a 5 minute bike ride.
    - Users live about 5 minutes away from another means of transportation, like the subway, and use the bike share service to ride from their home to the subway station.

+ Citi Bike has a very large population of subscribers, meaning users intend to use the service more than once and likely as a main form of transportation, mostly to and from work on a regular basis. The new business in Des Moines can cater to that population by locating areas with a higher density of businesses and office buildings and considering installing new bike stations that are at a distance within a 5 minute bike ride.

### Additional Visualization Suggestions

The cities of New York City and Des Moines are vastly different and in order to properly assess how a similar bike-sharing service might work in Des Moines, we could use some additional information. Two suggestions for visualizations are:

1. Type of Destination

Knowing the type of destination for each trip, such as place of business, restaurant, concert venue, or bus stop, could     help determine why users want to utilize a bike-sharing service. This in turn can help the service better provide for its   customers since we would know the need we are fulfilling for users and can place new bike locations appropriately.

2. Cost Basis

How much does it cost to rent a Citi Bike? Is it based on distance or time or is it a flat fee? Creating a visualization   that illustrates revenue over time or one that depicts the average cost per trip based on distance/time would be helpful   from an investor standpoint to help determine how many trips are needed for the business to be profitable.
