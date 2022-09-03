# Seoul-Bike-Sharing-Demand-Prediction

## Problem Statement

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


## Data Description:

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.




## Attribute Information:

   • Date : year-month-day
   
   • Rented Bike count - Count of bikes rented at each hour
   
   • Hour - Hour of the day
   
   • Temperature-Temperature in Celsius
   
   • Humidity - %
   
   • Windspeed - m/s
   
   • Visibility - 10m
   
   • Dew point temperature - Celsius
   
   • Solar radiation - MJ/m2
   
   • Rainfall - mm
   
   • Snowfall - cm
   
   • Seasons - Winter, Spring, Summer, Autumn
   
   • Holiday - Holiday/No holiday
   
   • Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)





## Data Pipeline:

● Exploratory Data Analysis (EDA): In this part we have done some  EDA on the features to see the trend. 

● Data Processing: In this part we went through each attributes and  encoded the categorical features.

● Model Creation: Finally in this part we created the various models.  These various models are being analysed and we tried to study  various models so as to get the best performing model for our project.





## Observations:

● Observation 1: In the Model Evaluation Matrices table, Linear Regression, KNN is not giving great results. 

● Observation 2: Random forest & GBR have performed equally good in terms of adjusted r2. 

● Observation 3: We are getting the best results from lightGBM and CatBoost.





## Conclusions:

● We started with loading the data, then we did Exploratory Data Analysis (EDA), null values treatment, feature selection, encoding of categorical columns, and then model building.With the data filtered for multicollinearity and features trimmed down, we ran several regression models on the features with test-train split of 0.25, of which Random Forest performed the best with an R2 of 0.91 on the test dataset.
