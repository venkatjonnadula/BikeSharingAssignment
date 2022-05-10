# Project Name - BikeSharingAssignment
> BookBikes - A bike-sharing system 
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions

There are below categorical variables present in our dataset. 
season, yr, mnth, holiday, weekday, workingday, weathersit.
Season: During summer & fall the number of users for boom bikes is high
Yr : The users are increased from year 2018 to 2019 
Mnth: During mid of year the users are more ( april to october)
Holiday: Nothing major to determine from visualisation except the median on non-holiday is high.
Weekday: all most all the days have similar pattern 
Workingday: all most all the days have similar pattern
Weathersit: On Partially_cloudy situations the number of users are more.

We can see that the equation of our best fitted line is:

𝑐𝑛𝑡=0.4822+0.236×𝑦𝑟−0.2032×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑−0.23×𝑠𝑝𝑟𝑖𝑛𝑔−0.05×𝑤𝑖𝑛𝑡𝑒𝑟+0.09×𝑃𝑎𝑟𝑡𝑙𝑦𝑐𝑙𝑜𝑢𝑑𝑦−0.20×𝑙𝑜𝑤𝑟𝑎𝑖𝑛−0.046×𝑆𝑢𝑛𝑑𝑎𝑦−0.10×𝐽𝑎𝑛+0.086×𝑆𝑒𝑝

Overall we have a decent model, but we also acknowledge that we could do better.


## Technologies Used
- Python3
Below libraries used for modeling:
- sklearn
- statsmodel
- rfe

## Acknowledgements

## Contact
venkat.jonnadula11@gmail.com
