
# Higher Education Predictors of Student Retention

## Project Overview

This project explores factors influencing student retention in higher education using statistical modeling techniques. The primary objective is to analyze relationships between explanatory variables and student retention outcomes using linear and logistic regression models.

## Dataset

- **Source:** [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention)
- **Description:** The dataset includes various student attributes that may impact retention, such as demographic data, academic performance, and institutional factors.

## Project Structure

The analysis is divided into two main sections:

### 1. Linear Regression Analysis

- **Objective:** Predict a continuous outcome variable related to student retention.
- **Methodology:**
  - Perform **Exploratory Data Analysis (EDA)** with summary statistics, histograms, and boxplots.
  - Select a subset of variables, ensuring a mix of categorical and continuous predictors.
  - Fit a **multiple linear regression model** to examine the impact of predictors.
  - Evaluate model performance using **R², adjusted R², and ANOVA tests**.
  - Check for model assumptions (linearity, homoscedasticity, and normality of residuals).
  - Incorporate **interaction terms** to capture complex relationships.

### 2. Logistic Regression Analysis

- **Objective:** Predict a binary outcome, such as whether a student is retained or not.
- **Methodology:**
  - Conduct **EDA** for binary classification.
  - Fit a **logistic regression model** with both continuous and categorical predictors.
  - Interpret model coefficients and compute **odds ratios**.
  - Assess model performance using **classification metrics** (e.g., accuracy, precision, recall).
  - Compare models using **stepwise regression techniques** (Forward/Backward selection).

## Data Preprocessing

- Handle **missing values** and identify potential **outliers**.
- Encode categorical variables appropriately for modeling.
- Normalize or scale numerical features when necessary.
- Split data into training and testing sets for model validation.

## Requirements

To run the analysis, install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

## How to Run the Project

1. **Download the dataset** from Kaggle and place it in the project directory.
2. **Run the Jupyter Notebook (****`project_analysis.ipynb`****)** or the provided Python scripts.
3. **Review the outputs**, including regression results, statistical summaries, and visualizations.

## Results & Insights

- The project examines **which factors have the strongest influence** on student retention.
- Comparison of **linear vs. logistic regression models** for different retention measures.
- Impact of interactions and non-linear relationships in predicting retention.

## Acknowledgments

- **Dataset:** [Kaggle - Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention).
- **Course Assignment:** The methodology is inspired by statistical analysis techniques covered in coursework.



