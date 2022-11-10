# Sales_price_for_Properties_in_NYC

[![author](https://img.shields.io/badge/author-Karim-red.svg)](https://www.linkedin.com/in/karim-gamal-407438188/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LP0A1ZZEbfeKvhz5uc0s0Sljn7-wP9kN?usp=sharing)

<p align="center">
  <img src="https://img.freepik.com/premium-vector/new-york-city-illustration-united-states-modern-metropolis-isolated-clipart-white-background-us-world-famous-landmarks-tourist-attractions-cartoon-design-elements_575670-2204.jpg?w=2000" />
</p>

Goal : For this project, I'm going to build a machine learning model that could predict the property sales price for properties in NYC. I'm dividing my project into the following sections:

- EDA
- Data Preparation
- Modelling

## Task 1: Read dataset, merge data, and perform basic data exploration.

- Note, you should briefely discuss the quality of dataset (missing values, duplicate entries, etc.)

- Also, in task 3, you would be asked to perform prediction on house sale price, thus it would be good to consider outliers related to this prediciton task when you perform data cleaning.


#### Identification of variables and data types

For this part of the EDA I'm identifying the type of variables in the dataset. It is imporant for an EDA to know with what kind of variables you are dealing with. There are two types of variables:

- Categorical
- Numerical

For this step, I'm creating two lists for each dataset where I'm saving the different columns.

BOROUGH: A digit code for the borough the property is located in; in order these are Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), and Staten Island (5).

#### Missing values and data cleaning

- For this step of the project, I'm checking for missing values in the datasets.


## Task 2: Data exploration using data visualization.

- Raise two questions that can be answered by performing data visualization.

- Briefely mention why you think this question would be interesting to whom (who is your audience).

- Think about the EDA principals.


## Task 3: Data Exploration via Statistical Test

- Raise one question that can be answered by performing hypothesis test.

- Briefely mention why you think this question would be interesting to whom (who is your audience).

- Also mention which statistical test you would choose and why.

## Task 4: Feature Engineering.

- If we would like to predict the house sale price.

- Analyze the scale of each attribute and determine which ones you would transfer (e.g., cateogorical features).

- Discuss how you plan to select important features.

## Task 5: AutoML

- Using Auto-sklearn to explore performance of one state-of-the-art autoML tool on the given data (after your previous preprocessing).

- Optional: compare with performing autosklearn on raw data. ref.

- And also compare its outputs results with Random Forest , LR  , KNN , SVR, DecisionTree Regressor , XGB , AdaBoostRegressor models.

