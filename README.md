# Bike Sharing
> Bike sharing company obsered a dip in the revenue due to pandemic. Therefore, a model needs to be developed to address the reopening of market and make most out of new possibilities.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The idea is to use Multiple linear regression (MLR) to design a model that fits optimally to predict the bike demand.
- The bike shareing company is operating since 2018 and saw a growth in the business in 2019. However, due to pandemic a dip in revenue was observed. 
- The company would like to make most of the opportunites that will be availabe in post-pandemic situations. Hence, the company would like to predict demand of Bikes to support the business.
- Everyday, Bike usage data available from 2018 and 2019.

## Conclusions
- Based on exploratory data analysis, below are the conditions under which the bike demand was most:
    1. weathersit = Good
    2. season = Fall
    3. workingday = yes
    4. mnth = May-Oct
- Actual temperature also plays a major role in the demand of bikes. 
- Final model for prediction
    1. atemp        
    2. windspeed
    3. season = Spring, Summer, Winter
    4. year_2019
    5. month = Aug, Dec, Jun, Nov, Sep
    6. holiday = yes
    7. workingday = no
    8. weathersit = bad, moderate
    9. weekday = Fri, Sun, Thu, Wed

## Technologies Used
- scikit learn
- stats model
- matplotblop
- seaborn
- pandas
- numpy

## Acknowledgements
- This project was based on [this blog](https://www.upgrad.com/blog/linear-regression-in-machine-learning/) and assignment from [upGrad course](https://learn.upgrad.com/).

## Contact
Created by [@pjsurve](https://github.com/pjsurve) - feel free to contact me!