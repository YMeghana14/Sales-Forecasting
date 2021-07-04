# Sales-Forecasting
Building a regression model for prediction on Weekend/Sales Offers Dataset

# Overview

1) In this project , we are building a model to predict the purchase amount of customer against various products which will help store managers to create personalized offer for customers against different products.
2) We will follow all the steps of Machine Learning Life Cycle from Data collection to Model Evaluation

# Problem Statement

A retail company wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and  Purchase from last month.

Now, they want to build a model to predict the overall purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

# Dataset Description

1) User_ID	- ID's of customers who visit store
2) Product_ID	- ID's of products available in store
3) Gender	- Sex of Customer
4) Age -  Age in bins
5) Occupation	- Occupation (Masked)
6) City_Category - Category of the City (A,B,C)
7) Stay_In_Current_City_Years -	Number of years stay in current city
8) Marital_Status - 	Marital Status
9) Product_Category_1 - 	Product Category (Masked)
10) Product_Category_2	- Product may belongs to other category also (Masked)
11) Product_Category_3	- Product may belongs to other category also (Masked)
12) Purchase	- Purchase Amount (Target Variable)

# 🛠️ Requirements

# Programming Language
  1. Python 3.6-3.8

# Frameworks and Libraries
1) Pandas
2) Sklearn
3) Matplotlib
4) Numpy
5) Seaborn

<h2>⚙️ Setup</h2>
  
  Installing Pandas
  
    $pip install pandas
  
  Installing Sklearn
  
    $pip install -U scikit-learn
  
  Installing Matplotlib
    
    $pip install matplotlib
  
  Installing Numpy
     
    $pip install numpy
 
  Installing Seaborn
  
    $pip install seaborn
 

  <h2>📈 Technique used to solve the problem</h2>
  
  >   Machine Learning
  
  *   Linear Regression
  *   Decision Trees
  *   XG Boost


# Conclusion

1) In this project, we tried to build a model using various algorithms such as Linear regression, Decision tree regression and XGB regressor to get the best possible prediction.
2) The hyperparameter tuned XGB regressor gives us the best rmse value and r2 score for this problem.
3) Deployed app using Flask
