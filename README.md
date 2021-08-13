# Bank-Note-Authenticity-Prediction(Binary Classification using RandomForest):

1. Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. 
   Wavelet Transform tool were used to extract features from images
2. Did univariate and bivariate analysis to check whether individual feature or their combination would be able to classify the dataset.
3. Observed during EDA that individual feature can't classify but scatterplot(in pairplot) of two features(Variance Wavelet and Skewness Wavelet) was showing good classification decision boundary.
4. Used Grid Search for hyperparameters tuning.Tuned n_estimators,max_features,bootstrap etc. Trained model using best parameters.
5. Used Elbow method to find decent n-estimators by plotting error and # of misclassification against n_estimators.
5. Acheived an accuracy of 99.4% on test set.
