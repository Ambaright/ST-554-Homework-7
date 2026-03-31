# ST-554-Homework-7
This homework assignment will practice fitting MLR and logistic regression models (including penalized and regularized methods).

## The Data
We will use a dataset from the UCI Machine Learning Repository. This data set is about wine quality (we
played around with this data in class at some point I think). You can learn more about the data here.
The data description describes the following variables:

Input variables (based on physicochemical tests)
- 1 - fixed acidity
- 2 - volatile acidity
- 3 - citric acid
- 4 - residual sugar
- 5 - chlorides
- 6 - free sulfur dioxide
- 7 - total sulfur dioxide
- 8 - density
- 9 - pH
- 10 - sulphates
- 11 - alcohol
- 
Output variable (based on sensory data):
- 12 - quality (score between 0 and 10)

• Rather than try to predict quality, let’s make our target variable for fitting multiple linear regression
type models alcohol.

• For fitting logistic regression type models we’ll use the type of wine as the response variable.
