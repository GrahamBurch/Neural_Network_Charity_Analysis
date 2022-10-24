# Neural_Network_Charity_Analysis

## Overview
* A deep neural network is used to determine funding eligibility from Alphabet Soup.

## Data Cleaning
* The target variable in this analysis is the Boolean 'IS_SUCCESSFUL'.
* The features variables in this analysis are 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION','USE_CASE','ORGANIZATION','STATUS','INCOME_AMT','SPECIAL_CONSIDERATIONS' and 'ASK_AMT'.
* The columns 'EIN' and 'NAME' were dropped because they are unneeded. 

## Compile, Train and Evaluate
* The model uses two hidden neural layers, the first layer having 24 nodes and the second layer 12 nodes. Layer 1 uses the ReLU activation function and Layer 2 uses the sigmoid activation function. 

* A 75% accuracy score was the goal for the model. However, the best accuracy score the model achieved was 73% after three rounds of changes to the model's structure. The three attempted changes were first to increase the number of nodes in hidden layers 1 and 2; second, adding a 3rd hidden layer holding 10 nodes; and third, attempting to analyze the data using a Random Forest Classifier. 

## Conclusions

* While the 75% accuracy mark was not met, an accuracy of 73% was achieved apparently regardless of the attempted changes to improve performance. Further changes that could be tested might include changing the layers' activation functions, implenting a different type of algorithm, or enriching the supply of input data. 

