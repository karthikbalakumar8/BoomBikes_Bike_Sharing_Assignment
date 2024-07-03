# Boom Bikes - Bike Sharing Assignment - Linear Regression Model

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate it's revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Technologies Used
numpy - version 1.20.3
pandas - version 1.3.4
matplotlib - version 3.4.3
plotly - version 5.6.0
seaborn - version 0.11.2
statsmodels - version 0.12.2
sklearn - version 0.24.2
scipy - version 1.7.1


## Conclusion

Comparision between Training and Testing dataset:

- Train dataset R^2          : 0.8130
- Test dataset R^2           : 0.7751
- Train dataset Adjusted R^2 : 0.8090    
- Test dataset Adjusted R^2  : 0.7621

We can see that the equation of our best fitted line is:

Demand of bikes depend on - 
- year
- holiday
- workingday
- temp
- atemp
- windspeed
- sep
- sat
- sun
- Light_snowrain
- Misty
- winter


## Contact
Created by [@karthikbalakumar8] - feel free to contact me!