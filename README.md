# Upgrad - Bike Sharing  Multiple Linear Regression Assignment 
 **submisson for MLR assignment from upgrad IITB, by Ajith Shenoy**

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

## Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Packages Used
- scikit-learn==1.2.2
- seaborn==0.12.2
- statsmodels==0.14.0
- pandas==1.5.3

## Model Interpretation


- Year (yr): has the highest positive coefficient (1999.64), indicating its significant importance. Each additional year leads to a substantial increase in bike rentals.

- Temperature (temp): also has a strong positive influence on rentals, with a coefficient of 3414.61. Warmer temperatures result in more bike rentals.

- Weather Conditions: Both 'weathersit_light snow & rain' and 'weathersit_mist & cloudy' have negative coefficients, emphasizing their importance. Adverse weather conditions significantly reduce bike rentals.
- Seasons: 'season_spring' has a notable negative coefficient (-1360.52), indicating that spring has lower rentals compared to the reference season. In contrast, 'season_winter' has a positive coefficient (707.81), signaling higher rentals in winter.

- Months: Several months have significant coefficients, both positive and negative. For example, 'mnth_mar' and 'mnth_nov' have positive coefficients, suggesting higher rentals during these months. In contrast, 'mnth_dec' and 'mnth_jul' have negative coefficients, indicating lower rentals.

- Wind Speed (windspeed): Wind speed has a negative coefficient (-775.36), showing that higher wind speeds deter bike rentals.

## Busniess Recommendations:

- Focus on Seasonal Strategies: The company should tailor its marketing and bike availability strategies based on the season. Expand marketing efforts during spring to attract more customers. Winter seems to be a strong season for rentals, so capitalizing on this demand is crucial.

- Weather-Based Strategies: Consider offering special promotions or maintenance services during periods of light snow, rain, or misty and cloudy weather to mitigate the impact of weather conditions on rentals.

- Yearly Growth: The company should expect an annual growth in bike rentals, as indicated by the 'yr' coefficient. Plan for expansion and capacity increases accordingly.

- Temperature Matters: Higher temperatures drive more bike rentals. Plan for increased bike availability and promotions during warmer months.

- Month-Specific Promotions: Design marketing campaigns that target months with positive coefficients ('mnth_mar' and 'mnth_nov'), and be prepared for lower demand during months with negative coefficients ('mnth_dec' and 'mnth_jul').
