# (Data Exploration On Ford Gobike Data)
## by (Osayuwamen Aigbogun)


## Dataset

> This dataset which is the Ford GoBike System Data, includes information
about individual rides made in a bike-sharing system covering the greater
San Francisco Bay area for the month of February 2019. There were 183412 entries
and 16 columns in the dataset, but after cleaning there was 174952 entries 
and 20 columns. Most features are numeric in nature, with three categorical features 
which are the member gender, weekday and user type.



## Summary of Findings

>In the exploration, I found out that there was a strong relationship between 
the duration and the age, member gender, user type, dates, and weekdays .The trip duration 
in the dataset take on a vary large range of values, and most are from about 61 seconds to 
about 10,000 secounds. Plotted on a logarithmic scale, the distribution of duration takes a 
unimodal shape and is slightly skewed right. The duration started at 200 with trips around 3000,
with the peak between 500 and 700, then it falls gradually.Most people who go for rides
are within the age range of 20-40 years, which gives an inverse proportion with duration, 
because as the age increases there is a decrease in trip duration. The male gender is more
dominant in the bike trips, from the data the gender Other have the highest duration, with the 
Females coming after, while the least are males, that means the Other gender spend most time on trips, 
while the males spends less time. Most users are subcribers, although subscribers are more, 
customers tend to go on longer trips. Most people go on bike rides on thursday, but they
tend to stay longer on weekends, which can be because they are not working days and they
have more time to themselves.


## Key Insights for Presentation

> For the presentation, I will focus on just the influence of the features on the duration
and leave out most of the intermediate derivations. I will start by introducing the distribution 
of the duration, plotted on a logarithmic scale, the distribution of duration takes a 
unimodal shape and is slightly skewed right. The duration started at 200 with trips around 3000,
with the peak between 500 and 700, then it falls gradually. After that I will look at some features
affecting it, like a bar chart of duration by member gender, which shows the male gender is more
dominant in the bike trips, from the data the gender Other have the highest duration, with the 
Females coming after, while the least are males. Then a bar chart of duration by weekday, 
which shows that most people spend more time on bike rides on weekends. Lastly a scatterplot of
duration by ages and user types, which will depict that the younger bikers tend to stay on rides
long than the older bikers.
