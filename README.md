# NYC Citibike Analysis

https://public.tableau.com/views/NYC_Citibike_Challenge_16574153673080/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link

An exploration of NYC Citibike data with Pandas and Tableau

## Overview

The purpose of this analysis is to evaluate different metrics of the NYC Citibike data and identify trends with the goal of advising the creation of a similar bikesharing company in a smaller urban market in the midwest. (In this specific case Des Moines, Iowa) The Specific metrics of focus were peak riding times, gender breakdown of riders, and duration of trips taken. 

## Results:

Key visualizations and descriptions can be viewed [on Tableau](https://public.tableau.com/app/profile/theodora.nutaitis.lopez/viz/NYC_Citibike_Challenge_16574153673080/NYCCitibikeAnalysis?publish=yes)

## Summary:

- Most trips are taken by male riders: 65.28% versus 25.1% for female riders. This can be further explored by isolating different age groups. IF further visualizations are created comparing The Baby Booomer (1946-1964) and Millennial (1981-1996) generations, there is a difference of around 4.5% in the number of trips taken by female riders

![Gender_Breakdown_Age](https://user-images.githubusercontent.com/99051640/187586477-15d466ff-cd23-48ca-98de-7c4d0365bf28.png)

- Most trips taken are around 5-6 minutes in duration. For female riders mnost trips are around 6 minutes, for male riders it's around 5 minutes. Starting and ending locations in NYC will most likely be closer in distance due to the unique geography. In a city like Des Moines, the trip durations will likely be higher due to the layout of a less urbanized location. This, in conjunction with trip distance, should be a condiseration for pricing strategy as there will likely need to be a different formula for calculation. 

- Most rides are taken during traditional "rush hour" times for both male and female riders. The most popular time is weekdays at 6pm. The most popular weekday is Thursday, the least popular is Wednesday. The most common time for bike checkout is around 5-6pm overall.  
  - Rides taken by riders whose gender is listed as "unknown" are mostly on Saturdays and Sundays. This could possibly be a reflection of one-time or infrequent users of the service who select "unknown" to save time during the sign up process because it is the default option (This possible scenario is mentioned again when exploring the number of rides by birth year.) 
  
 - The most popular ridig times for non-subscribing customers by contrast is during the weekends. The peak being Saturdays around 12pm

![customer_trips](https://user-images.githubusercontent.com/99051640/187589187-c4eeea30-04b4-4143-b4ae-16b628dd6638.png)

- Another important consideration to explor further is the age distribution of riders. With a simple bar graph, it appears many riders fall within a specfic range of birth years (1981-1995) which corresponds to the Gen Y generation. It would be beneficial to compare the age-related demographics of NYC and Des Moines to gague the potential demand as well as marketing strategy and considerations. Moreover, the culture of a city can vary to the point of potentially impacting the amount demand from older and/or younger age groups.
  - 1969 stands out with an unusually high number of rides that is possibly due to that year being the default option and selected more often due to user error, saving time or to avoid giving personal info. 

![Age Breakdown](https://user-images.githubusercontent.com/99051640/187582836-a2ed130c-1420-4445-ba3e-721248facfb7.png)

