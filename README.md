# House Price Prediction
This assignment is a programming assignment to model the price of houses with the available independent variables.

##Business Background
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. The company wants to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:

* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

##Consulting Expectation
The Consulation Analyst should build a model to predict the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

##Datasets used
House dataset: [train.csv]
Data Dictionary: [data_description[1].txt]
Solution file: python jupyter file: [House_Price_Rathnagiri.ipynb]
Subjective Question Answers PDF: [Subjective Questions_Housing_Assignment.pdf]

## Analysis
Following were the analysis done:
1. Exploratory Data Analysis
2. Prepare Data for Modelling
3. Model Building using RFECV
4. Ridge Regression
5. Lasso Regression
6. Model Analysis
7. Final Model

p.s. Models for answering subjective questions are at the end of the notebook

## Conclusion

Among the 3 models that were created, Linear, Ridge and Lasso: Lasso model has performed better with both training and test data.

The Analysis on the provided dataset the following could be inferred: Significant (Top5) variables to predict the hosue prices:
  1. OverallQual: Rates the overall material and finish of the house
  2. TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
  3. YearBuilt: Original construction date	
  4. GarageArea: Size of garage in square feet
  5. OverallCond: Rates the overall condition of the house
