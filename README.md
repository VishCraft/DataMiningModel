# DataMiningModel
Built a Data Mining System, From Data Cleaning to Model Evaluation.


Diabetes Data Mining Project
Overview
This project focuses on building a comprehensive data mining system for diabetes prediction, from data cleaning to model evaluation. The dataset used is sourced from Kaggle, containing information about individuals, including attributes like pregnancies, glucose concentration, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age. The goal is to predict the presence or absence of diabetes (1 or 0) for each individual.

Key Steps
Data Cleaning and Exploration:

Handle missing values.
Visualize the distribution of the target variable (Diabetes Outcome).
Explore correlations within the dataset.
Feature Transformation:

Compare the distribution of selected features in their original and transformed states.
Apply transformations to enhance data quality.
Model Training and Evaluation:

Utilize Stratified K-Fold cross-validation for robust evaluation.
Implement a Decision Tree Classifier with both Gini and Entropy impurity measures.
Visualize feature importances for model interpretation.
Results
The project concludes with a comparison of Gini and Entropy-based decision trees, highlighting the mean accuracy across folds. The preferred impurity measure is identified based on model performance.

How to Run
Clone the repository.
Download the Diabetes Dataset and place it in the project directory.
Run the provided Python script to execute the data mining process.
Create New Notebook:
In Jupyter Notebook, create a new notebook (Python 3).
Copy and Paste Code:
Copy the Python script from the GitHub repository.
Paste it into the cells of your Jupyter Notebook.
Run the Notebook:
Run each cell sequentially using Shift + Enter.
Check the output for visualizations and results.
