# Predicting_Credit_Card_Approvals_using_ML
This particular implementation focuses on the development of an algorithm that predicts the actions of the users regarding the approval and rejection of credit cards using a credit card predictor model very similar to that of commercial banks for the enhancement of credit card applications processing. Everyday banks receive a massive pile of credit card application forms, out of which a good percentage stands rejected due to a plethora of reasons i.e. the person has loaned too high an amount, the income is too low, or too many credit inquiries on one report have been made. The processes involved in manually scrutinizing these applications take up a lot of resources since they are prone to errors and are expensive. Machine learning can be incorporated in this regard for the great benefit of both the user and the service provider.

# Project Workflow 
1- Data Preprocessing: Address missing values by substituting in not applicable indicators as well as stemming and at last one hot encoding the categorical feature attributes. 

2- Model Training: Sample the data stratify and scale it appropriate and equally fit the logistic regression model on the borrower's data with the target of their credit card prediction. 

3- Hyperparameter Tuning: Maximize the efficiency of the SVC classifier model by searching for the optimal parameters with the GridSearchCV function. 

4- Evaluation: Measure the effectiveness of the model using a confusion matrix and an accuracy metric score.

# Results 
It can be deduced from the findings of the research that this model automates around 79% of credit card application approval processing, hence the model can be successfully used at the management level.

# Technologies Used 
1- Python (used for data manipulation and constructing a model) 

2- Pandas & NumPy (data wrangling) 

3- Scikit-learn (fitting and optimizing patterns) 
