# Assignment 1: Predicting Student Performance

## 1. Overview
In this assignment, you will act as a Data Analyst to explore a dataset of **10,000 students**. Your objective is to identify which behavioral and demographic factors (such as sleep, study hours, and practice tests) significantly impact a student's final academic score. 

You will build a **Multiple Linear Regression (MLR)** model to predict the "Performance Index" for future students.

---

## 2. Required Deliverables

### Task 1: Exploratory Data Analysis (EDA)
* **Correlation Heatmap:** Generate a heatmap to identify which features have the strongest linear relationship with the `Performance Index`.
* **Feature Distribution:** Use histograms to check the distribution of the target variable and identify any potential outliers.

### Task 2: Data Preprocessing
* **Encoding:** Convert the `Extracurricular Activities` column into a binary numeric format (1 for Yes, 0 for No).
* **Data Partitioning:** Split the dataset into a **Training Set (80%)** and a **Testing Set (20%)**.

### Task 3: Model Implementation & Statistics
* **The Fit:** Train a Multiple Linear Regression model using the training data.
* **Summary Statistics:** Use the `statsmodels` library to generate a detailed **OLS Regression Results** table.

### Task 4: Model Evaluation
* **Metric Calculation:** Report the **$R^2$**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.
* **Residual Analysis:** Plot the **Residuals** and a **Q-Q Plot** to verify model assumptions (Homoscedasticity and Normality).

### Task 5: The Prediction
Calculate the predicted score for a student with the following profile:
* **Hours Studied:** 10
* **Sleep Hours:** 8
* *(Assume average values for other variables if not specified, or use your model's intercept logic).*

---

## 3. Submission Requirements
Please submit the following through the course portal:
1. **PDF Report:** A clear document containing your visualizations, the OLS summary table, and written answers for Tasks 1-5.
2. **Python Notebook:** Your `.ipynb` file containing the clean, commented code used for the analysis.

---
**© 2026 Shanu Sushmita**
