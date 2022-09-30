## Dataset Overview
The dataset contains records of bike trips undertaken in the San Francisco Bay Area.
There are over 180,000 trip records for the month of February 2019 from bike renting/sharing company called Lyft. 
The data is in the form of a csv file, which is included in this repository , "201902-fordgobike-tripdata.csv". 
Information on trips is contained across 18 feature columns like duration_sec, start_station_name, member_gender, member_year to name just a few. 

## Wrangling Efforts
I found that this dataset contained some null values, and incorrect datatypes for columns like dates. I dropped rows containing these and corrected the datatypes. I also did some feature engineering to extract useful features like Age and Trip distance. The cleaner csv version after doing some wrangling is also included in the repository, bike_clean.csv. You will also note that I performed some aggregations on time series data to bring some insightful statistics.

## Summary of Findings
In exploring the profile of the bikers, I found out that trips were undertaken by mostly males as compared to other gender types. It was also apparent that Subscribers dominated the data than Customers who usually take 24 hour or 3 day passes. Most of the bikers do not share their bikes during the trip, with the Customer user type actually recording zero bike shares for the period February 2019. 

It was also interesting digging into the age profile. It came out that most trips were taken by bikers in their 20s and 30s. However, there was a significant number of trips taken by bikers in their 50s and 60s, with abnormal ages like the oldest being 141 years old at the time they took their trip. Surely, that must have been a data entry error or something.

There was also a highly positive correlation between three features: unique number of bikes rented, total distance covered during trips and the total number of rentals. It was however apparent that bikers preferred riding during the week, than on weekends. The geographical data when plotted showed that the most popular stations with riders were along Main St, in the San Francisco Bay area.

## Key Insights for Presentation
For the presentation I focused mainly on Age and Gender distribution profiles of the riders. The boxplot for age captures the emphasis on the 20s and 30s age group. It also highlights the 50s, and 60s age groups in the wings with outliers were also noted.
I also looked at the gender profile, showing Males dominating in trips, making up over 3 times more trips taken than Females. 
Lastly I presented time series data to show that most trips were taken during weekdays than on weekends.
