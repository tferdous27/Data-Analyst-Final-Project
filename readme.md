# Exploring Ford GoBike Data 2019
## by Tonima Ferdous


## Dataset

The dataset provides bike share statistics of approximately 183,000 individual rides made in California's San Francisco Bay Area in February 2019. The bike share schedule and pattern of the users are reflected in this data set. Among the variables we have duration_min, start_time & end_time, age, station names, user_type, member_gender, and etc. Around 9,000 data points are excluded from the dataset due to inconsistencies or missing information.


## Summary of Findings

In this investigation, I wanted to determine the trip pattern of Ford GoBike users by exploring a dataset of February 2019. Different features of the riders, such as, age, gender, and subscription are analyzed to identify their influence on the trips. Investigation is also conducted on trip stations, duration, and timing on weekdays and weekends.

**Duration and Age:** We have noticed an inverse relationship between these two variables. Trip duration decreases in general as age increases, as expected.

**Duration and User Type:** Trips taken by the customers are usually longer compared to the subscribers.

**Duration and Member Gender:** Female riders took longer trips compared to the males.

**User Type and Member Gender:** Higher percentage of males are subscribed members compared to the females. Only 1 in 8 female riders have bought the subscription. On the other hand, the subscriber to customer ratio is 6:1 in male members.

**Age and Member Gender:** Plots do not show any strong relationship. However, the other gender group has a small percentage of riders between 50 and 60 years, which is much higher compared to male and female riders.

**User Type and Start Time:** We found a similar distribution for subscribers and customers. The histograms are bimodal with spikes in 8 am and 5 pm. However, the count of trips are 25% higher at 5 pm compared to 8 am in customers. Looks like customers are more likely to rent a bike while returning from work and then leave the bike at some other time.

**Mean Trip Duration for Days and Hours:** Higher trip durations are observed during the weekends. Among the working days, Mondays and Thursdays have higher trip durations, about 10 to 14 minutes.

**Trip Duration by Genders for Different Days:** It is verified in the multivariate exploration that female riders are renting bikes for long durations, particularly, on the weekends.

**Trip Duration for Different Stations:** For each of the top 10 start stations and end stations, the median duration of bike trips is longer for customers than subscribers.


## Key Insights for Presentation

First, I included some primary interaction plots to create a preface of the findings I was going to present, such as, user types by age and gender, age and duration correlation plots, and etc. To depict the relationship between age and duration, I created two subplots—age and duration scatterplot and age and duration heatmap—side by side. This visualization offered a better understanding of the scenario compared to the exploration part, where the plots were presented in a different order.

Next, I moved on to the slides of my major findings. I created an explanatory visualization on trips by days and hours. For this particular analysis, I generated a new bivariate plot (start time histograms for different days of the week) which was not there in the exploration part of the project. However, similar kind of other plots (with these variables) actually triggered me to create this new interaction graph for my final presentation.

I, then included the polished plots of findings, such as, users take longer trips on weekends, customers take longer trips than subscribers, and females bike longer than males. I determined some very strong trip patterns or styles from the GoBike sharing data with these visualizations. Finally, I added another interesting finding on bikeshare stations with the plot called trip duration by top stations.
