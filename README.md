# Telecom-Churn-Group-Case-Study
Telecommunications industry experiences an average of 15 - 25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has become even more important than customer acquisition.
Here we are given with 4 months of data related to customer usage. In this case study, we analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
Churn is predicted using two approaches. Usage based churn and Revenue based churn. Usage based churn:
Customers who have zero usage, either incoming or outgoing - in terms of calls, internet etc. over a period of time.
This case study only considers usage based churn.
In the Indian and the southeast Asian market, approximately 80% of revenue comes from the top 20% customers (called high-value customers). Thus, if we can reduce churn of the high-value customers, we will be able to reduce significant revenue leakage. Hence, this case study focuses on high value customers only.
The dataset contains customer-level information for a span of four consecutive months - June, July, August and September. The months are encoded as 6, 7, 8 and 9, respectively.

The business objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months.

This is a classification problem, where we need to predict whether the customers is about to churn or not. We have carried out Baseline Logistic Regression, then Logistic Regression with PCA, PCA + Random Forest, PCA + XGBoost.
## Approach to solve this business problem
- Step 1 : Introduction -  Business Description, Problem Statement and Objective of the Project
- Step 2 : Data Understanding and Data Preparation
- Step 3 : Exploratory data analysis (EDA)
- Step 4 : Training the model
- Step 5 : Model Prediction and Evaluation
- Step 6 : Recommandations
