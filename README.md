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

- <https://developers.themoviedb.org/3/getting-started>
- <https://www.free-powerpoint-templates-design.com/old-style-movie-projector-powerpoint-templates/>
- <https://www.kaggle.com/rafjaa/resampling-strategies-for-imbalanced-datasets>
- <https://alexlenail.me/NN-SVG/index.html>
- <https://www.kdnuggets.com/2016/08/learning-from-imbalanced-classes.html/2>
- <https://arxiv.org/pdf/1608.06048.pdf>
- <https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/>
- <https://towardsdatascience.com/derivative-of-the-sigmoid-function-536880cf918e>
- <https://www.researchgate.net/figure/Calculation-of-Precision-Recall-and-Accuracy-in-the-confusion-matrix_fig3_336402347>
- <https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd>
