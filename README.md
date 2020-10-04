# Bike Sharing

## Overview 

Citi Bike is a bicycle sharing system in New York City. Travelers use bikes to explore historic landmarks, and there is the potential to start a similar bike-share business in Des Moines, Lowa. there may be an investor who might be interested in providing seed funding to explore a bike-share program in Des Moines. The first step is to figure out how the bike-share business works in New York City, and then create a proposal on how it may work in Des Moines. To solidify the business proposal, one of the key stakeholders would like to see the following in the bike trip analysis:

* The length of time that bikes are checked out for all riders and genders.
* The number of bike trips for all riders and genders for each hour of each day of the week.
* The number of bike trips for each type of user and gender for each day of the week.
    
## Results
    
### CitiBike Dashboard
* 1,900,356 were Subsriber Users and 443,865 were Customer Users.
* 1,530,272 were Males, 588,431 were Females and 225,521 were unknown users.
* Peak trip start time in August was 5 pm to 7 pm.
* Number for Bikes in use is lowest between 1 am to 5 am.

Dashboard:
![Citibike Dashboard](https://github.com/k2handa/bikesharing/blob/master/Tableau%20Story/Citibike%20Dashboard.png)

### Checkout Times for users

* The length of time that bikes were checked out by all riders(see image below).
* 4 to 6 hours was the peak length of time bikes were checked out for all rider.

![checkout time for users](https://github.com/k2handa/bikesharing/blob/master/Tableau%20Story/checkout%20time%20for%20users.png)

### Checkout times by gender

* The length of time that bikes were checked out by Gender (see image below).
* 4 to 6 hours was the peak length of time bikes were checked out for males.
* 5 to 7 hours was the peak length of time bikes were checked out for females.

![checkout times by gender](https://github.com/k2handa/bikesharing/blob/master/Tableau%20Story/checkout%20times%20by%20gender.png)

### Trips by weekday per hour 

* The number of bike trips for all riders for each hour of each day of the week (see image below).
* Weekdays have a higher stop-time from 7 am to 10 am and 5 pm to 7 pm for all rider.
* Weekend have spread out stop-time between 10 am to 7 pm for all rider.

![trips by weekday per hour](https://github.com/k2handa/bikesharing/blob/master/Tableau%20Story/trips%20by%20weekday%20per%20hour.png)

### Trips by gender (weekday per hour)

* The number of bike trips by genders for each hour of each day of the week (see image below).
* Weekdays have a higher stop-time from 7 am to 10 am and 5 pm to 7 pm for Male riders.
* Weekend have spread out stop-time between 10 am to 7 pm for Male riders.
* Weekdays have a higher stop-time from 8 am to 10 am and 5 pm to 7 pm for Female riders.
* Weekend have spread out stop-time between 11 am to 6 pm for Female riders.

![trips by gender (weekday per hour)](https://github.com/k2handa/bikesharing/blob/master/Tableau%20Story/trips%20by%20gender%20(weekday%20per%20hour).png)

### User Trips by user by weekday

* The number of bike trips for each type of user and gender for each day of the week (see image below).
* Male and Female Subscriber riders peak is during the weekdays
* Male and Female Customer riders peak is during the weekends.

![user trips by gender by weekday](https://github.com/k2handa/bikesharing/blob/master/Tableau%20Story/user%20trips%20by%20gender%20by%20weekday.png)

## Summary

* we can see the users tend to heavily use the bike sharing before and after working times, more so after working hours.
* male users seem to be the brunt of the users for bike sharing as well compared to women.
* while there a heavy amount of users during the weekdays before and after working hours, there is a more of a distribution of users on the weekends spread through   the day

further analysis that could have been done, is to create a calculation field to calculate the distance between Start Station and End Station for each trip and create the following two visualizations:

* The avg distance traveled for all riders and genders for each week of the day.
* The avg distance traveled for each type of user and gender for each week of the day.

please see NYC citibike story below:

[Link to Story](https://public.tableau.com/profile/kevin.handa#!/vizhome/citibikechallenge/NYCCitibankStory?publish=yes)
