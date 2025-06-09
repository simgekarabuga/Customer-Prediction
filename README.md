🎯 Project Objective: The main objective of this project is to enhance the effectiveness of marketing campaigns by analyzing customer data to:

Identify loyal customers,

Understand the demographic and behavioral patterns of loyal customers,

Analyze the impact of campaigns based on age groups,

🔍 Steps Taken: 📊 Data Preprocessing: Missing values were handled (e.g., Income column was filled with the mean).

Categorical variables were encoded into numerical format (Education, Marital_Status, Income group, etc.).

New features were created, including:

income_group_num (based on quartiles),

EducationLevel (ordinal encoding),

HasKid (combination of Kidhome and Teenhome),

Total_Spending (sum of all product spendings),

Is_Loyal (customers with spending above the 95th percentile labeled as 1).

📈 Loyal Customer Analysis: Is_Loyal variable was used to label loyal customers.

Among loyal customers:

Majority were aged 31–45,

Most were married with no children,

Top spending categories: Wines and Meat Products.

Monthly registration trends and age group distributions were visualized and analyzed.

🧠 Modeling: Feature engineering was performed to construct the model input.

Is_Loyal was defined as the target variable.

XGBoost classifier was used for predicting loyalty.

Model performance was evaluated using accuracy and F1 score metrics.

📊 Power BI Dashboard: Insights were visualized through an interactive Power BI dashboard, including:

Spending by product,

Age group distributions of loyal customers,

Monthly customer registration trends,

Average monthly spending by age groups.

The dashboard was designed to support quick business decisions and marketing strategy planning.

Results: Loyal customers were successfully identified, and key characteristics were extracted.

Features such as age, education, income, and having children were found to significantly influence customer loyalty.

The XGBoost model achieved high accuracy in predicting potential loyal customers.

Power BI visualization made it easy to interpret campaign effectiveness across time and demographics.
