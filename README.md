# Bank-Marketing-Classification
Classification analysis of bank marketing data to predict term deposit subscription using various machine learning algorithms.

1. Naive Bayes:
Accuracy: 0.7389 (around 73.9%)
The average precision, recall, and F1-score are around 0.74, indicating that this model has relatively balanced performance in detecting both classes.
Advantage: Naive Bayes works quickly and is suitable for large datasets, though its performance may degrade if there are highly dependent features.

2. K-Nearest Neighbors (KNN):
Accuracy: 0.7456 (around 74.6%)
Its performance is slightly better than Naive Bayes, with a higher F1-score.
Advantage: KNN performs well on smaller datasets, but its performance tends to degrade on larger datasets because it requires calculating the distance for each data point.

3. Logistic Regression:
Accuracy: (Not shown explicitly, but Logistic Regression generally performs well for binary and multiclass classification.)
Advantage: Logistic Regression is simple yet effective for less complex datasets. It is also easier to interpret compared to other models.

4. Decision Tree:
Accuracy: 0.78 (around 78%)
This model has the best accuracy with a higher average F1-score compared to other models.
Advantage: Decision Tree tends to model data well, though it can overfit if not properly tuned.

General Conclusion:
- Decision Tree is the best model in terms of accuracy for this dataset, achieving 78%. However, overfitting may be a concern.
- KNN performs well but requires more computational resources, especially for larger datasets.
- Naive Bayes and Logistic Regression are simpler models, yet still competitive, especially if the dataset has a linear or near-linear distribution.
  
Choosing the right model depends on the goals and constraints (e.g., computational speed, result interpretability, and dataset size). If better performance is desired, Decision Tree can be selected, but simpler models like Logistic Regression or Naive Bayes may be more efficient for interpretability and speed.
