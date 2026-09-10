# Car Price Prediction Using Machine Learning

## Objective

The objective of this project is to analyze used car data and build machine learning models to predict the selling price of a car based on different features.

## Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Selling Price
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

The dataset initially contained 301 records. After removing 2 duplicate rows, 299 records were used for analysis and modeling.

## Data Preprocessing

The following steps were performed:

- Checked the dataset shape and data types
- Checked for missing values
- Removed duplicate rows
- Created a `Car_Age` feature
- Encoded categorical variables using One-Hot Encoding
- Removed unnecessary columns such as `Car_Name` and `Year`

## Exploratory Data Analysis

The following visualizations were created:

- Distribution of Selling Prices
- Selling Price by Fuel Type
- Selling Price vs Car Age
- Feature Correlation Heatmap

### Key Observations

- Selling prices are concentrated mainly in the lower price range.
- Diesel cars generally have higher selling prices than petrol cars in this dataset.
- Older cars generally tend to have lower selling prices.
- `Present_Price` has a strong positive correlation with `Selling_Price`.

## Machine Learning Models

Two regression models were trained:

1. Linear Regression
2. Random Forest Regression

The dataset was divided into training and testing sets using an 80:20 split.

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 1.4729 | 2.5240 | 0.7528 |
| Random Forest | 1.4379 | 3.4154 | 0.5474 |

Based on the test results, Linear Regression performed better overall, with a lower RMSE and higher R² score.

## Feature Importance

The Random Forest model showed that `Present_Price` was the most important feature, followed by `Car_Age`.

## Conclusion

This project demonstrates how exploratory data analysis, data preprocessing, and machine learning can be used to understand and predict used car selling prices. Among the two models tested, Linear Regression performed better overall on the test dataset.
