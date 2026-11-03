# Telecom Customer Churn Prediction

## Project Overview
This project focuses on predicting customer churn in the telecommunications industry using machine learning. Customer churn occurs when customers stop using a company's services. The goal is to identify customers who are likely to leave so that telecommunications companies can develop better customer retention strategies.

## Dataset
The project uses the IBM Telco Customer Churn dataset, containing 7,043 customer records and 21 original columns.

The target variable is `Churn`, which indicates whether a customer has left the company.

## Project Objectives
- Understand customer churn patterns through Exploratory Data Analysis (EDA).
- Clean and prepare the dataset for machine learning.
- Build and compare Logistic Regression and Random Forest models.
- Evaluate model performance using appropriate classification metrics.
- Identify factors associated with customer churn.
- Suggest possible customer retention strategies.

## Technologies and Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology
1. Data inspection and cleaning.
2. Exploratory Data Analysis.
3. Feature selection and target separation.
4. Categorical encoding and numerical scaling.
5. Stratified train-test splitting.
6. Model training using Logistic Regression and Random Forest.
7. Model evaluation and comparison.
8. Feature importance and business recommendations.

## Model Results
Logistic Regression performed better than Random Forest during cross-validation.

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 80.42% | 78.61% |
| Precision | 65.79% | 63.10% |
| Recall | 54.78% | 46.96% |
| F1-score | 59.77% | 53.80% |
| ROC-AUC | 84.57% | 82.53% |

## Key Findings
- Approximately 26.54% of customers in the dataset churned.
- Month-to-month contracts had the highest churn rate.
- Customers who churned generally had shorter tenures.
- Customers who churned had higher median monthly charges.
- Contract type and tenure were important factors associated with churn predictions.

## Limitations
The dataset may not represent every telecommunications company or customer population. The model identifies statistical patterns and associations, not causes of customer churn. Further validation would be required before using it in a real business environment.

## Repository Structure
- `notebook/`: Complete project notebook.
- `visualizations/`: Saved graphs from the analysis.
- `README.md`: Project documentation.
- `requirements.txt`: Required Python libraries.

## Author
Student Machine Learning Project


## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/telecom-customer-churn-prediction.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Navigate to the Project Folder

```bash
cd telecom-customer-churn-prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Open the notebook using Jupyter Notebook or Google Colab.

The notebook contains the complete workflow, including data cleaning, exploratory data analysis, preprocessing, model training and evaluation.

### Dataset Access

The project uses the IBM Telco Customer Churn dataset. The dataset is loaded directly from its public GitHub source within the notebook.
