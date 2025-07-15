# Student Academic Performance Prediction

## Project Overview

This project, completed as part of **COMP534: Machine Learning Pipeline**, aims to develop a machine learning model capable of predicting whether a student will pass their academic year. The project simulates a data science consultancy engagement for a school franchise, focusing on the entire machine learning pipeline from data management to model evaluation.

The goal is to leverage various student characteristics to build a robust predictive model.

---

## Features

* **Data Management & Preprocessing:** Thorough analysis and preparation of the student dataset, including handling missing values, feature engineering, and appropriate data transformations (standardization, encoding).
* **Experimental Protocol:** Clearly defined data splitting strategies (e.g., k-fold cross-validation) for robust model training and evaluation.
* **Model Training & Hyperparameter Tuning:** Implementation and comparison of at least three distinct machine learning models suitable for classification tasks. Includes systematic hyperparameter search protocols to identify optimal model configurations.
* **Model Evaluation:** Comprehensive evaluation of the best-performing model using multiple appropriate metrics and in-depth analysis of the confusion matrix.

---

## Dataset Description

The dataset, provided in a CSV format, contains various student attributes. The target variable, **Grade**, indicates the final grade (0-20), with a passing grade defined as `>=12`.

Here's a breakdown of the features:

| Column       | Description                                                              |
| :----------- | :----------------------------------------------------------------------- |
| `School`     | Student's school ("GP" – Gregory Portland or "MS" - Mississippi School)  |
| `sex`        | Student's sex                                                            |
| `age`        | Student's age                                                            |
| `address`    | Student's home address type: Urban or Rural                              |
| `famsize`    | Family size (less or equal to 3; or greater than 3)                      |
| `Pstatus`    | Parent's cohabitation status (Together or Apart)                         |
| `Medu`       | Mother's education (from 0 – none to 4 – higher education)               |
| `Fedu`       | Father's education (from 0 – none to 4 – higher education)               |
| `Mjob`       | Mother's job                                                             |
| `Fjob`       | Father's job                                                             |
| `reason`     | Reason to choose this school ("home", "reputation", "course", or "other") |
| `guardian`   | Student's guardian                                                       |
| `traveltime` | Home <-> school travel time (from 1 = less than 15 minutes, to 4 = 1 hour+) |
| `studytime`  | Weekly study time (from 1 = less than 2 hours, to 4 = 10 hours+)         |
| `failures`   | Number of past class failures                                            |
| `schoolsup`  | Extra educational support (yes or no)                                    |
| `famsup`     | Family educational support (yes or no)                                   |
| `paid`       | Extra paid classes within the course subject (yes or no)                 |
| `activities` | Extra-curricular activities (yes or no)                                  |
| `nursery`    | Attended nursery school (yes or no)                                      |
| `higher`     | Wants to take higher education (yes or no)                               |
| `internet`   | Internet access at home (yes or no)                                      |
| `romantic`   | With a romantic relationship (yes or no)                                 |
| `famrel`     | Quality of family relationships (from 1 - very bad to 5 - excellent)     |
| `freetime`   | Free time after school (from 1 - very low to 5 - very high)              |
| `goout`      | Going out with friends (from 1 - very low to 5 - very high)              |
| `Dalc`       | Workday alcohol consumption (from 1 - very low to 5 - very high)         |
| `Walc`       | Weekend alcohol consumption (from 1 - very low to 5 - very high)         |
| `health`     | Current health status (from 1 - very bad to 5 - very good)               |
| `absences`   | Number of school absences                                                |
| `Grade`      | Final grade (from 0 to 20) – students need a grade of 12 or higher (>=12) to pass |

---

## Project Structure

The project is organized into a Jupyter Notebook, following a structured machine learning pipeline:

### 1. Data Management

* **Analysis and Preparation:** In-depth data exploration using various visualizations (histograms, box plots, scatterplots) to identify data issues, potential improvements, and unnecessary features. This includes steps like feature dropping, standardization, and encoding.
* **Experimental Protocol:** Definition of the data splitting strategy, such as cross-validation or k-fold, to ensure robust model evaluation.

### 2. Model Training

* **Model Selection:** Selection and comparison of at least three machine learning models appropriate for this classification problem (e.g., Logistic Regression, Support Vector Machines, Decision Trees, Random Forests, Gradient Boosting).
* **Hyperparameter Tuning:** Implementation of a systematic hyperparameter search protocol (e.g., GridSearchCV, RandomizedSearchCV) to optimize the performance of selected models.

### 3. Evaluate Models

* **Model Testing:** Evaluation of the best-performing model on a dedicated test dataset.
* **Performance Metrics:** Reporting of at least three different evaluation metrics (e.g., accuracy, precision, recall, F1-score, ROC AUC) relevant to the classification problem.
* **Confusion Matrix Analysis:** Visualization and discussion of the confusion matrix to understand the model's predictive strengths and weaknesses.

---

## Contributions

This project was developed by Fia Proffitt.
