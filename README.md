# Paris-Housing-ML
Paris Housing Price Prediction
Read the data 
Checked for missing values and outliers which were accurately dealt with 
Checked for correlatons between x and y and also between all the x 
Also checked for multiculiniarity
With the correlation and multiculiniarity we checked we were able to deciphered and drop off unnecessory columns
Splitted the independent(x) and dependent(y) variables into train and test
Normalized the x_trained
splitted the normalized x_trained and y_train into another train and test for validation
After that, Each of the Supersized machine learning models was incoperated to decipher the most suitable model
The first model that was used was Random forest regressor which helps us to check for feature importance.
Random forest told us only two colums i.e "garage" and "squareMeters" were important
From Random forest, we got MAE =  1.0245857993140818e-09, MSE = 1.958230271527036e-18 and R2 score = 1.0
Our error rate from Random forest was very good but we only made use of two columns which calls for the need for another model 
The next models that was used was Linear Regression, Using the Sklearn to generate our graph, it was discovered that out data were far away from the origin which calls for the need to test for another model
The next model that was used was pca, in this case , all except cityCode column was used 
With our PCA, were able to get a 100 percent R2 score and very minimum error rate.
Hence, the most suitable machine learning model to used is PCA
