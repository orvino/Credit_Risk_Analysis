# Credit_Risk_Analysis
## **Overview**
From our previous work on credit card dataset for LendingClub, Jill has asked us to use machine learning to train and evaluate models with unbalanced classes. We will use and describe the balanced accuracy score and the precision and recall scores of all six machine learning models; Native Random Oversampling, SMOTE Oversampling, Undersampling, Combination Under-Over Sampling, Balanced Random Forest Classifier, Easy Ensemble AdaBoost Clarifier.

## **Resources**
Software: Python 3.10.1, Visual Studio Code 1.63.2, Pandas 1.2.4, Jupyter Notebook 6.4.8
LoanStats_2019Q1.csc

## **Results**
### *Native Random Oversampling*
- Balanced Accuracy: 0.649
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.61/0.69
<img width="623" alt="native random over" src="https://user-images.githubusercontent.com/91889241/163892296-a530eca9-7a73-48d6-8302-ac1239064004.png">


### *SMOTE Oversampling*
- Balanced Accuracy: 0.616
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.59/0.65
<img width="625" alt="SMOTE Over" src="https://user-images.githubusercontent.com/91889241/163892311-8e51405f-9b80-4dca-ab69-0554114cbe0f.png">


### *Undersampling*
- Balanced Accuracy: 0.649
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.57/0.46
<img width="636" alt="Undersampling" src="https://user-images.githubusercontent.com/91889241/163892322-4364b49a-309e-4f4d-8e62-e0fabc9e346a.png">


### *Combination Under-Over Sampling*
- Balanced Accuracy: 0.616
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.70/0.58
<img width="614" alt="Combo Under-over" src="https://user-images.githubusercontent.com/91889241/163892333-c1638689-5880-4a10-b1e1-6f6f0628a2b3.png">


### *Balanced Random Forest Classifier*
- Balanced Accuracy: 0.788
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.67/0.91
<img width="623" alt="Balanced Random" src="https://user-images.githubusercontent.com/91889241/163892349-f3573d84-7cdf-4ec5-9506-3712be7f019e.png">


### *Easy Ensemble AdaBoost Clarifier*
- Balanced Accuracy: 0.925
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.91/0.94
<img width="629" alt="Easy Ensemble" src="https://user-images.githubusercontent.com/91889241/163892360-a016b0c2-5af5-44a6-8e76-903cd0e1e672.png">

## **Summary**
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
