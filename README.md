# Surprise Housing Assignment
> A regression model using regularization in order to predict the actual value of the prospective
properties and decide whether to invest in them or not



## Background

A US-based housing company named Surprise Housing has  decided to enter the Australian market. The company uses data analytics to  purchase houses at a price below their actual values and flip them on at a  higher price. For the same purpose, the company has collected a data set  from the sale of houses in Australia.


## Business Goal

You are required to model the price of houses with the available independent variables. This  model will then be used by the management to understand how exactly the prices vary with the variables.  They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.  Further, the model will be a good way for management to understand the pricing dynamics of a new market.



Steps are:

* Load the data and understand the variables
* Data Inspection
* EDA
* Train-Test Split
* Missing Value Imputation if required
* Scaling if required
* Modelling
* Tuning with Regularization (Ridge & Lasso)
* Model Evaluation

<!-- You can include any other section that is pertinent to your problem -->

## Regression Models
- Simple Linear Regression
- Ridge Regression
- Lasso Regression

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the Simple Regression Model - There is a huge diff between r2 score of train n test set, this indicates model is not a good one, since the Test R2 is too low, we will check for some alternate methods of Regression
- Conclusion 2 from Ridge Regression Model - The diff between r2 of train and test set has improved and ridge model has helped. Very good train and test scores, model performance good.
- Conclusion 3 from Lasso Regression Model - Very good train and test scores, model performance good.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Inference 

The r2_score of ridge is slightly higher than lasso for the test dataset in our case.


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@devikadev] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
