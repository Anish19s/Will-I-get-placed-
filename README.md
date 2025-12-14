Placement Prediction using Logistic Regression

Overview
This project implements a binary classification model to predict whether a student will be placed or not based on academic performance, skills, and training-related features. The goal is to demonstrate both core machine learning fundamentals and practical implementation skills.

The project includes:

1)A from-scratch implementation of Logistic Regression using Gradient Descent
2)A scikit-learn implementation for validation and comparison
3)Model evaluation using accuracy
4)Visualization of a projected decision boundary

Dataset

1)The dataset contains student-related features such as:
2)CGPA
3)Number of Internships
4)Projects completed
5)Workshops / Certifications
6)Aptitude Test Score
7)Soft Skills Rating
8)Extracurricular Activities
9)Placement Training
10)SSC and HSC Marks

The target variable is:

PlacementStatus (Placed / Not Placed)

Categorical features are encoded numerically, and all features are standardized before training.

Approach
1. Manual Logistic Regression

Implemented the sigmoid function

Used Binary Cross-Entropy as the loss function

Optimized parameters using Gradient Descent

Tracked loss reduction over epochs to verify convergence

This step ensures a strong understanding of the underlying mathematics and optimization process.

2. scikit-learn Logistic Regression

Used LogisticRegression from scikit-learn

Trained on the same standardized dataset

Compared accuracy with the manual implementation to validate correctness

Both approaches produce similar performance, confirming the validity of the custom implementation.

Results

Training Accuracy: ~80%

Testing Accuracy: ~79%

The close train and test accuracy indicates good generalization and minimal overfitting.

Visualization

A 2D visualization of the decision boundary is created by projecting the high-dimensional decision surface onto two important features (e.g., CGPA and Aptitude Test Score), while fixing other features at their median values.

This provides an interpretable view of how the model separates the classes.

Technologies Used

1)Python
2)NumPy
3)Pandas
4)Matplotlib
5)scikit-learn

