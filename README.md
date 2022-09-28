# Project Name
Surprise House Price Prediction Using MLR & Regularization Techniques

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#Acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Scope of the Project:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties.

Business Problem that Project is trying to solve:
    Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.

Business Goal:
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Both Lasso and Ridge Regression has given the similar results.
    Ridge_train_score 0.9193372231416144
    Ridge_test_score 0.8458062672444531
    Adjusted_R2_score_Ridge_Train 0.9003922125961824
    Adjusted_R2_score_Ridge_Test 0.8095912743212375

    Lasso_train_score 0.9193275306019792
    Lasso_test_score 0.8481576887420416
    Adjusted_R2_score_Lasso_Train 0.9003802436005071
    Adjusted_R2_score_Lasso_Test 0.8124949667274606

- Alpha used in Ridge:20 and Alpha used in Lasso Regression 0.001

- #Top 15 variables based on Model 2 [Ridge Regression]
GrLivArea
OverallQual_8
OverallQual_7
OverallQual_9
BsmtFinSF1
OverallQual_10
TotalBsmtSF
YearBuilt
OverallCond_7
GarageCars
OverallQual_6
PoolQC_Gd
LotArea
SaleType_New
Condition2_PosN

- #Top 15 variables based on Model 2 [Lasso Regression]

GrLivArea
YearBuilt
OverallQual_8
OverallQual_7
OverallQual_9
BsmtFinSF1
OverallQual_10
TotalBsmtSF
OverallCond_7
OverallQual_6
GarageCars
PoolQC_Gd
LotArea
SaleType_New
Condition2_PosN

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Jupyter Notebook


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
----


## Contact
Created by [@chanderraju] - feel free to contact me!

#Github Link Address
https://github.com/CHANDERRAJU/ar_assignment


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
