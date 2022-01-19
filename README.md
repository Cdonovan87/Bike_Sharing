# Bike_Sharing
[link to dashboard](https://public.tableau.com/app/profile/colin1467/viz/CitiBikeSharing_16426289746460/CitiBikeSharing "link to dashboard")
## Overview of Analysis
For this challenege I have been tasked with using citi bike data from New York to create vizualizations on Tableau to help convince investors to create a ride sharing program in Des Moines, Iowa. I were tasked with first transforming the trip duration to datetime on jupyter notebook. Then I had to create visualizations using this citi data to portray a story to the investors. For my story I first decided to look at bike usage and potential times to repair bikes. I then jumped into looking at tripduration and start time. I then begin to look at these metrics based on gender and user type.
## Results
1. Usage of Bikes

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/bikeuse.png)

Using this graph we are able to see which bikes have been used the most and will need to be repaired soon.

2. Peak Start Time

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/peakstarttime.png)

Piggybacking off of the first vizual we can use this graph to see what time would be best to do repairs. It seems that the time frame of 1-5 am is the best for repairs as that is the time with the lowest usage.

3. Trip Duration

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/tripduration.png)

Using this graph we can see what the peak trip duration for all users is. The peak duration is around 5 minutes.


4. Trip Duration by Gender

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/tripgender.png)

Much like before this graph shows trip duration but this time based on user gender. We can see that Males fall into the peak of 5 minutes and females are around the same but with just a little bit longer duration.

5. Start time by weekday per hour

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/weekdayperhour.png)

This graph shows us the start times by users by the day of the week per hour. Looking at it we see that most trips are started around 8 am and 5 pm during the week and between 10 am & 5 pm on the weekend.

6. Start Time by weekday per gender

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/weekdaygender.png)

Like the graph above we see the start time for each day for the different genders. Much like before the peak start times are the same but we can see that more males use the service than females.


7. Start Time by weekday per gender and user

![alt text](https://github.com/Cdonovan87/Bike_Sharing/blob/main/images/weekdaygenderuser.png)

Finally this graph shows us the start time by day based on gender and user type. Looking at we can see that more subscribers use the service than customers and that more men use it and that there are more male subscribers


## Summary
Looking at the results we can see a few things. First, for the bike repair, we can see that the best time to repair overused bikes would be between 1-5 am as that is the lowest point of bike usage. We can then see that the peak trip duration is around 5 minutes. We can also see that males and females use the bikes for different durations but not by much. Also, we can see that the average time that bikes are used by users is early in the morning, 8 am, and afternoon, 5 pm ( around the time work gets off). The same can be said when we look at it by gender as they are similar but Males still use the service more than females. We can also see that there are more subscribers than customers and that Males are more dominant as the users. Looking at the data two more visualizations I would make are looking at the average age of users and the average tripduration based on user age.
