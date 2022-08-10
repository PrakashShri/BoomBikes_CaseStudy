# BoomBikes Case Study

#### Problem Statement and Business Objective:

A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

Essentially, the company wants —

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- To know the accuracy of the model.



## Table of Contents
General Info
Technologies Used
Conclusions
Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all-around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
• Which variables are significant in predicting the demand for shared bikes.
• How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

The objective is to build model for demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### Linear relationship betwwen predictor variables and target variable.:-
-One of the most important assumptions is that a linear relationship is said to exist between the 
dependent and the independent variables. If you try to fit a linear relationship in a non-linear 
data set, the proposed algorithm won’t capture the trend as a linear graph, resulting in an 
inefficient model. Thus, it would result in inaccurate predictions.From our analysis we observe that there is a linear relationship exixst between predictor variables and target variables. Also there is strong linear relationship between the dependent .

#### Error terms are independent of each other:-
In our developed model we observed the residuals (error terms) are independent of each other. In other words, there is no 
correlation between the consecutive error terms of the time series data. The presence of 
correlation in the error terms drastically reduces the accuracy of the model. If the error terms 
are correlated, the estimated standard error tries to deflate the true standard error.

#### Normal distribution of error terms:-
our model error terms following  a normal distribution. 

#### Homoscedasticity check
The data points are spread across equally without a prominent pattern, it means the residuals have constant variance (homoscedasticity)

#### Final expression and equation:-
0.4774temp + 1.0274year_2019 + 0.3267 month_Sep + 0.1821season_summer + 0.4703season_winter - 0.4393holiday - 0.0967humidity - 0.1411windspeed - 0.2724season_spring - 0.1782month_Dec - 0.2031month_Jan - 0.2333month_Jul - 0.1883month_Nov - 0.2071weekday_Sun - 1.1438weather_Light_Snow - 0.2656weather_Mist_Cloudy - 0.4109


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
We have used python coding to analyze the data and developed the model.Below are the few important libraries name from python which is used in the analysis
- library 1 -pandas 
- library 2- matplotlib
- library 3- warnings
- library 4 -numpy
- library 5 -seaborn
- library 6 -seaborn
- library 7- sklearn
- library 8-statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
This project is completed after successfully completing the learning session provided by IIITB & UpGrad for the EDA analysis,Pyhton and their libraries like Pandas, numpy ,matplotlib etc.

## Contact
Created by [@PrakashShri] - feel free to contact me!


<!-- You don't have to include all sections - just the one's relevant to your project -->
