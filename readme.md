# Bay Wheels Ride Data Exploration & Visualization
## by Muhammad Ahmad Raza

## Dataset

> [Bay Wheels](https://www.lyft.com/bikes/bay-wheels) is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District.Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. **Source** [wikipedia](https://en.wikipedia.org/wiki/Bay_Wheels)

> The Dataset I'm using for my Data Analizing and visualization consist of monthly trips performed by individuals (Customers and Subscribers). Please check data source here: [baywheels-data](https://s3.amazonaws.com/baywheels-data/index.html). I'm using data from January 2018 to December 2018.

**Assessments from this Data Set Which I cleaned by my self:**
- start_time and endtime must be datetime objects.
- start_station_id and end_station_id must be string obects.
- start_station_id and end_station_id are ending with extra .0
- DataType for user_type and bike_share_for_all_trip should be Category.

## Summary of Findings
- 17:00 was the most busy hour as more then 200000 riders travelled in this time on everyday.
- Tuesday, Wednesday and Thursday were days with more riders, more then 300000 riders travelled on these days throughout the year 2018 on these days.
- There were more riders from May to October as compare to remaining month. These were 175000 in these months.
- Obviously, the most of riders were those who got subscription before ride. On the other hand very few as compare to subscribers were thoese who were just non subscribers.
- Most of the time bike was not shared in the whole trip, as it can be seen that only bellow 200000 riders shared their bikes in the whole year.
- The most of the trips were shorder then 1hr.
- The Number of Subscribers are more then number of customers. About 80% users are those who had subsucription from comapny.
- There were more long duration trips on weekedns then Week days.
- The number of riders are more in weekdays then weedays.
- San Francisco Caltrain Station 2 (Townsend St at 4th St) is the most popular station where most of the riders took rides.
- 2nd St at S Park St is the least popular station and very few riders use this service in this area. It is observed that less then 20 riders only start their journy from this station in 2018

## Key Insights for Presentation
> As I've draw two different heatmaps 1 for customers and others for Subscribers which shews usage pattren for two different rider types. It can be seen clearly that Subscribers heavily use rides on Weekdays whereas the Customers mostly use rides on Weekends. If we talk about timing which are most popular in both categories, we can say that Subscribers mostly use it to commute to office in the morning and in the evening 7:00 -9:00 and 16:00 -18:00 respectively. Whereas, use 10:00 to 17:00 on weekend respectively.
