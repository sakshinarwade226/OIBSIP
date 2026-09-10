# Sales Prediction Using Python

## Objective

The objective of this project is to analyze the relationship between advertising expenditure and product sales and build machine learning models to predict Sales.

## Dataset

The dataset contains advertising expenditure for three channels:

- TV
- Radio
- Newspaper

The target variable is:

- Sales

The dataset contains 200 records.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps

### 1. Data Loading and Cleaning
- Loaded the Advertising dataset using Pandas.
- Checked the dataset shape, data types, missing values, and descriptive statistics.
- Removed the unnecessary index column.

### 2. Exploratory Data Analysis

Performed:
- Pairplot analysis
- Sales vs TV scatter plot
- Sales vs Radio scatter plot
- Sales vs Newspaper scatter plot
- Correlation heatmap

The analysis showed that TV advertising had the strongest relationship with Sales, followed by Radio.

### 3. Machine Learning

The dataset was divided into training and testing sets using an 80:20 split.

Two regression models were trained:

- Linear Regression
- Random Forest Regression

### 4. Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 1.46 | 1.78 | 0.899 |
| Random Forest | 0.62 | 0.77 | 0.981 |

Random Forest performed better than Linear Regression, with an R² score of approximately 98.13%.

### 5. Feature Importance

Random Forest feature importance showed:

| Feature | Importance |
|---|---:|
| TV | 0.624810 |
| Radio | 0.362201 |
| Newspaper | 0.012989 |

TV advertising was the most important feature for predicting Sales.

## Conclusion

The project demonstrates how advertising expenditure can be used to predict product Sales using machine learning. Among the three advertising channels, TV had the highest influence on Sales predictions, followed by Radio. Random Forest provided better predictive performance than Linear Regression on the test dataset.

## Files

- `Advertising.csv` – Dataset
- `Sales_Prediction.ipynb` – Jupyter Notebook containing the complete analysis and machine learning implementation
