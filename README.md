# House-Prices---Advanced-Regression-Techniques-Kaggle-

This project is to see if one can use advanced regression techniques to predict house prices. 
To do this I am using Random Forest Regression, which I am using sklearns built in RandomForestRegressor.
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

Some of the features had text values so I had to make a function that could transform there text values to numeric values. I looked at all the features and chose thoghs which seemed most relevant for the price values. 
After that I made a list of the features and the salas price, and then used sklearns built in RandomForestRegressor. I train the model to the traning data, and the predicted the house prices on the test data. 

After this I found the features with the highest importances. After founding it I then did the RandomForestRegressor with the 3 highest. I then looked at the difference, but since there is no way to know if one i better then the other, I then ended the project.

