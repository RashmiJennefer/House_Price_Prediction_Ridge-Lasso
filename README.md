# US House Price Prediction
> US House Price Prediction using Ridge and Lasso Regression.


## Table of Contents
* Assignment Part -1 Problem Statement
* Steps
* Conclusion
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## Assignment Part -1 Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps
1. Importing dataframe
2. Data understanding and cleaning
3. EDA Analysis
4. Scalling and Train test split
5. Model building (Linear regression, Lasso and ridge regresssion)
6. Model evalution
7. Conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusion
The following variables are very important to predict the price of house

1. LotArea: Lot size in square feet
2. OverallQual: Rates the overall material and finish of the house
3. OverallCond: Rates the overall condition of the house
4. BsmtFinSF1: Type 1 finished square feet
5. TotalBsmtSF: Total square feet of basement area
6. YearBuilt: Original construction date
7. GrLivArea: Above grade (ground) living area square feet
8. Neighborhood: Physical locations within Ames city limits (Northridge)
9.TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
10. GarageCars: Size of garage in car capacity
11. Neighborhood: Physical locations within Ames city limits (Stone Brook)
12. ScreenPorch: Screen porch area in square feet
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## How well those variables describe the price of a house
1. The Value of R2 score in ridge regrassion in train data is 0.9358 and in test data is 0.9141.
2. The Value of R2 score in lasso regrassion in train data is 0.9305 and in test data is 0.9189.

So the variation between train data and test data is very less, hence model is good and all variables are well describing the price of house.

## Optimal value of lambda for ridge and lasso regression.
1. Optimal value of lambda for ridge regression is 4
2. Optimal value of lambda for lasso regression is 100

## Acknowledgements
I thank God almighty for giving me the strength and wisdom to do the project.
This project was inspired by family and friends.


## Contact
Created by [@RashmiJennefer] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
