 eBay wheels Data exploration
## by (Abd ALJalil Nasser)


## Dataset
Bay wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District.Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States .
The dataset cotains the trips for 2019 year (i used months from 1 to 12 csv files). https://www.lyft.com/bikes/bay-wheels/system-data
Each trip is anonymized and includes:
Trip Duration (seconds)
Start Time and Date
End Time and Date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)



## Summary of Findings

  - The trips duration distribtuion is right skewed 
  - Tuseday is the day with the highest number of trips followed by Thursday .
    Sunday is is the day with the lowest number of trips.
  - july is the month with the highest number of trips followed by March .
    December is the month the lowest number of trips .
  - Hour 17 in the day is the hour with the highest number of trips followed by hour 8 and hour 18 .
    Hour 3 in the day is the lowest number of trips followed by hour 4 and hour 2.
  - App is more likely to be used as a rental access method 
  - most of the users are subscribers . 
  - Almost trips duration distributions are the same for all the monthes except the peek of the distribution .
  - Almost trips duration distributions are the same for all the days of the week except the peek of the distribution.
  - customer rides longer trips then subscriber although number of subscriber riders are very high then customer.
  - users who use app for as a rental access method rides longer trips than users who use clipper . 


## Key Insights for Presentation
  - tip duration in the dataset take on range of values from about 1 minute to 100 minutes.Plotted 
 on a decimal scale, the distribution of trip duration takes a right skewed. Trip durations mostly centered at values less than 30 minutes with peak arround 8 minutes.
  - users who are customers and use app as rental access method ride longer than customers who use clipper.
  - users who are subscribers and use app as rental access method ride longer than customers who use clipper.
  - users who are customers ride for longer trips than subscribers .
