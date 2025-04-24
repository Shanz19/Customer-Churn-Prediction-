# Customer-Churn-Prediction-
## Introduction
This project analyzes telecom customer data to predict which customers are likely to churn (discontinue their service). In the highly competitive telecom industry, where the annual churn rate reaches 15-25%, early identification of at-risk customers can significantly impact a company's bottom line.

## What is Customer Churn?
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.
In the telecommunications industry, customers have numerous service providers to choose from and frequently switch between them. Understanding and preventing churn is crucial for maintaining market position and profitability.

## How Can Customer Churn Be Reduced?
To reduce customer churn, telecom companies need to:

Predict high-risk customers - Identify which customers are likely to leave
Develop a holistic view of customer interactions across various channels
Implement targeted retention strategies for at-risk customers
Address service issues that may be causing dissatisfaction

By addressing churn proactively, companies can preserve their market position while reducing costs and increasing profits.

## Project Objectives
The main objectives of this analysis are to:

Determine the percentage of customers who churn versus those who remain active
Identify patterns in churn behavior based on demographics like gender
Analyze preferences and churn patterns based on service types
Discover which features and services are most profitable
Build predictive models to identify customers likely to churn
Evaluate various machine learning algorithms for churn prediction

## Data Exploration
The dataset includes information about:

Customer demographics: gender, age range, partners, dependents
Account information: tenure, contract type, payment method, billing preferences
Services used: phone service, internet type, security features, streaming services
Financial data: monthly charges, total charges
Churn status: whether the customer left in the last month

## Key findings from exploratory analysis:

26.6% of customers switched to another firm
Customer distribution is balanced between males (50.5%) and females (49.5%)
75% of customers with month-to-month contracts churned
Customers with electronic payment methods showed higher churn rates
Fiber optic users demonstrated higher churn rates despite popularity
Absence of online security and tech support increased likelihood of churn
New customers and those with higher monthly charges were more likely to churn

## Data Preprocessing
The preprocessing pipeline included:

Handling missing values in the TotalCharges column
Converting categorical variables using label encoding
Standardizing numerical features using StandardScaler
Splitting data into training and testing sets (70/30 split)

## Machine Learning Models
Several classification algorithms were implemented and evaluated:

K-Nearest Neighbors (KNN)
Support Vector Classifier (SVC)
Random Forest Classifier
Logistic Regression
Decision Tree Classifier
AdaBoost Classifier
Gradient Boosting Classifier
Voting Classifier (ensemble of top performers)

## Results and Evaluation
Model performance comparison:
| Model | Accuracy |
|-------|----------|
| Voting Classifier | 81.7% |
| Random Forest | 81.4% |
| Logistic Regression | 80.9% |
| Gradient Boosting | 80.8% |
| AdaBoost | 80.8% |
| SVC | 80.8% |
| KNN | 77.5% |
| Decision Tree | 72.5% |
The final Voting Classifier achieved the best overall performance with 81.7% accuracy and balanced precision/recall metrics for churn prediction.

## Conclusion
The analysis revealed several key factors that influence customer churn:

Contract type has the strongest correlation with churn
Tenure and security features significantly impact retention
Monthly charges are positively correlated with churn risk
Support services (tech support, online security) are important retention factors

Customer churn significantly impacts a firm's profitability. The best strategy to reduce churn is to:

Identify at-risk customers early using predictive models
Improve customer satisfaction through better service
Build customer loyalty through personalized experiences
Survey churned customers to understand their reasons for leaving

## Technologies Used

- Python: Primary programming language
- Pandas & NumPy: Data manipulation and analysis
- Matplotlib & Seaborn: Data visualization
- Scikit-learn: Machine learning algorithms and evaluation metrics
- Plotly: Interactive visualizations

