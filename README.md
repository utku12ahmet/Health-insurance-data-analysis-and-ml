Health Insurance Data Analysis and Machine Learning

This project analyzes health insurance data using visualization techniques and machine learning models. The dataset contains information such as age, BMI, number of children, smoking status, and medical charges. The goal is to explore insights through data visualization and build predictive models for insurance charges.

Project Overview

The project consists of the following main steps:

Data Analysis and Visualization

Distribution of medical charges based on gender and smoking status

Relationship between BMI and medical charges

Correlation analysis between numerical features

Analysis of BMI categories and age groups

Effect of children count on medical charges

Regional differences in charges, age, and BMI

Machine Learning Models

Linear Regression model to predict medical charges

Polynomial Regression to improve predictions

Residual analysis to evaluate model performance

Learning curve analysis to assess model generalization

Libraries Used

pandas - Data manipulation

numpy - Numerical computations

matplotlib & seaborn - Data visualization

scikit-learn - Machine learning models and evaluation

How to Run the Project

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the Python script:

python analysis.py

Results and Insights

Smoking significantly increases medical charges.

Higher BMI values are correlated with higher medical costs.

Polynomial Regression provides better predictions than Linear Regression.

Overfitting is checked using residual plots and learning curves.

Future Improvements

Implement feature engineering to improve model accuracy.

Try other regression models such as Decision Trees or Random Forest.

Deploy the model using a web-based interface
