# Multivariate Statistical Analysis of Credit Risk Classification

A comprehensive statistical analysis project that investigates the financial and behavioral factors influencing credit risk classification. The project applies classical statistical methods and machine learning techniques to identify the variables that best predict whether a customer presents a high or low credit risk.

---

## Project Overview

Financial institutions rely on credit risk assessment to determine whether applicants are likely to repay loans. This project explores a credit score dataset using exploratory data analysis, multivariate statistical analysis, and predictive modeling to understand the relationships among customer attributes and develop a Logistic Regression model for credit risk classification.

---

## Objectives

- Perform exploratory analysis of customer financial data.
- Clean and preprocess the dataset.
- Analyze relationships among variables.
- Apply multivariate statistical techniques.
- Build a Logistic Regression model for credit risk classification.
- Evaluate model performance using standard classification metrics.
- Interpret the most important predictors of credit risk.

---

## Dataset

The dataset contains customer financial and behavioral information, including:

- Age
- Annual Income
- Monthly Salary
- Outstanding Debt
- Number of Credit Cards
- Number of Bank Accounts
- Credit History Age
- Interest Rate
- Number of Loans
- EMI per Month
- Credit Utilization Ratio
- Delayed Payments
- Credit Mix
- Payment Behaviour
- Credit Score (Target Variable)

### Target Variable

- Low Risk
- Medium Risk
- High Risk

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn

---

## Statistical Methods

The following statistical and machine learning techniques were applied:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Correlation Analysis
- Hypothesis Testing
- Chi-Square Test
- ANOVA
- Principal Component Analysis (PCA)
- Hierarchical Clustering
- K-Means Clustering
- Logistic Regression
- Model Evaluation

---

## Project Structure

```text
Multivariate-Statistical-Analysis-Credit-Risk/
│
├── credit_train_clean.7z            # Compressed cleaned dataset
├── proyecto_final.ipynb             # Main Jupyter Notebook
├── proyecto_final_analisis_multivariable.qmd # Quarto document file
├── index.html                       # HTML report output
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/bielng/logistic_regression_presentation_iteso.git
```

Navigate to the project directory:

```bash
cd logistic_regression_presentation_iteso
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebooks in the following order:

1. Data Cleaning
2. Exploratory Data Analysis
3. Statistical Analysis
4. PCA and Clustering
5. Logistic Regression

---

## Model Evaluation

The Logistic Regression model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Classification Report

---

## Key Findings

- Financial behavior significantly influences credit risk classification.
- Outstanding debt and payment history are among the strongest predictors.
- Logistic Regression provides an interpretable and effective classification model.
- PCA reduces dimensionality while preserving the majority of the dataset's variance.
- Clustering techniques identify distinct customer financial profiles.

---

## Visualizations

The project includes several visualizations, including:

- Correlation Heatmap
- Distribution Plots
- Boxplots
- Pairplots
- PCA Scatter Plot
- Hierarchical Clustering Dendrogram
- K-Means Cluster Visualization
- Confusion Matrix

---

## Future Improvements


- XGBoost
- Support Vector Machine ##incase of any future improvement yeah we gonna test it out
- and see if i will perform good among the four model we tested out first 


---

## Authors



**Taban James Biel Ngunar**
Data Science & Engineering Student

GitHub: [https://github.com/bielng](https://github.com/bielng)

Portfolio: [https://ngunar.vercel.app](https://ngunar.vercel.app)

**Luis Alfonso Díaz Solórzano**
Nanotechnology Engineering, ITESO Guadalajara

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

This project was completed as part of the **Multivariate Statistical Analysis** course
