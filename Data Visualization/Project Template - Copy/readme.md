# Exploration of Cancelled Flights
### by Jason Kanhai


## Dataset

TThe data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. For the purpose of this project, focus was given on the most recent data from 2008 that included over 7 million commercial flights. It provides details on delayed flights, aircraft details, distance and length of flights, cancelled flights and reasons for cancellation. 
The dataset can be found [here](https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009)

## Summary of Findings

During my exploration, my main aim was to look at the temporal characteristics of cancelled flights. 
Small variations in the number of cancelled flights were observed across the days of the week but greater variation was seen across months of the year. Variation was also observed across days of the month, however this didn't shed any additional light on the data, also many months lack 31 days and any further insights pulled from this wouldn't be a true representation of the dataset. 

It was interesting and surprising to observe that the distribution of Cancelled flights across Days of the Week and Months of the year shared a similar trend with % flights cancelled across the same periods. It suggests that a direction relationship exists between the number of flights and the number of cancelled flights on that given day/month. 

Additional exploration of cancelled flight characteristics were done including their duration, distance covered, scheduled departure time and and cause for Cancellation. When plotted separated, it was noted that most cancelled flights had a duration of 80-100 mins and distances of 500-900 km. However, when these variables were plotted against each other on a heat map, the highest concentration of cancelled flights had durations between 50-100 mins and covered distances of 100-400km. 

In the final multivariate heat map which brought together flight distance, duration, Cancellation type and Scheduled Departure Time, some key insights were drawn which showed that most Security related cancellations happened in the Early PM on flights that covered distanced between 200-300km and durations of 60-70 mins. Weather related cancellations also happening with these distances and durations but less likely to occur in the Early AM. No security cancellations occured in the early AM. 


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

For the presentation, focus is initially given to the % of flights cancelled in 2008, I then dive deeper, lookign into the temporal characteristics of cancelled flights (Day of Week and Month) while also focusing on the distrubition of Cancelled flight durations and distances separateley. 

Following this, I begin to introduced Cancellation Type by looking at the percentage of each that makes up all cancellations. By using various bivariate visualizations, I begin to look at how each Cancellation type varies across the week and by month. I can then focus is on which flights were most likely to be cancelled in 2008 based on their distance and duration using a heatmap. 
Using this subset dataframe, I am then able to look at which flights were cancelled in 2008 based on flight distance, duration, Cancellation type and Scheduled Departure Time using multivariate visualizations.
