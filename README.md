# Data Preprocessing Practical Exam Project

## Project Overview

This project demonstrates complete Data Preprocessing and Exploratory Data Analysis (EDA) techniques used in Data Science and Machine Learning.

The project includes:
- Data Loading
- Data Cleaning
- Missing Value Handling
- Outlier Detection
- Encoding
- Feature Scaling
- Feature Engineering
- Data Transformation
- Final Processed Dataset Export

---

# Problem Statement

The objective of this project is to preprocess customer-related data collected from multiple sources such as:
- CSV Files
- JSON Files
- SQL Database
- API Data

The final goal is to prepare clean and transformed data suitable for Machine Learning models.

---

# Machine Learning Problem

This project follows a Binary Classification approach:

- `purchased = 1` → Customer purchased product
- `purchased = 0` → Customer did not purchase

---

# Datasets Used

## 1. Customer Dataset (CSV)
Contains:
- Customer_ID
- Name
- Age
- Gender
- City
- Income

---

## 2. Transactions Dataset (JSON)
Contains:
- transaction_id
- customer_id
- product_id
- amount
- payment_mode
- date

---

## 3. SQL Database
Contains customer records stored inside SQLite database.

---

## 4. API Dataset
Data fetched using:
https://dummyjson.com/users

---

# Libraries Used

```python
pandas
numpy
matplotlib
seaborn
sqlite3
json
requests
scikit-learn
```

---

# Project Steps

# Step 1: Data Import & Understanding

Performed:
- CSV Loading
- JSON Loading
- SQL Loading
- API Fetching
- Dataset Merging
- Dataset Inspection

Functions Used:
```python
read_csv()
json.load()
sqlite3.connect()
requests.get()
info()
describe()
head()
```

---

# Step 2: Exploratory Data Analysis (EDA)

## Univariate Analysis
- Histograms
- Distribution Analysis

## Bivariate Analysis
- Correlation Heatmap
- Scatter Relationships

## Multivariate Analysis
- Pairplots
- Feature Relationships

Libraries:
```python
matplotlib
seaborn
```

---

# Step 3: Handling Missing Values

Techniques Used:
- Simple Imputer
- Most Frequent Imputation
- Missing Indicator
- Random Sample Imputation
- KNN Imputer
- MICE Imputer

---

# Step 4: Outlier Detection & Handling

Methods Used:
- Z-Score Method
- IQR Method
- Percentile Method
- Winsorization using clipping

---

# Step 5: Date & Time Handling

Performed:
- Date Conversion
- Date Feature Extraction
- Days Since Signup
- Last Purchase Analysis

---

# Step 6: Encoding Categorical Data

Techniques:
- Label Encoding
- One Hot Encoding
- Ordinal Encoding

---

# Step 7: Feature Scaling

Scaling Methods:
- StandardScaler
- MinMaxScaler
- MaxAbsScaler
- RobustScaler
- Normalizer

Also used:
```python
ColumnTransformer
```

---

# Step 8: Feature Engineering & Transformation

Performed:
- Feature Construction
- Log Transformation
- Power Transformation
- Binning
- Binarization

---

# Final Output

Generated:
```python
processed_customer_data.csv
```

This dataset is fully cleaned and transformed for Machine Learning.

---

# Biggest Issues Found in Dataset

- Missing Values
- Null Categories
- Outliers
- Skewed Numerical Data
- Mixed Data Types

---

# Best Techniques Used

| Problem | Best Technique |
|---|---|
| Missing Values | KNN Imputer, MICE |
| Outliers | RobustScaler |
| Skewed Data | Log Transformation |
| Categorical Data | One Hot Encoding |

---

# Conclusion

This project successfully demonstrates complete Data Preprocessing workflow required before building Machine Learning models.

The final processed dataset is:
- Clean
- Scaled
- Encoded
- Feature Engineered
- Ready for ML

---

# Author

Kval Rampariya
