### Alphabet Soup Deep Learning Model

#Overview
- The purpose of this analysis is to create a binary classification model using deep learning techniques to predict an organizations success if funded by Alphabet Soup. The model utilizes data from over 34,000 organizations that have received funding from Alphabet Soup.

#Results
  Data Preprocessing
  - Target Variable: The target variable for the model is IS_SUCCESSFUL.
  - Feature Variables: The feature variables for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
  - Removed Variables: EIN and NAME were removed from the input data as they are identification columns and were not useful as features or targets.
  - NAME variable was added back into the model as a Feature Variable for one of the optimizations.

    
