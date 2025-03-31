**Game of Thrones - Exploratory Data Analysis (EDA)**

**Introduction**

This project performs Exploratory Data Analysis (EDA) on Game of Thrones datasets to uncover insights, clean data, and handle missing values. The analysis is conducted on three datasets:

1. battles.csv

2. character-deaths.csv

3. character-predictions.csv

**Data Cleaning and Handling Missing Values**

To ensure data quality, various imputation techniques were applied:

1. Median Imputation: Used for numerical features with skewed distributions to prevent data distortion.

2. Mode Imputation: Applied to categorical columns, filling missing values with the most frequently occurring value.

3. KNN Imputer: Used to fill missing values by estimating values based on similar data points.

**Steps in EDA**

Data Loading: Read and inspect datasets for inconsistencies.

1. Handling Missing Values: Applied different imputation techniques as per feature type.

2. Data Cleaning: Removed duplicates, standardized column names, and corrected inconsistencies.

3. Exploratory Analysis: Visualized key statistics, relationships, and patterns in the data.

**Tools Used**

Pandas for data manipulation

NumPy for numerical operations

Matplotlib & Seaborn for visualization

Scikit-learn for KNN imputation
