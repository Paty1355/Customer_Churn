# Customer Churn Analysis and Prediction

This project focuses on analyzing and predicting customer churn using data-driven approaches. It includes exploratory data analysis (EDA), statistical testing, data preprocessing, feature engineering, model selection, and hyperparameter tuning.

## 📊 Project Overview

The main goal of this project is to understand the patterns behind customer churn and build a predictive model that can help businesses retain their customers more effectively.

### Key Steps:
- Exploratory Data Analysis (EDA)
- Statistical Tests
- Data Preprocessing
- Feature Engineering
- Model Training and Evaluation
- Hyperparameter Tuning

## 🛠️ Technologies Used

- **Python**  
- **Pandas, NumPy** – data manipulation  
- **Matplotlib, Seaborn** – data visualization  
- **Scikit-learn** – modeling and evaluation  
- **XGBoost / CatBoostClassifier / RandomForestClassifier / GradientBoostingClassifier** – main models  
- **Statsmodels / Scipy** – statistical analysis  

## 📈 Exploratory Data Analysis

- Visualized churn distribution, correlations, and customer behavior
- Identified patterns and relationships between features and churn

## 📋 Statistical Tests

- Conducted hypothesis testing to validate assumptions
- Used chi-squared tests, U Manna-Whitneya (Wilcoxona), Kruskal Wallis and Bonferroni Test depending on feature types

## ⚙️ Data Processing

- Handled missing values
- Encoded categorical variables
- Testing improvenent scaled numerical features

## 🧠 Feature Engineering

- Created new meaningful features based on domain knowledge
- Reduced dimensionality where necessary
- Selected the most important features using model-based techniques - MCA

## 🤖 Model Development

- Compared multiple models: Logistic Regression, Random Forest, XGBoost, GradientBoosting itd.
- Evaluated using metrics like Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Final model chosen based on balanced performance and interpretability

## 🔍 Hyperparameter Tuning

- Used RandomizedSearchCV
- Optimized key parameters for best performance 

## 🚀 Results

- Achieved strong predictive performance:
  
Accuracy: 0.8611
Precision: 0.8546
Recall: 0.8961
F1 Score: 0.8748
ROC AUC: 0.9434
