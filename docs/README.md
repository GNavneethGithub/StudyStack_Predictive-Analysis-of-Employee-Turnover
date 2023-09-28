# Predictive Analysis of Employee Turnover

This project encapsulates a comprehensive analysis aimed at predicting employee terminations within a fictitious organization over a span of 10 years. By employing machine learning models, the endeavor is to discern patterns that might indicate an impending termination, thereby providing a nuanced understanding of employee churn. The dataset utilized for this analysis comprises fabricated data, reflecting various attributes of employees, including their employment status over the years.


## Introduction

The dataset under scrutiny encompasses a range of attributes such as employee id, record date, birth date, hire date, termination date, age, length of service, city, department, job title, store number, gender, termination reason, termination type, status year, status, and business unit. The primary intent is to predict the 'status' of an employee, i.e., whether they are active or terminated, based on the available data.

This project involves the creation and evaluation of three machine learning models to predict employment termination, providing a deep dive into the data, its characteristics, and the preliminary observations that guide the subsequent analysis.

## Objective

The core objective of this project is to harness machine learning algorithms to predict individual employee terminations, moving beyond the conventional aggregate-level turnover analyses. By identifying the potential indicators of employee churn, this analysis aims to contribute to the broader understanding of employee retention and organizational dynamics.

## Concepts Used

- **Data Preprocessing**: Cleaning and transforming the dataset to ensure it's well-suited for training machine learning models. This includes handling missing values, converting data types, and creating new categorical features based on existing data.
- **Exploratory Data Analysis (EDA)**: Uncovering the underlying structure of the data, identifying anomalies, and discovering patterns that could inform the model building process.
- **Machine Learning**: Utilizing supervised learning algorithms to train models capable of predicting employee termination.
- **Model Evaluation**: Assessing the performance of the machine learning models using appropriate metrics to ensure their reliability and accuracy.

## Tools/Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib/Seaborn**: For data visualization.
- **Scikit-Learn**: For implementing machine learning algorithms and evaluating models.


## Conclusions

The analysis reveals significant insights into the factors that might influence employee terminations. The machine learning models, with a scoring metric around 0.98, exhibit a high degree of accuracy in predicting employee churn. The peaks observed in the age and length of service data provide a nuanced understanding of the different stages at which employees are likely to exit the organization. These findings could serve as a foundation for further research and practical applications in human resource management and organizational development.
