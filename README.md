# Prediction-model
We take the enlisted housing details of atmost 20,000 houses in the state of California. The dataset is from Kaggle and is attached in the form of csv here. 
> We apply decision tree and random forest ML algorithms to predict the house value of any house situated in California by using some features in our dataset.
* Pefroming EDA on the dataset to study the data. And to understand features for the prediction of house values
* Creating correlation matrix to find the correlation coefficents between different variables. Plotting all features of correlation matrix with scatter plot.
* Do feature selection, handle any missing values by using SimpleImputer, and tranform the whole training set.
* Performing data preprocessing we handle categorical attributes by OneHotEncoder then, creating custom transformer. And finally, creating transformation pipelines.
* Train the model with regression algorithms; decision tree and random forest. We saw random forest performs well thus, moving on with random forest model.
* To check how well our model works, we fine-tune it with cross-validation and grid search.
* Now, at the final stage we analyze and evalute the best model. Thus, predicting the final predictions.
