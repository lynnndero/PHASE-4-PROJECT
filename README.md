Student name: LYNN WANJIKU NDERO

Student pace: FULL TIME

Scheduled project review date/time: 1 WEEK



# FORECASTING REAL ESTATE PRICES USING TIME SERIES MODEL

View nontechnical presentation here: https://docs.google.com/presentation/d/1yRxTkkOyODKE8x7fndwAyvNRJo5sBSyrkjyQnmrDPog/edit?usp=sharing

## Table of Contents
1. [Introduction](#introduction)
2. [Business Understanding](#business-understanding)
3. [Problem Statement](#problem-statement)
4. [Main Objective](#main-objective)
5. [Research Questions](#research-questions)
6. [Loading data](#loading-data)
7. [Data Preprocessing](#data-preprocessing)\
     i)Calculating ROI and CV \
     ii)Checking for outliers\
     iii)Handling missing values
8.  [Exploratory Data Analysis And Visualization] 
9.  [Model Building](#model-building)
10. [Model Interpretation](#model-interpretation)
11. [Conclusion](#conclusion)
15. [Recommendations](#recommendations)

# 1. Business understanding

## a) Introduction
Laser investment firm is a reputable  real estate investment firm that is dedicated to assist their clients to achieve their financial goal through implementing strategic real estate investment. It boasts of its ability to deliver exceptional value to their clients by identifying and capitalizing on lucrative real estate opportunities.
Our main goal is to forecast the top best zipcodes to invest in by use of time series model.


## b) Problem statement
Laser investment firm wants to know the top 5 best zipcodes to invest in. For this to be effective and achievable, they need to have a deep understanding on how the trends on real estate investments have been over the past years as seen in 'time-series/zillow_data.csv' dataset. Moreover, our goal is to complete this real-world task in regard to time series modeling to help answer the questions considering there could be some form of ambiguity. We will look at valuable insights by looking at the Return On Investment and Co-efficient of variation over the past years to help plan and make informed decisions.


## c) Main objective
The main objective of this project is to design and implement a time series model  that can effectively help forecast real estate prices for investments.

## d) Specific objectives
1. Top 5 best zip codes to invest in
2. Recommendations based on profit margin


## e) Research question

1. What are the top 5 best zip codes to invest in?
2. What recommendations can you give based on profit margin?
3. Are there any risks involved in investmenting in the zipcode areas?

# 2. Data Understanding
For this project, we shall use 'time-series/zillow_data.cvs' dataset to analyze the real estate prices from 1996 to 2018 so as to help decide which areas to invest in.\
The columns in the dataset are:\
       1.RegionID  \
       2.RegionName \
       3.City  \
       4.State \
       5.Metro\
       6.CountyName\
       7.SizeRank \
       8..1996-04 to 2018-04 columns
  


# Success Metrics
For this project we were looking at the Return on Investment, CV as one of the evaluation metrics to determine the top 5 zipcodes to invest in.
We were also looking at the Root Mean Squared Error (RMSE) which was 7932701.297595864
We were also looking at the future prediction values and graphs.


# Conclusions
The final ARMA model after iterations achieved a lower AIC and BIC value than the baseline model(ARMA model 1) which was 3812.142 and 3833.598 respectivelyindicating a better model.

The Root Mean Squared Error (RMSE) of predicted 7932701.297595864 indicating that deviation from the true values.
This shows a higher prediction than the previous model.

From ROI and CV columns above, we can be able to get the top 5 zipcode to invest in due to their high Return on Investment and CV.
When making decisions, we need to balance between the risk represented as CV and return potential represented as ROI.
The higher the risk the higher the returns.

# Recommendations
The company should consider investing in York(NewYork) which has the highest ROI of 2.8671, Santa Barbara (2.8667), Person (2.8569), Marin (2.8565), San Diego (2.8561)

Other factors such as infrastructure development should also be considered as it may have a big effect on house prices in the areas.

Cities such as Austin should be thoroughly explored due to the high price shown.







