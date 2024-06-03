# Alphabet Soup Deep Learning Model

## Overview
- The purpose of this analysis is to create a binary classification model using deep learning techniques to predict an organizations success if funded by Alphabet Soup. The model utilizes data from over 34,000 organizations that have received funding from Alphabet Soup.

## Results
  ### Data Preprocessing
  - Target Variable: The target variable for the model is IS_SUCCESSFUL.
  - Feature Variables: The feature variables for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
  - Removed Variables: EIN and NAME were removed from the input data as they are identification columns and were not useful as features or targets.
  - NAME variable was added back into the model as a Feature Variable for one of the optimizations.

  ### Compiling, Training, and Evaluating the Model

![Model Creation](https://github.com/robert-yaggi/deep-learning-challenge/assets/153320218/c4c064fe-d7a9-439e-af6d-d1b421e4f170)

![Model Creation Accuracy](https://github.com/robert-yaggi/deep-learning-challenge/assets/153320218/46b3fdbb-0487-4ae4-b91e-5c6c4d31d96c)

![Model 2](https://github.com/robert-yaggi/deep-learning-challenge/assets/153320218/79edc62d-8a81-41a0-a8a4-330eed932cac)

![Optimized Accuracy](https://github.com/robert-yaggi/deep-learning-challenge/assets/153320218/762c59a9-5365-45e7-b1a9-d2c894dd7c40)

## Summary
The deep learning model achieved the desired performance of % accuracy in predicting the success of Alphabet Soup funded organizations. Multiple attempts were made in order to optimize the model through data preprocessing and neural network structure changes, leading to improvements in overall model performance. As an alternative, a Random Forest Classifier could be used for this scenario. This method has the potential to provide better accuracy and generalization while reducing the likelihood of overfitting. This alternative method may lead to better performance in predicitng the success of organizations that are funded by Alphabet Soup. 
    
