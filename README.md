# Elevate-Labs-Internship-TASK 01

### In the Task-1 folder and in the jupyter notebook names as 'Task1_solution_code.ipynb' and in that I have completed task-1 in the below process

1. Data Exploration & Handling Missing Values
Basic Inspection: Analyzed dataset structure (rows/columns), data types, and missing values.

Imputation:

Filled missing Age values with the median age.

Replaced missing Embarked values with the most frequent category (mode).

Marked missing Cabin entries as "Unknown" to retain data presence.

2. Categorical Feature Encoding
Label Encoding: Converted the Sex column to numerical values (e.g., male: 1, female: 0).

One-Hot Encoding: Transformed the Embarked column into binary columns (e.g., Embarked_C, Embarked_Q).

Column Removal: Dropped Name, Ticket, and Cabin due to high cardinality or irrelevance to analysis.

3. Feature Scaling
Standardization: Scaled numerical columns (Age, Fare, SibSp, etc.) using StandardScaler to ensure consistent ranges for modeling.

4. Outlier Detection & Removal
Visualization: Generated boxplots to identify outliers in numerical features.

IQR Method: Removed outliers using interquartile range thresholds to reduce data skewness.

5. Output
Exported the cleaned dataset to Cleaned_Titanic_Dataset.csv for future use in predictive modeling.

This preprocessing pipeline ensures the dataset is structured, normalized, and free of major inconsistencies, making it suitable for training machine learning models.

