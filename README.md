# Credit-Card-Default-Prediction
![image](https://user-images.githubusercontent.com/112092937/205936879-ece9a092-3dda-43b3-ad6b-57f5c9754d5c.png)


**Problem Description**
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.We can use the K-S chart to evaluate which customers will default on their credit card payments.

**Data Desciption**

     • ID: ID of each client
     • LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
     • SEX: Gender (1=male, 2=female)
     • EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)
     • MARRIAGE: Marital status (1=married, 2=single, 3=others)
     • AGE: Age in years
     • PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months,8=payment delay for eight months,9=payment delay for nine months and above)
     • PAY_2: Repayment status in August, 2005 (scale same as above)
     • PAY_3: Repayment status in July, 2005 (scale same as above)
     • PAY_4: Repayment status in June, 2005 (scale same as above)
     • PAY_5: Repayment status in May, 2005 (scale same as above)
     • PAY_6: Repayment status in April, 2005 (scale same as above)
     • BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
     • BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
     • BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
     • BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
     • BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
     • BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
     • PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
     • PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
     • PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
     • PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
     • PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
     • PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
     • default.payment.next.month: Default payment (1=yes, 0=no)
      
     
**Algorithms Used :**
      (1) Logistic Regression
      (2) Decision Tree Classifier
      (3) Random Forest Classifier
      (4) Gradient Boosting Classifier
      (5) XGBoost Clssifier
      (6) K Neighbors Classifier
      (7) Support Vector Classifier
      (8) Naive Bayes Classifier
