# Text-Classification
Project: Text Classification

Overview

This project involves the classification of text data using various algorithms, focusing on feature selection and its impact on model performance. The goal is to analyze how the choice and number of features affect key metrics such as precision, recall, F1-score, and overall accuracy.

The project demonstrates that while increasing the number of features can improve accuracy, there are diminishing returns beyond a certain point, and a balance must be struck between computational viability and performance.

Observations

Recall and Precision: The model achieves excellent recall for some classes, while performance for others is moderate. This variability is likely due to the selection of features.
Feature Selection: More accurate feature selection improves the model’s F1-score, precision, and recall.
Confusion Matrix: Analysis of the confusion matrix reveals that the model works well for certain classes, indicating that the algorithm is effective but could be fine-tuned further.
Accuracy: The model achieves an accuracy of around 86%, which is comparable to the performance of the built-in Multinomial Naive Bayes algorithm.
Feature Impact on Accuracy: Increasing the number of features (up to 50,000) in the 13th cell could improve accuracy to about 90%. However, beyond a certain point, the increase in accuracy becomes marginal, and it may be more computationally efficient to limit the number of features to 10,000 or 20,000 for this dataset.
Requirements

Python libraries:
pandas
numpy
sklearn (for model building and evaluation)
