# Machine-Learning-Mini-Project-3-

Project objectives

Business Objective: Reduce monthly customer churn by identifying high risk customers well in advance

Hypothesis
• Company CEO believes that existing models can predict churners precisely, but it's too late to take any retention actions, as customers usage have significantly declined by then

Analytics Objective
1. Build a classification model to predict churners one month in advance
2. Identify key churn drivers

1. Detect and resolve problems in the data (Missing value, Outliers, Unexpected value, etc.) 
i. How many customers had zero monthly revenue?
ii. How many columns have missing values percentage > 5%?
iii. For columns, "UniqueSubs" and "DirectorAssistedCalls" remove outliers, if any

2. Perform exploratory analysis to analyze customer churn
i. Does customers with high overage minutes also have high revenue?
ii. Does high number of active subscribers lead to low monthly revenue?
iii. Does credit rating have an impact in churn rate?

3. Create additional features to help predict churn
i. Percent of current active subs over total subs
ii. Percent of recurrent charge to monthly charge
iii. Percent of overage minutes over total monthly minutes

4. Build classification model to predict customer churn 
i. Build a simple logistic regression model to predict churn and evaluate model
accuracy on test data set
ii. Build Random Forest classifier to compare model accuracy over the logistic
regression model
iii. Identify most important features impacting churn
(Model evaluation metrics to be used: GINI, AUC, Precision and Recall)

5. Use the hold out data provided to predict churners using the best model identified in step 4
