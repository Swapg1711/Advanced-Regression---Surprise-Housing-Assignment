# Advanced Regression Assignment - Surprise Housing
> To build a Advanced Regression model for the prediction of demand for houses results in high return.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

- What is the background of your project?
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

- What is the business probem that your project is trying to solve?
- The company is looking at prospective properties to buy to enter the market. we are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- The company wants to know:


- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

- What is the dataset that is being used?
- Data has been provided by Surprise Housing.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Top 10 variables are -

•	OverallQual_9
•	Neighborhood_Crawfor
•	OverallQual_8
•	GrLivArea
•	Functional_Typ
•	SaleType_New
•	SaleCondition_Normal
•	TotalBsmtSF
•	MSSubClass_70
•	BsmtExposure_Gd

- Optimal value of lambda for Ridge Regression = 9
- Optimal value of lambda for Lasso = 0.001

Ridge at alpha = 9
•	R2 Score (Train) = 0.95
•	R2 Score (Test) = 0.92

Lasso at alpha = 0.001
•	R2 Score (Train) = 0.93
•	R2 Score (Test) = 0.92


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- from sklearn import linear_model, metrics
- from sklearn.linear_model import LinearRegression
- from sklearn.linear_model import Ridge
- from sklearn.linear_model import Lasso
- from sklearn.model_selection import GridSearchCV
- from sklearn.metrics import mean_squared_error, r2_score

- import os

# hide warnings
- import warnings
- warnings.filterwarnings('ignore')

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Swapg1711] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
