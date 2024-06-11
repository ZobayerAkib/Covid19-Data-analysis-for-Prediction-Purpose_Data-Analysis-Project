## Prediction of Total COVID-19 Cases in Bangladesh using Linear Regression

### Overview

In this project, we aimed to predict the total number of COVID-19 cases per day in Bangladesh using linear regression. We split the dataset into training and testing sets, with a test size of 35%. Our goal was to analyze the effectiveness of linear regression in predicting the progression of COVID-19 cases in Bangladesh.

### Model Training and Evaluation

We utilized the following steps for model training and evaluation:
- **Features (X):** Date
- **Target (y):** Total COVID-19 cases
- **Model:** Linear Regression

We split the dataset into training and testing sets using the `train_test_split` function from scikit-learn, with a test size of 35% and a random state of 42. We trained the linear regression model on the training data and evaluated its performance using the Mean Squared Error (MSE) metric.

### Results

The Mean Squared Error (MSE) obtained for the linear regression model was 536,298,547,099.31. This metric indicates the average squared difference between the predicted and actual total COVID-19 cases per day. 

### Conclusion

Further analysis with different models or additional features may be necessary to improve predictive accuracy.

