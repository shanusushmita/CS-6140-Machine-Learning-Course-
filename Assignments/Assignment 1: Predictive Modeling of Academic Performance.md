# Assignment 1: Student Performance Prediction (MLR)

## 1. Project Overview
In this assignment, you will act as an Educational Data Analyst. You have been provided with a dataset of **10,000 students**. Your goal is to identify which factors (e.g., sleep, study hours, practice tests) have the most significant impact on a student's final score and to build a predictive model for future academic performance.

---

## 2. Dataset Description
The dataset contains the following variables:
* **Target:** `Performance Index` (Continuous score from 10 to 100)
* **Predictors:** * `Hours Studied`: Total study hours.
    * `Previous Scores`: Scores from prior exams.
    * `Extracurricular Activities`: Binary (Yes/No).
    * `Sleep Hours`: Average daily sleep.
    * `Sample Question Papers Practiced`: Count of practice exams taken.

---

## 3. Required Deliverables

### Task 1: Exploratory Data Analysis (EDA)
* **Correlation Heatmap:** Identify which features have the strongest linear relationship with the Performance Index.
* **Feature Distribution:** Use histograms to check the distribution of the target variable and identify any outliers.

### Task 2: Data Preprocessing
* **Encoding:** Convert the `Extracurricular Activities` column into a binary numeric format (**1 for Yes, 0 for No**).
* **Data Partitioning:** Split the 10,000 rows into a **Training Set (80%)** and a **Testing Set (20%)**.

### Task 3: Model Implementation & Statistics
* **The Fit:** Train a Multiple Linear Regression model using the training data.
* **Summary Statistics:** Use the `statsmodels` library to generate an **OLS Regression Results** table.
* **Hypothesis Testing:** Identify which variables have a **P-value < 0.05**.

### Task 4: Model Evaluation
* **Metric Calculation:** Report the **$R^2$**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.
* **Residual Analysis:** Plot the residuals against the predicted values. Generate a **Q-Q Plot** to verify the normality of errors.

### Task 5: The Prediction
Using your final model, calculate the predicted `Performance Index` for a student with the following profile:
* **Hours Studied:** 10
* **Sleep Hours:** 8
* *(Note: Use the specific coefficients from your OLS summary to calculate this manually or via Python).*

---

## 4. Submission Instructions
Please submit the following files to the course portal:
1.  **PDF Report:** A formal document containing your answers to Tasks 1-5, including all required plots and the OLS summary table.
2.  **Python Notebook (.ipynb):** Your complete, commented code.

---
**© 2026 Shanu Sushmita**
