# Diabetes_prediction_test

This is a machine learning model made for a kaggle competition

https://www.kaggle.com/competitions/playground-series-s5e12

The notebook performs a data science workflow, loading the data, exploring and analysing it, preprocessing it and using it to train a randomforest model to accurately assess if a patient has diabetes 

The project utilizes two main datasets:
- train.csv: Contains 700,000 records with 26 features, including the target variable diagnosed_diabetes.
- test.csv: Contains 300,000 records used for generating final predictions.

The key features are:
- Demographic: Age, Gender, Ethnicity, Income, Education level
- Health metrics
- Medical history and family history of diabetes

The notebook uses pandas, numpy and scikit-learn

Workflow:

- We load the data and inspect it
- Check for any missing values
- Explore the dataset and the type of variables
- Divide demographic values and a few medical history variables into ordinal and nominal values
- We process nominal values so that each possible value has its column, and is now binary
- We train the model using a randomforest algorithm and generate the output
