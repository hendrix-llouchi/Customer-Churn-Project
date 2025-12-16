Customer Churn Prediction Project

Role: Data Science Intern
Organization:** Go2Cod
Intern: Henry Cobbinah
Duration: 1 Month
Tools: Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit



Project Overview

This project focused on predicting customer churn by analyzing customer behavior data and building a machine learning model to identify customers who are likely to leave a business. The aim was to support better decision-making around customer retention through data-driven insights.

The work covered the full data science lifecycle, from raw data preparation to model deployment.


Problem Statement

Customer churn directly affects business growth and revenue. The goal of this project was to:

* Understand key factors that influence customer churn
* Build a predictive model to classify churn risk
* Present insights in a way that is accessible to non-technical users



Dataset Description

The dataset contained customer-level information with the following attributes:

* Email
* Address
* Avatar
* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership
* Yearly Amount Spent

Initially, the dataset was provided without column headers, which required manual column assignment and validation.



Data Cleaning and Preprocessing

Data preparation was a major focus of the project.

* Assigned meaningful column names to the dataset
* Removed non-informative features such as Email, Address, and Avatar
* Checked and handled missing values and duplicates
* Ensured correct data types across all features
* Explored feature distributions and relationships using visualizations
* Applied feature scaling where necessary to support model performance



Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and feature relationships. Correlation analysis and visual exploration revealed patterns between engagement metrics and customer retention.



Model Development

* Split the dataset into training and testing sets
* Trained classification models including Logistic Regression
* Evaluated models using accuracy, precision, recall, and F1-score
* Selected the best-performing model based on balanced evaluation metrics


Results and Insights

* Time spent on the app and length of membership showed strong influence on customer retention
* Lower engagement levels were associated with higher churn probability
* The final model demonstrated reliable performance in identifying churn-prone customers


 
Deployment

A Streamlit application was developed to allow users to input customer data and receive real-time churn predictions. This made the model accessible to stakeholders without a technical background.

---
 Documentation

The full workflow was documented in Jupyter Notebook, including explanations for preprocessing decisions, model selection, and results interpretation. Visual comparisons were included to show data states before and after cleaning.



 Skills Applied

* Data cleaning and preprocessing
* Exploratory data analysis
* Machine learning model development
* Model evaluation and interpretation
* Streamlit application deployment
* Technical documentation



 Challenges

* Working with datasets lacking column names
* Identifying meaningful features for prediction
* Balancing model interpretability with performance



Outcome

The project delivered a complete, end-to-end churn prediction solution and reinforced practical data science skills applicable to real-world business problems.





End of document
