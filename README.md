# Neural_Network_Charity_Analysis

## Project Overview:
The purpose of the project was to use neural network machine learning help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results:
  - ### Data Processing
  
    - Target for the model was `IS_SUCCESSFUL` field.
    
    - Features for the model were `APPLICATION_TYPE`, `AFFILIATION, ASK_AMT`, `CLASSIFICATION, INCOME_AMT`, `ORGANIZATION, SPECIAL_CONSIDERATIONS`, `STATUS`, `USE_CASE`.
    
    - Fearures that were removed inputs were `NAME` & `EIN`.

  - ### Compiling, Training, and Evaluation the Model
  
    - Layers and Output were `1st layer with 80 neurons and activation with relu`, `2nd layer with 30 neurons and activation with relu`, and `output activation as sigmoid`.
    
    - I was not able to acheive the target of 75% or greater, only acheive `64%`.
    
    - Throught my 3 attempts at optimzation for achieved target with different setups like dropping an input `SPECIAL_CONSIDERATIONS`, varies tries with binning data selection, and added layer with higher and lower neurons.

## Summary:
I would try using other machine learning process maybe a supervised learning model with Random Forest model might helpful with combining decision trees for a higher accuracy model.
