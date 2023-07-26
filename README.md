# Surprise Housing Assignment

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in a CSV file.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
> 1. Which variables are significant in predicting the price of a house, and

> 2. How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information
> Business Goal:
Create a model for the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions

The top five features influencing the house prices are:
> GrLivArea
> OverallQual_Excellent
> OverallQual_Very Excellent
> Neighborhood_NoRidge
> RoofMatl_WdShngl

The performance of both ridge and lasso are quite similar in terms of R2_score. Lasso has some advantages over ridge like feature selection and ease of understanding due to less number of features.So, we will apply Lasso regression for this case.


## Technologies Used
> numpy version 1.21.5
> pandas version 1.4.4
> matplotlib version 3.5.2
> seaborn version 0.11.2
> sklearn version 1.0.2
