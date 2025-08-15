# Ad-Click-Prediction
ML with Python and Scikit-learn 
Click Prediction Model

Goal: Build a machine learning model to predict whether a user will click based on their time spent on a site, salary, and country.

🔍 Key Steps

Data Exploration:

Checked class balance (Clicked vs Not Clicked)

Visualized relationships between time on site, salary, and click behavior


Feature Engineering:

Interaction term: Time × Salary

Log transformation of salary to reduce skew

Salary categorization into Low / Medium / High

One-hot encoding of categorical variables


Modeling:

Logistic Regression (with scaling)

Random Forest Classifier (no scaling needed)

5-fold Stratified Cross-Validation


Evaluation:

Accuracy & ROC-AUC on test set

ROC curves for model comparison

Confusion matrices for classification breakdown



📊 Results

Model	Accuracy	ROC-AUC

Logistic Regression	0.840	0.928
Random Forest	0.950	0.970


Best Model: Random Forest — achieved 95% accuracy and 0.97 ROC-AUC on unseen data.
