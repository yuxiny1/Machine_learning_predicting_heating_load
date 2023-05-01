
Heating Load Prediction

This project aims to predict the heating load of 768 buildings using various machine learning algorithms. Each building is described by 10 features (9 numerical and 1 categorical) and a target variable "Heating Load" (also numerical).

Overview

Data Inspection
Data Preprocessing
Data Visualization
Model Fitting and Evaluation
Model Fine-Tuning
Model Comparison
Conclusion
Data Inspection

The dataset is inspected for:

Overview of the data
Shape of the dataset
Data types of the columns
Missing values
Duplicates
Unique values
Outliers
Correlation between features
Data Preprocessing

The dataset is preprocessed by:

Handling missing values
Creating a training and test set using stratified sampling
Preparing the data for machine learning algorithms using pipelines
Data Visualization

Various visualizations are used to gain insights into the data and experiment with attribute/variable combinations.

Model Fitting and Evaluation

Several machine learning models are initialized and fitted to the data:

Ridge Regression
Elastic Net Regression
Neural Network
These models are then evaluated using metrics such as R-squared, Root Mean Squared Error (RMSE), and Mean Squared Error (MSE).

Model Fine-Tuning

Hyperparameters of the models are fine-tuned to achieve better performance. Randomized and grid search methods are used for this purpose.

Model Comparison

The performance of each model is compared based on their training and testing scores, as well as their RMSE and MSE values.

Conclusion

Based on the given data, the MLPRegressor model outperforms the Elastic Net Regression model in terms of both training and testing scores. The MLPRegressor model has a higher training score of 0.911 and a higher testing score of 0.884, while the Elastic Net Regression model has a training score of 0.808 and a testing score of 0.782.

In terms of RMSE, the MLPRegressor model also performs better than the Elastic Net Regression model. The MLPRegressor has a lower training RMSE of 3.004 and a lower testing RMSE of 3.415, while the Elastic Net Regression model has a training RMSE of 4.431 and a testing RMSE of 4.680.

Overall, the MLPRegressor model seems to be a better choice for predicting the heating load of housing compared to the Elastic Net Regression model, based on the given data.
