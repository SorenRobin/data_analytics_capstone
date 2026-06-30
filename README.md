# Chicago Taxi Trips Sample Capstone
Capstone Project analyzing sample data from the City of Chicago's regulatory department, original data covering from 2013-2023.
<br >

## About the Data

The data comes from BigQuery's public datasets, but can also be accessed on the City of Chicago's website ([found here](https://data.cityofchicago.org/Transportation/Taxi-Trips-2013-2023-/wrvz-psew)).
My dataset is a random sample of 1,000,000 observations from the greater whole.
* **unique_key:** Unique identifier for a specific taxi trip taken
* **taxi_id:** Anonymous identifier for particular taxi vehicles assigned to a driver
* **trip_start_timestamp:** Starting date and time of the trip (rounded to nearest 15 minutes)
* **trip_end_timestamp:** Ending date and time of the trip (rounded to nearest 15 minutes)
* **trip_seconds:** Duration of trip in seconds
* **trip_miles:** Distance of trip in miles
* **pickup_census_tract & pickup_community_area:** Numbered identifier for pickup locations (some suppressed for anonymity)
* **dropoff_census_tract & dropoff_community_area:** Numbered identifier for dropoff locations (some suppressed for anonymity)
* **fare:** Trip base pricing
* **tips:** Tips made to the driver
* **tolls:** Fees for tolled highways and bridges
* **extras:** Miscallaneous fees
* **trip_total:** Sum of fare, tips, tolls, and extras
* **payment_type:** Form of payment used
* **company:** Taxi service the trip was made with
* **pickup_latitude & pickup_longitude:** Coordinates of pickup location (some supressed for anonymity)
* **dropoff_latitude & dropoff_longitude:** Coordinates of dropoff location (some supressed for anonymity)
* **pickup_location & dropoff_location:** Written location of pickups and dropoffs (some supressed for anonymity)

## Project Overview

**Problem Statement:** We want to understand the travel patterns being made in a large city, so that we can attempt to identify any opportunities for growing public transit.
* Which sections of the city are using taxis the most?
* Are there any identifiable patterns in fares, tipping, and trip totals that could tell us something about why taxis are chosen for transit?
* To help protect tourists and citizens alike, are any taxi companies displaying concerning patterns with how many trips they're used for?
