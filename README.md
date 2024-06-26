# Project Name
Surprise Housing 

# Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.


Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

- What is the background of your project?
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- What is the business problem that your project is trying to solve?
The company wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.


Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?
train.csv collected by the company.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- <b>Data understanding</b>
- Dataset is about the housing data, describes various features of the house and target variable is SalePrice
- the shape of the data is (1460, 81), with 1460 rows and 81 features including target variable.
- we have 38 - numeric  and 43 categorical features

Ridge – alpha = 1, with 41 features with a R^2(Test) 0.82499
Alpha: 1, R^2(Train): 0.8206308053471565, R^2(Test): 0.8249970901945431,f-c:41
Alpha: 2, R^2(Train): 0.8198421576782735, R^2(Test): 0.8251560361589055,f-c:41 (slightly better)

Lasso – alpha = 100 with 41 features with a R^2(Test) 0.8256
Alpha: 100, R^2(Train): 0.8192046912182973, R^2(Test): 0.825627053987788,f-c:41
Alpha: 200, R^2(Train): 0.8146813023705348, R^2(Test): 0.8226684383827453,f-c:41 (slightly reduced)

Ridge: 
Alpha: 2, R^2(Train): 0.8187824573686472, R^2(Test): 0.824026926828994,f-c:36
Lasso:
Alpha: 100, R^2(Train): 0.818399697268194, R^2(Test): 0.825052838278836,f-c:36
		


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodels


## Contact
Created by [@iilnreddy] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->