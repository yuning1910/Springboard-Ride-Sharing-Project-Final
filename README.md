# Springboard-Ride-Sharing-Project-Final
Springboard Second Capstone Project - Ride Sharing Service Fee Estimation 
Introduction 
On March 28th, 2019,  San Francisco based ride hailing company Lyft became a public company via IPO.  It is expected that Lyft’s major competitor Uber will follow the suit to be IPO soon. Peer-to-peer ridesharing become an important part of people’s life everywhere. Ridesharing company implements a dynamic pricing model when calculating the trip cost. As an active ridesharing service customer, I have been interested in the pricing model those companies implemented for a while. The goal of this project is to develop a ridesharing service pricing model that allows customer like me to estimate the trip cost. 

Dataset
During my research for related data, I was lucky enough to discover that City of Chicago is the first city to release the ride hailing related data to public. Therefore, I was able to obtain Trip information from Chicago Data Portal. The actual dataset contains 17.4 million rows as the portal started to collect data from November, 2018. For this project, a random sample of 1 million rows were selected and loaded into Jupyter notebook. Dataset contains the following 21 features:

Trip ID: A unique identifier for the trip. 
Trip Start Timestamp: When the trip started, rounded to the nearest 15 minutes.
Trip End Timestamp:  When the trip ended, rounded to the nearest 15 minutes.
Trip Seconds: Time of the trip in seconds.
Trip Miles:  Distance of the trip in miles.
Pickup Census Tract: The Census Tract where the trip began.This column often will be blank for locations outside Chicago.
Dropoff Census Tract: The Census Tract where the trip ended. This column often will be blank for locations outside Chicago.
Pickup Community Area: The Community Area where the trip began. This column will be blank for locations outside Chicago.
Dropoff Community Area: The Community Area where the trip ended. This column will be blank for locations outside Chicago.
Fare: The fare for the trip, rounded to the nearest $2.50.
Tip:  The tip for the trip, rounded to the nearest $1.00. Cash tips will not be recorded.
Additional Charges: The taxes, fees, and any other charges for the trip.
Trip Total: Total cost of the trip. This is calculated as the total of the previous columns, including rounding.
Shared Trip Authorized: Whether the customer agreed to a shared trip with another customer, regardless of whether the customer was actually matched for a shared trip.
Trips Pooled: If customers were matched for a shared trip, how many trips, including this one, were pooled. All customer trips from the time the vehicle was empty until it was empty again contribute to this count, even if some customers were never present in the vehicle at the same time. Each trip making up the overall shared trip will have a separate record in this dataset, with the same value in this column.
Pickup Centroid Latitude: The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
Pickup Centroid Longitude: The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
Pickup Centroid Location: The location of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
Dropoff Centroid Latitude: The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
Dropoff Centroid Longitude: The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
Dropoff Centroid Location: The location of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.

