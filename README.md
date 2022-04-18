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
- Recall: High/Low risk = 0.61/0.69
<img width="625" alt="SMOTE Over" src="https://user-images.githubusercontent.com/91889241/163892311-8e51405f-9b80-4dca-ab69-0554114cbe0f.png">


### *Undersampling*
- Balanced Accuracy: 0.649
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.59/0.65
<img width="636" alt="Undersampling" src="https://user-images.githubusercontent.com/91889241/163892322-4364b49a-309e-4f4d-8e62-e0fabc9e346a.png">


### *Combination Under-Over Sampling*
- Balanced Accuracy: 0.616
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.57/0.46
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
In the financial industry, sensitivity is more valuable than precision for analyzing risk and default rates on loan candidates. This because banks want to be able to mark all of the high-risk individuals as high-risk for them not to default. It doesn't matter if it is not as precise as long as the posible defaults are marked as that.

In terms of precision, all six algorithms had a really low precision rate for high risk individuals. The highest one was the Easy Ensemble AdaBoost Classifier with 7% precision which is still considered pretty low for finding these high risk individuals not to give loans to. This means that out of all the customers marked as high-risk 7% were actually high-risk. On the other hand, all the models had a perfect precision for low-risk individiauls meaning that all of the low-risk customers were marked as that.

Having this in mind, precision is not telling us much information to compare the algorithms, so we should take a look at sensitivity. The model with the highest sensitivity was the easy ensemble adaboost classifier (91% for high-risk and 94% for low-risk individuals), meaning that 91% of the time all the high-risk individuals are marked as high-risk individuals. Followed by this model, the other two with high recall were the Random Forest Classifier (67%) and SMOTEENN Resample (70%).

And last but not least, we are going to look at the balanced accuracy score to make the final decision of which model to use. The accuracy score stands for how correct was the model, meaning out of all the predictions how many of them were true to the classification. As we were able to see, the model with the highest accuracy score by far was the Easy Ensemble AdaBoost Classifier. So, this should be the one we chose because of its high accuracy, highest precision, and highest sensitivity.
