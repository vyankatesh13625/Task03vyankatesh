# Task03vyankatesh
##  Objective
Implement and understand Simple and Multiple Linear Regression using a housing price prediction dataset.

##  Dataset
- Name: Housing Price Prediction
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

## Tools & Libraries
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

##  Task Breakdown

### 1. Data Preprocessing
- Loaded the dataset using `pandas`
- Handled missing values using `.dropna()`
- Converted categorical variables using `pd.get_dummies()`

### 2. Multiple Linear Regression
- Features used: All columns except `price`
- Split data using `train_test_split()`
- Trained using `LinearRegression()` from `sklearn`
- Evaluation metrics:
  - **MAE**
  - **MSE**
  - **RMSE**
  - **R² Score**

### 3. Simple Linear Regression
- Used `area` as the only feature to predict `price`
- Trained a separate model for visualization
- Plotted regression line using `matplotlib`

### 4. Visualization
- Scatter plot with regression line (`area` vs `price`)
- Residual distribution
- Coefficients of all features from the multiple regression model

##  Results

| Metric        | Value          |
|---------------|----------------|
| MAE           | *[insert value]* |
| MSE           | *[insert value]* |
| RMSE          | *[insert value]* |
| R² Score      | *[insert value]* |

> Note: Replace the above with your actual results from code output.

##  Files Included

- `linear_regression_task.ipynb` – Jupyter notebook with full code
- `Housing.csv` – Dataset used
- `README.md` – This file

##  Submission
- Uploaded GitHub repo link in the Google Form provided.

---

##  Contact
For any queries or feedback, feel free to reach out via GitHub or email.

