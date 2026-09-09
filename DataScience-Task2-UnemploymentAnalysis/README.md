# Unemployment Analysis with Python

## Project Overview

This project analyzes unemployment data in India to understand regional and monthly unemployment trends and the changes observed during the COVID-19 period.

The analysis was completed as part of the Oasis Infobyte Data Science Internship (OIBSIP).

## Objective

The main objectives of this project are:

- Analyze unemployment rates across different regions of India.
- Study month-wise unemployment trends.
- Compare unemployment trends across selected regions.
- Identify the top 10 regions with the highest average unemployment rate.
- Analyze the relationship between unemployment, employment, and labour participation.
- Compare employment conditions before and during the COVID-19 period.

## Dataset

The dataset contains unemployment-related information for different regions of India from May 2019 to June 2020.

### Main Columns

- `Region` – Name of the region
- `Date` – Date of the observation
- `Frequency` – Frequency of the data
- `Estimated Unemployment Rate (%)` – Estimated unemployment rate
- `Estimated Employed` – Estimated number of employed people
- `Estimated Labour Participation Rate (%)` – Labour participation rate
- `Area` – Rural or Urban area

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Cleaning

- Checked dataset shape and column names.
- Checked for missing values and duplicate records.
- Removed missing and duplicate records.
- Converted the `Date` column into datetime format.

### 2. Regional Analysis

Calculated the average unemployment rate for each region and identified regions with higher and lower unemployment levels.

### 3. Monthly Trend Analysis

Analyzed the month-wise average unemployment rate to identify changes over time.

### 4. Regional Time-Series Analysis

Compared unemployment trends for Maharashtra, Haryana, and Tamil Nadu.

### 5. Top 10 Regions

Identified the 10 regions with the highest average unemployment rates.

### 6. Correlation Analysis

Analyzed the relationship between:

- Unemployment Rate
- Estimated Employed
- Labour Participation Rate

### 7. COVID-19 Analysis

Compared employment conditions between the Pre-COVID period and the COVID period.

The comparison included:

- Average unemployment rate
- Average estimated employment
- Average labour participation rate

## Key Findings

- Unemployment rates varied considerably across different regions of India.
- Tripura recorded the highest average unemployment rate among the regions in the dataset.
- The overall unemployment rate remained relatively stable before COVID-19 but increased sharply during April and May 2020.
- Haryana generally recorded higher unemployment than Maharashtra and Tamil Nadu during the study period.
- The average unemployment rate increased from approximately 9.51% before COVID-19 to 17.77% during the COVID period.
- Average estimated employment decreased from approximately 7.47 million to 6.52 million during the COVID period.
- Labour participation decreased from approximately 43.89% to 39.33%.
- The correlation analysis showed weak relationships among unemployment, estimated employment, and labour participation.

## Conclusion

The analysis shows significant regional and temporal variation in unemployment across India. The COVID-19 period was associated with a clear deterioration in employment conditions, with unemployment increasing while estimated employment and labour participation decreased.

The visualizations and statistical comparisons provide useful insights into India's unemployment situation during the period covered by the dataset.

## Project Structure

```text
DataScience-Task2-UnemploymentAnalysis/
│
├── data/
│   └── Unemployment in India.csv
│
├── screenshots/
│
├── README.md
│
└── Unemployment_Analysis.ipynb

