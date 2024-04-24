# Loan Status Predictor 
 
## Contributors
- Madhumita Thiruppathi
- Ponnusamy Saishenetha
- Sukainah Begam


## Problem Definition
The main aim of our project is to develop a predictive model to assess the likelihood of loan default, aiding lending institutions in mitigating financial risk and making informed decisions. By accurately predicting whether a borrower will pay off their loan, we aim to provide lenders with a valuable tool for assessing the creditworthiness of loan applicants and reducing potential losses due to defaults.

## Models Used

1. Decision Tree Classifier 
2. Logistic Regression
3. Random Forest Classifier

## Conclusion

- Top 3 numerical datas based off correlation are interest rate, inquires in the last 6 months and loan amount.
- Top 3 categorical columns based off Cramers V Statistic are grade, term and verification status.
Model Performance:
- Decision Tree Classifier: Achieved consistent accuracy of around 64-65% on both training and testing datasets, with relatively high true positive and true negative rates but high false negative rate.
- Logistic Regression: Showed similar performance to Decision Tree Classifier, with accuracies of approximately 61-62% and high false positive and false negative rates.
- Random Forest Classifier: Outperformed the other models, with accuracies ranging from 66-71% and relatively high true positive and true negative rates, indicating effective classification of both "Fully Paid" and "Charged Off" loans.
Recommendations:
- Hyperparameter Tuning: Utilize techniques like Randomized Search for finding the best hyperparameters.
- Randomized Search suggested the optimal depth for Decision Tree Classifier as 9 and for Random Forest Classifier, max depth is 10, min samples split as 4 and estimators as 975
  
In future work, we recommend regularly monitoring and updating models to maintain accuracy as data distributions and customer behaviors evolve. Additionally, exploring other ensemble methods like Gradient Boosting Machines, AdaBoost, or XGBoost might further improve predictive performance.

Yes, it is possible to predict the loan status with acceptable amount of accuracy, high TPR and TNR values. We recommend to use the Random Forest Classifier model to predict the loan status.

## What did we learn from this project?

- Handling imbalanced datasets using resampling techniques (Upsampling)
- OneHot encoding
- Chi Square Statistic, Cramér's V
- Logistic Regression from sklearn
- Collaborating using GitHub
- Hyperparamter Tuning
- Randomised Search Cross validation tool (RandomizedSearchCV)

## References

- <https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-logistic-regression/#:~:text=Logistic%20regression%20is%20a%20supervised%20machine%20learning%20algorithm%20that%20accomplishes,1%2C%20or%20true%2Ffalse.>
- <https://www.geeksforgeeks.org/random-forest-algorithm-in-machine-learning/>
- <https://www.kdnuggets.com/2016/08/learning-from-imbalanced-classes.html/2>
- <https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd>
- <https://scales.arabpsychology.com/stats/how-to-calculate-cramers-v-in-python/#:~:text=The%20Cramer's%20V%20statistic%20is,columns%20(whichever%20is%20smaller).>
- <https://www.analyticsvidhya.com/blog/2022/02/a-comprehensive-guide-on-hyperparameter-tuning-and-its-techniques/>
- <https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8>
- 



