##Restaurant Customer Satisfaction Prediction
Project Overview
This project explores customer satisfaction in the restaurant industry using machine learning classification models. By analyzing synthetic data representing customer interactions and business variables, the goal is to predict satisfaction levels and identify key drivers behind positive and negative experiences.

The analysis uses Decision Trees, Random Forests, and data balancing techniques such as SMOTE to build interpretable, high-performance models.

Objectives
Predict customer satisfaction (Satisfied / Not Satisfied)

Identify top features contributing to customer experience

Evaluate model performance using accuracy, precision, recall, and F1-score

Apply Stratified k-Fold Cross Validation to assess model robustness

Provide actionable recommendations for restaurant managers

Tools & Libraries
Python

Scikit-learn

Pandas, NumPy

Matplotlib, Seaborn

SMOTE (from imblearn)

Jupyter Notebook

Dataset Description
A synthetic dataset simulating restaurant interactions:

Reservation Method (Online, Phone, Walk-in)

Time Waited, Loyalty Member, Staff Friendliness

Food Quality, Cleanliness, Bill Accuracy

Customer Satisfaction (Target Variable)

Models & Techniques
Decision Tree Classifier

Random Forest Classifier

SMOTE for balancing class imbalance

Stratified K-Fold Cross-Validation

Confusion Matrix, Precision, Recall, F1-Score

Key Insights
Loyalty Membership, Wait Time, and Food Quality were the most influential factors

Random Forest outperformed other models with improved precision and recall

SMOTE helped mitigate bias toward majority class (Satisfied customers)

Visualizations clarified satisfaction patterns and data distributions

Repository Contents
thesis_report.pdf – Full academic report

satisfaction_model.ipynb – Jupyter notebook with data cleaning, EDA, modeling

plots/ – Visualizations used in the analysis

README.md – You’re here

Conclusion
This project demonstrates how machine learning can uncover the key drivers of customer satisfaction in a restaurant setting and guide better decision-making. Future work could expand to regression tasks (e.g., star ratings) or real-world datasets.


