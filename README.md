# Zoo Animal Classification using Decision Tree Classifier

This project uses a Decision Tree Classifier to predict the class of animals based on their physical and behavioral traits. The dataset contains 101 animals with 17 features (like hair, feathers, eggs, milk, etc.) and a target variable class_type which categorizes the animals into 7 distinct classes.

Project Steps:
Data Preprocessing: Dropped irrelevant features like animal_name.
Model Training: Split the dataset (80% training, 20% testing) and trained a Decision Tree Classifier.
Evaluation: Achieved an accuracy of 80.95% on the test data.
Features:
hair, feathers, eggs, milk, etc. (16 total features)
Model Used:
Decision Tree Classifier (criterion: Gini impurity)
Results:
Prediction accuracy: 80.95%
How to Run:
Install dependencies: pandas, numpy, sklearn
Load the zoo dataset.
Train the model and evaluate its performance.
