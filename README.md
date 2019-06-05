# Springboard-Ride-Sharing-Project-Final
Springboard Second Capstone Project - Ride Sharing Service Fee Estimation 

Introduction 
On March 28th, 2019,  San Francisco based ride hailing company Lyft became a public company via IPO.  It is expected that Lyft’s major competitor Uber will follow the suit to be IPO soon. Peer-to-peer ridesharing become an important part of people’s life everywhere. Ridesharing company implements a dynamic pricing model when calculating the trip cost. As an active ridesharing service customer, I have been interested in the pricing model those companies implemented for a while. The goal of this project is to develop a ridesharing service pricing model that allows customer like me to estimate the trip cost. 

Dataset
During my research for related data, I was lucky enough to discover that City of Chicago is the first city to release the ride hailing related data to public. Therefore, I was able to obtain Trip information from Chicago Data Portal. The actual dataset contains 17.4 million rows as the portal started to collect data from November, 2018. For this project, a random sample of 1 million rows were selected and loaded into Jupyter notebook. Dataset contains the following 21 features:

Trip ID
Trip Start Timestamp
Trip End Timestamp
Trip Seconds 
Trip Miles
Pickup Census Tract
Dropoff Census Tract
Pickup Community Area
Dropoff Community Area
Fare
Tip
Additional Charges
Trip Total
Shared Trip Authorized
Trips Pooled
Pickup Centroid Latitude 
Pickup Centroid Longitude
Pickup Centroid Location
Dropoff Centroid Latitude
Dropoff Centroid Longitude
Dropoff Centroid Location


Conclusion

The Ride Sharing data from the City of Chicago has been processed and fitted into several regression models to estimate the trip fare. As there is no significant difference among the model accuracy,  a simple linear regression with an accuracy score of 0.852 can be used. Spatial variables has been converted into categorical variables to incorporate them into the model. Since time variables were not directly included in model building, it will be interesting to include them in future analysis to access the impact of time on fare. 

