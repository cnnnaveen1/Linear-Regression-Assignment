# Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


# Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents
* [Overview Business Understanding](#overview-business-understanding)
* [Problem Statement Business Objectives](#problem-statement-business-objectives)
* [Data in depth](#data-in-depth)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Overview Business Understanding
* Need to understand the demnad for shared bikes based on the available independent variables.

## Problem Statement Business Objectives
Identify the list of independent variable which can be used for predicting the demand.

### Want to
 * Understand the independen variables which can affect the demand
 * the model will be a good way for management to understand the demand dynamics of a new market.
## Data in depth
- We are going to analyze dataset provided by boombikes which has information regarding demand and the other independent variables
- Overall it has 730 rows and 16 variables

## Approach
  #### Data Preparation:
  - Data quality checks to be performed
  - Categorical variables & Dummy variables are added appropriately
  - New metrics are derived if applicable and are used for analysis and modelling.
  - The data is converted to a clean format suitable for analysis.
  #### Model Building
  - Model parameters are tuned using correct principles and the approach is explained clearly. Both the technical and business aspects are considered while building the model. 
  - Correct variable selection techniques are used. A reasonable number of different models are attempted and the best one is chosen based on key performance metrics.
  - Residual analysis is performed after model building and the assumptions are validated..
  #### Model Evaluation:
  - Model evaluation is done using the correct principles and appropriate evaluation metrics are chosen.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Overall R-squared for trained set is 0.823 and for test set is 0.79


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Numpy
- Panda
- Matplotlib
- Seaborn
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@cnnnaveen1] - feel free to contact me!
