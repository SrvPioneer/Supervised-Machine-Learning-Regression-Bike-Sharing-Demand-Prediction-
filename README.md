# Project Title : Bike_Sharing_Demand_Prediction_Capstone_Project

# Problem Description:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Steps Involved
* Exploratory Data Analysis
![image6](https://user-images.githubusercontent.com/93809665/229980200-812fdaaf-af45-4fc7-89a3-8dceaa0c1eb9.PNG)

* Extracting features from date
* Model Building
1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. ElasticNet Regression
5. DecisionTree Regressor
6. RandomForest Regressor
7. Gradient Boost
8. Xg Boost
* Model Evaluation through Metrics :
1. Mena Squared Error
2. Root Mean Squared Error
3. R-Squared
4. Adjusted R-Squared
 
# Model Summary

# For Train Dataset
![image7](https://user-images.githubusercontent.com/93809665/229980307-dd8b2a65-88e6-4476-8891-f9dae00b8ceb.PNG)

# For Test Dataset
![image8](https://user-images.githubusercontent.com/93809665/229980367-e2066c7b-b363-4974-a428-7c810f860387.PNG)



# Conclusions:

* As it was stated in the problem, rented bike count was low in 2017 untill november. After that rented bike count started increasing.

* There was sharp increase in demand from the end of 2017 that too in winter season of the year. The demand however decrease at the end of 2018.

* Bike count rent is highly correlated with 'Hour', which seems obvious. Demand for bike is mostly in morning (7 to 8) and in the evening (3 to 9).

* After doing exploratory data analysis, applying Linear Regression model didn't go quite well as it gave only 56% accuracy.

* Lasso and Ridge Regression helps to reduce model complexity and prevent over-fitting which may result from simple linear regression. with Lasso, ridge and ElasticNet regressor We got r squared value of 0.5624, 0.5624, 0.5267 respectively.

* With Decision Tree we are able to achieve the r2 score of 0.7639.

* Gradient Boost gave r squared value of 0.8249 on test data.

* XG Boost gave r squared value of 0.8242

* RandomForest Regressor gives higher value of R squared metric in train data 0.9834 and on test data it is 0.8651

* RandomForest Regressor came with best accuracy to approximate numbers of rented bikes demand. It gives amazing results of training r-square at 0.9834 and test r-square value at 0.8651 also with adjusted r-square with 0.8638.

# Next Step :
Implementing the model on production will give us a prediction of exact number of bikes to be placed so as to met demand, for peek hours there can be over prediction which will eventually not a problem but during the least demand hours the underprediction could be an issue , solving this would make the model ready for production.
