# Bike Sharing
>  Building a multiple linear regression model to find the most significant variables which would help in prediction of demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
- The company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation
- The company wants to know significant variables in predicting the demand and how well they describe the demands.
- A dataset containing demand details of the year 2018 and 2019 is provided


## Conclusions
- Assumptions derived from the model
    - Snowy or misty weather decreases the demand
    - Clear weather is the best weather for high demands
    - No data recorded for rainy weather.
    - During summer and fall the demand is significantly higher than spring and winter
    - From the month of May to October the demand keeps on increasing
    - Demand is constantly high during working days
    - After pandemic, demand is twice next year. So futher increase in coming years can be expected
    - Summer and fall seasons are the best time and has high demand. So increasing the number of bikes for rent and increasing price would be profitable
    - During spring the demand goes down rapidly. So discounts in those time might increase the business
    - Weekdays have high demand and holidays have negative impact on demand.
    - When the weather is not clear, it has a negative impact on the demand. So planning based on weather forecast is advisable
    - Lower windspeed leads to greater demand
- Model Evaluation outcome
    - The train set R square is 0.83. The test set Rsquare value is 0.80
    - Very less difference of Rsquare value between test and train set assures that the model is a good and consistent one. 
    - The probability of F-statistics is way less than 0. This assures that the model is valid and proves that the outcome is not by chance or luck
    - The p-value anf VIF of all the features are within acceptable range
    - The error is normally distributed
    - The predicted value and target value is closer to the best fit line in a linear regression pattern



## Technologies Used
- numpy - 1.24.3
- python - 3.11.4
- seaborn - 0.13.0
- pandas - 1.5.3
- plotly - 5.17.0
- matplotlib - 3.7.1


## Acknowledgements
- This project was based on "BoomBikes Bike sharing demand by upgrad"


## Contact
Created by [@PriyadharshiniVijayan] - feel free to contact me!

