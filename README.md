# Employee-Attrition-Prediction



1. **Problem Statement**: Employee attrition, which refers to employees leaving an organization, can lead to significant losses. The project aims to predict whether employees are likely to leave their jobs, allowing organizations to take proactive measures to retain valuable employees.

2. **Data Exploration**: The project begins with importing necessary Python libraries for data analysis and visualization. Exploratory data analysis (EDA) is performed to understand the distribution of features in the dataset. KDE plots are used to visualize relationships between various features such as age, daily rate, job satisfaction, etc.

3. **Correlation Analysis**: A correlation matrix is generated to understand the relationships between different features. The plot helps identify poorly correlated columns, which can be beneficial for building predictive models.

4. **Feature Engineering**: Categorical variables in the dataset are numerically encoded using Pandas' get_dummies method. This step prepares the data for training machine learning models.

5. **Machine Learning Model**: The Random Forest Classification model from Scikit-learn is trained on the dataset. SMOTE (Synthetic Minority Over-sampling Technique) is used to address class imbalance in the target variable (attrition). The model achieves an accuracy score of around 85%.

6. **Feature Importance**: The Random Forest model provides insights into feature importance. A scatter plot is used to visualize the importance of different features in predicting employee attrition.
