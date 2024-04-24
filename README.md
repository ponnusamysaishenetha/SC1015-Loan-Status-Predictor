# Loan Status Predictor 
 
## Contributors
- Madhumita Thiruppathi
- Ponnusamy Saishenetha
- Sukainah Begam


## Problem Definition
The main of our project is to develop a predictive model to assess the likelihood of loan default, aiding lending institutions in mitigating financial risk and making informed decisions. By accurately predicting whether a borrower will pay off their loan, we aim to provide lenders with a valuable tool for assessing the creditworthiness of loan applicants and reducing potential losses due to defaults.

## Models Used

1. Decision Tree Classifier 
2. Logistic Regression
3. Random Forest Classifier

## Conclusion

- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Handling imbalanced datasets using resampling methods and imblearn package
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- API Usage
- Other packages such as tqdm, json, requests
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## References

- <https://developers.themoviedb.org/3/getting-started>](https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-logistic-regression/#:~:text=Logistic%20regression%20is%20a%20supervised%20machine%20learning%20algorithm%20that%20accomplishes,1%2C%20or%20true%2Ffalse.)
- <https://www.geeksforgeeks.org/random-forest-algorithm-in-machine-learning/ 
- <https://www.kdnuggets.com/2016/08/learning-from-imbalanced-classes.html/2 
