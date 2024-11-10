# maya_portfolio

# [project 1: Churn Analysis using Predictive Modelling]([https://github.com/udaybhan10/CustomerChurnPrediction](https://github.com/mayurinegi/churn-analysis-dataset/blob/main/230173266_models.ipynb)

Project: Customer Churn Prediction for a Digital Music Streaming Platform

This project was undertaken as part of my Master's dissertation in Business Analytics at Aston Business School. The research aimed to develop effective machine learning models to predict customer churn for a major music streaming service using large-scale behavioral and transactional data.

Key Highlights:

Project Overview:

Developed as a part of my MSc dissertation, focusing on predictive analytics to address customer churn for subscription-based platforms like KKBox.
Leveraged data science techniques to identify high-risk customers and recommend personalized retention strategies.

Data Sources and Preprocessing:

Integrated and preprocessed datasets comprising transaction logs, demographic details, and daily user activity.
Applied data cleaning, feature engineering, and stratified sampling to handle class imbalance and prevent data leakage.
Engineered new variables, such as engagement scores, discount categories, and retention indicators, for enhanced model accuracy.

Machine Learning Models:

Evaluated various algorithms: 

Decision Tree, Random Forest, XGBoost, and CatBoost for churn prediction.
Conducted model evaluation using precision, recall, F1-score, and ROC-AUC metrics to benchmark performance.
Achieved balanced performance with Random Forest and CatBoost models, excelling in both precision (0.818) and recall (0.845).

Feature Engineering:

Developed custom metrics like completion ratio, skip ratio, and weighted engagement scores to capture user behavior patterns.
Implemented feature scaling using StandardScaler to optimize model performance for numerical attributes.

Model Evaluation & Results:

Compared advanced models against a baseline dummy classifier to demonstrate significant performance improvements.
XGBoost excelled in precision (0.822), minimizing false positives, while CatBoost achieved robust overall scores.
Random Forest and CatBoost models demonstrated the best balance of precision and recall, making them ideal for churn prediction tasks.

Visualization & Insights:

Used data visualization to analyze relationships between churn and factors such as price tiers, auto-renewal status, and user engagement.
Extracted actionable insights to inform retention strategies, such as targeting users based on subscription duration and engagement metrics.

Conclusion & Future Work:

Ensemble models like Random Forest and CatBoost were recommended due to their superior predictive capabilities for identifying potential churners.
Future work includes integrating real-time data streams and exploring deep learning models for more nuanced user behavior analysis.
