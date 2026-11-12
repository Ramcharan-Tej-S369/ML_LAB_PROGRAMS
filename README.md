# Machine Learning Laboratory

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-orange?style=for-the-badge&logo=googlecolab&logoColor=white" />
  <img src="https://img.shields.io/badge/Library-Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Environment-Jupyter-orange?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

## About the Repository

This repository contains the programs, experiments, and practical implementations completed as part of the **Machine Learning Algorithms Laboratory**.

The repository covers fundamental machine learning concepts, starting with Python libraries used for data analysis and visualization, followed by regression algorithms, cross-validation, regularization techniques, and logistic regression classification.

Each experiment is implemented using Python and its machine learning libraries, with Jupyter Notebook files for executing the programs and observing their results.

## Student Information

| Detail | Information |
|---|---|
| Name | Ramcharan Tej S |
| USN | 4NI24CI127 |
| Subject | Machine Learning Algorithms Laboratory |
| Course Code | BCIL504 |
| Semester | 5th Semester |

---

## Repository Contents

The following table provides an overview of all the programs and supporting files available in this repository.

| Sl. No. | File Name | Description |
|---|---|---|
| 1 | [EXP1.ipynb](./EXP1.ipynb) | Introduction to Python libraries used in Machine Learning, including Math, NumPy, Pandas, and Matplotlib. |
| 2 | [LINEAR_REGRESSION.ipynb](./LINEAR_REGRESSION.ipynb) | Implementation of Simple Linear Regression using Python and Scikit-learn, including slope, intercept, MSE, and visualization. |
| 3 | [POLYNOMIAL_REGRESSION.ipynb](./POLYNOMIAL_REGRESSION.ipynb) | Implementation of Polynomial Regression to model nonlinear relationships using polynomial features. |
| 4 | [K_FOLD_CSV.ipynb](./K_FOLD_CSV.ipynb) | Implementation of K-Fold Cross-Validation using the KFold method to evaluate a regression model. |
| 5 | [K_FOLD_LINEAREGRESSION.csv](./K_FOLD_LINEAREGRESSION.csv) | CSV dataset associated with the K-Fold Linear Regression experiment. |
| 6 | [LASSO_RIDGE_REGULARIZATION.ipynb](./LASSO_RIDGE_REGULARIZATION.ipynb) | Comparison of Ordinary Least Squares (OLS), Ridge Regression, and Lasso Regression using different data splits. |
| 7 | [Activity_Case_a.ipynb](./Activity_Case_a.ipynb) | Practical implementation of regression calculations, including deviation tables, coefficient calculations, predictions, and error evaluation. |
| 8 | [Banknote_activity_2.ipynb](./Banknote_activity_2.ipynb) | Banknote Authentication using Logistic Regression, including data analysis, preprocessing, model training, and performance evaluation. |
| 9 | [Report_acitivty_2.pdf](./Report_acitivty_2.pdf) | PDF report documenting the Banknote Authentication activity. |

---

## Experiments Overview

### 1. Python Libraries for Machine Learning

**File:** `EXP1.ipynb`

Introduction to essential Python libraries used in Machine Learning and data science.

Topics covered:
- Math library and mathematical operations.
- NumPy arrays and numerical computations.
- Pandas for handling and manipulating data.
- Matplotlib for data visualization.
- Line charts, bar charts, histograms, scatter plots, and pie charts.

### 2. Simple Linear Regression

**File:** `LINEAR_REGRESSION.ipynb`

Implementation of Simple Linear Regression to understand the relationship between independent and dependent variables.

Topics covered:
- Loading and preparing datasets.
- Training and testing data.
- Building a Linear Regression model.
- Calculating slope and intercept.
- Predicting output values.
- Evaluating the model using Mean Squared Error (MSE).
- Visualizing the regression line.

### 3. Polynomial Regression

**File:** `POLYNOMIAL_REGRESSION.ipynb`

Implementation of Polynomial Regression to understand nonlinear relationships between variables.

Topics covered:
- Polynomial feature generation.
- Using `PolynomialFeatures` from Scikit-learn.
- Fitting a polynomial regression model.
- Calculating model coefficients and intercept.
- Predicting values using the trained model.
- Evaluating performance using MSE.
- Visualizing polynomial curves.

### 4. K-Fold Cross-Validation

**File:** `K_FOLD_CSV.ipynb`

Implementation of K-Fold Cross-Validation to evaluate the performance and reliability of a Linear Regression model.

Topics covered:
- Understanding cross-validation.
- Splitting data into 5 folds.
- Training and validation using different folds.
- Calculating MSE for individual folds.
- Comparing model performance across folds.
- Calculating average validation error.

**Supporting dataset:** `K_FOLD_LINEAREGRESSION.csv`

### 5. Lasso and Ridge Regularization

**File:** `LASSO_RIDGE_REGULARIZATION.ipynb`

