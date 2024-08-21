# mlprojects


1. Using the student performance dataset (Dataset | Google Colab) where the target feature is the GradeLevel, logistic regression resulted in the highest accuracy of ParentalSupport predicting Volunteering at 84%.
2. Using the SciKit library, I tried 5 regression models instead of classifiers with GPA as the target variable: Random Forest, Extra Trees, Decision Trees, K-Nearest-Neighbor, and Gaussian Process. These models were more complex and took in multiple features to predict the GPA, resulting in higher accuracy: At 8 features, I got around 80-90% accuracy for all models, which was decent. I used Grid Search to optimize hyperparameters but it barely increased the accuracy of each model (it took a long time).
3. Adding 4 extra binary classification features seemed to help all regression models perform significantly better, to now 87-95% accuracy, with the Gaussian Process achieving the highest r^2 score of 95%.
