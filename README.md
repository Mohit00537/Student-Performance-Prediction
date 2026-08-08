# Student Performance Prediction Using Machine Learning

## Project Overview

This project predicts a student's final academic score using Machine Learning based on factors such as study hours, attendance, previous score, sleep hours, and assignments completed.

## Objective

The main objective of this project is to develop a machine learning model that can predict student performance based on academic and behavioral factors.

## Dataset

The dataset contains the following features:

* Study Hours
* Attendance
* Previous Score
* Sleep Hours
* Assignments Completed
* Final Score

**Target Variable:** Final Score

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook
* Joblib

## Machine Learning Algorithms

### 1. Linear Regression

Used to predict the continuous numerical value of the student's final score.

### 2. Decision Tree Regressor

Used to predict the final score using decision-based rules.

## Model Evaluation

The models were evaluated using:

* R² Score
* Mean Squared Error (MSE)

The model with better evaluation performance was selected as the final model.

## Project Workflow

1. Dataset Collection
2. Data Loading
3. Data Inspection
4. Missing Value Check
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Comparison
10. Student Score Prediction
11. Model Saving

## Sample Prediction

The model can predict the expected final score of a new student based on their study hours, attendance, previous score, sleep hours, and completed assignments.

## How to Run

Clone the repository and install the required libraries:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
Student_Performance_Prediction.ipynb
```

## Conclusion

This project demonstrates how Machine Learning can be used to predict student academic performance using relevant academic and behavioral features.

