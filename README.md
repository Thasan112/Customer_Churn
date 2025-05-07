
# Customer_Churn
Predict customer churn using telecom usage and billing data.

# Telecom Industry Churn Prediction 📉

This project analyzes a telecom dataset to understand customer churn and build predictive models that help identify which customers are at risk of leaving.

 ## Problem Statement
Customer churn is a critical challenge in the telecom industry. With increasing competition and saturated markets, acquiring new customers is becoming more expensive and resource-intensive. Therefore, retaining existing customers is not only more cost-effective but also vital for long-term business success.

This project focuses on understanding customer behavior through historical data analysis and building a robust machine learning model to predict customer churn. By identifying customers who are likely to leave, telecom companies can take proactive measures to retain them.

## Objectives:
Analyze customer behavior and usage patterns to uncover key churn indicators.
Recommended actionable strategies to improve customer retention based on behavioral insights.
Build a predictive model that accurately identifies customers at risk of churning.
Enable data-driven decision-making for customer engagement and loyalty strategies.
Through this project, telecom providers can reduce churn, enhance customer satisfaction, and improve profitability by leveraging data analytics and predictive modeling.

## 🗃️ Dataset

The dataset includes the following features:

Churn: Whether the customer churned (1) or not (0)

AccountWeeks: Weeks since the customer joined

ContractRenewal: 1 if the contract was renewed recently

DataPlan: 1 if the customer has a data plan

DataUsage: Monthly data usage in GB

CustServCalls: Customer service calls in the last month

DayMins: Total daytime minutes used

DayCalls: Total daytime calls

MonthlyCharge: Monthly bill amount

OverageFee: Total overage fee for the past year

## 📊 Exploratory Data Analysis (EDA)

Key findings:

- Customers with higher customer service calls are more likely to churn.
- Having a data plan is associated with lower churn.
- Recent contract renewals strongly correlate with customer retention.

## 🧠 Machine Learning Models

The following models were built and evaluated:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**

Metrics used for evaluation:

- **Accuracy**
- **Classification Report**
- **ROC AUC Score**
- **Confusion Matrix**
- **ROC Curve**

## 📌 Key Results

- **Random Forest** performed best with the highest AUC score.
- Important predictors of churn `ContractRenewal`, `CustServCalls`, and `DataPlan`.

## 📁 Project Structure

