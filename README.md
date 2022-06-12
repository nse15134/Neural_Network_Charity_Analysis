# Neural_Network_Charity_Analysis

# Overview of the analysis: 
In this challenge, we would like to use ML and Neural Networks to help Beks create a classifier that will assist in predicting if applicants will be successful if they are funded by alphabet soup. We will  be analyzing a csv file containing data from more thatn 34,000 organizations that have been funded by alphabet soup.  There is data on:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

## Results
 
### Data Preprocessing


What variable(s) are considered the target(s) for your model?
WE would look at the IS_SUCCESSFUL variable

What variable(s) are considered to be the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

What variable(s) are neither targets nor features, and should be removed from the input data?
EIN, NAME

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used 43 input features with 80 nodes in first layer and 30 nodes in the 2nd layer.  This brought me to an accuracy score of 72.85%
Sticking wiht the 80/30 model, i utilized the trainscale fit. 

Were you able to achieve the target model performance?
I was not able to achieve the target model, I hovered around 73% accuracy for all 3 attempts.

## Summary

1st attempt
![image](https://user-images.githubusercontent.com/98061420/173250256-7775bac6-9b09-438d-aae2-90bcf8b398b4.png)


2nd attempt
![image](https://user-images.githubusercontent.com/98061420/173250266-970a7db8-59ad-4a01-92c7-88464dbc8f3c.png)


3rd attempt
![image](https://user-images.githubusercontent.com/98061420/173250272-4e9f8ade-4d07-471c-be2f-d01f5a238111.png)

