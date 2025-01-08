# ML-linear-logistic
Machine Learning for Human-Zombie Screening: Linear and Logistic Regression Approaches

This combined project centers on developing machine learning models for screening and classifying individuals based on their human-zombie score. Using a dataset with features like height, weight, and activity levels, it explores both regression and classification tasks.

The linear regression component predicts the human-zombie score as a continuous variable, implementing multivariate regression from scratch and using scikit-learn for comparisons. Techniques like gradient descent and regularization methods (Ridge, Lasso, and ElasticNet) are employed, with model performance evaluated through mean squared error.

The logistic regression part classifies individuals into categories: "Human," "Needs Further Testing," or "Zombie," based on thresholded scores. Implementations include a manual regularized logistic regression model and scikit-learn’s version. The project incorporates multiclass classification using the One-vs-All approach, with metrics like accuracy, F1 score, and confusion matrices reported.

Both models are designed to enhance the screening process for a fictional migration to "Earth Junior," ensuring the survival of humanity by minimizing the risk of zombie infiltration.
