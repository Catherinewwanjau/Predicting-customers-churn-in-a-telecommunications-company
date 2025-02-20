# Predicting Customer Churn

# Project Overview
This project aims to predict customer churn in the telecommunications industry using machine learning models. By identifying key factors that contribute to customer churn, businesses can take proactive measures to improve customer retention and minimize revenue loss.
# Objectives
Develop a predictive model to classify customers as likely to churn or not.

Identify key factors influencing customer churn.

Provide actionable insights to improve customer retention strategies.

# Dataset
The dataset used for this project is bigml.csv, containing 3333 rows and 20+ features related to customer activity, such as:
* Numerical features: Account length, total day minutes, total eve calls, total night charge, customer service calls, etc.
* Categorical features: State, area code, international plan, voice mail plan.
* Target variable: churn (True/False) indicating whether a customer has left the company.
# Tools & Libraries
* Python 
* Pandas, numpy - Data manipulation
* Scikit-learn - Machine learning modeling
* Matplotlib, seaborn - Data visualization
 # Data Preprocessing
* Dropped unnecessary columns (e.g., phone number).
* Encoded categorical variables using Label Encoding.
* Split data into training (70%) and testing (30%) sets.
 # Models Used
1 Logistic Regression

 Accuracy: 86.00%
 
 AUC-ROC: 0.7819
 
 Strength: Simple and interpretable.
 
 Weakness: Lower recall, meaning it fails to detect many churn cases.
 
2 Decision Tree

Accuracy: 94.00%

Precision: 91.26%

Recall: 64.83%

AUC-ROC: 0.8547

Strength: High performance in identifying churners, better recall.

Weakness: Risk of overfitting if not properly tuned.

# Key Insights
The Decision Tree model outperforms Logistic Regression, making it the better choice for deployment.

Important factors influencing churn include customer service calls, international plans, and voice mail plans.

High churn customers often have frequent interactions with customer service.
 # Recommendations
Deploy the Decision Tree model to monitor churn risk in real-time.

Use predictive insights to offer personalized retention strategies.

Improve customer service experience to lower churn rates.

Continuously update the model with new data to maintain accuracy.

# Contributions
Feel free to fork this repository, submit issues, or create pull requests to improve the project.


