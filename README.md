**Telecom EDA Case Study**

**Business Understanding and Overview:**
This repository contains a case study focusing on exploring customer data from a telecommunications company. The primary objective of this analysis is to gain insights into customer behavior, preferences, and factors influencing churn rates. By examining the dataset, we aim to identify patterns, correlations, and potential predictors of churn, which can guide decision-making strategies to mitigate churn and enhance customer satisfaction.

**Understanding the Data:
Churn:**

Churn rate is observed to be lower when the monthly charges are low.
Positive correlation (~0.40) with the 'Contract_Month-to-Month' variable.
Negative correlation (~ -0.30) with the 'Contract_Two year' variable.

**Missing Data:**
Initially, 'TotalCharges' Dtype is object, which should be float.
After converting to float, 11 null (NaN) values are detected in the 'TotalCharges' column.
Null rows are dropped, resulting in the dataframe length reducing to 7032 from 7043.

**Graphical representation of tenure:**
**Data cleaning **
Results in the creation of a new categorical feature 'tenure_group' based on specified intervals.
'tenure_group' provides a more granular representation of customer tenure than the original 'tenure' variable.
Initial Intuition From Data:
Mean monthly charge: approximately $64.80.
Standard deviation of monthly charges: approximately $30.09.
Mean total charge: approximately $2283.30.
Standard deviation of total charges: approximately $2266.77.
Insights into distribution and variability of key variables are obtained.

**Categorical Analysis:**
Distribution of predictor categories with respect to churn status is visualized.
Comparison of churned and non-churned customers within each category is made.
Observations suggest predictors with potential impact on churn behavior.

**Numerical Analysis:**
Kernel density plots (KDE) are used to analyze 'MonthlyCharges' stratified by churn status.
Differences in distributions suggest relationship between monthly charges and churn.
Further numerical univariate analysis reveals insights into churn behavior based on monthly charges.

**Univariate and Bivariate Analysis:**

**Univariate Analysis:**

Numerical analysis of 'MonthlyCharges' revealed differences in churn behavior based on monthly charges.
KDE plots helped understand the relationship between monthly charges and churn.
Insights derived from univariate analysis provided initial intuition into churn behavior.
Univariate and Bivariate Analysis:
Univariate Analysis:

Numerical analysis of 'MonthlyCharges' revealed differences in churn behavior based on monthly charges.
KDE plots helped understand the relationship between monthly charges and churn.
Insights derived from univariate analysis provided initial intuition into churn behavior.
**Bivariate Analysis:**

Categorical analysis of predictor categories with respect to churn status provided insights into predictors impacting churn behavior.
Comparison of churned and non-churned customers within each category helped identify potential predictors of churn.
Observations from bivariate analysis aided in understanding the relationship between predictors and churn.

Categorical analysis of predictor categories with respect to churn status provided insights into predictors impacting churn behavior.
Comparison of churned and non-churned customers within each category helped identify potential predictors of churn.
Observations from bivariate analysis aided in understanding the relationship between predictors and churn.

**Final Thoughts:**
Churn rate for Total charges is higher when the total charge is low, suggesting potential reasons such as early churn.
High monthly charges are associated with higher churn rates.
Senior citizens exhibit higher churn rates (~41.68%).
Insights into various predictors and their association with churn behavior are derived.
Conclusion:
This case study provides valuable insights into customer churn behavior within the telecommunications company. By leveraging exploratory data analysis (EDA) techniques, we have identified key predictors, correlations, and trends that influence churn rates. These findings can inform strategic decision-making processes aimed at reducing churn, enhancing customer satisfaction, and optimizing business operations.

For more detailed insights and visualizations, please refer to the Jupyter Notebook provided in this repository.
