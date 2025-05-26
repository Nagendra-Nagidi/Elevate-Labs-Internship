# Elevate-Labs-Internship-TASK 01

#### In the Task-1 folder and in the Jupyter notebook-'Task1_solution_code.ipynb', I have completed Task-1 through the process outlined below.

### 1. Data Exploration & Handling Missing Values
Basic Inspection: Analyzed dataset structure (rows/columns), data types, and missing values.
Imputation:
Filled in missing Age values with the median age.
Replaced missing Embarked values with the most frequent category (mode).
Marked missing Cabin entries as "Unknown" to retain data presence.

### 2. Categorical Feature Encoding
Label Encoding: Converted the Sex column to numerical values (e.g., male: 1, female: 0).
One-Hot Encoding: Transformed the Embarked column into binary columns (e.g., Embarked_C, Embarked_Q).

### 3. Feature Scaling
Standardization: Scaled numerical columns (Age, Fare, SibSp, etc.) using StandardScaler to ensure consistent ranges for modeling.

### 4. Outlier Detection & Removal
Visualization: Generated box plots to identify outliers in numerical features.
IQR Method: Removed outliers using interquartile range thresholds to reduce data skewness.

### 5. Output
Exported the cleaned dataset to Cleaned_Titanic_Dataset.csv for future use in predictive modeling.

