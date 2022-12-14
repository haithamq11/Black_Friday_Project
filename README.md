# Black_Friday_Project


## Problem Statement 

A retail company "ABC Private Limited" wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. they have shared purchase summary of various customers for selected high volume products from last month.

the data set also contains customer demogrphics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

now, they want to build a modle to predict the purchase amount of customer against various products which will help them to create personalized offer for customer against different products. The dataset has 550,069 rows and 12 columns.

## Data Overview

Dataset has 537577 rows (transactions) and 12 columns (features) as described below:

* User_ID: Unique ID of the user. There are a total of 5891 users in the dataset.
* Product_ID: Unique ID of the product. There are a total of 3623 products in the dataset.
* Gender: indicates the gender of the person making the transaction.
* Age: indicates the age group of the person making the transaction.
* Occupation: shows the occupation of the user, already labeled with numbers 0 to 20.
* City_Category: User's living city category. Cities are categorized into 3 different categories 'A', 'B' and 'C'.
* Stay_In_Current_City_Years: Indicates how long the users has lived in this city.
* Marital_Status: is 0 if the user is not married and 1 otherwise.
* Product_Category_1 to _3: Category of the product. All 3 are already labaled with numbers.
* Purchase: Purchase amount.


## Predicting the Amount Spent

we will use one of the simplest machine learning models, i.e. the linear regression model, to predict the amount spent by the customer on Black Friday.

Linear regression represents a very simple method for supervised learning and it is an effective tool for predicting quantitative responses. You can find basic information about it right here: Linear Regression in Python

This model, like most of the supervised machine learning algorithms, makes a prediction based on the input features. The predicted output values are used for comparisons with desired outputs and an error is calculated. The error signal is propagated back through the model and model parameters are updating in a way to minimize the error. Finally, the model is considered to be fully trained if the error is small enough. This is a very basic explanation and we are going to analyze all these processes in details in future articles.
