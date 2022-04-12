# Boombikes-LinearRegression-Assignment 
> Linear Regression performed on the Boombikes bike rental dataset as part of an assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore. 


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework in the Machine Learning module. 
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc. 
- The Boombikes bike rental dataset is being used. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The R-squared value of the train set is 82.71% whereas the test set has a value of 81.13% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

- Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set. 

- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@pattanaikay] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
