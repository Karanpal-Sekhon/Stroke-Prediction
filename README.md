# Stroke Prediction using Linear and Logistic Regression

## A comparison of the methods of linear and logistic regression with sklearn module
                                        
First we start off with Data Exploration, where we see age, previous stroke history, heart disease, glucose level, and BMI were all good predictors of stroke occurence. We also see much of the categorical variables like gender, marriage status, work type, etc. are not 
good predictors, except for smoking status. We then go through more data visuals where we see, confirmations of our hypotheses. Afterwards we split the data using sklearns train_test_split, and create the model by instantiating LogisticRegression(). We then fit the model,
and test our predictions and see in a confusion matrix that logistic regression performs very well with a 95% accuracy. However, it also very seldom predicts a stroke occurence. This could be due to the dataset, or a fault of model creation. 
<br>
<br>
We then move on to Linear Regression. It is obvious that we cannot use categorical variable in LR, so we copy the dataframe and drop those variables. Then we drop the target variable and store it as our y. We then do the same step as before and we split the data using train_test_split, and fit and test the model. We then see, linear regression performs quite poorly in comparison, however it is good showing of how we can use regression to predict strokes.
