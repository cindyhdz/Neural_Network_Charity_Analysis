# Neural_Network_Charity_Analysis

## Overview:
Creating a binary classifier that can predicts whether applicants will be successful if funded by Alphabet Soup.

## Results:
### Data Preprocessing
- The target variable is: Is Successful 
- Model Features are: organization, status, income amount, special considerations, ask amount, application type, affiliation, classification and use case
- Name and EIN are removed as they are not targets or features
### Compiling, Training, and Evaluating the Model:
#### Model Configuration:
- hidden_nodes_layer1 = len(X_train[0])
- hidden_nodes_layer2 = 80
- number_input_features = 30
- The model did achieve and accuracy of 0.7289795875549316
## Summary: 
Model resulted in an accuracy of 0.7289. Perhaps a different model could solve for a higher accuracy rate.
