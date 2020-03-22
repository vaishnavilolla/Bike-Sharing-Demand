# Bike-Sharing-Demand-Python

# Data Description:
Bike Sharing Dataset contains the hourly count of rental bikes related to the bike-sharing program of Washington DC for the years 2011 and 2012. The dataset contains 17 variables with 17379 rows. The count of bicycles rented is highly correlated to seasonal and environmental factors. Day of the week, season, an hour of the day, weather conditions can significantly affect the rental behaviors. Target Variable: Count - Count of total rental bikes. The data is collected from UCI Machine Learning Repository. 
URL: https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset

# Problem Statement:
Generally, in bike-sharing systems, administrators need to know the number of cycles that will be needed at each bicycle station. Knowing this count enables them to arrange a proper number of cycles at the stations and decide whether a particular station requires extra bicycle stands, based on the demand, location and time of the day. In this project, we studied various prediction algorithms to understand which algorithm can work better for the realworld problem of bike-sharing demand prediction. We built a predictive model for bike rental volume using artificial neural networks and compared its performance with methods like linear regression, decision trees, bootstrap forest and boosted trees. We have also analyzed the impact of each of the predictor variables on the number of bikes that are rented out on an hourly basis.

# Conclusions:
1. The variable ‘hour’ is the most influential factor in predicting the total count of the rental bikes.
2. The second most key indicator in predicting the count of the rental bikes is FeelsTemperature.
3. The Random Forest tree model gives the best results in predicting the count which is observed through relatively smaller   RMSE values and larger accuracy score values.

# Recommendations:
1. While analyzing the data, we observed that more bikes are rented out between 8-9 AM and 5-6 PM. Hence it would be profitable for the company to stock up on bikes at the kiosks during these times.
2. The company can devise different pricing strategies for peak hours vs non-peak hours to entice more customers to rent out the bikes.
3. A bulk maintenance of bikes can be done during the months of January and February as least number of bikes are rented out during these months. General maintenance can be conducted during 10-11 AM and 2-3 PM.
4. Since the contribution to the count of rental bikes is more from registered users than casual users, the company can offer customized discounts for the loyal customers. This will drive more conversion of casual users to registered.
5. Access to external data such as the pick-up and docking locations, customer data, and GPS information will help us develop a sensor network and analyze traffic patterns.
