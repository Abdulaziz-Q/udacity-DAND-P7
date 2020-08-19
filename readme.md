# Ford GoBike System Data
## by Abdulaziz Alqumayzi


## Dataset

> Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.

> In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019. The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.


## Summary of Findings

> The first variable `duratuion_sec` which shows total duration use of the bikes per second.  It shows one insight, which is most of the duration used is below 20k seconds. But after digging deeper, I found that the second graph shows the most of the duration is below 1600 seconds.

> The variable `user_type` is 54.4% of the users are subscribers, and 45.6% of the users are customers. Very small difference. For the `rental_access_method` variable, there is a massive use of the app with respect to the clipper.

> The variables `start_station_id` and `end_station_id` shows stations that people started from and ended with.
Most of the start and end of the stations are nearly the same. Stations id that is below the id `150` is the most visited for both as start or end of the trip.

> I compared the duration time per minute and seconds with the user type to check the relationships. I found that there is no difference in the duration time between the customer and subscribers. They seem to lookalike with little bit difference. But, the interesting thing is that customers are more using bikes than subscribers.

>The duration time between the use of rental access method (app and clipper) are near to each other. But, with a small difference to the app.


## Key Insights for Presentation

> The duration time average is higher for the customer than the subscriber. Whether they are using the rental access method for the app or clipper. The average duration ride for a customer that using the app is 1535 and the who is using clipper is 770. For a subscriber, the average duration time for a ride and using the app is 756, and the who is using the clipper is 654.
> The trip duration time is between 400 to 800 seconds. Or, 6 to 13 minutes.
