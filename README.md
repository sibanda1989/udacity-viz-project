## Dataset Overview
The dataset contains records of bike trips undertaken in the San Francisco Bay Area.
There are over 180,000 trip records for the month of February 2019 from bike renting/sharing company called Lyft.

## Preliminary Wrangling
There were some rows which contained null values for columns like Gender, Birth Year. These were dropped because such demographic information is not easy to engineer. I also did some feature engineering to calculate Age from Birth Year, and trip distance from Longitude and Latitude data.

## Insights
The Age and Gender profiles of clients was investigated. Generally, the majority of trips were taken by people in their 20s and 30s. Although there were notable riders in their 50s, and 60s. Outliers were also noted with the oldest recorded being 141 years old, which is very odd. Males dominated in trips, making up over 3 times more trips taken than Females. I also investigated time series data to show that most trips were taken during weekdays than on weekends.
