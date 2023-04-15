### obuchenie_s_uchitelem_dmitrak.ipynb ###

The work was performed for a bank in order to predict the departure of customers based on their behavioral history. 
Decision tree, random forest and logistic regression models were built and the best model was selected based on the maximization of the F1 measure.

The best model turned out to be the Random Forest model with increasing sampling.

The best parameters: {'max_depth': None, 'n_estimators': 300}
Best F1 on CV: 0.9129871849420832
ROC_auc: 0.7463485895804195

When trained on the test data, the model showed the following results:
ROC curve area: 0.8351543077323237
F1: 0.5943877551020408
This exceeds the conditionally specified value of 0.59.


** Tools used:**

- scikit-learn
- imblearn
- pandas
- seaborn
- matplotlib
- re
- numpy


