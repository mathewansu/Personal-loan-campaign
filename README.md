# Personal-loan-campaign
Goal is to predict the likelihood of a liability customer buying personal loans on basis of ID, Age, Experience, Income, ZIP Code, Family, CCAvg, Education, Mortgage, Personal Loan, Securities, CD account, Online, Credit Card

Performed Exploratory Data Analysis and trained a model for predicting the likelihood of a liability customer buying personal loans

### Confusion Matrix at threshold 0.5
![alt text](https://github.com/mathewansu/Personal-loan-campaign/blob/main/Confusion%20Matrix_1.PNG)

### Confusion Matrix at threshold 0.6
![alt text](https://github.com/mathewansu/Personal-loan-campaign/blob/main/Confusion%20Matrix.PNG)

### ROC
![alt text](https://github.com/mathewansu/Personal-loan-campaign/blob/main/ROC.PNG)

### Feature Importance
- "Education_3", "Education_2","CD Account_1", "Family_3", "Family_4" seems to be top 5 features which influence the model's output. Based on the coefficients value.
- "Mortgage" and "Securities Account_1"doesn't play any role in predicting the target variable.

![alt text](https://github.com/mathewansu/Loan-Prediction/blob/main/Feature%20Importance.PNG)

### Business Insights

- Model has good accuracy and precision
- Recall is bit less
- We can tweek threshold of model and find better values
- 95% predicted values are correct
- Here more focus towards should be towards recall because our target variable is 'Personal Loan' , i.e whether the customer is accepting the personal loan or not. Here bank wants more people to accept personal loan (less number of False Negative), so that bank doesn't lose real customers who want to take loan. Hence the focus should be on increasing Recall. Here when we increase threshold from 0.5 to 0.6, Recall has increased from 0.65 to 0.72

