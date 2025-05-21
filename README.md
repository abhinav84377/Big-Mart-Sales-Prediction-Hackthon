# Big-Mart-Sales-Prediction-Hackthon


Big Mart Sales Prediction – Thought Process and Experimentation Summary
Problem Statement
The objective of this project was to predict sales for Big Mart outlets using historical data. The approach focused on exploratory data analysis, feature engineering, and model selection to achieve optimal performance.
**Exploratory Data Analysis (EDA)**

  - Descriptive Statistics & Distribution Check
  - Initial analysis included checking summary statistics to understand the overall data distribution.
  - Examined skewness in the dependent variable to assess the presence of extreme values.
    
**Outlet Sales Analysis & Insights**

  - Conducted EDA to analyze trends in sales across different outlet types.
  - Observed key insights:
  - Tier 1 cities exhibit lower fat content consumption than Tier 3 cities.
  - Tier 3 cities have higher item sales across all product categories.
  - Supermarket 3 showed a high variance in outlet sales.
Feature Correlation & Data Integrity Checks
- Investigated correlations among features but found no significant relationships.
- Confirmed the absence of multicollinearity and cardinality issues.
- Identified outliers but opted to retain them, given the robustness of tree-based models.
Feature Engineering
- Missing Value Imputation
- Imputed missing values based on statistical methods:
- Mean for numerical variables.
- Mode for categorical variables, ensuring feature relevance.
Encoding & Scaling
- Applied One-hot encoding to categorical features for effective model learning.
- Standardized numerical features to enhance convergence in models utilizing gradient descent.
Modeling Approach
- Baseline to Advanced Models
- Started with a Decision Tree model as a baseline approach.
- Progressed to more advanced ensemble methods, including XGBoost, to improve predictive accuracy.
- Hyperparameter Tuning
- Used GridSearchCV to systematically find the best hyperparameters for selected models.
- AutoML Exploration
- Considered AutoML frameworks as an alternative to manual feature selection and hyperparameter tuning.
Conclusion
The methodology employed a structured pipeline—EDA, feature engineering, and model optimization—to create a robust predictive model for Big Mart sales. The insights generated provide valuable business perspectives, while model selection ensures scalability and accuracy.




![image](https://github.com/user-attachments/assets/8bd21b96-472a-4db5-abb4-94d5fdd1fc92)
