# House Price Prediction Case Study
A case study to solve a business problem by building a regression model using regularization for the prediction of house prices.
* Comprehend the given data set and perform Exploratory Data Analysis (EDA) to analyse the data set.
* Build a regression model to identify the best fit variables that can predict the house prices.

## Table of Contents
* [General Info](#general-information)
* [Project Contents](#project-contents)
* [Conclusion](#conclusion)
* [Software and Library Versions](#software-and-library-versions)
* [Acknowledgements](#acknowledgements)

### General Information
A US-based housing company named **Surprise Housing** has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. They have contracted a consulting company to understand the factors on which the house prices depends and decide whether to invest in them or not.
The company wants to know:
* Which variables are significant in predicting the price of a house
* How well those variables describe the price of a house

#### Data Set Brief Information
The data set contains information about the sale prices and properties of the house.
A data dictionary is provided along with the data set to understand various terms and variables used.

#### Business Objective
Analyse and Perform Exploratory Data Analysis (EDA) on the given data set. Build a regression model using regularization for the prediction of house prices.
Determine the optimal value of lambda for ridge and lasso regression.

#### Business Solution
Present the model, which can predict the house prices. Surprise Housing management will use this model to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


### Project Contents
* **House Price Prediction Case Study.ipynb** - Jupyter Notebook for BHouse Price Prediction Case Study (Language : Python)
* **Advanced Regression Assignment Subjective Questions.pdf** - Questions and Answers to subjective questions related to Assignment
* **train.csv** - Data Set
* **data_description** - Data Dictionary
* **README.md** - Readme file


### Conclusion
Any business analytics problem can be solved using **CR**oss **I**ndustry **S**tandard **P**rocess for **D**ata **M**ining (CRISP-DM) model.
* Data set was analysed and prepared for EDA. EDA was done on data set to understand the relationship between variables.
* Advanced Regression model was built for target variable 'SalePrice' using both regularization methods - Ridge and Lasso

#### Recommendation

##### R2 Score and Optimal Alpha of Ridge Regression
* Train R^2 : **0.947**
* Test R^2 : **0.891**
* Alpha : **0.8**

##### Top 5 predictor variables of Ridge Regression
* GrLivArea (log scale)
* 1stFlrSF (log scale)
* OverallQual
* LotArea (log scale)
* RoofMatl_WdShngl 

##### R2 Score and Optimal Alpha of Lasso
* Train R^2 : **0.937**
* Test R^2 : **0.893**
* Alpha : **0.001**

##### Top 5 predictor variables of Lasso
* GrLivArea (log scale)
* OverallQual
* LotArea (log scale)
* OverallCond
* 1stFlrSF (log scale)


### Software and Library Versions
* ![Jupyter Notebook](https://img.shields.io/static/v1?label=Jupyter%20Notebook&message=4.9.2&color=blue&labelColor=grey)

* ![NumPy](https://img.shields.io/static/v1?label=numpy&message=1.21.5&color=blue&labelColor=grey)

* ![Pandas](https://img.shields.io/static/v1?label=pandas&message=1.4.2&color=blue&labelColor=grey)

* ![matplotlib](https://img.shields.io/static/v1?label=matplotlib&message=3.5.1&color=blue&labelColor=grey)

* ![seaborn](https://img.shields.io/static/v1?label=seaborn&message=0.11.2&color=blue&labelColor=grey)

* ![statsmodels](https://img.shields.io/static/v1?label=statsmodels&message=0.13.2&color=blue&labelColor=grey)

* ![sklearn](https://img.shields.io/static/v1?label=sklearn&message=1.0.2&color=blue&labelColor=grey)


### Acknowledgements
This case study is an assignment, done as part of [Upgrad](https://www.upgrad.com/ ) - **Master of Science in Machine Learning & Artificial Intelligence** programme.


### Contact
Created by [Sanjeev Surendran](https://github.com/Sanjeev-Surendran)


<!-- ## License -->
<!-- This project is not a open source and sharing the project files is prohibited. -->
