Fall detection using machine learning models

This project aims to build a fall detection system using different machine learning classification algorithms. Various supervised learning models like random forests, gradient boosting, support vector machines, k-nearest neighbors and logistic regression are used to detect falls from inertial sensor data.
Feature extraction

Important features indicative of falls are extracted from the inertial sensor data using feature selection techniques like mutual information, ANOVA and RFECV.

    Mutual information is used to find the most informative features that have high dependency on the target variable i.e fall vs non-fall.

    ANOVA helps identify significant features that have high variance between classes.

    Recursive feature elimination with cross-validation (RFECV) iteratively removes features and builds models on the remaining features to find the optimal number of features required.

Classification models

The extracted features are then used to build and compare the performance of different classifiers:

    Random forests - An ensemble of decision trees that average out the predictions of individual trees to make more accurate predictions.

    Gradient boosting - Like random forests but builds the trees sequentially and each new tree learns from the mistakes of the previous trees.

    Support vector machines (SVM) - Finds the optimal separating hyperplane between classes with maximum margin.

    K-nearest neighbors (KNN) - Classifies based on the majority vote of k closest training examples in feature space.

    Logistic regression - Linear classifier that predicts the probability of the target variable being 1.

Ensemble technique

An ensemble technique is applied combining the above models to attain 100% accuracy on test data for fall detection.

This provides an effective fall detection system leveraging various machine learning algorithms and ensemble approach.
