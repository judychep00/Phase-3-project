# Phase-3-project

The goal of this project is to build a machine learning classifier that predicts customer churn for SyriaTel, a telecommunications company. By identifying customers who are likely to stop using the service, the company can implement targeted retention strategies to reduce revenue loss.

Business and Data Understanding: The primary stakeholder is SyriaTel's business team, including marketing, customer support, and product management. Their key interest is in reducing churn to maintain customer base and revenue.

The dataset contains anonymized customer account data, such as usage patterns, service plans, and churn status. It includes variables like:International and voice mail plan

Number of customer service calls

Total minutes and charges for day, evening, night, and international calls

The task is to find patterns that reliably predict whether a customer is likely to churn.

 Modeling:  Three machine learning models were trained and evaluated:

Logistic Regression (with and without hyperparameter tuning)

XGBoost Classifier (with GridSearchCV tuning)

Decision Tree Classifier

The modeling process included: Train-test splitting,  Feature scaling, Hyperparameter tuning using GridSearchCV, Model comparison based on classification metrics

Evaluation: Each model was evaluated using accuracy, F1 score, precision, recall, and ROC curves to assess performance on the test data.
Key findings: XGBoost was the best-performing model, Important features influencing churn: international plan, customer service calls, total day minutes/charges, These insights were used to guide business recommendations.

![image](https://github.com/user-attachments/assets/eecf9c71-1f71-440e-bb80-de10840263d6)  it shows performance of the models.

![image](https://github.com/user-attachments/assets/f48df76c-180c-42c7-b7c6-198ce8dcca75) Shows how some of the important features were evaluated before modelling.

Conclusion
The model successfully identifies high-risk customers with strong predictive performance. Business teams at SyriaTel can now act proactively by targeting at-risk customers through:

Better support experiences

Incentivized retention plans

Adjusting plans based on usage behavior

This project demonstrates how machine learning can drive business value by turning raw data into actionable insights

![image](https://github.com/user-attachments/assets/4a2f5474-58f6-41dc-8c13-cc7b33ae5f64) helped us to come up with some of the solutions as you will see in the presentation.



