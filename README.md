# Project: Toxic Comments Classification

## Description
This project focuses on building a tool for automatic detection of toxic comments on an e-commerce platform. The solution enables routing unwanted messages to moderation and improving the overall quality of communication on the platform.

## Goal
Build a machine learning model to classify comments as toxic or non-toxic, achieving high performance on toxic content detection.

## Workflow
- Text preprocessing: cleaning, lemmatization, duplicate and missing value checks
- Exploratory Data Analysis (EDA): class balance analysis and word frequency analysis
- Text vectorization using TF-IDF
- Modeling:
   - Training and comparing Logistic Regression, Complement Naive Bayes, and LightGBM models
   - Hyperparameter tuning with GridSearchCV
   - Model evaluation using F1-score and selection of the best model
- Conclusions and recommendations

## Technologies
Python, Pandas, NumPy, SpaCy, Scikit-learn, TF-IDF, LightGBM, GridSearchCV, Matplotlib, Seaborn

## Key Results
- Built and compared multiple text classification models
- Best performance achieved with Logistic Regression + TF-IDF vectorization
- F1-score = 0.76, exceeding the required threshold of 0.75
- Developed a model applicable to automated content moderation systems
