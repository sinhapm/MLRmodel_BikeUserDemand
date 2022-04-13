# MLRmodel_BikeUserDemand
> A python program to make a Multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?


## Conclusions
- The estimated multi-regression model is as follows:

$TotalUsers = 0.258 + 0.306  \times  clearWeather + 0.265  \times  year2019 + 0.223 \times mistyWeather - 0.055 \times summer - 0.086 \times holiday - 0.088 \times windspeed - 0.094 \times winter - 0.344 \times spring$

- Demand of the bike is positively correlated with clear weather(strongly), mistyweather & with year 2019.
- Demand of the bike is negatively affected by the season spring(strongly), winter, windspeed, holiday & summer season.
- It cannot be said that this can only be the final model. There is always a scope for the betterment of model with further analysis.


## Technologies Used
- Jupyter Notebook - version 6.4.5
- VS Code - version 1.65.0
- Python - version 3.9.7
- Pandas - version 1.3.4
- Numpy - version 1.20.3
- Matplotlib - version 3.4.3
- Seaborn - version 0.11.2
- Scikit-learn - version 0.24.2
- Scipy - version 1.7.1


## Acknowledgements
- This project was the case study from the Upgrad. We are thankful to the Upgrad & IIIT, Bangalore for providing the necessary knowledge & support.
- Other references is taken form the various internet source.


## Contact
Created by [@sinhapm] - feel free to contact me!
