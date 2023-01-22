# Neural_Network_Charity_Analysis

## Overview:

  From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within   this dataset are a number of columns that capture metadata about each organization, such as the following:
  
  - EIN and NAME—Identification columns
  - APPLICATION_TYPE—Alphabet Soup application type
  - AFFILIATION—Affiliated sector of industry
  - CLASSIFICATION—Government organization classification
  - USE_CASE—Use case for funding
  - ORGANIZATION—Organization type
  - STATUS—Active status
  - INCOME_AMT—Income classification
  - SPECIAL_CONSIDERATIONS—Special consideration for application
  - ASK_AMT—Funding amount requested
  - IS_SUCCESSFUL—Was the money used effectively
  
  The purpose of this project is to create binary clasifer that is capable of predicting whether applicant will be successful if funded by charity.
  
  ## Results:
  
    - Data Processing
     
    1. What variable(s) are considered the target(s) for your model?
    
      The target for the model is "IS_SUCCESSFUL" column.
      
    2. What variable(s) are considered to be the features for your model?
    
      The features of this model are the NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and         ASK_AMT
      
    3. What variable(s) are neither targets nor features, and should be removed from the input data?
    
    
    - Compiling, Training, and Evaluating the Mode
    
    1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
      In this model there are three hidden layers each with many neurons, because this seeemed to increased the accuracy above 75%. The number of epochs wasn't               changed. The first activation function was 'relu' but the 2nd and 3rd were 'sigmoid'and the output function was 'sigmoid'. Changing the 2nd and 3rd activation         functions to 'sigmoid' also helped boost the accuracy.
      
    2. Were you able to achieve the target model performance?
    
      Yes
      
    3. What steps did you take to try and increase model performance?
    
       Name column needs to be converted into data points, which has the highest impact on model performance.And, it also required adding a third layer and using the          "sigmoid" activation function for the 2nd and 3rd layer.
       
    ## Summary
    
       By increasing the accuracy above 75% we are able to correctly classify each of the points in the test data 75% of the time.       
       
       
