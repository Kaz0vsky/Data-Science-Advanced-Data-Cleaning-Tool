# Data Science - Advanced Data Cleaning Tool
A tool that performs basic data cleaning tasks such as removing duplicates, filling missing values, Handling Outliers,  Custom Missing Value Handling,  Data Type Conversion, Normalization, orrelation Analysis, Outlier Handling, Flexible Missing Value Handling, Data Type Conversion, Correlation-Based Column Removal.

Requirements:

pip3 install pandas seaborn matplotlib scikit-learn numpy

Usage:

    python3 clean_data.py data.csv zscore ffill None True 0.9

    zscore: Method to handle outliers (options: zscore, iqr, or None).
    ffill: Method to handle missing values (options: ffill, bfill, mean, median, mode, custom).
    None: Custom value to fill missing values (used if the method is custom).
    True: Whether to normalize numerical columns (options: True, False).
    0.9: Correlation threshold for dropping columns with high correlation.

![image](https://github.com/user-attachments/assets/c37e06d2-3b7d-4f3d-b5b6-c7590ad2384f)


