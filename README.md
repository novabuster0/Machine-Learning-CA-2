Bank Customer Churn Prediction Using Machine Learning
Project Overview

Developed a supervised machine learning solution to predict bank customer churn (Exited vs. Retained).

Utilized customer demographic, financial, and behavioral data to identify customers at risk of leaving.

The model enables banks to implement data-driven retention strategies and reduce customer attrition.

Project Objectives

Perform data cleaning and preprocessing on a real-world banking dataset.

Analyze key factors influencing customer churn through Exploratory Data Analysis (EDA).

Train and compare multiple supervised machine learning classification models.

Evaluate model performance using standard classification metrics.

Identify the most effective model for churn prediction.

Methodology / Approach
1. Data Preparation

Imported bank customer dataset containing attributes such as Credit Score, Age, Balance, and Account Activity.

Removed non-informative identifiers (e.g., CustomerId, Surname).

Encoded categorical variables:

Gender: Label Encoding

Geography: One-Hot Encoding

Applied StandardScaler to normalize numerical features for distance-based models.

2. Exploratory Data Analysis (EDA)

Analyzed churn distribution and class imbalance.

Studied correlations between customer attributes and churn.

Visualized key patterns using histograms, bar plots, and heatmaps.

3. Model Development

Split data into 80% training and 20% testing sets.

Trained and evaluated the following supervised learning models:

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Decision Tree Classifier

Linear Support Vector Machine (SVM)

4. Model Evaluation

Compared models using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Tools & Technologies

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook

Best Performing Model

K-Nearest Neighbors (KNN) achieved the highest accuracy (~85%).

Demonstrated strong performance by effectively clustering similar customer profiles.

Outperformed linear models and the baseline Decision Tree on this dataset.

Key Insights & Findings

Class Imbalance: Approximately 80% retained customers vs. 20% churned.

Age Factor: Older customers exhibited a higher likelihood of churn.

Geographical Impact: Customers from Germany showed higher churn rates compared to France and Spain.

Customer Activity: Active members were significantly less likely to exit than inactive customers.

Project Outputs

Model accuracy comparison visualization.

Confusion matrix highlighting correct and incorrect churn predictions.

Classification reports detailing precision, recall, and F1-score for each class.
