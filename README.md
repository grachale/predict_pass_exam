# Classification

## Data Source
We will focus on predicting whether a student will pass or fail an exam based on the number of study hours and their scores in the previous exam. We have training data in the file `data/student_exam_data.csv`.


## Feature List
- `n_estimators`: This parameter determines the number of weak learners (trees) that will be trained. Increasing the number of estimators generally improves the performance of the model, but it also increases the computational cost.
- `learning_rate`: It is used to slow down training and to prevent overfitting of the model (if less than one).

## Model
We will use Adaboost classifier with decision trees from scikit-learn. AdaBoost (Adaptive Boosting) is an ensemble learning method that combines the predictions of multiple weak learners (in our case decision trees) to create a strong learner.