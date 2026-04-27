# AI/ML Internship Tasks
This repository contains the completed tasks for my AI/ML internship. Each task demonstrates fundamental concepts of data analysis, visualization, regression, and classification using Python and popular machine learning libraries.

# Task 1: Iris Dataset Visualization

### Objective
The objective of this task was to explore and understand a simple dataset by performing data inspection and visualization. This helps in identifying patterns, relationships, and distributions in the data.

### Dataset
The Iris dataset is a well-known dataset in machine learning that contains measurements of flowers such as:

Sepal length
Sepal width
Petal length
Petal width
Species (Setosa, Versicolor, Virginica)

### Steps Performed
Loaded the dataset using seaborn
Inspected the dataset using:
.shape() for dimensions
.head() for preview
.info() for structure
.describe() for statistical summary
Created visualizations:
Scatter plot to analyze relationships between features
Histograms to observe distributions
Box plots to detect outliers

### Key Insights
Clear separation between different species based on petal length and width
Setosa species has significantly smaller petal dimensions
No missing values were found in the dataset

### Conclusion
Data visualization is a powerful technique to understand datasets before applying machine learning models. This task helped build a strong foundation in exploratory data analysis (EDA).

# Task 6: House Price Prediction

### Objective
The goal of this task was to build a regression model to predict house prices based on various features such as income, number of rooms, and population.

### Dataset
The California Housing dataset was used, which includes features like:

Median Income
Average Rooms
Population
House Age
Target variable: House Price

### Steps Performed
Loaded dataset using sklearn
Explored the dataset using pandas functions
Visualized relationships between features and target variable
Prepared data by separating features (X) and target (y)
Split dataset into training and testing sets
Trained a Linear Regression model
Made predictions on test data
Evaluated model using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

### Key Insights
Median income has a strong positive relationship with house prices
The model captures general trends but has some prediction errors
Real-world data can have variability affecting accuracy

### Conclusion
Linear Regression is a simple yet effective algorithm for predicting continuous values. This task provided a clear understanding of regression modeling and evaluation techniques.

# Task 3: Heart Disease Prediction

### Objective

The objective of this task was to build a classification model to predict whether a person is at risk of heart disease based on medical attributes.

### Dataset
The dataset contains medical features such as:

Age
Sex
Chest pain type
Cholesterol level
Maximum heart rate
Target variable: Presence of heart disease (0 = No, 1 = Yes)

### Steps Performed
Loaded dataset from an online source
Performed exploratory data analysis (EDA)
Visualized target distribution and feature relationships
Prepared data by separating features and target
Split data into training and testing sets
Trained a Logistic Regression model
Evaluated model using:
Accuracy Score
Confusion Matrix
ROC Curve and ROC-AUC Score
Analyzed feature importance

### Key Insights
The model achieved good accuracy in predicting heart disease
Certain features like age and cholesterol play an important role
Classification models are useful in healthcare predictions

### Conclusion
Logistic Regression is an effective algorithm for binary classification problems. This task demonstrated how machine learning can assist in medical decision-making.

### Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
GitHub

### Overall Learning
Through these tasks, I learned:
Data loading and preprocessing
Exploratory Data Analysis (EDA)
Data visualization techniques
Regression and classification models
Model evaluation methods
Version control using GitHub

# Task: ML Pipeline for Customer Churn

## Objective
Build an end-to-end ML pipeline for churn prediction.

## Techniques Used
- Data preprocessing
- Pipeline (scikit-learn)
- GridSearchCV

## Models
- Logistic Regression
- Random Forest

## Result
Achieved good accuracy using optimized pipeline.