Implementation and comparison of three regression techniques to understand the effect of regularization on model performance.

Algorithms covered:
- Ordinary Least Squares (OLS) Regression.
- Ridge Regression (L2 Regularization).
- Lasso Regression (L1 Regularization).

Topics covered:
- Understanding regularization.
- Comparing regression coefficients.
- Calculating model intercepts.
- Training, validation, and testing data splits.
- Predicting values using different regression models.
- Calculating Training MSE, Validation MSE, and Test MSE.
- Comparing the effect of L1 and L2 penalties.

### 6. Regression Calculations – Activity Case A

**File:** `Activity_Case_a.ipynb`

Practical implementation of regression calculations using a sample dataset.

Topics covered:
- Calculating mean values of X and Y.
- Preparing deviation tables.
- Calculating deviations from the mean.
- Calculating squared deviations.
- Calculating covariance-related terms.
- Determining regression coefficients.
- Making predictions and evaluating regression performance.

### 7. Banknote Authentication using Logistic Regression

**File:** `Banknote_activity_2.ipynb`

A machine learning classification activity that uses Logistic Regression to classify banknotes as genuine or forged based on extracted statistical features.

Topics covered:
- Loading the Banknote Authentication dataset.
- Exploratory Data Analysis (EDA).
- Understanding dataset features.
- Data preprocessing.
- Splitting data into training and testing sets.
- Feature scaling using StandardScaler.
- Building a Logistic Regression classification model.
- Using Scikit-learn pipelines.
- Evaluating classification performance.

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

**Report:** [Report_acitivty_2.pdf](./Report_acitivty_2.pdf)

---

## Technologies and Tools Used

### Programming Language
- Python

### Libraries

| Library | Purpose |
|---|---|
| NumPy | Numerical operations and array manipulation. |
| Pandas | Data handling and analysis. |
| Matplotlib | Data visualization and plotting. |
| Scikit-learn | Machine learning algorithms, preprocessing, model training, and evaluation. |

### Development Platforms and Tools

| Tool | Purpose |
|---|---|
| Google Colab | Cloud-based Python notebook execution. |
| Jupyter Notebook | Interactive development and execution of experiments. |
| Git | Version control. |
| GitHub | Source code hosting and repository management. |

---

## Repository Structure

```text
ML_LAB_PROGRAMS/
│
├── EXP1.ipynb
│
├── LINEAR_REGRESSION.ipynb
│
├── POLYNOMIAL_REGRESSION.ipynb
│
├── K_FOLD_CSV.ipynb
│
├── K_FOLD_LINEAREGRESSION.csv
│
├── LASSO_RIDGE_REGULARIZATION.ipynb
│
├── Activity_Case_a.ipynb
│
├── Banknote_activity_2.ipynb
│
├── Report_acitivty_2.pdf
│
└── README.md
```

---

## Installation and Setup

### Prerequisites

Make sure the following are installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Google Colab (optional)
- Git

### Clone the Repository

```bash
git clone https://github.com/Ramcharan-Tej-S369/ML_LAB_PROGRAMS.git
```

Navigate to the project directory:

```bash
cd ML_LAB_PROGRAMS
```

### Install Required Libraries

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Alternatively, you can open the notebooks directly using Google Colab.

---

## How to Run the Programs

1. Clone or download the repository.
2. Open the repository in Jupyter Notebook or Google Colab.
3. Select the experiment notebook (`.ipynb`) you want to execute.
4. Make sure the required datasets are available.
5. Execute the notebook cells sequentially.
6. Observe the generated outputs, predictions, graphs, and evaluation metrics.

**Note:** The K-Fold notebook currently references a dataset named `kfolds_lab.csv`, whereas the repository contains `K_FOLD_LINEAREGRESSION.csv`. Update the filename in the notebook or rename the dataset before running it locally.

The Banknote Authentication notebook also loads its dataset externally, so an internet connection is required for that experiment.

---

## Machine Learning Concepts Covered

This repository provides practical exposure to the following concepts:

- Python libraries for Machine Learning.
- Data manipulation and visualization.
- Simple Linear Regression.
- Polynomial Regression.
- Model training and prediction.
- Training and testing data splitting.
- Mean Squared Error (MSE).
- K-Fold Cross-Validation.
- Ordinary Least Squares (OLS).
- Ridge Regression (L2 Regularization).
- Lasso Regression (L1 Regularization).
- Logistic Regression.
- Feature scaling and preprocessing.
- Classification performance evaluation.

---

## Author

**Ramcharan Tej S**

BE – Computer Engineering (AI & ML)

USN: 4NI24CI127

Machine Learning Algorithms Laboratory

Course Code: BCIL504

---

<p align="center">
  <b>Machine Learning Laboratory | 5th Semester</b>
  <br>
  Built with Python and Scikit-learn.
</p>
