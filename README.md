# DevelopersHub Data Science & Analytics Internship

## Task 1: Exploring and Visualizing a Simple Dataset

### Objective
Understand how to read, summarize, and visualize a dataset.

### Dataset
Iris Dataset (built-in via seaborn library)

### Approach
- Loaded dataset using pandas and seaborn
- Explored dataset structure using .shape, .columns, .head()
- Created 3 visualizations: Scatter Plot, Histogram, Box Plot

### Key Insights
- Virginica has the largest sepal and petal sizes
- Setosa is clearly separated from other species
- Petal length increases as sepal length increases
- One outlier found in Virginica species

## Task 2: Credit Risk Prediction

### Objective
Predict whether a loan applicant is likely to default on a loan.

### Dataset
Loan Prediction Problem Dataset (Kaggle)

### Approach
- Handled missing values using mean and mode
- Visualized loan amount, education and income
- Trained Logistic Regression model

### Key Insights
- Graduates have higher loan approval rate
- Credit history is the most important factor
- Model achieved good accuracy on test data

## Task 3: Customer Churn Prediction

### Objective
Identify customers who are likely to leave the bank.

### Dataset
Churn Modelling Dataset (Kaggle)

### Approach
- Cleaned and prepared the dataset
- Encoded Geography and Gender columns
- Trained Random Forest Classifier
- Analyzed feature importance

### Key Insights
- Age is the most important churn factor
- Older customers (45+) are more likely to leave
- Germany has the highest churn rate
- Model achieved high accuracy on test data

## Task 4: Predicting Insurance Claim Amounts

### Objective
Estimate medical insurance charges based on personal data.

### Dataset
Medical Cost Personal Dataset (Kaggle)

### Approach
- Encoded categorical columns
- Visualized BMI, Age and Smoker impact
- Trained Linear Regression model

### Key Insights
- Smokers pay 3-4x more than non-smokers
- Age and BMI positively impact charges
- MAE: 4186, RMSE: 5799
