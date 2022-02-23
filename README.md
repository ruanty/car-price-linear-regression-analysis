# Car Price - Linear Regression Analysis

## TL;DR
Estimating the price of a car is a complicated process. Before launching a car into the market, a good business strategy opted by most automobile companies is to perform market analysis. One aspect of such market analysis is to understand what factors affect the price of the car. There are fixed and dynamic variables in play. Together with Monashree Sanil and Wei He, in this report, we are trying to identify what fixed variables play a significant role in estimating the price of a car and how significant is the effect.

## Data Used
We have used a dataset from [Kaggle](https://www.kaggle.com/sanjogyadav/car-price-prediction-mlr/code). The dataset contains 15 features and the target variable we are interested in:
<img width="663" alt="image" src="https://user-images.githubusercontent.com/86521753/155241393-293fa957-470b-4b80-b4d8-537ba5b954c4.png">

## Stages
In the report, we covered the stages below to examine the problem:
- Exploratory Data Analysis
- Type of Regression - Multiple Linear Regression
- Before Model Fitting - Multicollinearity
- Initial Model 1 and Model Diagnostics
- Initial Model 2 and Model Diagnostics
- Model Selection
- Summary of findings
- Potential problems

## Final Findings
Based on our final model, the conclusion is that Year and Engine Cylinders have significant negative impact on MSRP while Engine HP and highway MPG have significant positive impact on MSRP. For the categorical variable Transmission Type, AUTOMATIC or MANUAL have a significant negative impact on MSRP compared with AUTOMATED MANUAL. For the categorical variable Driven Wheels, compared with all-wheel drive, cars only have front wheel drive or rear wheel drive will have lower MSRP. But there is no significant difference between the price of all-wheel drive and four wheel drive. For the categorical variable Vehicle Size, midsize cars and large size cars both have a significantly higher MSRP. At last, for the categorical variable vehicle style, apart from convertible suv, all the other vehicle styles of cars have significantly higher MSRP prices compared with cab pickup. 

## Links to the Report
- The Jupyter Notebook version of the report could be retrived [here](https://github.com/ruanty/car-price-linear-regression-analysis/blob/main/Linear%20Regression%20Final%20Project%20-%20Car%20Price%20Prediction.ipynb).
- The PDF version of the report could be retrived [here](https://github.com/ruanty/car-price-linear-regression-analysis/blob/main/Linear%20Regression%20Final%20Project%20-%20Car%20Price.pdf).
