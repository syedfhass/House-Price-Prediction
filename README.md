# House Price Prediction
House Price Prediction of IceLand Houses using dataset available on the govt website. This is my first academic project in AIML program

In this project, I have tried to find the the best variables and better performing model for house price predictions with two different approaches of  Regression analysis:

    The first one is by keeping most of the data as is (i.e. without enough cleaning) and using basic models

    The second one  is by removing irrelevant data by applying advanced data cleaning & model tuning techniques


Second approach, using HyperParamter Tuning on Random Forest Regression with better cleaned data provided the best results among all the different approaches applied

Linear model with first approach (Partially cleaned dataset):
  Mean Absolute Percentage Error (MAPE): 0.28415481279757837
  R^2: 0.5802626282718357
  RMSE:  8966.3011848338
  
Random Forest Regression with first approach (Partially cleaned dataset):
  RMSE: 5835.158591997413
  
QQ Plot in 1st approach:

![image](https://user-images.githubusercontent.com/113072173/226500551-41a5df10-28a6-453a-bf36-8150a2c84764.png)


  
Hyperparameter Tuned Random Forest (GridSearch) Model Metrics:
  Mean Absolute Percentage Error (MAPE): 0.12947954336429485
  R^2: 0.8547795977071275
  Average Error: 2634.2708 degrees.
  Accuracy = 87.05%.
  
Residuals QQ Plot in 2nd Approach:

![image](https://user-images.githubusercontent.com/113072173/226500478-a6f56cbf-6dcc-4ee0-a143-d37a00f6cdb1.png)




