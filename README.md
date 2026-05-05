## Project Requirements Completion
**1. Data Preprocessing**
Cleaned and prepared the dataset
Converted categorical variables using one-hot encoding
Scaled features using StandardScaler
Ensured consistency across training, validation, and test sets

**2. Data Splitting**

Split dataset into:
70% Training set
15% Validation set
15% Test set

This allowed proper training, tuning, and final evaluation

**3. Model Training**
Trained the following classification models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier (XGBoost)
K-Nearest Neighbors (KNN)
Support Vector Classifier (SVC)

**4. Model Evaluation & Comparison**

Evaluated all models using:

Accuracy → overall correctness

Precision → correctness of positive predictions

Recall → ability to detect actual positives

F1-Score → balance between precision and recall

ROC-AUC → overall classification performance

Compared results using:

Performance tables


**5. Ensemble Models**

Built ensemble models using the top 3 models (XGBoost, Decision Tree,KNN):

Voting Classifier: Combined predictions using soft voting (probabilities)

Bayesian Ensemble (Weighted Average): Assigned weights based on model performance, Combined probabilities using weighted average

**6. Ensemble Evaluation**

Evaluated both ensemble models on: Validation set, Test set

Compared: Voting vs Bayesian results, Ensemble vs individual models
