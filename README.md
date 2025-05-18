# Customer_Churn_Analysis
🔍 Project Overview
This end-to-end project analyzes customer churn behavior for a subscription-based service. The objective is to identify key patterns and predict whether new customers are likely to churn or stay using data analysis and machine learning models.

🗂 Tools Used: MySQL · Power BI · Power Query · Google Colab · Python (Logistic Regression, Decision Tree, Random Forest)
📌 Key Steps & Workflow
1. Data Import & Cleaning in MySQL
Imported raw CSV data into MySQL.
Cleaned and preprocessed the dataset:
Removed null values and replaced them with appropriate values.
Standardized data types for analysis.
Performed initial Exploratory Data Analysis (EDA) to understand churn trends.

2. View Creation in MySQL
vw_churned: Contains complete information about both churned and stayed customers.
vw_joiner: Contains new customers who joined recently (used for prediction).

3. Power BI for EDA & Reporting
Imported data into Power Query Editor in Power BI.
Performed further data transformations and EDA.
Created an interactive dashboard to visualize:
Churn trends
Demographics
Key influencing factors
Predicted new churners

4. Machine Learning in Google Colab
Imported vw_churned into Google Colab.
Trained the data using:
Logistic Regression – 82% accuracy
Decision Tree – 77% accuracy
Random Forest – 85% accuracy
Imported the test data (vw_joiner) to predict churn.
Final prediction: 380 new joiners likely to churn.

5. Dashboard Output
The final Power BI dashboard includes:
ML prediction summary
Churn distribution
KPIs & visual storytelling of churn drivers
Highlight of the 380 predicted joiners at risk

🎯 Business Insights
Month-to-month customers with higher charges show higher churn risk.
Longer customer tenure and bundled services reduce churn.
Predictive modeling can help target at-risk customers with retention offers.

📁 Files Included
SQL scripts (data cleaning, view creation)
Power BI dashboard (.pbix file)
Google Colab notebook (.ipynb)
Readme with project explanation

🚀 Conclusion
This project showcases a full data pipeline – from raw data ingestion to interactive dashboarding and predictive modeling. It reflects practical business analyst and data science skills using real-world tools and techniques

![image](https://github.com/user-attachments/assets/d36bf4e7-130e-48af-9ce1-22c3bdb47287)
![image](https://github.com/user-attachments/assets/c99cb72d-95ef-43df-ab23-817769bd59be)
![image](https://github.com/user-attachments/assets/1bf75ca5-282d-4e40-b254-9aac4df671eb)

