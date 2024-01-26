# Project Title: Purchase Prediction with Decision Tree Classifier for Social Network ads.

## Project Overview:

This project aims to construct a decision tree classifier model to predict whether an individual is likely to purchase a certain product based on their age and estimated salary. This model can be used to target marketing efforts effectively towards the most receptive audience.

## Key Steps:

Data Loading:

Import the dataset 'Social_Network_Ads.csv' using pandas.
Separate features (age and estimated salary) from the target variable (purchased).
Data Splitting:

Divide the dataset into training and testing sets (80% for training, 20% for testing).
Model Training:

Create a decision tree classifier model using scikit-learn's DecisionTreeClassifier.
Train the model on the training set.
Model Evaluation:

Generate predictions on the testing set.
Calculate the model's accuracy score using accuracy_score.
Visualize the decision tree structure using tree.export_graphviz.
Model Saving:

Save the trained model for future use using joblib.dump.
User Interaction:

Create a command-line predictor function that:
Loads the saved model.
Prompts the user to enter age and salary.
Predicts the purchase likelihood using model.predict.
Displays the prediction result to the user.


# Instructions for Use:

Ensure all required files are present in the working directory.
Run the 'Purchase Predictor.ipynp' script to train and save the model.
Execute the user code to make predictions:
Enter age and salary when prompted.
The predicted purchase likelihood will be displayed.
