# House Price Prediction using Advanced Regression Techniques
This project aims to explore the use of advanced regression techniques to predict house prices. Specifically, the Random Forest Regression method is employed using scikit-learn's built-in RandomForestRegressor. More information about this model can be found in the official documentation. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

## Motivation
The motivation behind this project is to investigate the performance of RandomForestRegressor in predicting house prices using a subset of features from the Ames Housing dataset.

## Data Processing and Feature Engineering
Some of the features in the dataset contain text values, so a function is implemented to transform these text values into numeric values. A subset of relevant features is chosen based on their potential impact on the house prices. The selected features are then preprocessed and engineered as described in the previous summary.

## Model Building and Evaluation
Using the preprocessed data, a RandomForestRegressor model is built and trained on the training dataset. The model is then used to predict the house prices on the test dataset. The performance of the model is evaluated by comparing its predictions to the true target values.

## Feature Importance Analysis
After building the model, the features with the highest importance values are determined. A new model is then built using only the top 3 most important features. The performance of this new model is compared to the original model to assess the impact of using a reduced feature set.

## Conclusion
This project demonstrates the potential of advanced regression techniques, such as Random Forest Regression, in predicting house prices using a subset of features from the Ames Housing dataset. The model achieves high accuracy on the training dataset, and the feature importances provide insights into the model's performance and the importance of each feature. However, there is no definitive way to determine if the reduced feature set model is better than the original model. Despite this, the project showcases the capabilities of RandomForestRegressor and its ability to handle complex datasets.

